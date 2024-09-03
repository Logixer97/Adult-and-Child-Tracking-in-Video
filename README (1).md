
# Adult and Child Tracker In Video

This project aims to build a person detector (specifically, only, child and adult) along with a tracking approach, to assign unique IDs to persons, and track them throughout the video. The proposed method should be able to:

Assign Unique IDs: The aim is to assign unique IDs to persons and track them throughout the video.

Track Re-entries: The proposed method should be able to track the person if he/she goes out and re-enters the frame. This includes multiple children and adults.

Assign New IDs: Assign a new ID to a person entering the frame for the first time.









## Deployment

To deploy this project run

```bash
  pip install -r requirements.txt
```
```bash
  pip install -r ultralytics
```
```bash
  python track_v8.py --source path_to_input_video.mp4 --track --count
```
Here you should add input video of .mp4 format. and give the path of that input video in place of "path_to_input_video.mp4".

After running this an output file will be created and the output video of the model will be saved there





## About custommodel.pt
This is customly trained a yolov8n model. I train this model to detect child and Adult. The data set used to train is linked below

Data set link-https://universe.roboflow.com/idan-kideckel-67kqi/children-and-adults/dataset/1