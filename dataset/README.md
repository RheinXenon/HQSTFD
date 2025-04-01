# HQSTFD

## Introduction

The HQSTFD dataset is designed for training edge-preserving image smoothing tasks. It provides a suitable platform for evaluating various smoothing methods that can preserve the edges in an image while reducing noise.

## Installation

To get started, follow these steps:

1. **Clone the repository**:

   ```
   git clone https://github.com/RheinXenon/HQSTFD
   ```

2. **Install required Python dependencies**:

   Make sure you have Python 3.7 or higher installed, then install the necessary dependencies with the following commands:

   ```
   pip3 install torch torchvision torchaudio
   pip3 install matplotlib
   ```

3. **Download the dataset**:

   Use the link below to download the dataset (you will need to enter the provided code):

   ```
   https://pan.baidu.com/s/1fUj8KWl42NnlyWdOZe1tGw?pwd=a3zi (code: a3zi)
   ```

## Usage

### Testing Methods

- **BDCN Method**:  
   To test the model with the BDCN method, run the `test_HQSTFD.py` script located in the `.\BDCN` directory. You can specify the dataset (e.g., BSDS500 or NYUD) to test on by using the `-t` flag:

   ```
   run test_HQSTFD.py -t [BSDS500\NYUD]
   ```

- **BEPS Method**:  
   To train the model using BEPS, run the `BEPS_train_by_TED.py` script located in the `.\BEPS` directory.

### Results

After testing or training, the results will be saved in the corresponding method's `result` directory for further evaluation.

## Requirements

Make sure you have the following software versions:

- Python 3.7
- PyTorch 1.8.1
- Matplotlib 3.4.1

