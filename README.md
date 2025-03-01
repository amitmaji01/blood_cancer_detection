# Blood Cancer Classification Web App

## Overview
This is a Flask-based web application that uses a Convolutional Neural Network (CNN) to classify blood cell images into different categories. The model is built using TensorFlow and deployed with Flask for easy interaction.

## Features
- Upload an image of a blood cell
- Predict the class of the blood cell using a pre-trained CNN model
- Display the predicted class along with confidence score
- Simple web interface for easy interaction

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Flask
- TensorFlow
- NumPy
- Werkzeug

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/blood-cancer-classifier.git
   cd blood-cancer-classifier
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the application:
   ```sh
   python app.py
   ```
5. Open your browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

## File Structure
```
├── app.py              # Flask web app
├── cnn_model.h5        # Trained CNN model
├── templates/
│   ├── index.html      # HTML template for UI
├── static/             # Stores uploaded images
├── requirements.txt    # List of dependencies
├── README.md           # Project documentation
```

## Usage
- Upload a blood cell image using the web interface.
- The model processes the image and predicts its category.
- The prediction and confidence score are displayed on the UI.

## Model Details
- The model is a CNN trained on blood cell images.
- It predicts five classes:
  - Basophil
  - Erythroblast
  - Monocyte
  - Myeloblast
  - Segmented Neutrophil

## Contributing
Feel free to fork this repository and contribute by submitting pull requests.

## License
This project is licensed under the MIT License.

