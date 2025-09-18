# hebrew-support-call-sim
Internship assignment: Hebrew customer support call simulation using gTTS + Whisper.  Generates client and agent audio files, transcripts, and a simple end-to-end demo in Colab.
# Hebrew Support Call Simulation

This project simulates a customer support call in **Hebrew**:
- Client requests TV subscription cancellation
- Agent replies with confirmation
- Both sides generate **audio (.wav)** and **transcripts (.txt)**

## Tools
- gTTS → Hebrew Text-to-Speech
- OpenAI Whisper (small) → Speech-to-Text
- Phonikud → Phoneme/nikud support

## Usage
Open the notebook in **Google Colab**:

1. Install dependencies  
   ```bash
   !pip install gTTS openai-whisper phonikud
