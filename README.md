# Multimodal Alzheimer’s Disease Risk Assessment Dashboard

An interactive Machine Learning web application designed to assist clinicians in the early detection of Alzheimer's Disease by analyzing demographic, clinical, and structural brain MRI metrics simultaneously.

## 🚀 Live Demo
You can run the interactive dashboard directly via Google Colab. 
*Note: The temporary deployment generates a active `.gradio.live` link when the notebook cells are run.*

## 📊 Project Features & Tech Stack
- **Data Source:** OASIS (Open Access Series of Imaging Studies) Cross-Sectional Dataset.
- **Machine Learning Engine:** RandomForestClassifier (Scikit-Learn) optimized to prevent overfitting (Max Depth: 5).
- **Model Accuracy:** 89.36% on unseen testing data.
- **Data Preprocessing:** Handled missing clinical features (SES, Education) via median imputation.
- **Frontend & Deployment:** Interactive web form UI generated natively via Gradio.

## 📁 Repository Structure
- `notebooks/`: Contains the complete data cleaning, model training, and Gradio interface code.
- `models/model.pkl`: The serialized, trained Random Forest model weights.
