
# Iris Flower Prediction App

This is a simple web application built using **Streamlit** that predicts the type of Iris flower based on user-provided inputs for sepal and petal dimensions. The app uses a pre-trained **Random Forest Classifier** from **scikit-learn**.

---

## Features

- Interactive sliders to input the dimensions of sepals and petals.
- Prediction of the Iris flower species (Setosa, Versicolor, or Virginica).
- Display of prediction probabilities for each class.

---

## Installation

Follow these steps to set up and run the application locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/iris-flower-prediction-app.git
   cd iris-flower-prediction-app
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate       # On macOS/Linux
   venv\Scripts\activate          # On Windows
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```bash
   streamlit run app.py
   ```

---

## Requirements

The required Python libraries are listed in the `requirements.txt` file:
- `streamlit`
- `pandas`
- `scikit-learn`

---

## How It Works

1. The app takes input for sepal and petal dimensions using sliders in the sidebar.
2. It uses a trained **Random Forest Classifier** to predict the species of the Iris flower.
3. The prediction and the probability of each class are displayed on the main page.

---

## Demo

![Iris Flower Prediction Demo](demo_image.png)

---

## Author

Developed by Sri Krishna Garishapati.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
