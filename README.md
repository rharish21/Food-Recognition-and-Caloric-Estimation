# Deep Learning Food Image Recognition and Calorie Estimation

This project uses deep learning to recognize food items from images and estimate their calorie content, with improvements and additional features for better usability and performance.

---

## Features

- **Food Recognition**: Uses a deep learning model to identify food items from images.
- **Calorie Estimation**: Estimates the calorie content of recognized food items.
- **Improved Model**: Enhanced model accuracy and performance.
- **User-Friendly Interface**: Simplified setup and execution steps.

---

## Technologies Used

- **Python**: Core programming language.
- **TensorFlow/Keras**: For building and training the deep learning model.
- **OpenCV**: For image processing.
- **NumPy**: For numerical computations.
- **Pandas**: For data handling and calorie estimation.

---

## How to Use

### Prerequisites

1. **Python 3.8+**: Ensure Python is installed on your system.
2. **Git**: To clone the repository.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/rharish21/Food-Recognition-and-Caloric-Estimation.git
```

2. Navigate to the project directory:

```bash
cd DeepLearning-Food-Image-Recognition-And-Calorie-Estimation
```
3. Install the required dependencies:

```bash
pip install -r requirements.txt
```
## Running the Model

1. Prepare the Dataset:

- Place your food images in the data/images directory.

- Ensure the images are labeled correctly for training.

- Train the Model:

2. Run the training script:

```bash
python train.py
```
3. The model will be saved in the models directory.

## Test the Model:

1. Run the testing script with an image:

```bash
python test.py --image_path data/test_image.jpg
```

2. The script will output the recognized food item and its estimated calorie content.

## Calorie Estimation:

- The calorie estimation is based on predefined values in the data/calorie_data.csv file.

- You can update this file with your own data for more accurate estimations.

## Improvements Over the Original

- Clear Execution Steps: Added detailed instructions for setting up and running the model.

- Enhanced Model Performance: Improved the deep learning model for better accuracy.

- User-Friendly Interface: Simplified the process of training and testing the model.

- Documentation: Added comprehensive documentation for better understanding and usage.

## Future Enhancements

1. Real-Time Recognition: Implement real-time food recognition using a webcam.

2. Mobile App: Develop a mobile application for on-the-go calorie estimation.

3. Database Integration: Integrate with a food database for more accurate calorie data.

4. User Feedback: Allow users to provide feedback to improve the model.


## Acknowledgments

**Deep Learning Project by [jubins](https://github.com/jubins/DeepLearning-Food-Image-Recognition-And-Calorie-Estimation)**

**Contributors and open-source community**
