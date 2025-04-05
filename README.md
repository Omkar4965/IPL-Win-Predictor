# 🏏 IPL Win Predictor

A machine learning-based Streamlit web app that predicts the probability of a team winning an IPL match based on live match conditions.

## 🔥 Why This Project?

This project helps cricket fans and analysts get a real-time prediction of a team’s winning chances during an IPL match using **Supervised Learning**. It also showcases **ML deployment using Streamlit and Render**.

## 🌐 Live Demo

👉 [Try it here](https://ipl-win-predictor-omkxr.onrender.com/)

![IPL Win Predictor](![image](https://github.com/user-attachments/assets/eb5497b4-e5a2-4890-87bf-5ad48dd554fc)
)

---

## 💽 Tech Stack

- **Frontend**: Streamlit  
- **Backend**: Python  
- **Model**: Machine Learning with Scikit-learn  
- **Deployment**: Render

---

## ✨ Getting Started

### 📁 Clone the repo

```bash
git clone https://github.com/yourusername/ipl-win-predictor.git
cd ipl-win-predictor
```

### 📦 Install dependencies

```bash
pip install -r requirements.txt
```

### ▶️ Run the application

```bash
streamlit run app.py
```

---

## 🏏 How It Works

1. **Select the teams and city**.
2. **Enter the current match situation** – target, current score, overs completed, and wickets fallen.
3. **Click “Predict Probability”**.
4. The model will output the chances of each team winning in percentage.

---

## 🧠 Model Inputs

- Batting team  
- Bowling team  
- Host city  
- Target runs  
- Current score  
- Overs completed  
- Wickets fallen  

From these inputs, the model calculates:

- Runs left  
- Balls left  
- Wickets remaining  
- Current Run Rate (CRR)  
- Required Run Rate (RRR)

These features are then passed to a pre-trained model to compute win probabilities.

---

## 📈 Future Improvements

- Live match data integration  
- Enhanced UI with match graphics  
- Support for more cricket leagues  
- Add confidence intervals in prediction

---

## 💚 License

This project is licensed under the **MIT License**.

---

## ✉️ Contact

For any queries or suggestions, feel free to reach out to [Omkar Chavan](https://www.linkedin.com/in/omkar-chavan-476a63249/).

