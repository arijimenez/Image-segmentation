----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Computer Vision Midterm:
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Image segmentation is a process in computer vision that involves dividing an image into multiple segments or regions, each corresponding to a different object or region of interest within the image. Image segmentation aims to simplify an image's representation and make it easier to analyze or understand.

Some key points about image segmentation:

-Object Identification: Image segmentation is used to identify and isolate specific objects or regions within an image. This could include separating foreground objects from the background or distinguishing between different objects in the scene.
-Pixel-level Classification: It involves classifying each pixel in an image into a specific category or label. For example, in a medical image, segmentation might be used to separate different types of tissues or organs.
-Boundaries or Contours: Segmentation can also involve identifying the boundaries or contours that define the edges of objects within an image. This is useful for tasks like object recognition or tracking.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------
Applications:
---------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Medical Imaging: Segmentation identifies and isolates organs or abnormalities in medical images like MRI or CT scans.
-Autonomous Vehicles: It's crucial for tasks like lane detection, object detection, and obstacle avoidance.
-Satellite and Aerial Imagery: Used for land cover classification, urban planning, and environmental monitoring.
-Robotics: Helps robots identify and interact with objects in their environment.
-Computer Graphics: Used for tasks like image-based rendering and special effects.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Deployment steps:
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-Clone this repository
-cd jetson-inference
-docker.run/sh
-cd python
-cd examples
-./segnet.py --network=FCN-ResNet18-MHP-512x320 /dev/video0

