# LiteRT Android for Object Detection
This project is an implementation of converting the YOLO11 object detection model to LiteRT (.tflite) format and deploy it on Android using Google AI Edge for on-device inference.


## Steps to run:

1. Clone the repository on your local machine.
2. Open the [Colab notebook](https://colab.research.google.com/github/gy6543721/LiteRT/blob/initial/LiteRT.ipynb) to export YOLO11 to LiteRT (TF Lite) format.
3. Download the LiteRT model on your local machine and copy it in the `assets` folder in Android Project.
4. Open the `Android_App` project in Android Studio and let it build.
5. Install the app on your phone and enjoy real-time object detection on Android.
