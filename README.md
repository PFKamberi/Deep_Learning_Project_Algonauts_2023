# Deep Learning Final Project - How the Human Brain Makes Sense of Natural Scenes

This project was implemented in the context of the Deep Learning course during our studies at the MSc of Data Science program of the NCSR Demokritos and the University of the Peloponnese. The project is based on the [Algonauts Project 2023](http://algonauts.csail.mit.edu/index.html)).

## Implementation Steps:

1. **Data Acquisition:** 
   - We used the data provided by the Algonauts Project 2023. The data can be accessed using the [Guide_to_access_the_data.ipynb]([link-to-guide](https://github.com/PFKamberi/Deep_Learning_Project_Algonauts_2023/blob/main/Guide_to_access_the_data.ipynb)) notebook.

2. **Transfer Learning and Linearizing Encoding Models:**
   - We utilized transfer learning based on pretrained image models (ResNet50 and VGG16) to create linearizing encoding models. These models are required to solve the problem of mapping images to brain voxel values.
   - The models for ResNet50 and VGG16 are located in their respective folders. The notebooks are named as DL_{pretrained model name}_{LEFT OR RIGHT}_HEMISPHERE.ipynb.

3. **Model Evaluation:**
   - We conducted comprehensive evaluations of each model in the DL_{pretrained model name}_EVALUATION.ipynb notebooks.

4. **Trained Model Files:**
   - For the ResNet50 model, we provide the .pt files of the trained model, which can be found in the models subfolder of the ResNet50 folder.
   - Unfortunately, due to the large size of the trained model, the VGG16 model files were not uploaded to GitHub.

5. **Demo and Showcase:**
   - We provide a demo showcasing the capabilities of the ResNet50-based model. The demo includes both test images and external images.

6. **Requirements:**
   - The requirements for this project in terms of Python packages can be found in the [requirements.txt](link-to-requirements) file.

Please refer to the individual notebooks and folders for more detailed information on each step of the implementation.
