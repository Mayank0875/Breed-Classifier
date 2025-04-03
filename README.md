# 🐶 Breed Classifier using Naïve Bayes

##  Project Overview
This project is a **breed classification model**, where I generated my own dataset from **probability distributions**. The classifier predicts a dog's breed based on features like **height, weight, bark days, and ear-to-head ratio**.

---

##  Features
✅ **Custom dataset** generated using probability distributions  
✅ **Probabilistic classification approach**  
✅ Implements **Naïve Bayes Classifier** for breed prediction  

---

##  Dataset Information

### **Feature Distributions**
| Feature               | Distribution            | Explanation |
|-----------------------|------------------------|-------------|
| **Height**          | **Normal Distribution** | Dog heights typically follow a normal distribution since most breeds cluster around an average height with some variation. |
| **Weight**        | **Normal Distribution** | Like height, weight is normally distributed, with some dogs being lighter or heavier but most around an average. |
| **Bark Days**       | **Binomial Distribution** | Barking frequency is modeled as a binomial event (e.g., barking or not barking on a given day). |
| **Ear-to-Head Ratio**  | **Uniform Distribution** | Ear-to-head ratio is assumed to be uniformly distributed between a range of possible values. |

---

## 📌 How It Works
1️⃣ **Generate synthetic data** using probability distributions  
2️⃣ **Train a Naïve Bayes Classifier**, assuming feature independence  
3️⃣ **Calculate conditional probabilities** using Bayes’ theorem  
4️⃣ **Predict the breed** with the highest probability  

---


