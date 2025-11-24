# 📊 COS 802 – Automatic Speech Recognition (ASR) and Topic Modeling for African Languages

![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?logo=python)
![Big Data](https://img.shields.io/badge/Focus-Big%20Data-orange)
![Status](https://img.shields.io/badge/Assignment-Completed-brightgreen)
![Accuracy](https://img.shields.io/badge/Accuracy-85.3%25-green)

This repository includes a research project on Automatic Speech Recognition (ASR) for Xitsonga podcast data, achieving **85.3% accuracy** with comprehensive Word Error Rate assessment and linguistic analysis.

## 👨‍🎓 Author Credentials
**Muphulusi Dzivhani (u18069682)**  
University of Pretoria  
COS 802 Research Project Module

## 📖 About This Project

The objective of this project is to bridge the digital gap for African Languages through an ASR pipeline for Xitsonga, a low-resource language in South Africa with 4.5 million native speakers. This research fine-tunes OpenAI's Whisper model using 117 Nalibali Xitsonga podcast episodes and achieves production-grade accuracy.

## 🎯 Research Questions

- To what accuracy can Whisper accommodate natural podcast speech in Xitsonga?
- What is the Word Error Rate for African language data using fine-tuned models?
- How accurate is transcription for language-specific features like click consonants?
- What is the most effective preprocessing pipeline for Xitsonga audio?
- What are the key ASR implementation challenges for African languages?

## 🛠️ Implementation of the Technical Component

### ASR Solution
- **Model**: Fine-tuned OpenAI Whisper-small
- **Platform**: Hugging Face Transformers + Google Colab
- **Audio Preprocessing**: Librosa
- **Quantitative Metrics**: Custom WER calculation + visualization

### Advantages
- **117 files** processed with 100% success rate
- **85.3% accuracy** achieved on Xitsonga speech
- Comprehensive Word Error Rate assessment
- Linguistic analysis of Xitsonga features
- Fully replicable automated pipeline

## 📊 Results

### Performance Metrics
- **Word Error Rate**: 14.7% across 117 Xitsonga podcast files
- **Accuracy**: 85.3% (commercial-grade performance)
- **Processing Effective Rate**: 100% (117/117 files processed)
- **Click Consonants Recognition**: ~85% 
- **Processing Speed**: ~60 seconds per file

### Quality Distribution
- **Perfect Transcriptions**: 40% of files
- **Good Transcriptions**: 40% of files  
- **Fair Transcriptions**: 20% of files
- **Poor Transcriptions**: 0% of files

## 🚀 Lecturer Instructions: Running the Project

### Option 1: Automatic Download (Recommended)
1. **Upload the notebook** to Google Colab
2. **Run Cell 1** to install dependencies
3. **Run Cell 2** - automatically downloads dataset from Kaggle
4. **Continue with remaining cells** sequentially


### Expected Output
- Automated dataset organization
- Model loading and validation
- Batch transcription of 117 audio files
- Performance evaluation with 85.3% accuracy
- Visualizations and analysis charts


