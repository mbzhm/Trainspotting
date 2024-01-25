# Trainspotting
A dataset of train vibration features and corresponding train model label.

Number of features: 9

List of features: 
1. Mean
2. Amplitude (max value)
3. Root mean square (RMS)
4. Duration
5. Number of peaks
6. Zero crossing rate
7. Peak-to-peak values (max - min)
8. Mean of peak values
9. Variance of peak values

Number of train labels: 6
List of decoded train labels: 
1: ICE 
2: IC
3: EC
4: Cargo
5: RE 
6: RB

ICE, IC, and EC are fast passenger trains. IC and EC trains only differ by name,
but share the same type of locomotive and wagons. RE and RB are regional 
passenger train types. Cargo stands for the very diverse cargo train class.

Number of instances: 135
