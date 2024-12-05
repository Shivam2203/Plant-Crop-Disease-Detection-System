# Plant Disease Detection System

## Overview
The Plant Disease Detection System is an innovative application designed to assist farmers and agricultural professionals in the early identification of plant diseases. By leveraging advanced machine learning techniques, this system provides accurate predictions based on images of plant leaves, enabling timely intervention and better crop management.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- **User-Friendly Interface**: Built with Streamlit, the application offers an intuitive web interface for easy interaction.
- **Real-Time Predictions**: Users can upload images of plant leaves and receive instant predictions regarding potential diseases.
- **Comprehensive Disease Classification**: The model is trained to recognize multiple plant diseases, providing detailed insights for various crops.
- **Fast and Efficient**: The system processes images quickly, allowing for rapid decision-making in agricultural practices.

## Technology Stack
- **TensorFlow**: For building and training the machine learning model.
- **Streamlit**: For creating a web-based interface to interact with the model.
- **Python**: The primary programming language used in the project.
- **NumPy**: For numerical operations and image processing.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For visualizing data and model performance.

## Installation
To set up the project locally, follow these steps:

### Clone the Repository

git clone https://github.com/Shivam2203/Plant-Crop-Disease-Detection-System.git

cd Plant-Crop-Disease-Detection-System


## Usage
### Run the Streamlit App
1. **Start the Application**:
   Launch the Streamlit app by executing the following command in your terminal:
   ```bash
   streamlit run main.py
   ```

2. **Upload an Image**:
   Navigate to the "Disease Recognition" page, and upload an image of a plant leaf suspected of being diseased.

3. **View Predictions**:
   Click on the "Predict" button to see the model's prediction regarding the plant's health.

## Dataset
The dataset used for training the model consists of approximately 87,000 RGB images of plant leaves, encompassing both healthy and diseased samples. The images are categorized into 38 distinct classes, covering a diverse range of plant species and diseases.

### Dataset Source
You can download the dataset from Kaggle:
- [Plant Disease Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)

## Model Training
The model is trained using TensorFlow and Keras. The training process involves:
- Preprocessing the images to a uniform size.
- Splitting the dataset into training, validation, and test sets.
- Training a convolutional neural network (CNN) to classify the images.

For detailed instructions on how to train the model, refer to the `training.py` script in the repository.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
