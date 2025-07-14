# <span style="color:deepskyblue"> Real-time Object Detection and Tracking with YOLOv8 & Streamlit </span>

This  project showcasing the seamless integration of **object detection and tracking** using **YOLOv8** (object detection algorithm), along with **Streamlit** (a popular Python web application framework for creating interactive web apps). The project offers a user-friendly and customizable interface designed to detect and track objects in real-time video streams from  YouTube URLs, as well as static videos and images.


## Requirements

Python 3.6+
YOLOv8
Streamlit
Python-opencv

```bash
pip install ultralytics streamlit pytube
```

## Installation

- Clone the repository: git clone <https://github.com/dev-vikash2v7/VisionTrackAI.git>
- Change to the repository directory: `cd VisionTrackAI`
- pip install -r requirements.txt
- 
## Usage

- Run the app with the following command: `streamlit run app.py`
- The app should open in a new browser window.

### Detection on images / videos

- Select a source. (radio button selection `Image / Video`).
- Upload an image/video by clicking on the "Browse files" button.
- Click the "Detect Objects" button to run the object detection algorithm on the uploaded media with the selected confidence threshold.
- The resulting media with objects detected will be displayed on the page. Click the "Download " button to download the media.



### Detection on YouTube Video URL

- Select the source as YouTube
- Copy paste the url inside the text box.
- The detection/segmentation task will start on the YouTube video url

<https://user-images.githubusercontent.com/104087274/226178296-684ad72a-fe5f-4589-b668-95c835cd8d8a.mov>
