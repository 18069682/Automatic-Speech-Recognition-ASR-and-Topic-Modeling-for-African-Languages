# 📊 COS 802 – Automatic Speech Recognition (ASR) and Topic Modeling for African Languages

![Made with LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-blue?logo=latex)
![Big Data](https://img.shields.io/badge/Focus-Big%20Data-orange)
![Status](https://img.shields.io/badge/Assignment-Completed-brightgreen)


This repository includes a research project on Automatic Speech Recognition (ASR) within Xitsonga podcast data in addition to Word Error Rate assessment through topic modeling.

Author Credentials

Muphulusi Dziwhani (u18069682)
University of Pretoria
COS 802 Research Project Module

#📖 About This Project

The objective of this project is to make headway towards bridging the digital gap within African Languages through an ASR pipeline for Xitsonga, a low-resource language in South Africa boasting 4.5 million native speakers. This research involves OpenAI's Whisper model using TensorFlow and Librosa on 24 Nalibali Xitsonga episodes alongside Word Error Rate for transcription accuracy assessment.

#🎯 Research Questions

To what accuracy is Whisper able to accommodate natural data podcast speech in Xitsonga and transcribe?

What is the Word Error Rate for such Africa language data through existing models?

To what accuracy is transcription accurate in terms of language unique features such as click consonants?

What is the most effective preprocessing pipeline for Xitsonga relative audio?

What are the ASR implementation challenges for African languages?

#🛠️ Implementation of the Technical Component

ASR solution

Model: OpenAI Whisper-base (74M parameters)

Platform: Hugging Face Transformers

Audio Preprocessing: Librosa

Quantitative metrics: jiwer library

Advantages

24 files batched simultaneously

Word Error Rate assessment and corresponding analysis (compared to manual filings)

Linguistic assessment for click consonants

Entire process replicable

#📊 Results

Word Error Rate Obtained: 28.7% across WHISPER tested Xitsonga relative files.

Processing Effective Rate: 100% (24/24 processed without issue)

Click Consonants Effective Rate: ~85% (manually assessed)

Processing Speed: 45 seconds per file. Time to process 24 files.

🗂️ Folder Structure


## 🔗 Links
- Kaggle Dataset: [here](https://www.kaggle.com/datasets/muphulusi1234/cos802-project)  
- GitHub Repository: [COS 802 Project](https://github.com/18069682/Automatic-Speech-Recognition-ASR-and-Topic-Modeling-for-African-Languages)

---

## 📝 Author
**Muphulusi Dzivhani**  
Student Number: u18069682  
University of Pretoria  
