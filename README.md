# Dog Breed Classifier

A Streamlit web application that predicts dog breeds using a deep learning model. Currently, the model can classify between three dog breeds:
- Scottish Deerhound
- Maltese Dog
- Bernese Mountain Dog

## Features

- Real-time dog breed prediction
- Simple and intuitive user interface
- Support for PNG image uploads
- Instant visual feedback with uploaded image display
- Clear prediction results

## Tech Stack

- Python 3.x
- Streamlit
- OpenCV (cv2)
- TensorFlow/Keras
- NumPy

## Installation

1. Clone the repository:
```bash
git clone https://github.com/zariffromlatif/dog-breed-classifier.git
cd dog-breed-classifier
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Start the Streamlit app:
```bash
streamlit run main_app.py
```

2. Open your web browser and navigate to the local URL provided by Streamlit

3. Upload a PNG image of a dog using the file uploader

4. Click the "Predict" button to see the classification result

## Model Information

The classifier uses a pre-trained deep learning model (`dog_breed.h5`) trained on three different dog breeds. The model processes images of size 224x224 pixels.

## File Structure

```
dog-breed-classifier/
├── main_app.py          # Main Streamlit application
├── dog_breed.h5         # Trained model file
├── requirements.txt     # Project dependencies
└── README.md           # Project documentation
```

## Requirements

- streamlit
- numpy
- opencv-python
- tensorflow
- keras

## Future Improvements

- Add support for more dog breeds
- Include confidence scores in predictions
- Add support for different image formats
- Implement batch prediction capabilities
- Add model performance metrics

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
