
## Large Shape & Textures (LAS&T) Dataset 

# [MAIN WebPage for  (LAS&T) Dataset](https://sites.google.com/view/lastdataset/home) 

## Addtional sources: (zenodo)[https://zenodo.org/records/15453634], [Kaggle](https://www.kaggle.com/datasets/sagieppel/las-and-t-large-shape-and-texture-dataset)
## Code related to the paper [Shape and texture recognition in large vision-language models](https://arxiv.org/pdf/2503.23062)



LAS&T is the largest and most diverse dataset for shape, texture and material recognition and retrieval in 2D and 3D with 650,000 images, based on real world shapes and textures.
Overview

The LAS&T Dataset aims to test the most basic aspect of vision in the most general way. Mainly the ability to identify any shape, texture, and material in any setting and environment, without being limited to specific types or classes of objects, materials, and environments. For shapes, this means identifying and retrieving any shape in 2D or 3D with every element of the shape changed between images, including the shape material and texture, orientation, size, and environment. For textures and materials, the goal is to recognize the same texture or material when appearing on different objects, environments, and light conditions. The dataset relies on shapes, textures, and materials extracted from the real world, images leading to almost unlimited quantity and diversity of real-world natural patterns. Each section of the dataset (shapes, and textures), contains 3D parts that rely on physics-based scenes with realistic light materials and object simulation and abstract 2D parts. In addition, the real-world benchmark for 3D shapes.
 
## The dataset contain four parts parts:

(3D shape recognition and retrieval)[https://sites.google.com/view/lastdataset/home#h.92xq3mv1tfg7]

(2D shape recognition and retrieval)[https://sites.google.com/view/lastdataset/home#h.76i1qp3jyirq]

(3D Materials recognition and retrieval)[https://sites.google.com/view/lastdataset/home#h.k87sv8vbo94w]

(2D Texture recognition and retrieval)[https://sites.google.com/view/lastdataset/home#h.1426e7197024]

Each can be used independently for training and testing.

Additional assets are a set of 350,000 natural 2D shapes extracted from real-world images (SHAPES_COLLECTION_350k.zip)[https://zenodo.org/records/15453634/files/SHAPES_2D_365k.zip?download=1]

3D shape recognition (real-world images benchmark)[https://zenodo.org/records/15453634/files/Real_Images_3D_shape_matching_Benchmarks.zip?download=1]

## Scripts

2) Code for a) 2D shape extraction from images and b) generation of 2D shapes and textures matching test available from: [this url](https://github.com/sagieppel/Automatic-Extraction-Of-Shapes-From-Images-Shape-dataset-generation-)
4) Collection of 400k  2D shapes extracted from real images can be found in these urls: [12k shapes](https://drive.google.com/file/d/1Mb6aYvcwqRGdydCY7AFdvs1zwR8JpOwQ/view?usp=drive_link),[350k shapes](https://icedrive.net/s/G2VGh2Cu7PDgDTkDg2Xy1266hQ74)
5) [Code for generating 3D objects/shapes matching tests](https://github.com/sagieppel/Generate_3D_Shape_Recognition_and_Retrieval_Synthetic_Dataset_Blender).
6) Samples of the 3D shape matching tests: [Zenodo](https://zenodo.org/records/14681299), [Google drive](https://drive.google.com/drive/folders/1pxSnX-qpBfcQ47BbPQmy8pbURk0vXMzu?usp=drive_link), [Pcloud](https://e.pcloud.link/publink/show?code=kZz7FKZ8xfKSIHppBShSuU65cxBvQkorVXV).
7) [Code for testing/evaluating LVLMs using the LAS&T dataset](https://github.com/sagieppel/Testing-Large-Vision-Language-Models-LVLM-on-visual-questions).
