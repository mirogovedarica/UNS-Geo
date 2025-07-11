UNS-Geo dataset

Point cloud of urban area of Novi Sad, Serbia. Point cloud consisting of 4 820 426 points
for training and 582 189 for testing classified into 8 classes: 

- 1 - ground
- 2 - road
- 3 - parking
- 4 - pedestrian lane
- 5 - wall
- 6 - roof
- 7 - tree
- 8 - car

Points contain RGB values as well as number of returns, return number and intensity.

The part of the city has been scanned using LiDAR platform. Riegl LMS-Q680i laser scanner and digital camera DigiCAM H39 were used along with GPS-IMU navigation system used for georeferencing the data.
This dataset has been later processed using conventional methods of automatic, semi-automatic and manual classification.

![konačna_karta](https://github.com/user-attachments/assets/26896cac-3632-44ca-bbaa-ba351b7480c3)

Data used in the training phase consists of a point cloud previously manually classified into 5 classes 
(ground, impervious surfaces consisting of roads, pedestrian lanes and parking, buildings, trees and cars)
and it consists of ~4.8M points (40 points per square meter). Test dataset consists of ~0.58M points. 

<img width="502" height="181" alt="image" src="https://github.com/user-attachments/assets/7dc08cb7-61ae-47d0-832d-0dfd1dab02b0" />
