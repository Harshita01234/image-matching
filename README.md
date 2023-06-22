# image-matching
IMAGE MATCHING - RECONSTRUCT 3D SCENES FROM 2D
Problem Statement :
    Your best camera may just be the phone in your pocket. You might take a snap of a landmark, then share it with friends. By itself, that photo is two-dimensional and only includes the perspective of your shooting location. Of course, many people may have taken photos of that same landmark. If we were able to combine all of our photos, we may be able to create a more complete, three-dimensional view of any given thing and this is what we aim in this project. Our objective is building a 3D model of a scene given an unstructured collection of images taken around it.

Project Introduction :
    The project utilizes computer vision algorithms to align images, enabling the reconstruction of 3D scenes from 2D models. It leverages techniques such as feature extraction, image registration, and structure-from-motion to produce accurate and detailed 3D representations.
    KEY FEATURES :
    - Image matching algorithms
    - Visualization of reconstructed 3D scenes

Installation :
    To set up the project,
    - I started by importing the libaries that are required for the project (like - panda, numpy etc.)
    - Additional installation -  https://raw.githubusercontent.com/colmap/colmap/dev/scripts/python/read_write_model.py

    - for Dataset - https://www.kaggle.com/competitions/image-matching-challenge-2023/overview
    I have downloaded from here.

Usage : 
    1. Gather a collection of 2D images capturing the scene you want to reconstruct.
    2. Run the image matching algorithm
    3. The algorithm will start matching and aligning the images. Progress updates and relevant information will be displayed in the console or log files.
    4. after the reconstruction is complete, you can visualize the 3D scene.

