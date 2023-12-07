# Image Segmentation using U-Net Model

## Dataset:

The project utilizes the Oxford Pets - IIIT dataset for model training. This dataset includes pet images, their classes, segmentation masks, and regions of interest in the head. For this experiment, we will focus on using only the images and segmentation masks.

The dataset comprises images of 37 pet breeds, with 200 images per breed (~100 each in the training and test splits). Each image is associated with a corresponding label and pixel-wise masks. The masks categorize each pixel into one of three classes:

- **Class 1:** Pixel belonging to the pet.
- **Class 2:** Pixel bordering the pet.
- **Class 3:** None of the above/surrounding pixel.

## Learning Objectives:

Upon completing this project, you will gain the following learning objectives:

1. **Understand, Prepare, and Visualize Dataset:**
    - Gain proficiency in understanding, preparing, and visualizing a dataset containing images and their corresponding masked images used for segmentation.

2. **Understand U-Net Architecture:**
    - Comprehend the encoder, bottleneck, and decoder regions of a U-Net architecture for image segmentation.

3. **Build and Train U-Net Architecture:**
    - Acquire skills to build and train a U-Net architecture for image segmentation tasks.

4. **Create Masked Image (Prediction):**
    - Implement the U-Net model to generate masked images as predictions for segmentation.

5. **Evaluate Segmentation Performance:**
    - Calculate accuracy scores like Intersection over Union (IoU) and Dice-Score commonly used in image segmentation evaluations.

6. **Understand and Implement DeeplabV3+ Architecture:**
    - Gain insights into the DeeplabV3+ architecture and implement it for image segmentation.

## Files Contained in the Project:

- **`Image_Segmentation_using_UNet_Model.ipynb`**: Jupyter notebook containing the project implementation and experimentation.

## Usage:

1. Clone the repository:

```bash
git clone https://github.com/Praveen76/Image_Segmentation_using_UNet_Model.git
cd Image_Segmentation_using_UNet_Model
```

2. Open and explore the Jupyter notebook `Image_Segmentation_using_UNet_Model.ipynb` to understand the project implementation.

3. Execute the code cells within the notebook to experiment with image segmentation using the U-Net model.

4. Visualize the results and interpretations.

Feel free to contribute, report issues, or suggest improvements!

## Contributing

If you have a Data Science mini-project that you'd like to share, please follow the guidelines in [CONTRIBUTING.md](https://github.com/Praveen76/Data-Science-Mini-Projects/blob/main/contributing.md).

## Code of Conduct
Please adhere to our [Code of Conduct](https://github.com/Praveen76/Data-Science-Mini-Projects/blob/main/CODE_OF_CONDUCT.md) in all your interactions with the project.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or inquiries, feel free to contact me on [Linkedin](https://www.linkedin.com/in/praveen-kumar-anwla-49169266/).

## **About Me**:
I’m a seasoned Data Scientist and founder of [TowardsMachineLearning.Org](https://towardsmachinelearning.org/). I've worked on various Machine Learning, NLP, and cutting-edge deep learning frameworks to solve numerous business problems.
