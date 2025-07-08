# SocialSleuth – Investigating Fake Instagram Accounts

**SocialSleuth** is a machine learning-based tool that analyzes Instagram profile data to determine whether an account is **genuine or fake**. Inspired by how social media platforms battle spam and bots, this project uses behavioral and profile-level features to identify suspicious patterns.

---

## What This Project Does

- Classifies Instagram accounts as **Fake (1)** or **Genuine (0)**
- Uses features like follower/following ratio, profile picture presence, bio length, etc.
- Trains and compares models – **Random Forest** vs **Logistic Regression**
- Outputs predictions for unseen data
- Visualizes key trends and feature importances

---

##  Dataset

- `train.csv` – labeled data used to train the model
- `test.csv` – unlabeled data used to generate final predictions

Each row in the dataset represents one Instagram profile with numerical and boolean features derived from public information.

---

## Features Considered

- Has profile picture or not
- Username and fullname complexity
- Description/bio length
- External URL presence
- Number of posts, followers, followings
- Account privacy status
- Username matching fullname

---

## Models & Accuracy

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression | 86%      |
| **Random Forest**   | **91%** ✅ |

Final predictions were generated using the Random Forest classifier.

---

##  Visualizations

- Class distribution (Fake vs Genuine)
- Followers and Followings by account type
- Feature importance chart
- Confusion matrix for evaluation



