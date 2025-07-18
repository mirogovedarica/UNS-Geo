**UNS Geo dataset**

UNS Geo is dense anotated aerial LiDAR point cloud dataset, designed specifically for the classification of complex urban environments. The dataset is focused on the Liman neighborhood in Novi Sad (Serbia), an area representative of Southeast European urban morphology developed during the post–World War II period.

<img width="650" height="400" alt="UNSgeo" src="https://github.com/user-attachments/assets/26896cac-3632-44ca-bbaa-ba351b7480c3" />

Figure 1. Study area

The datased consists of 5.4 milion of points separeted to train (4 820 426 points) and test dataset (582 189). Average density is 35 points per squer meter. To each point the following attributes are assigned: XYZ coordinates, Number of return, Return number, Intensity, RGB, Normals XYZ, and Class labele.

The data set is classified into 8 classes. 

<img width="500" height="350" alt="image" src="https://github.com/user-attachments/assets/51aa4a7b-f9b9-46c9-9024-f63145ede36d" />


Classes can be organized hierarchicaly enabling different applications and combination with existing datasets:
<img width="500" height="350" alt="UNSgeo" src="https://github.com/user-attachments/assets/07ba82ac-dd3a-4711-8046-b042e5e9f74c" />

If you use the UNS Geo dataset in your research, please cite the following paper:

```bibtex
@inproceedings{govedarica2025unsgeo,
  author    = {Govedarica, M. and Jakovljevic, G. and Ruskoviski, I. and Pajic, V.},
  title     = {UNS Geo: LiDAR Dataset for Point Cloud Classification in Urban Areas},
  booktitle = {International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences},
  volume    = {XLVIII-4/W13-2025},
  pages     = {135--141},
  year      = {2025},
  doi       = {10.5194/isprs-archives-XLVIII-4-W13-2025-135-2025},
  url       = {https://doi.org/10.5194/isprs-archives-XLVIII-4-W13-2025-135-2025}
}
