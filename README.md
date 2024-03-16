# Object-Detection-Using-zero-shot-grounding-dino-model
Detecting objects using zero shot grounding dino model

# Zero-Shot Object Detection
Zero-shot object detection is a computer vision task to detect objects and their classes in images, without any prior training or knowledge of the classes. Zero-shot object detection models receive an image as input, as well as a list of candidate classes, and output the bounding boxes and labels where the objects have been detected.

# About Zero-Shot Object Detection

## Use Cases
Zero-shot object detection models can be used in any object detection application where the detection involves text queries for objects of interest.

## Object Search
Zero-shot object detection models can be used in image search. Smartphones, for example, use zero-shot object detection models to detect entities (such as specific places or objects) and allow the user to search for the entity on the internet.

## Object Counting
Zero-shot object detection models are used to count instances of objects in a given image. This can include counting the objects in warehouses or stores or the number of visitors in a store. They are also used to manage crowds at events to prevent disasters.

## Object Tracking
Zero-shot object detectors can track objects in videos.


# Grounding Dino
Grounding DINO is a zero-shot object detection model made by combining a Transformer-based DINO detector and grounded pre-training.
Grounding DINO is a cutting-edge zero-shot object detection model that marries the powerful DINO architecture with grounded pre-training. Developed by IDEA-Research, Grounding DINO can detect arbitrary objects based on human inputs, such as category names or referring expressions.

Key components of Grounding DINO
1. Image Backbone: Extracts essential features from input images.
2. Text Backbone: Extracts text-based features from corresponding descriptions.
3. Feature Enhancer: Fuses image and text features, facilitating cross-modality information exchange.
4. Language-Guided Query Selection: Initializes queries using language information.
5. Cross-Modality Decoder: Predicts bounding boxes based on the fused features and queries.

![image](https://github.com/AkhilJx/Object-Detection-Using-zero-shot-dino-model/assets/78065413/88a26a75-3431-4439-bed3-d3865bfab45a)


## Useful Resources
https://huggingface.co/docs/transformers/tasks/zero_shot_object_detection

https://blog.roboflow.com/grounding-dino-zero-shot-object-detection/

https://roboflow.com/model/groundingdino

https://www.ikomia.ai/blog/grounding-dino-zero-shot-detection-explained#:~:text=Grounding%20DINO%20is%20a%20cutting,category%20names%20or%20referring%20expressions.
