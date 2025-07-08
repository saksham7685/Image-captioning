# Image Captioning with CNN-LSTM

An implementation of an image captioning system using a CNN encoder and LSTM decoder. This project generates natural language descriptions of images using deep learning.


## Features

- **Encoder**: ResNet-152 pretrained on ImageNet for image feature extraction
- **Decoder**: LSTM network for sequence generation
- **Attention Mechanism**: Generates captions by focusing on relevant parts of the image
- **Pre-trained Models**: Ready-to-use models available for quick inference



### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Saksham7685/image-captioning.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Training

To train the model:

1. Download the COCO dataset from download.sh file
2. Preprocess the data:
   ```bash
   python build_vocab.py
   python resize.py
   ```
3. Start training:
   ```bash
   python train.py
   ```

## Sample Image

### Input 
![alt text](image-1.png)

### Output 
a dog is sitting on a green grass covered field 
