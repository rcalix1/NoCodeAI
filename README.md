# No Code AI


## Tools

* https://teachablemachine.withgoogle.com
* ChatGPT
* Replicate.com
* roboflow.com
* 

## Data

* Images: https://github.com/rcalix1/CyberSecurityAndMachineLearning/tree/main/FirstEdition/Ch10_AIassurance/AdversarialML
* 

## More advanced (more complicated)

* Amazon sagemaker
* Vertex AI (Google cloud)

####################

# 🧠 No-Code AI: Interactive Machine Learning Without Programming

This repository contains demos and examples of **No-Code AI tools**—powerful platforms that allow users to build, train, and deploy machine learning models without writing code. These tools are ideal for educators, startups, and anyone looking to rapidly prototype AI solutions.

## 📌 What is No-Code AI?

**No-Code AI** refers to the use of graphical interfaces, drag-and-drop tools, and automation pipelines to create AI/ML models **without the need for traditional programming or data science expertise**.

These platforms abstract away the complexity of machine learning workflows, offering:
- Point-and-click interfaces for model training and deployment.
- Built-in data preprocessing, model selection, and evaluation.
- Integration with APIs and exportable models.
- Support for vision, language, audio, and tabular data.

No-Code AI democratizes machine learning by putting it in the hands of **teachers, marketers, artists, business analysts, students**, and others who wouldn’t typically build AI models.

---

## 🧰 Featured Tools & Examples

### 🌟 Google Teachable Machine

> Interactive tool to build AI models for **image, sound, or pose recognition** in minutes.

