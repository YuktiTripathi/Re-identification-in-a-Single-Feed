# Re-identification-in-a-Single-Feed
This project demonstrates player tracking and re-identification in a single video feed using a custom YOLOv11 model and ByteTrack.

### Dependencies:

ultralytics

opencv-python

### Environment Requirements
Python 3.x, access to a GPU (highly recommended for YOLO inference, though CPU will work, albeit slower).

### Setup:

Ensure you have Python installed.

### Install required libraries:

!pip install ultralytics opencv-python.

Download the input video (15sec_input_720p.mp4) and the custom YOLOv11 model (best.pt) and place them in the specified paths within the script (or adjust the VIDEO_PATH and MODEL_PATH variables). For Kaggle, ensure these are correctly added as dataset inputs.

### Run: Execute the Python script: python your_script_name.py.

