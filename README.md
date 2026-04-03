# Rainfall Predictor

A machine learning web application for predicting monthly rainfall using a Random Forest regression model. The model leverages atmospheric parameters such as temperature, humidity, wind speed, and more to provide accurate rainfall forecasts.

## Features

- Web-based interface for easy prediction input
- Random Forest model trained on historical weather data
- Supports multiple atmospheric parameters
- Built with Flask for the backend

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vijethpoojary-a18/Rain-fall-predictor.git
   cd Rain-fall-predictor
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

4. Open your browser and go to `http://localhost:5000`

## Usage

- Enter the required atmospheric parameters in the web form.
- Click "Predict" to get the rainfall forecast.

## Project Structure

- `app.py`: Main Flask application
- `data/`: Dataset files
- `models/`: Trained model files
- `notebooks/`: Jupyter notebooks for model development
- `static/`: Static files (CSS, JS, images)
- `template/`: HTML templates
- `docs/`: Documentation

## Model Details

The model uses a Random Forest Regressor trained on the weatherAUS.csv dataset. It predicts rainfall based on features like:
- Date (day, month)
- Min/Max Temperature
- Rainfall
- Evaporation
- Sunshine
- Wind Gust Speed
- Wind Speed at 9am and 3pm
- Humidity at 9am and 3pm

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
