# Research-on-Azerbaijani-Automatic-Speech-Recognition-ASR-for-Low-Resource-Scenarios

### Project Overview
This project aims to fine-tune OpenAI’s Whisper model for Azerbaijani Automatic Speech Recognition (ASR) using the Common Voice 11.0 dataset. Since Azerbaijani is a low-resource language, this fine-tuning process enhances the model’s ability to transcribe Azerbaijani speech accurately.

### Objectives
Improve speech-to-text accuracy for Azerbaijani.
Utilize transfer learning on Whisper’s pre-trained model.
Evaluate Word Error Rate (WER) to measure performance.
Deploy an interactive demo to test real-time transcription.
Dataset
The Mozilla Common Voice 11.0 dataset is used for training and evaluation. It consists of audio clips with corresponding transcriptions, helping the model learn Azerbaijani pronunciation, grammar, and vocabulary.

### Fine-Tuning Process
Data Preparation: The dataset is preprocessed by normalizing text, removing unnecessary symbols, and ensuring consistency.
Feature Extraction: The model extracts relevant features from audio signals to process speech effectively.
Training: The Whisper model is fine-tuned using Common Voice 11.0, adjusting parameters to optimize accuracy.
Evaluation: The fine-tuned model is tested using WER to assess transcription accuracy.
Deployment: A user-friendly interface is created for real-time transcription using an ASR demo.
Results
The fine-tuned model demonstrates better performance in Azerbaijani ASR compared to the original version.
WER analysis highlights improvements in recognizing Azerbaijani-specific words and sentence structures.
Future optimizations may include expanding the dataset, tuning hyperparameters, and adopting more efficient models.
