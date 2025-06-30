---
# 💻 Laptop Price Predictor

This project predicts the price of a laptop based on its specifications using machine learning techniques. It includes data preprocessing, feature engineering, model training, and a web interface built using **Flask** for user interaction.

---

## 📌 Project Features

- Cleans and preprocesses raw laptop data
- Feature engineering including PPI calculation and one-hot encoding
- Multiple model training and comparison
- Best model selection based on R² score and RMSE
- Flask web interface for live predictions
- Interactive visualizations (heatmap, distribution plots, scatter plots)

---

## 📊 Dataset Overview

The dataset includes various features like:

- Company  
- TypeName  
- Ram  
- Weight  
- Touchscreen  
- IPS Panel  
- Screen Size  
- Resolution  
- CPU  
- HDD  
- SSD  
- GPU  
- Operating System  
- Price (Target Variable)

---

## 🧪 Data Preprocessing and Feature Engineering

- **Binary Encoding** for `Touchscreen` and `IPS`
- **PPI (Pixels Per Inch)** calculated using screen resolution and size
- **Text cleanup** for CPU, GPU, and Operating System columns
- **One-Hot Encoding** for categorical features
- **Train-Test Split**: 80% training, 20% testing

---

## 📈 Model Evaluation

The following models were evaluated:

- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  

📌 **Random Forest** performed best with the highest R² score and lowest RMSE.

---

## 🌐 Web Interface

A Flask-based web app allows users to input laptop specifications and get a price prediction in real time.

### How to Run the App:

```bash
# Clone the repo
git clone https://github.com/Piyush1716/laptop-price-predictor-regression-project.git
cd laptop-price-predictor

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
```

Visit `http://127.0.0.1:5000` in your browser.

---

## 📷 Visualizations

The project includes plots such as:

- Correlation heatmap of features  
- Distribution plot of laptop prices  
- Scatter plot of Price vs Weight  

📌 (Note: Add these plots manually in the README or report)

---

## 🛠 Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- Flask for web deployment
- VS Code / Jupyter Notebook

---

## 📁 Folder Structure

```
laptop-price-predictor/
│
├── static/             # CSS/JS/Images
├── templates/          # HTML templates
├── app.py              # Flask application
├── model.pkl           # Trained ML model
├── preprocess.py       # Data preprocessing
├── README.md           # Project README
└── requirements.txt    # Python dependencies
```

---

## 📬 Contact

For questions or feedback, reach out to:

- **Name**: [Chunara Piyush]  
- **Email**: [chunarapiyush10@gmail.com]  
- **GitHub**: [https://github.com/Piyush1716]

