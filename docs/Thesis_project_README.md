# A Novel NeRF-based Approach for Extracting Single Objects and Generating Synthetic Training Data for Grasp Prediction Models 

## Abstract
One of the main challenges in robotic manipulation is to grasp previously unseen objects without
prior knowledge. State-of-the-art methods rely on dedicated machine learning models which are
trained on RGB-Depth (RGB-D) images and annotated labels to predict grasp poses in unstructured
environments and for a wide range of previously unseen objects. Collecting a diverse and labeled
dataset, however, can be time-consuming and costly. To overcome these challenges, we propose
to use Neural Radiance Fields (NeRF) to generate RGB-D images and to combine these with a
cutting-edge automatic-labeling approach to create data for training grasp prediction networks.

The main contribution of this thesis is a novel method for obtaining individual NeRFs for objects of
interest and backgrounds. The method requires two input scenes: a complete scene containing an
object of interest and the same scene but without the object. The steps of the method include training
a NeRF on the background scene, aligning it with the object scene, combining it with another NeRF
to be trained on the object scene, and joint optimization of both NeRFs with depth regularization
loss added to NeRF loss. By applying this approach to various datasets, it is possible to create a
library of trained object and background NeRFs. Arbitrary combinations of these NeRFs can then
be used to generate novel scenes and render synthetic images for training detection networks.

In a comprehensive ablation study, we employ our approach to create four distinct datasets, apply an
automatic labeling pipeline to them and use them to train corresponding grasp prediction networks.
The results validate the viability of NeRF-generated data for training detection models, showcasing
a performance nearly on par with real data. Furthermore, our approach unveils exciting potential for
scalability by facilitating the generation of novel data.

Overall, this research advances the field of robotic manipulation by proving the potential of
using NeRF-generated synthetic data and novel scenes to train robust grasp prediction models for
real-world applications.

## Main Objectives

  1. Object Extraction via NeRFs: Utilize Neural Radiance Fields (NeRFs) to extract individual objects effectively.
  2. Composition of Realistic Scenes: Combine multiple NeRFs representing various objects and backgrounds to create diverse and lifelike scenes.
  3. Synthetic Dataset Generation: Generate a synthetic dataset leveraging NeRF technology for training purposes.
  4. Training Grasp Prediction Networks: Train a grasp prediction network using the generated synthetic dataset.
  5. Training on Real Data: Train another grasp prediction network using real-world datasets for comparative analysis.
  6. Performance Evaluation: Evaluate and compare the performance of both networks using real-world datasets to assess their effectiveness.

## Methodology
Will be added later

## Results
Highlight the outcomes achieved. This could involve metrics, successful implementations, or any notable findings. Visual aids like charts, graphs, or screenshots can be helpful here.

## Installation
The code is confidential and cannot be shared

## Contributing
A Novel NeRF-based Approach for Extracting Single Objects and Generating Synthetic Scenes  

## License
Specify the license under which the project is distributed.
