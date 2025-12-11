# Earthquake Prediction and Risk Analysis

A machine learning project that predicts earthquake magnitude categories and visualizes earthquake risk zones using historical data from 1990-2023.

## Features

- **Earthquake Risk Map**: Interactive heatmap visualization of significant earthquakes (magnitude ≥ 5.0)
- **Magnitude Prediction Model**: Deep learning model (ANN) that classifies earthquakes into three categories:
  - Low (magnitude 0-4.0)
  - Moderate (magnitude 4.0-6.0)
  - High (magnitude 6.0-10.0)
- **Model Evaluation**: Comprehensive evaluation with confusion matrix and classification reports

## Project Structure

```
├── code-1.py                    # Earthquake risk map visualization
├── final code.py                # ANN model for magnitude prediction
├── code2.py                     # Additional analysis
├── earthquake_risk_map.html     # Generated interactive map
├── Confusion Matrix.png         # Model evaluation visualization
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
```

## Requirements

- Python 3.8+
- TensorFlow/Keras
- Pandas
- NumPy
- Scikit-learn
- Folium
- Matplotlib
- Seaborn

## Installation

1. Clone this repository:
```bash
git clone <your-repository-url>
cd earthquake-prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Download the dataset:
   - Dataset: Earthquakes-1990-2023.csv
   - Update the file path in the Python scripts to match your local path

## Usage

### Generate Earthquake Risk Map
```bash
python code-1.py
```
This will generate an interactive HTML map showing the top 100 most significant earthquakes.

### Train and Evaluate the Prediction Model
```bash
python "final code.py"
```
This will:
- Train an Artificial Neural Network on the earthquake data
- Display model accuracy and loss metrics
- Generate a confusion matrix
- Provide classification report
- Make example predictions

## Model Architecture

The ANN model consists of:
- Input layer (5 features: longitude, latitude, depth, tsunami, significance)
- Hidden layer 1: 64 neurons with ReLU activation + Dropout (0.3)
- Hidden layer 2: 32 neurons with ReLU activation + Dropout (0.3)
- Output layer: 3 neurons with Softmax activation (multi-class classification)

**Optimizer**: Adam  
**Loss Function**: Categorical Crossentropy  
**Training**: 100 epochs with batch size of 32

## Dataset

The model uses historical earthquake data (1990-2023) with the following features:
- Longitude
- Latitude
- Depth
- Tsunami indicator
- Significance score
- Magnitude (target variable)
- Location/Place
- Date

## Results

The model achieves classification of earthquake magnitudes into Low, Moderate, and High categories with detailed performance metrics available in the confusion matrix and classification report.

## Visualization

The earthquake risk map includes:
- Heatmap overlay showing earthquake concentration
- Interactive markers with earthquake details (location, date, magnitude)
- Global view with zoom functionality

## Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Earthquake data source: [Specify your data source]
- Built with TensorFlow, Scikit-learn, and Folium

## Contact

For questions or suggestions, please open an issue in this repository.
