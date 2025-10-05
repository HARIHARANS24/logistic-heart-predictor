# 🫀 Heart Disease Detection Using Logistic Regression

A machine learning web application that predicts the likelihood of heart disease based on clinical features using Logistic Regression. Built with Python and Streamlit for real-time user interaction.

## 📋 Project Structure

```
heart_disease_detection_using_logistic_regression/
├── app.py                                      # Streamlit web application
├── heart_disease_detection_using_logistic_regression.py  # Core ML model implementation
├── Heart_Disease_Detection_Using_Logistic_Regression.ipynb  # Jupyter notebook for analysis
├── dataset.csv                                # Heart disease dataset
└── requirements.txt                           # Project dependencies
```

## 🚀 Features 

- Real-time heart disease prediction
- User-friendly web interface
- Logistic Regression model for accurate predictions
- Input validation and error handling
- Interactive data visualization

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/HARIHARANS24/logistic-heart-predictor.git
cd logistic-heart-predictor
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## 💻 Usage

1. Run the Streamlit application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the provided local URL (typically http://localhost:8501)

3. Input the required clinical features:
   - Age
   - Sex
   - Chest pain type
   - Resting blood pressure
   - Cholesterol
   - Fasting blood sugar
   - Resting ECG results
   - Maximum heart rate
   - Exercise-induced angina
   - ST depression
   - Slope of peak exercise ST segment
   - Number of major vessels
   - Thalassemia

4. Click "Predict" to get the heart disease prediction

## 📊 Model Details

The project uses Logistic Regression for binary classification to predict the presence or absence of heart disease. The model is trained on the UCI Heart Disease dataset and includes:

- Data preprocessing
- Feature scaling
- Model training and evaluation
- Performance metrics calculation

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **HARIHARANS24** - *Initial work* - [GitHub Profile](https://github.com/HARIHARANS24)

## 🙏 Acknowledgments

- UCI Machine Learning Repository for the heart disease dataset
- Streamlit for the web application framework
- Scikit-learn for the machine learning implementation

## 📞 Contact

For any questions or suggestions, please feel free to reach out through GitHub issues or create a pull request.

---
Made with ❤️ by HARIHARANS24 