- **Website**: [https://teachablemachine.withgoogle.com/](https://teachablemachine.withgoogle.com/)
- **Use Cases**:
  - Create custom speech commands (e.g., “yes” / “no”)
  - Recognize hand gestures or facial expressions
  - Detect presence or absence of an object via webcam
- **Exports**: TensorFlow, ONNX, and web-ready models
- **Bonus**: No account required. Runs in the browser.

🧪 Example in this repo: `teachable-speech-demo/` – a simple sound classifier for 3 classes.

---

### 🖼️ Roboflow

> End-to-end platform for **computer vision** tasks including object detection, segmentation, and classification.

- **Website**: [https://roboflow.com/](https://roboflow.com/)
- **Features**:
  - Upload and annotate images
  - Auto-augment datasets
  - Train using Roboflow Train or export to YOLO, TensorFlow, etc.
  - Host models via REST API or embed on web
- **Use Cases**:
  - Barcode scanning
  - Defect detection in manufacturing
  - Wildlife monitoring

🧪 Example in this repo: `roboflow-object-detection/` – a demo for detecting everyday objects using uploaded photos.

---

### 💻 Replicate

> A cloud platform that hosts and runs **open-source ML models** with one-click deployment.

- **Website**: [https://replicate.com/](https://replicate.com/)
- **Highlights**:
  - Run models like Stable Diffusion, Whisper, LLaMA, and more
  - Just use a **simple API call** to run powerful models
  - No training or infrastructure required
- **Use Cases**:
  - Image generation (e.g., turning text into art)
  - Audio transcription
  - Text summarization and chatbot generation

🧪 Example in this repo: `replicate-stable-diffusion/` – generate images from prompts using a pre-trained model.

---

### 🧪 [Weka](https://www.cs.waikato.ac.nz/ml/weka/)

> A classic and robust open-source tool for machine learning on structured data — used in universities and industry for decades.

- **Type**: Desktop GUI (Java-based)
- **Download**: https://waikato.github.io/weka-wiki/downloading_weka/
- **Focus**: Traditional machine learning on tabular data (classification, regression, clustering)
- **Features**:
  - Upload CSV or ARFF datasets
  - Train and evaluate models like decision trees, SVMs, k-NN, logistic regression, etc.
  - Full GUI for preprocessing, feature selection, cross-validation, and performance visualization
  - Includes scripting options and experiment runners for reproducibility
- **Best For**:
  - Researchers and students learning ML theory
  - Practitioners doing fast experimentation with real-world datasets
- **Limitations**:
  - Not deep learning or neural net focused
  - Interface feels dated but is extremely feature-rich
- **Data**
  - Data: https://github.com/rcalix1/DeepLearningAlgorithms/tree/main/SecondEdition/chapter4_Reg_MLP_DL

🧰 *Why it matters for No-Code AI*: Weka is a **mature**, **well-documented**, and **self-contained** tool that requires **zero programming**, and supports hundreds of ML algorithms out-of-the-box.

📦 Try it with any spreadsheet-style dataset (CSV) and explore classifiers, attribute selection, confusion matrices, ROC curves, and more — all through a GUI.

---

### 🤖 ChatGPT as Your No-Code AI Engineer

> ChatGPT (from OpenAI) can help you build and understand machine learning systems — without coding — by *talking* your way through solutions.

---

#### ✅ What ChatGPT Can Help You Do

| Task | Example |
|------|---------|
| 📈 Data Modeling | “Build me a decision tree to predict loan defaults based on income, age, and credit score.” |
| 🧹 Data Cleaning | “How can I clean missing values from a CSV?” |
| 🧪 Tool Discovery | “What no-code tools can classify images?” |
| 🧾 Report Writing | “Summarize this model’s performance for a non-technical manager.” |
| 🧠 Education | “Explain how logistic regression works with a diagram.” |
| 🛠️ Pseudocode Generation | “Outline an AI pipeline from raw CSV to model deployment.” |

---

#### 💬 Sample Prompts

Try saying things like:
- “Create a machine learning pipeline to predict customer churn using a spreadsheet.”
- “Give me a feature importance report like SHAP, but in plain English.”
- “Explain the difference between classification and regression with visual analogies.”
- “Compare Roboflow and Teachable Machine for a classroom project.”

---

#### 🧠 Why ChatGPT is Powerful for No-Code AI

- Works as your **AI co-pilot** for tool discovery, explanations, and design decisions.
- Helps you **translate ideas into code**, **code into concepts**, and **concepts into action**.
- Can write full Jupyter notebooks, explain Python/PyTorch/TensorFlow code, or show how to *do the same things without code*.

---

### 🧰 Use Case in This Repo

Check the `chatgpt-assist-scenarios/` folder for example conversations:
- `loan-prediction-chat.md`: Prompting ChatGPT to design a classification model
- `explain-svm.md`: Teaching support vector machines to a non-coder
- `feature-ranking-help.md`: Explaining which variables matter, and why

---

🧠 *TL;DR:* If you can describe your problem clearly, ChatGPT can help you build or understand the solution — code optional.

###############

### Prompt

I have a CSV file with structured data (e.g., customer info, product sales, loan applications, etc.). I want to build a machine learning model to predict one of the columns — but I don’t want to write any code.

Please walk me through:
1. How to prepare the data (cleaning, encoding, splitting)
2. Which no-code tools I can use for this (that actually work)
3. What kind of model is best (classification vs regression)
4. How to interpret the results (feature importance, accuracy, etc.)
5. How to explain it to a non-technical audience

Keep it step-by-step, and assume I want to do this completely without programming.



##############

---

## 🚀 Why Use No-Code AI?

| Benefit                 | Description |
|-------------------------|-------------|
| **Speed**              | Build and deploy models in minutes instead of days. |
| **Accessibility**      | No programming or math background required. |
| **Experimentation**    | Quickly test ideas and data without a full ML pipeline. |
| **Educational Value**  | Great for classrooms and workshops on machine learning. |

---

## 🧠 Future Additions

We plan to expand this repository with additional No-Code AI tools like:
- [MLJAR AutoML](https://mljar.com/) – for structured data tasks.
- [MonkeyLearn](https://monkeylearn.com/) – for no-code NLP tasks like sentiment analysis and keyword extraction.
- [Google AutoML Tables](https://cloud.google.com/automl-tables) – enterprise-grade tool for tabular data models.

---

## 👋 About

Maintained by [Ricardo Calix](https://www.rcalix.com), author and AI consultant. This repository supports interactive workshops and masterclasses on **AI without code**. Contact: rcalix@rcalix.com

## Books

<a href="https://amzn.to/3QmKKwC">
  <img src="https://m.media-amazon.com/images/I/71F2QLFMCFL._SL1233_.jpg" alt="Books" width="300" />
</a>

## Disclaimer

- This repository contains AI-assisted content.
- This post includes [Amazon affiliate links](https://amzn.to/3QmKKwC), which may earn commissions at no additional cost to you.

