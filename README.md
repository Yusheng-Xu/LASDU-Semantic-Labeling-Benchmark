# LASDU-Semantic-Labeling-Benchmark

This dataset is used as the reference for the semantic labeling of ALS point clouds: LASDU

### Data introduction

Here we present a  novel  aerial  LiDAR  dataset  termed  as LASDU (Large-scale ALS data for Semantic labeling in Dense Urban areas), which is designed for semantic labeling of ALS point clouds in highly-dense urban areas.

This dataset was a part of data acquired in the campaigns from HiWATER (Heihe Watershed Allied Telemetry Experimental Research) project.  The ALS point clouds were originally acquired in July 2012, by the use of a Leica ALS70 system onboard on an aircraft with a flying height of about 1200 m. The average point density was approximately 3~4 pts/m^2, and the vertical accuracy ranges between 5–30 cm. The annotated dataset covers an urban area of around 1 km × 1 km, with highly-dense residential and industrial buildings. 

For the annotation of points, we have manually labeled this area with five different classes of objects and one class of unclassified points and points of different labels rendered with different colors:

Label 1: Ground (color codes: #AFAFAF): artificial ground, roads, bare land.

Label 2: Buildings (color codes: #00007F): buildings.

Label 3: Trees (color codes: #09781A): tall and low trees.

Label 4: Low vegetation (color codes: #AAFF7F): bushes, grass, flower beds.

Label 5: Artifacts (color codes: #FF5500): walls, fences, light poles, vehicles, other artificial objects.

Label 0: Unclassified (color codes: #000000): noise, outliers, and unlabeled points.

<img src="/figures/LASDU_ColorMap.png" height="80%" width="80%" >

The total number of annotated points is approximately 3.12 million. The entire labeled point cloud of the investigating area has been divided into four sections, and the numbers of points in these four sections are around 0.77 million, 0.59 million, 1.13 million, and 0.62 million, respectively. In the following figure, the separation of the study area is illustrated.

<img src="/figures/LASDU_Map_Sections.png" height="90%" width="90%" >

For this dataset, the observed city blocks covered both the unchanged area and the changed one. The unchanged area means the stable objects (e.g., road, buildings, tree) are not changed over the years by comparing the point cloud and the satellite image. Dynamic objects like moving vehicles are not included. In the following figure, we give an example of the unchanged area. Note that the point cloud was acquired in 2012, while the satellite image was taken in 2014. The changing area in this data is mainly about construction sites. During the acquisition of the ALS point cloud, there were several on-going construction projects (for a single building or for an entire area).

<img src="/figures/LASDU_Details.png" height="90%" width="90%" >

### Data access

Please contact [Prof. Xiaohua Tong](mailto:xhtong@tongji.edu.cn?subject=[LASDU]%20Xiaohua%20Tong) or [Dr. Zhen Ye](mailto:z.ye@tum.de?subject=[LASDU]%20Zhen%20Ye) for getting this dataset. 

### Copyright
The annotated ALS dataset is copyrighted by College of Surveying and Geo-informatics, Tongji University and Photogrammetry and Remote Sensing, Technical University of Munich. If this annotated data is used in your work, it is made available under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0).

### Reference:

Please refer the following publication, if this reference dataset is used in your work:

```
@article{xu2020lasdu,
  title={LASDU: A Large-scale Aerial LiDAR Dataset for Semantic Labeling in Dense Urban Areas},
  author={Yusheng~Xu,
          Zhen~Ye,        
          Rong~Huang,
          Xiangfeng~Liu,
          Kuifeng~Luan,
          Xin~Li,
          Ludwig~Hoegner,
          Xiaohua~Tong,
          Uwe~Stilla},
  year={2020}
}
@article{li2013heihe,
  title={Heihe watershed allied telemetry experimental research (HiWATER): Scientific objectives and experimental design},
  author={Li, Xin and Cheng, Guodong and Liu, Shaomin and Xiao, Qing and Ma, Mingguo and Jin, Rui and Che, Tao and Liu, Qinhuo and Wang, Weizhen and Qi, Yuan and others},
  journal={Bulletin of the American Meteorological Society},
  volume={94},
  number={8},
  pages={1145--1160},
  year={2013},
  publisher={American Meteorological Society}
}
```
