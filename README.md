# Object_Recognition_On_Drone
The goal of this project is to identify objects of interest in a scene, where an object detection is ran on a live video data transmitted wirelessly from drone to ground station using an HDMI transmitter/receiver configuration.

<h3>Object Recognition</h3>
<ul>Object detection is a computer vision technique that works to identify and locate objects within an image or video.</ul>

<ul>Specifically, object detection draws bounding boxes around these detected objects, which allow us to locate where said objects are in (or how they move through) a given scene. </ul>

<ul>Objects are detected using Single Shot MultiBox Detector (SSD)), a convolutional approach, and this model can detect up to 90 different objects. </ul>

<ul>The model is trained over COCO dataset using Tensorflow API and converted to Tensorflow Lite to run on power efficient devices (i.e. IoT devices) like Raspberry pi </ul>
