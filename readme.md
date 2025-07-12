

# 🩺 Disease Prediction Web App

An intelligent and accessible web application that allows users to predict the probability of **Diabetes** and **Skin Diseases** using machine learning and deep learning models. Designed to create early awareness and support timely diagnosis — especially for underdiagnosed conditions.

---



## 🌟 Key Features

✅ **User Authentication**  
- Secure registration and login system.

🧠 **Skin Disease Prediction**  
- Upload a skin image and get predicted disease using **CNN (VGG16)**.

🩸 **Diabetes Prediction**  
- Select symptoms via checkboxes and get disease likelihood using **Random Forest Classifier**.

📊 **Result Display**  
- Clear, user-friendly result interpretation to support awareness and next steps.

---

## 💻 Tech Stack Used

| Technology      | Purpose                                         |
|------------------|--------------------------------------------------|
| **Python**        | Core backend & machine learning models          |
| **Flask**         | Web framework to run server and APIs            |
| **MySQL**         | Store user data securely                        |
| **HTML/CSS/JS**   | Frontend user interface                         |
| **CNN (VGG16)**   | Deep Learning model for image-based prediction  |
| **Random Forest** | ML model for diabetes prediction from symptoms  |

---

## 🧠 ML & DL Methodology

### 🔬 Skin Disease Detection (CNN)
- Pre-trained **VGG16** model from ImageNet.
- Top layers removed and replaced with custom layers.
- Classifies based on uploaded skin image.

### 🧪 Diabetes Prediction (Random Forest)
- Trained on labeled health data.
- Symptoms like Polyuria, Itching, Partial Paresis, etc.
- Uses **Information Gain** to determine most impactful features.

---

## 🎯 Dataset Details

- Skin images collected from open sources.
- Diabetes dataset with 14 symptom-based features.
- Accuracy:
  - ✅ Random Forest: **94%**
  - ✅ Naive Bayes: **86%**
  - ✅ VGG16 (Skin CNN): **86%**

---

## 📉 Limitations

- Small and imbalanced dataset.
- Accuracy drops as number of skin diseases increases.
- Noisy images affect prediction quality.

---

## 🔮 Future Scope

🚀 Planned upgrades include:
- Support for more diseases (e.g., **Cancer**, **Tuberculosis**, **Meningitis**, etc.)
- Clean and diverse datasets for better accuracy.
- Android/iOS App for wider accessibility.



The purpose of the project is to create early awareness about diseases and timely treatment of problems which might later prove to be fatal. The project is a working website which predicts diabetes chances based on symptoms and skin disease based on photo uploaded.
</br>
</br>
Installation Process </br>
STEP 1: Installation of anaconda </br>
Anaconda Navigator is a desktop graphical user interface included in Anaconda that allowsyou to launch applications and easily manage conda packages, environments and channels without the need to use command line commands.https://anaconda.org/anaconda/anacondanavigator#:~:text=Anaconda%20Navigator%20is%20a%20desktop,to%20use%20command%20line%20commands. </br>
STEP 2: Creating a new virtual environment in anaconda </br>
https://www.geeksforgeeks.org/set-up-virtual-environment-for-python-using-anaconda/ </br>
STEP 3: Installation of jupyter text editor</br>
STEP 4:Installation of spyder</br>
STEP 5: Installation of MySQL</br>
STEP 6: Installation of SQLyog</br>
STEP 7: Start(run) the app.py file in Spyder</br>


## 👨‍💻 Developed By

**Abhishek Pathak**  
B.Tech Final Year — Artificial Intelligence & Machine Learning  
Roll No: 2237786  
🛠️ Passionate about building real-world ML applications.

---

## 📚 References

1. [Automated Skin Disease Identification Using Deep Learning](https://biomedpharmajournal.org/vol11no3/automated-skin-disease-identification-using-deep-learning-algorithm/)
2. [Diabetes Prediction Using Machine Learning](https://www.analyticsvidhya.com/blog/2022/01/diabetes-prediction-using-machine-learning/)
3. NEJM Research on Disease Awareness

---

## 📝 License

This project is developed for academic purposes. For any external use or collaboration, feel free to reach out.

---

⭐ _If you like this project, give it a star on GitHub!_


