### Description:
This is an exercise for the `Bootcamp - Microsoft AI for Tech – Creating Intelligent Prompts` by [DIO](https://www.dio.me/).<br>

The [documentation](https://github.com/MariWB/fashion-detection/edit/master/README.md#result) for this project was created with AI based on good prompt engineering practices.

### AI:
Used the `Copilot` with the `Think Deeper` as the motor.

### Prompt for generating documentation:

Using the data from the original [README](https://github.com/lcarli/fashion-detection/blob/dcad49b4f97666ab6ca7f56dec67a43de46e1afb/README.md) as a basis, I created this prompt to ask for the creation of project documentation:

```bash
You are an experienced and organized programmer and need to document your project on GitHub by creating a clear, intuitive, and detailed README using markdown.
Create the project documentation that I will detail below. 
Use all the information to create the README with markdown: 

Project name: Fashion Detection in the Wild (Deep Clothes Detector) 
Ziwei Liu detailed document link: https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Liu_DeepFashion_Powering_Robust_CVPR_2016_paper.pdf 
Overview: Deep Clothes Detector is a clothes detection framework based on Fast R-CNN. Given a fashion image, this software finds and locates potential upper-body clothes, lower-body clothes and full-body clothes in it, respectively. 
Requirements Fast R-CNN: https://github.com/rbgirshick/fast-rcnn 
EdgeBox: https://github.com/pdollar/edges 
Piotr's Computer Vision Toolbox: https://github.com/pdollar/toolbox 
Getting started Install and compile the Fast R-CNN, EdgeBox and Piotr's Computer Vision Toolbox libraries. 
Download the pre-trained model fashion_detector.caffemodel (https://drive.google.com/open?id=0B7EVK8r0v71pUlZjeGZuNWZLaFU): 
Place "fashion_detector.caffemodel" into "./models/" 
Run the testing script: matlab ./demo.m 
Dataset http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html 
License and Citation The use of this software is RESTRICTED to non-commercial research and educational purposes. 
@inproceedings{liu2016deepfashion, author = {Ziwei Liu, Ping Luo, Shi Qiu, Xiaogang Wang, and Xiaoou Tang}, title = {DeepFashion: Powering Robust Clothes Recognition and Retrieval with Rich Annotations}, booktitle = {Proceedings of IEEE Conference on Computer Vision and Pattern Recognition (CVPR)}, month = {June}, year = {2016} }

```

---

# RESULT:

# Fashion Detection in the Wild (Deep Clothes Detector)

**Deep Clothes Detector** is a clothes detection framework based on **Fast R-CNN**. Given a fashion image, this software identifies and localizes potential upper-body clothes, lower-body clothes, and full-body clothes, respectively.

---

## Overview

<img src='./misc/demo.gif' width=280>

`Deep Clothes Detector` leverages the robustness of [Fast R-CNN](https://github.com/rbgirshick/fast-rcnn) to power a fashion-oriented clothes detection system. This framework is specifically designed to detect multiple clothing regions within fashion images, including:
- Upper-body clothes
- Lower-body clothes
- Full-body clothes
<br>
<img src='./misc/demo_teaser.jpg' width=600>


## Ziwei Liu Documentation
For detailed technical insights, refer to the [official paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Liu_DeepFashion_Powering_Robust_CVPR_2016_paper.pdf).

---

## Requirements

To run this project, you'll need the following dependencies:

- **Fast R-CNN**: [GitHub Repository](https://github.com/rbgirshick/fast-rcnn)
- **EdgeBox**: [GitHub Repository](https://github.com/pdollar/edges)
- **Piotr's Computer Vision Toolbox**: [GitHub Repository](https://github.com/pdollar/toolbox)

Ensure these libraries are installed and properly configured in your environment.

---

## Getting Started

Follow these steps to set up and run the project:

1. **Install Dependencies**  
   Install and compile the required libraries:  
   - [Fast R-CNN](https://github.com/rbgirshick/fast-rcnn)  
   - [EdgeBox](https://github.com/pdollar/edges)  
   - [Piotr's Computer Vision Toolbox](https://github.com/pdollar/toolbox)

2. **Download the Pre-trained Model**  
   Download the pre-trained model `fashion_detector.caffemodel` from this link:  
   [fashion_detector.caffemodel](https://drive.google.com/open?id=0B7EVK8r0v71pUlZjeGZuNWZLaFU)

3. **Place the Model**  
   Move the `fashion_detector.caffemodel` file into the `./models/` directory.

5. **Run the Testing Script**  
   Execute the testing script using MATLAB:  
   ```bash
   matlab ./demo.m
   
## Dataset
The project utilizes the DeepFashion Dataset, which is available here: DeepFashion Dataset

## License and Citation
The use of this software is RESTRICTED to non-commercial research and educational purposes.

If you use this software or its associated dataset in your work, please cite the following paper:

```
@inproceedings{liu2016deepfashion,
 author = {Ziwei Liu, Ping Luo, Shi Qiu, Xiaogang Wang, and Xiaoou Tang},
 title = {DeepFashion: Powering Robust Clothes Recognition and Retrieval with Rich Annotations},
 booktitle = {Proceedings of IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
 month = {June},
 year = {2016} 
}
```

