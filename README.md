# fake-login-detection-keystroke-ml
ML-based Fake Login Detection using Keystroke Dynamics (Behavioral Biometrics

# 🔐 Fake Login Detection using Keystroke Dynamics (ML)

This project uses Machine Learning to detect fake login attempts by analyzing how a user types (keystroke dynamics). It treats typing behavior as a behavioral biometric for authentication.

## 🎯 What this does
- Learns typing patterns of a genuine user  
- Detects impostors even if the password is correct  
- Adds an extra security layer beyond passwords  

## 🧠 How it works
- Extracts timing features (dwell time, flight time)  
- Trains ML models (e.g., Random Forest, SVM)  
- Evaluates using security metrics like FAR and FRR  

## 🛠 Tech Stack
Python · Scikit-learn · Pandas · NumPy · Jupyter  

## 📁 Project Structure
data/ → datasets (or links)
notebooks/ → experiments & training
src/ → ML pipeline scripts
results/ → metrics & plots


## 🚀 Future Improvements
- Try deep learning (LSTM)  
- Continuous authentication  
- Real-time demo app  

## 👤 Author
Divija
