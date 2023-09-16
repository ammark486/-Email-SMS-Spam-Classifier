## Email/SMS Spam Classification

This project aims to develop a machine learning model that can accurately classify text messages as either spam or ham (not spam). The model utilizes the SMS Spam Collection dataset and follows a comprehensive methodology, including data cleaning, exploratory data analysis, text preprocessing, model training, and evaluation. The Naive Bayes algorithm from the scikit-learn library is used for classification, with model deployment achieved using Streamlit.

![1_nBgCTU_hAVG00eYkcRf6Mw](https://github.com/ammark486/-Email-SMS-Spam-Classifier/assets/74138421/2591abf7-6c4b-48f3-bcc3-e9614f265ea5)


## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Tools and Libraries Used](#tools-and-libraries-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Spam messages pose a significant challenge in communication systems, inundating email inboxes and SMS folders. The goal of this project is to develop an efficient machine learning model capable of accurately differentiating between spam and ham messages. By leveraging the SMS Spam Collection dataset and employing the Naive Bayes algorithm, this project provides a robust solution to this problem.

![89773689-09eb2d80-db22-11ea-81b0-3deb4eae08c0](https://github.com/ammark486/-Email-SMS-Spam-Classifier/assets/74138421/c380cef9-3cd9-4b83-a15a-ba38db926ab5)
![89773691-0bb4f100-db22-11ea-9d57-13b6ffcc45b0](https://github.com/ammark486/-Email-SMS-Spam-Classifier/assets/74138421/910b9a5c-3fd0-4c04-b850-cb71f559620f)


## Dataset

The SMS Spam Collection dataset serves as the primary data source for this project. It consists of a collection of SMS messages, each labeled as either spam or ham. The dataset is publicly available and widely used for spam classification tasks. The dataset is preprocessed and cleaned to ensure high-quality data for training the machine learning model.

## Methodology

The project follows a systematic methodology to achieve accurate spam classification. The key steps involved are:

1. **Data Cleaning:** The dataset is thoroughly examined and cleaned to remove any inconsistencies, missing values, or irrelevant information. This ensures a clean and reliable dataset for subsequent analysis and modeling.
2. **Exploratory Data Analysis (EDA):** Exploratory data analysis techniques are applied to gain insights into the dataset. Statistical summaries and visualizations are utilized to understand the distribution of spam and ham messages, identify patterns, and extract meaningful features.
3. **Text Preprocessing:** As text data is inherently unstructured, it is necessary to preprocess it before training the machine learning model. Techniques such as tokenization, stop word removal, stemming, and lemmatization are applied to transform the text data into a format suitable for modeling.
4. **Model Training and Evaluation:** The Naive Bayes algorithm, implemented using the scikit-learn library, is employed to train the classification model. The dataset is split into training and testing sets, and the model is trained on the former and evaluated on the latter. Performance metrics such as accuracy, precision, recall, and F1 score are calculated to assess the model's effectiveness.
5. **Model Deployment:** The trained model is deployed using Streamlit, a user-friendly web application framework. This allows users to interact with the model and classify text messages as spam or ham through a simple and intuitive interface.

## Tools and Libraries Used

The following tools and libraries are utilized in this project:

- Python: The programming language used for implementing the project.
- Matplotlib: A data visualization library for creating informative plots and charts.
- Seaborn: A statistical data visualization library built on top of Matplotlib, offering enhanced aesthetics and additional plotting capabilities.
- Scikit-learn: A powerful machine learning library that provides efficient implementations of various classification algorithms.
- NLTK (Natural Language Toolkit): A comprehensive library for natural language processing, offering tools and resources for text preprocessing and analysis.
- Streamlit: An open-source library for building interactive web applications with Python.

## Installation

To run this project on your local machine, follow these steps:

1. Clone the repository: `git clone https://github.com/ammark486/Email-SMS-Spam-Classifier.git`
2. Navigate to the project directory: `cd Email-SMS-Spam-Classifier`
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage

To use the deployed model via the Streamlit web application, follow these steps:

1. Ensure you have completed the installation steps mentioned above.
2. Run the Streamlit application: `streamlit run app.py`
3. Open your web browser and go to `http://localhost:8501`.
4. Interact with the web application by inputting text messages and obtaining their spam/ham classification.

## Results

The trained machine learning model achieves impressive results in classifying text messages as spam or ham. The model's performance is evaluated using accuracy and precision. The results demonstrate the effectiveness and reliability of the model in accurately identifying spam messages, thus assisting users in prioritizing their attention and avoiding potential scams or unwanted content.

## Conclusion

The Email/SMS Spam Classification project provides a robust solution to the problem of spam detection and classification. By leveraging machine learning techniques and the Naive Bayes algorithm, the project offers an accurate and efficient model that can differentiate between spam and ham messages. The project's methodology, which includes data cleaning, exploratory data analysis, text preprocessing, and model training and evaluation, ensures that the model performs optimally. Additionally, the model is deployed using Streamlit, allowing users to easily interact with it and classify text messages.

## Contributing

If you would like to contribute to this project, you can follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name: `git checkout -b feature/your-feature`.
3. Make the necessary changes and commit them: `git commit -m "Add your feature"`.
4. Push your changes to your branch: `git push origin feature/your-feature`.
5. Open a pull request on the original repository and provide a descriptive summary of your changes.

## License

This project is licensed under the [MIT License](LICENSE). You are free to modify and distribute the code as per the terms of the license.
