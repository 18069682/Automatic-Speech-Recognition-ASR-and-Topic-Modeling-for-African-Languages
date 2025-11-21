# 📊 COS 802 – Automatic Speech Recognition (ASR) and Topic Modeling for African Languages

![Made with LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-blue?logo=latex)
![Big Data](https://img.shields.io/badge/Focus-Big%20Data-orange)
![Status](https://img.shields.io/badge/Assignment-Completed-brightgreen)


This repository contains a research project implementing Automatic Speech Recognition (ASR) for Xitsonga podcast content using OpenAI's Whisper model and analyzing the transcription quality through topic modeling techniques.

**Author:** Muphulusi Dziwhani (u18069682)  
**Institution:** University of Pretoria  
**Course:** COS 802 Research Project  

## 📖 Project Overview

This project addresses the digital divide for African languages by developing an ASR pipeline for Xitsonga, a low-resource South African language with approximately 4.5 million speakers. Using OpenAI's Whisper model implemented with TensorFlow and Librosa, we process 24 Nalibali Xitsonga podcast episodes and evaluate transcription quality through Word Error Rate analysis.

## 🎯 Research Questions

- How accurately can the Whisper model transcribe Xitsonga speech from real-world podcast data?
- What Word Error Rate can be achieved on Xitsonga content using modern ASR approaches?
- How effectively does the model handle Xitsonga-specific linguistic features like click consonants?
- What preprocessing pipeline is most effective for Xitsonga audio content?
- What are the practical implementation challenges for African language ASR?

## 🛠️ Technical Implementation

### ASR System
- **Model:** OpenAI Whisper-base (74M parameters)
- **Framework:** TensorFlow with Hugging Face Transformers
- **Audio Processing:** Librosa for loading and preprocessing
- **Evaluation:** jiwer library for Word Error Rate calculation

### Key Features
- Batch processing of 24 Xitsonga podcast episodes
- Word Error Rate analysis with manual validation
- Linguistic analysis of Xitsonga-specific features
- Complete reproducible pipeline

## 📊 Results

- **Word Error Rate:** 28.7% on evaluated Xitsonga content
- **Processing Success:** 100% (24/24 files processed)
- **Click Consonant Accuracy:** ~85% (manual evaluation)
- **Average Processing Time:** 45 seconds per file

## 🗂️ Project Structure

## 🔗 Links
- Kaggle Dataset: [here](https://www.kaggle.com/datasets/muphulusi1234/cos802-project)  
- GitHub Repository: [COS 802 Project](https://github.com/18069682/Automatic-Speech-Recognition-ASR-and-Topic-Modeling-for-African-Languages)

---

## 📝 Author
**Muphulusi Dzivhani**  
Student Number: u18069682  
University of Pretoria  
