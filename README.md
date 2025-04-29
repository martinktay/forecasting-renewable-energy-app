# Wind Energy Power Prediction

A Flask web application that predicts wind energy power production based on historical data and machine learning models. The application provides an intuitive interface for users to select a timeframe and visualize predicted wind energy production.

## Features

- Interactive date selection for prediction timeframe
- Visual representation of predicted wind energy production
- Responsive and modern user interface
- Historical data-based predictions using XGBoost model
- Mobile-friendly design

## Screenshots

### Main Dashboard

![Dashboard Form](screenshots/dashboard1.jpg)
_Input form for prediction timeframe selection_

### Prediction Results

![Prediction Results](screenshots/dashboard2.jpg)
_Visualization of predicted wind energy production_

## Technologies Used

- Python 3.9
- Flask 3.0.2
- NumPy 1.26.4
- Pandas 2.2.1
- Seaborn 0.13.2
- Matplotlib 3.8.3
- XGBoost
- HTML/CSS
- Font Awesome Icons

## Installation

1. Clone the repository:

```bash
git clone <your-repository-url>
cd forecasting-renewable-energy-app
```

2. Install required dependencies:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
python app/app.py
```

4. Open your web browser and navigate to:

```
http://127.0.0.1:5000
```

## Project Structure

```
forecasting-renewable-energy-app/
├── app/
│   ├── app.py              # Main Flask application
│   ├── model.py            # ML model and data processing
│   ├── static/
│   │   ├── style.css       # Application styling
│   │   └── output.png      # Generated prediction plots
│   └── templates/
│       └── index.html      # Main application template
└── requirements.txt        # Project dependencies
```

## Usage

1. Access the application through your web browser
2. Select a start date and end date for the prediction
3. Click "Generate Prediction" to view the forecast
4. The results will be displayed as a time series graph

## Data Limitations

- Last recorded date in the dataset: 01/04/2020
- Prediction accuracy decreases for longer forecast periods
- Historical data is used for training the model

## Uploading to GitHub

1. Create a new repository on GitHub (don't initialize with README)

2. Initialize git in your local project (if not already done):

```bash
git init
```

3. Add your files to git:

```bash
git add .
```

4. Commit your changes:

```bash
git commit -m "Initial commit"
```

5. Add your GitHub repository as remote:

```bash
git remote add origin <your-github-repository-url>
```

6. Push your code to GitHub:

```bash
git push -u origin main
```

## Contributing

Feel free to fork this project and submit pull requests with improvements. You can also open issues for bugs or feature requests.

## Contact

For any questions or feedback, please open an issue in the GitHub repository.
