# VoiceDoc

> Forked from [aditya10avg/voice_doc](https://github.com/aditya10avg/voice_doc). Upstream authorship and history are preserved.

An experimental application that explores Parkinson's symptom prediction from voice-related data.

## Features

- Loads the UCI Parkinson's dataset
- Trains a random forest classifier
- Standardizes training and test features
- Records speech through a Gradio interface
- Extracts basic audio features with Librosa
- Saves recorded features to CSV

## Run

```bash
git clone https://github.com/BhaskarJadhav/voice_doc.git
cd voice_doc
python -m venv .venv
pip install torch pandas numpy scikit-learn matplotlib librosa gradio
python "Pakinson's_analysis.py"
```

## Important limitation

The feature set extracted from recorded audio does not currently match the full feature set used to train the classifier. The repository is an experimental prototype and must not be used for medical diagnosis or treatment decisions.
