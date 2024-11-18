# Object-Detection-for-Blind-Assistance

This project provides a simple and efficient object detection system to assist visually impaired individuals. It detects objects in images and announces them via audio feedback, making navigation and awareness more accessible.


**Features**

**Object Detection:** Uses a pre-trained SSD MobileNet V2 model to identify objects in images.

**Audio Feedback:** Announces detected objects using Google Text-to-Speech (gTTS).

**Extended Labels:** Customizable to include essential objects like guide dogs, canes, etc.

**Visualization:** Displays bounding boxes and labels for detected objects.

**Setup**

Clone the repository and install required libraries:

bash

Copy code

pip install tensorflow opencv-python gtts matplotlib  

Run the object_detection_with_speech.py script in Google Colab or locally.

Upload an image, and the system will detect objects and provide audio output.

**Usage**

Image Input: Upload an image for detection.

Speech Output: Listen to the names of detected objects announced aloud.

Visualization: View labeled images with bounding boxes.

**Acknowledgments**

TensorFlow Model Zoo for the pre-trained SSD MobileNet V2 model.

Google Text-to-Speech for generating audio output.

Contributions and suggestions are welcome!
