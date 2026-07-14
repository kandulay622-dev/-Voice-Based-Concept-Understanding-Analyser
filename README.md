# 🎙️ Voice Based Concept Understanding Analyser

## 📌 Project Overview

The **Voice Based Concept Understanding Analyser** is an AI-powered application that evaluates a user's conceptual understanding through voice responses. The system converts spoken answers into text using speech recognition, compares them with a reference answer using Natural Language Processing (NLP), calculates a similarity score, and provides feedback based on the user's understanding.

This project demonstrates the use of Artificial Intelligence and Machine Learning to automate concept evaluation in educational environments.

---

## ❓ Problem Statement

Traditional methods of evaluating students' conceptual understanding require manual assessment, which is time-consuming and subjective. This project aims to automate the evaluation process by analyzing voice responses and providing instant, objective feedback.

---

## 🎯 Objectives

- Convert voice input into text.
- Analyze the semantic meaning of the spoken response.
- Compare the user's answer with the expected answer.
- Calculate a concept understanding score.
- Provide automated feedback.
- Generate a PDF report of the evaluation.

---

## 💡 Proposed Solution

The proposed system uses OpenAI Whisper for speech-to-text conversion and Sentence Transformers (SBERT) for semantic analysis. The similarity between the user's response and the reference answer is calculated using Cosine Similarity, and the system generates feedback based on the score.

---

## ⚙️ Technologies Used

- Python
- Google Colab
- OpenAI Whisper
- Sentence Transformers (SBERT)
- Scikit-learn
- Streamlit
- ReportLab
- NumPy
- Machine Learning
- Natural Language Processing (NLP)

---

## ✨ Features

- 🎤 Voice Input Upload
- 📝 Speech-to-Text Conversion
- 🤖 AI-Based Concept Evaluation
- 📊 Semantic Similarity Analysis
- 📈 Understanding Score Generation
- 💬 Automated Feedback
- 📄 PDF Report Generation
- 🌐 Streamlit User Interface

---

## 📂 Project Structure

```
Voice-Based-Concept-Understanding-Analyser/
│
├── app.py
├── speech.py
├── similarity.py
├── report.py
├── requirements.txt
├── README.md
├── sample_audio.wav
└── Report.pdf
```

---

## 🔄 Workflow

1. User uploads a voice recording.
2. Whisper converts speech into text.
3. SBERT converts text into embeddings.
4. Cosine Similarity compares the user's answer with the reference answer.
5. Similarity score is calculated.
6. Feedback is generated.
7. PDF report is created.

---

## 📊 System Architecture

```
Voice Input
      │
      ▼
Speech-to-Text (Whisper)
      │
      ▼
Text Processing
      │
      ▼
Sentence Transformer (SBERT)
      │
      ▼
Cosine Similarity
      │
      ▼
Similarity Score
      │
      ▼
Feedback Generation
      │
      ▼
PDF Report
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Voice-Based-Concept-Understanding-Analyser.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

---

## 📦 Requirements

```
streamlit
openai-whisper
sentence-transformers
scikit-learn
reportlab
numpy
torch
pydub
```

---

## 📌 Sample Input

**Question**

```
What is Machine Learning?
```

**Expected Answer**

```
Machine Learning is a branch of Artificial Intelligence that enables computers to learn from data without being explicitly programmed.
```

**User Voice Response**

```
Machine learning allows computers to learn patterns from data without explicit programming.
```

---

## 📌 Sample Output

```
Converted Text:
Machine learning allows computers to learn patterns from data without explicit programming.

Similarity Score:
89%

Feedback:
Excellent Understanding
```

---

## 🧠 Model Details

### OpenAI Whisper

- Converts speech into text accurately.
- Supports multiple languages.

### Sentence Transformers (SBERT)

- Generates semantic embeddings for text.
- Captures contextual meaning of sentences.

### Cosine Similarity

- Measures similarity between reference and user responses.
- Produces a similarity score between 0 and 100%.

---

## 🌍 Applications

- Smart Learning Platforms
- Online Examinations
- Interview Assessment
- Educational Institutions
- Corporate Training
- E-Learning Systems

---

## 🚀 Future Enhancements

- Real-time voice recording.
- Multi-language support.
- AI-generated questions.
- Personalized learning recommendations.
- Cloud deployment.
- Student performance dashboard.

---

## ⚠️ Limitations

- Requires clear audio input.
- Accuracy depends on speech recognition quality.
- Limited to predefined reference answers.
- Internet connection may be required for model downloads.

---

## ✅ Conclusion

The Voice Based Concept Understanding Analyser is an AI-powered solution that automates the evaluation of conceptual understanding using speech recognition and Natural Language Processing. It provides quick, objective, and intelligent feedback, making it a valuable tool for modern education and training systems.

---

## 👨‍💻 Author

**Kandula Yamini**

Department of Computer Science and Engineering (Artificial Intelligence & Machine Learning)

