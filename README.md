# SMS Spam Detection System

A machine learning-based web application to detect whether a given SMS is spam or not. The system is built using Python, Streamlit, and a trained classification model.
![Screenshot 2025-01-09 170534](https://github.com/user-attachments/assets/12355173-5a32-4a8f-bfb9-8969a675694d)


## Features

- **Real-time SMS Classification**: Predicts if an SMS is spam or not.
- **User-Friendly Interface**: Built with Streamlit for an interactive experience.
- **Pre-Trained Model**: Uses a trained machine learning model for accurate predictions.
- **Easy Deployment**: Hosted on [Streamlit Cloud](https://sms-spam-detection-sys.streamlit.app/).

## Live Demo

Access the live application here: [SMS Spam Detection System](https://sms-spam-detection-sys.streamlit.app/)

## How It Works

1. Enter an SMS into the input field.
2. The model processes the input and predicts whether it is **Spam** or **Not Spam**.
3. Results are displayed instantly on the web interface.

## Technology Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Machine Learning**: Sklearn (for model training and evaluation)

## Project Structure
SMS-Spam-Detection-System/ │ ├── data/ # Dataset used for training and testing ├── models/ # Pre-trained models and training scripts ├── app.py # Streamlit application script ├── requirements.txt # Dependencies └── README.md # Project documentation


## Installation

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Sreelakshmi148/-SMS-Spam-Detection-System.git
   
2.Navigate to the project directory:
cd SMS-Spam-Detection-System

3.Install the dependencies:
pip install -r requirements.txt

4.Run the Streamlit application:
streamlit run app.py

Dataset
The project uses a preprocessed SMS dataset containing labeled examples of spam and non-spam messages. The dataset is available in the data folder.

Deployment
This application is deployed on Streamlit Cloud. Follow these steps to deploy your own version:

Fork the repository and push your changes to your GitHub account.
Link the repository to Streamlit Cloud and configure the app to run app.py.
Contributing
Contributions are welcome! Feel free to submit a pull request or report issues in the repository.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Author
Developed by Sree Lakshmi. If you found this project helpful, please give a ⭐ on GitHub!


Let me know if you want any specific adjustments!

