Team Member

  Shreyash Verma 
  Sachin Singh 
 Shivam Chaurasia 
 
  Plant Disease Detection Using Machine Learning
This project uses machine learning and image processing to detect plant diseases from leaf images. 
It features a user-friendly web interface built with Flask and can be run locally using Anaconda.

code to send/
├── app.py                        # Main Flask application
├── static/                       # Static files (CSS, JS, Images)
├── templates/                   # HTML templates
├── static/css/                  # Stylesheets
├── static/scripts/             # JavaScript files
├── static/images/              # Images for the UI
└── templates/                  # Web pages (disease input, results, etc.)

 Features
Upload leaf images to detect diseases

Provides disease information and suggestions

Built-in crop and fertilizer recommendation modules

Clean and modern UI

 Installation
Requirements

Anaconda (Python 3.x)

Flask

TensorFlow/Keras

NumPy, OpenCV, Pillow, and other common libraries

Setup Steps
1 - Clone this repository:
git clone https://github.com/Sachinsinghas/plant-disease-detection.git
cd plant-disease-detection/code\ to\ send
2- Create a new Anaconda environment:
conda create -n plantenv python=3.9
conda activate plantenv
3-Install dependencies:
pip install -r requirements.txt
4- Run the application:
python app.py
5- Open your browser and go to:
http://127.0.0.1:5000/
Model
The image classification model used for disease detection should be pre-trained and loaded in app.py.
Make sure the model file (e.g., model.h5) is available in the working directory.




