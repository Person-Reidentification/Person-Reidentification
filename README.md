# Person-Reidentification

# IRIUST Dataset

This dataset is being completed...


![1](https://github.com/IRIUST/Iranians_Reid_dataset/assets/141324225/782122d5-235a-4314-9d81-7eceec56c960)


### About dataset

The IRIUST dataset is different from the international datasets and has been prepared according to the culture and environment of Iran. Also, it has been tried to record raw dataset movies from places and conditions that maintain a range of challenges (quality of movies, amount of light, diversity, etc. ) in the dataset. Field-of-view overlap exists among different cameras. Therefore, this dataset can be a good representative of the real world dataset.
These videos were recorded by cameras with different resolution quality in places such as Iran University of Science and Technology, Al-Aima Mosque, Arbaeen procession, local fruit shop and supermarket in Tehran, the details of which are given separately in the table below.

| Location  | Cameras | Total hours | Resolution |Num of day|
| ------  | :---:  | :---:  | :---:  | :---:  |
| Iran University of Science and Technology  | 17 | 383 h| Variable| 5|
| Al-Aima Mosque | 5 | 40 h| 960×1080 | 2|
| local fruit shop | 7 | 38 h | 944×1080 | 1 |
| local supermarket | 6 | 124 h | 1280×1944  | 4 |
| Arbaeen procession | 2 | 3 h | 1280×720 | 5 |

Currently, more than 270,000 frames containing 32,668 annotated border boxes with 1501 identities have been annotated among the prepared raw videos.Also, in terms of gender, this dataset contains 50 female identities and 20 male identities. The IRIUST dataset has four salient features:

First, it uses the YOLO model trained on the COCO dataset as a pedestrian detector.
Second, it uses the ByteTrack model trained on the Crowd Human dataset as pedestrian tracking.
Third, it uses the Gender Classification model trained on a portion of the same dataset as gender detector.
Fourth, because the above artificial intelligence models may not have sufficient efficiency (such as not detection when entering and leaving the camera range, not detection veiled people, not detection pedestrians' equipment, or ID Switching, etc.), human annotators modify the annotations made so that the least possible bugs occur in the training of the models in terms of the dataset.
To know the details of annotation rules, you can refer to the following link:

https://docs.google.com/document/d/1rZ8E1QVWvn_c9F-WZD

In the demo below, the reason for the inadequacy of using artificial intelligence models is obvious
https://github.com/IRIUST/Iranians_Reid_dataset/assets/141324225/fde81249-5d40-4a11-9be4-2117e11c2896

Also, this dataset includes images of people who are not in front of the camera with the same clothes.
Pay attention to the image below, this identity was present in several frames with a tent and in the rest of the frames with a mantle.

![2](https://github.com/IRIUST/Iranians_Reid_dataset/assets/141324225/ec09a671-b130-408a-aaa5-c405d2d81c08)

### Download dataset
The dataset package is can be downloaded from any of the following links:

[Link 1] (Google Drive)

### Bboxes naming convention
In bbox "D1_F29115_ID5.jpg", "D1" is the name of the first camera.

"F29115" is the 29115th frame in camera "D1".

"ID5" is the name of the 5th identity in synchronized cameras.

























Work progress report:

Time units are in movie half-hours(mhh)

All data: 548 + 216 houres

Partitioned data: 76 mhh

Bytrack outputs: 11 mhh

Cvat(refine bytrack) outputs:4 mhh

Cvat(refine bytrack) verify: 1 mhh

Reid outputs: 1 mhh is adapted in 2 cameras


<!-- [![Ashutosh's github activity graph](https://github-readme-activity-graph.cyclic.app/graph?username=Ashutosh00710)](https://github.com/ashutosh00710/github-readme-activity-graph) -->


![Screenshot (34)](https://github.com/Person-Reidentification/Person-Reidentification/assets/68585351/abdc7faf-dfb9-4039-8cd1-91ef79a9d517)
