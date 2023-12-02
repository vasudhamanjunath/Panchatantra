# Panchatantra

# Overview
This project aims to convert input text into engaging and child-friendly audio segments using a Text-to-Speech (TTS) system. The process involves paragraph and sentence segmentation, division into manageable audio segments, and synthesis using the ForwardTacotron and FastPitch models.

# Getting Started
Prerequisites

Make sure you have the following installed:

-> Python 3.x

-> Required Python packages 

# Usage
1) Input Text Preparation: Place the input text file(s) in the data/ directory.

2) Run the TTS Synthesis Script:
   
python src/tts_synthesis.py

This script will execute the entire TTS process, including paragraph and sentence segmentation, audio segment division, and synthesis using the ForwardTacotron and FastPitch models.

3) Check the Output:

The synthesized audio segments will be saved in the output/ directory.

# Customization
Adjust the number of sentences per audio segment in tts_synthesis.py.

Explore and fine-tune the ForwardTacotron and FastPitch models for specific needs.

Modify the pitch function in the code to tailor it for different age groups or preferences.

# License
This project is licensed under the MIT License.

# Acknowledgments
ForwardTacotron and FastPitch model developers for their contributions.


