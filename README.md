# OpenCV

# Object Detection System

This project implements object detection using the OpenCV library and pre-trained deep learning models. It consists of two components: one for object detection without a graphical user interface (GUI) and one for object detection with a GUI.

## Object Detection without GUI:

### Overview:

The object detection system without GUI focuses on real-time object detection in video streams and webcam feeds. It utilizes the OpenCV library and a pre-trained deep learning model to detect objects and annotate them with bounding boxes and labels.

### Features:

- Real-time object detection in video streams
- Object detection in live webcam feeds
- Highlighting detected objects with bounding boxes and labels
- Recording output videos with annotated objects

### Usage:

1. **Processing Video Files:**
   - Use the `process_video()` function to detect objects in a selected video file.
   - Configure the necessary parameters and call `object_detector.process_video()` to initiate the process.

2. **Processing Webcam Feed:**
   - Utilize the `process_webcam()` function to detect objects in the live webcam feed.
   - Call `object_detector.process_webcam()` to start real-time object detection.

## Object Detection with GUI:

### Overview:

The object detection system with GUI provides a user-friendly interface for object detection. Users can interact with the GUI to select video files or webcam feeds, adjust detection settings, and visualize the detected objects in real-time with annotations.

### Features:

- Graphical user interface for object detection
- Interactive selection of video files or webcam feeds
- Adjustable detection settings (confidence threshold, NMS threshold, etc.)
- Visual representation of detected objects with bounding boxes and labels

### Usage:

1. **Launching the GUI:**
   - Run the `gui_main.py` script to launch the object detection system with GUI.
   - Interact with the GUI to perform object detection tasks.

2. **Configuring Detection Settings:**
   - Use the GUI controls to adjust detection parameters and fine-tune the object detection process.
   - See real-time updates of detected objects in the video feed.

### Additional Notes:

- Both components of the object detection system leverage the power of OpenCV and deep learning models for accurate object detection.
- Feel free to explore and customize the system further to suit your specific requirements and use cases.

---

This comprehensive README provides detailed information on both components of the object detection system - "Object Detection without GUI" and "Object Detection with GUI", outlining their features, usage guidelines, and interactive capabilities.





