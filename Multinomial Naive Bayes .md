# 📊 Multinomial Naive Bayes for Text Classification

Multinomial Naive Bayes is a machine learning algorithm widely used for **text classification** tasks like **spam detection** or **sentiment analysis**.

---

## 🔍 In Simple Words

It looks at how **frequently each word appears** in different types of documents (e.g., spam vs not spam) and uses that information to **predict the type of a new document**.

---

## 🧠 Why "Naive"?

The algorithm makes a **naive assumption**:  
> All words in a sentence are **independent** of each other.

While this is rarely true, the assumption simplifies calculations and still performs surprisingly well in many NLP tasks.

---

## 📦 Why "Multinomial"?

The term "multinomial" refers to the fact that the model **uses word counts** (how many times each word appears) instead of just presence or absence.

---

## 📨 Example

| Email                 | Type  |
|-----------------------|-------|
| "Win money now"       | Spam  |
| "Let's meet today"    | Ham   |

Now, if a new email is:

> **"Win money today"**

The algorithm will:

- Check how often the words **"win"**, **"money"**, and **"today"** appear in both spam and ham emails.
- Multiply those probabilities for each class.
- Choose the class (Spam or Ham) with the **higher overall score**.

---

## ✅ Common Use Cases

- 📩 Spam Detection  
- 😀 Sentiment Analysis  
- 📰 News Categorization  
- 🌍 Language Detection  

---
