# Part of the master thesis project

A Novel NeRF-based Approach for Extracting Single Objects and Generating Synthetic Training Data for Grasp Prediction Models 
(docs/Thesis_project_README)

## Main Objectives

  1. Object Extraction via NeRFs: Utilize Neural Radiance Fields (NeRFs) to extract individual objects effectively.
  2. Composition of Realistic Scenes: Combine multiple NeRFs representing various objects and backgrounds to create diverse and lifelike scenes.
  3. Synthetic Dataset Generation: Generate a synthetic dataset leveraging NeRF technology for training purposes.
  4. Training Grasp Prediction Networks: Train a grasp prediction network using the generated synthetic dataset.
  5. Training on Real Data: Train another grasp prediction network using real-world datasets for comparative analysis.
  6. Performance Evaluation: Evaluate and compare the performance of both networks using real-world datasets to assess their effectiveness.

## Datasets

1. For NeRF training: dataset should consist of images and their corresponding camera information (extrinsics, intrinsics). 
* camear infromation ccould be estimated using structure from motion approachs (COLAP, DSO)
* folder-per-sample or folder-per-category (default)

## Methodology
Will be added later

## Results
The final synthized dynamic scene:
1. Scene 1
  ![alt text](https://github.com/anasmobasher/NeRF_Novel_Scene_Synthesis/blob/main/docs/pics/scene1.gif?raw=true)
2. Scene 2
  ![alt text](https://github.com/anasmobasher/NeRF_Novel_Scene_Synthesis/blob/main/docs/pics/Scene2.gif?raw=true)

## Installation
1. Train a standered NeRF on the background dataset from the nerf_base_module
2. Train using the trained Background NeRF on the object dataset using nerf_combine_module
3. Using nerf_EvalSynthmulti.py to generate scenes form the trained Object NeRFs and Background NeRFs.  
4. 
## Contributing
A Novel NeRF-based Approach for Extracting Single Objects and Generating Synthetic Scenes  

## License
