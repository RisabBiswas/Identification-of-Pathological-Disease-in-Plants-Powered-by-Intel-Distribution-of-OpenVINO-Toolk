# Overview
In modern Agriculture and Forestry purposes Plant Pathological Research is very much essential for the crop improvement. In every year, huge crop is damaged by pathogen attack. In most of the cases, Farmers and lay men suffers huge loss due to severe pathogenic infestation. For crop improvement, the first and foremost essential key point is diseases identification. After proper identification of diseases we will be able to treat the diseases. Most of the cases lab oriented research is time taking and very much expendable but instant identification of plant diseases with its causal organism by using modern technology is most suitable and cost effective and also authentic. This type identifying methodology will help us to identify the diseases with its proper control measures. Above 95 % accuracy and authentic identification is possible by using this methodology.

## Identified Diseases are :

1. Blister Blight of Tea (Family: Theaceae)
2. Citrus Canker (Happens in Citrus Plants, Family: Rutaceae)
3. Early Blight (Happens in Tomato, Potato and Egg Plant, Family: Solanaceae)
4. Late Blight (Happens in Tomato, Potato and Egg Plant, Family: Solanaceae)
5. Powdery Mildew (Happens in Wheat, Barley and other Cereals, Legumes, Grape, Gourds and melons, infection happens more in cucurbitaceae family)

This methodology finds it's application in Agriculture, Horticulture, Floriculture, Forestry and every aspect of crop improvement.


## Methodology and Architecture :

**1. Architecture:** The model is having two variants, One built in Faster RCNN and the other in SSD Mobilenet (ssd_mobilenet_v2_coco). Final one is on the SSD Mobilenet, as SSD Mobilenet model is well supported by both OpenVino and TensorFlow Lite.
**2. Back-end Framework:** Intel Optimized TensorFlow.
**3.** OpenCV for the Computer Vision Algorithm building.
**4. Dataset:** High Quality Images taken from Google Images using Web Crawling. Actually this is one of the bottleneck's I am facing. Since going into the fields and clicking images is one of the most tedious and time consuming approach that's why I went for the images available on the internet.But, for my present approach I need high quality and a huge amount of data, as the classes are increasing. I will gather the images and create my own Dataset. In future that can be open sourced so that people can use that.
**5. Log Loss:** I am able to drop down the log loss up-to 0.0173 at a step count of 32,517 after 14 hours of training. In terms of accuracy, as the inference shows that it ranges between 85-95%, depending upon the image or image that has been provided for the inference.
**6. Mobile Application:** The mobile application is being built for the Android Platform as of now. I am using TensorFlow Lite and Android Studio for building it.
**6.** Model Optimization and Inference on PC/Laptop or any other edge device other than Smart phone is being carried out by Intel Distribution of the OpenVino ToolKit.

## Technologies Used :

### Hardware Stack :-

**1.** Intel AI DevKit.
**2.** Intel RealSense Camera.
**3.** Intel AI DevCloud.

### Software Stack :-

**1.** Intel Optimised Python.
**2.** Intel Optimised TensorFlow
**3.** TensorFlow Lite.
**4.** Intel's OpenVino ToolKit for Computer Vision.
