# Iris Classification Web Application

A professional web application for classifying Iris flowers based on their features using machine learning.

## Features

- Modern, responsive UI using Bootstrap 5
- User-friendly form for entering Iris measurements
- Input validation and error handling
- Visual representation of the classification results
- Display of prediction confidence levels (if model supports probabilities)
- Educational information about the Iris dataset

## Requirements

- Python 3.8+
- Flask
- NumPy
- Pandas
- scikit-learn

## Installation

1. Clone the repository
2. Create a virtual environment (recommended)
   ```
   python -m venv venv
   ```
3. Activate the virtual environment
   - Windows: `venv\Scripts\activate`
   - Unix/macOS: `source venv/bin/activate`
4. Install the required packages
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application
   ```
   python main.py
   ```
2. Open your web browser and navigate to:
   ```
   http://localhost:8080
   ```
3. Enter the Iris measurements (sepal length, sepal width, petal length, petal width)
4. Click the "Predict Species" button to get the classification result

## Project Structure

- `main.py`: Flask application and machine learning prediction logic
- `CONFIG.py`: Configuration settings
- `requirements.txt`: Required Python packages
- `templates/`: HTML templates
  - `index.html`: Main web interface
- `artifacts/`: ML model and assets
  - `model.pkl`: Trained ML model
  - `asset.json`: Model metadata

## Model Information

The application uses a machine learning model trained on the classic Iris dataset to classify Iris flowers into three species:

1. Iris Setosa
2. Iris Versicolor
3. Iris Virginica

The model takes four input features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

## License

MIT 