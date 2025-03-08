# NewsBlink



This project utilises a BERT-based approach for categorizing and clustering Indian news videos across diverse topics, including politics, technology, health, and more. News data is collected through audio-to-text conversion and YouTube video transcription, then summarized using a self-attention-based encoder-decoder model. Various pre-trained BERT models process these summaries, with clustering performed using K-Means and AGNES. The best results were achieved using paraphrase-MiniLM-L6-v2 with AGNES, yielding a maximum Silhouette Score of 0.5647. Additionally, the NewsBlink app enables users to analyze YouTube news videos, enhancing automated news categorization and media analytics.


## Contents

- [Submission or project name](#submission-or-project-name)
  - [Contents](#contents)
  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [The solution](#the-solution)
  - [Tech stack used](#tech-stack-used)
  - [App Workflow](#app-workflow)
  - [How to Run the App](#how-to-run-the-app)
  - [App Screenshots](#app-screenshots)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Short description

### 🚀 What's the problem?

The exponential growth of digital news content, particularly in video format, has made it challenging to efficiently categorize and analyze news from diverse sources. Traditional methods of manual classification and summarization are time-consuming, inconsistent, and prone to biases. Additionally, the lack of structured datasets for Indian news videos limits the ability to perform effective clustering and retrieval of relevant information.

### 🛠 How can technology help?

Technology enables automated categorization and clustering of Indian news videos using BERT-based models, reducing the need for manual classification. Audio-to-text conversion and self-attention-based summarization streamline news processing, making vast amounts of content more accessible. Additionally, machine learning-driven clustering enhances media analytics, helping users discover structured news insights efficiently.

### ✅ The solution

This project provides an **automated solution** for categorizing and clustering Indian news videos using a **BERT-based pipeline**. It processes news through **audio-to-text conversion** and **YouTube transcription**, followed by **self-attention-based summarization**. Pre-trained **BERT models** extract features for clustering using **K-Means and AGNES**, with performance evaluated through **Silhouette Score and Davies-Bouldin Index**. The **NewsBlink app** enables users to input a **YouTube news link** and receive a **summary, category, and clustering evaluation metrics**, improving **media analytics and structured news access**.


## 🛠 Tech stack used
- Backend 
  - Framework: FastAPI
  - Programming Language: Python
  - Natural Language Processing: Hugging Face Transformers
  - Machine Learning: Scikit-learn
  - Data Processing: NumPy, Pandas
- Frontend 
  - Framework: Flutter
  - Languages: Dart


## 🔄 App Workflow

- User Input: The user enters a YouTube news video link.
- Transcription & Summarization: The app extracts audio, converts it to text, and generates a concise summary.
- Categorization: The summary is categorized into predefined news topics using a BERT-based model.
- Clustering: The app applies K-Means and AGNES clustering for news grouping.
- Evaluation Metrics: The Silhouette Score and Davies-Bouldin Index are displayed.
- Output Display: The user receives the summary, category, and clustering results in the app interface.

## ⚡ How to Run the App


## 📸 App Screenshots

- Homepage: (Describe the main interface)
- Input Section: (Where users enter a YouTube link)
- Summary & Categorization Output: (Show how the news summary and category are displayed)
- Clustering & Evaluation Metrics: (Display clustering results with metrics)


## Authors

1.  [Pratik Saha](https://github.com/Pratik-03-12)
2.  [Preeti Mandal](https://github.com/Preetix28)
3.  [Ishita Mondal](https://github.com/ishitaM2mondal)
4.  [Ritika Das](https://github.com/RitikaDas-21)

## LICENSE

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Based on real time applications.
