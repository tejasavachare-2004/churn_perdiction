# churn_perdiction

# 🔮 Customer Churn Prediction using ANN

This project implements an **Artificial Neural Network (ANN)** to predict customer churn. It includes a user-friendly **Streamlit web interface** and an interactive **Jupyter Notebook** for training and evaluation.

---

## 📁 Project Structure

📦 ANN_implementation/
├── app.py # Streamlit app
├── experiments.ipynb # Jupyter Notebook for training
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── data/ # Dataset folder (optional)

yaml
Copy code

---

## 🚀 Features

- ✅ Predicts customer churn using ANN
- ✅ Built with TensorFlow/Keras
- ✅ Streamlit interface for easy interaction
- ✅ Jupyter Notebook for experimentation
- ✅ Configurable epochs, layers, and parameters

---

## 📦 Requirements

- Python 3.11+
- TensorFlow
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (optional)

---

## 🛠 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ann-churn-prediction.git
cd ann-churn-prediction
2. Create and Activate a Virtual Environment
bash
Copy code
conda create -n ann python=3.11
conda activate ann
3. Install Required Packages
bash
Copy code
pip install -r requirements.txt
🧪 Run the Jupyter Notebook
Open the notebook to explore the ANN training process:

bash
Copy code
jupyter notebook experiments.ipynb
To run the whole notebook at once:

bash
Copy code
jupyter nbconvert --to notebook --inplace --execute experiments.ipynb
🌐 Run the Streamlit App
Launch the web app using:

bash
Copy code
streamlit run app.py
📊 Dataset
Ensure the dataset used in experiments.ipynb is available locally in a data/ folder. If you are using a public dataset (like from Kaggle), download it and place it accordingly.

🧠 Model Architecture (Example)
Input Layer: Based on dataset features

Hidden Layer: 1 (customizable)

Activation: ReLU / Sigmoid

Output Layer: Sigmoid for binary classification

📌 TODOs
 Add more model configuration options

 Improve dataset preprocessing

 Dockerize the app for deployment

 Add testing & evaluation metrics

📜 License
MIT License. Feel free to use and modify.

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss.

🙏 Acknowledgements
TensorFlow & Keras

Streamlit

Scikit-learn

Dataset provider (e.g., Kaggle or UCI ML Repo)

yaml
Copy code

---

Let me know if you also want a `requirements.txt` sample to go with this.
