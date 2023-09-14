This dataset contains the motion data of 14 healthy older aged between 66 and 86 years old, performed broadly scripted activities using a batteryless, wearable sensor on top of their clothing at sternum level. Data is sparse and noisy due to the use of a passive sensor. 
Participants were allocated in two clinical room settings (S1 and S2). The setting of S1 (Room1) uses 4 RFID reader antennas around the room (one on ceiling level, and 3 on wall level) for the collection of data, whereas the room setting S2 (Room2) uses 3 RFID reader antennas (two at ceiling level and one at wall level) for the collection of motion data. 
The activities performed were: 
 walking to the chair, 
 sitting on the chair, 
 getting off the chair, 
 walking to bed, 
 lying on bed, 
 getting off the bed and 
 walking to the door. 
Hence the possible class labels assigned for every sensor observation are:
- Sitting on bed
- Sitting on chair
- Lying on bed
- Ambulating, where ambulating includes standing, walking around the room. 

The content of the file is as follows:
Comma separated values (CSV) format.
Column 1: Time in seconds 
Column 2: Acceleration reading in G for frontal axis
Column 3: Acceleration reading in G for vertical axis
Column 4: Acceleration reading in G for lateral axis
Column 5: Id of antenna reading sensor
Column 6: Received signal strength indicator (RSSI) 
Column 7: Phase
Column 8: Frequency
Column 9: Label of activity, 1: sit on bed, 2: sit on chair, 3: lying, 4: ambulating
In addition, gender of participant is included in the last character of file name eg: d1p33F (F:female).


Source:
https://archive.ics.uci.edu/dataset/427/activity+recognition+with+healthy+older+people+using+a+batteryless+wearable+sensor