# TOW-IDS: Intrusion Detection System Based on Three Overlapped Wavelets for Automotive Ethernet

## Project Overview
This project is dedicated to developing an effective Intrusion Detection System (IDS) aimed at identifying Abnormal behaviors in a network traffic which is collected from CAN, AVB, and gPTP
protocols in Automotive Ethernet. Utilizing Deep Learning algorithms like ResNet50 and EfficientNetB0 and a customized DCNN model, this system is designed to detect abnormal network traffic. refer to the  [TOW-IDS - IEEE paper link](https://ieeexplore.ieee.org/document/9947068/algorithms?tabFilter=dataset#algorithms)


## Installation
Instructions for setting up the Intrusion Detection System on Jupyter Notebook:

1. **Prerequisites**: Ensure you have [Python 3.8+](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installation/) installed.

2. **Install the dependencies**:
   ```bash
   pip install requirements.txt
3. **Setup the Files**:
    Run the preprocessing file and wavelet transformation file, the generated files will be saved in a folder, then train each of the model. If you have gpu enabled, the training will be faster or else you can train it on cpu.
