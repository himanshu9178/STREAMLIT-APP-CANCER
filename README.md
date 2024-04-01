
# Breast Cancer Detection App

## Overview

This Streamlit application is designed to leverage machine learning for the early detection of breast cancer. Utilizing the Wisconsin Breast Cancer dataset, the app predicts whether a breast mass is benign or malignant based on various measurements. Early detection of breast cancer can significantly increase the chances of successful treatment, making this app a valuable tool in healthcare.

## Importance

Breast cancer is one of the most common cancers among women worldwide, affecting millions each year. Early detection is crucial in improving the survival rate and minimizing the intensity of treatment required. This app aims to assist healthcare professionals by providing an accessible and user-friendly tool for analyzing tissue samples and predicting cancerous conditions.

## Application

The Breast Cancer Detection app uses a pre-trained machine learning model to analyze tissue sample measurements such as radius, texture, perimeter, and area, among others. Users can input or adjust these measurements using the app's interactive interface, and the model will provide a prediction on the nature of the breast mass.

## App Screenshot

![Breast Cancer Detection App Interface](https://github.com/himanshu9178/STREAMLIT-APP-CANCER/blob/main/Screenshot%202024-04-01%20231237.png)

*Screenshot of the Breast Cancer Detection Streamlit App.*

## Instructions

### Prerequisites

- Ensure you have Python (3.x recommended) installed on your machine.
- Pip package manager should be available for installing dependencies.

### Installation

1. **Clone the Repository:**
   Clone this project to your local machine using the following command:

    ```bash
    git clone https://github.com/himanshu9178/STREAMLIT-APP-CANCER/.git
    ```

2. **Navigate to the Project Directory:**

    ```bash
    cd STREAMLIT-APP-CANCER
    ```

3. **Install Dependencies:**
   Install the required Python packages using:

    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

- Launch the application with Streamlit by running:

    ```bash
    streamlit run APP/main.py
    ```

- The app will automatically open in your default web browser. If it doesn't, follow the URL provided in your terminal.

### How to Use

1. **Adjust the Input Values:** Use the sliders in the Streamlit sidebar to adjust the measurements of the tissue sample.
2. **View Prediction:** The app will display the model's prediction, indicating whether the sample is likely benign or malignant.
3. **Interpret the Results:** Use the prediction as a guide for further medical analysis and consultation.

## Contributions

Your feedback and contributions are welcome! Please feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

*This app is intended as a tool to aid in the detection of breast cancer and should not replace professional medical advice and diagnosis.*

