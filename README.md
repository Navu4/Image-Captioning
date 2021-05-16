# Image-Captioning

TensorFlow implementation of Show, Attend and Tell: Neural [Image Caption Generation with Visual Attention](https://arxiv.org/pdf/1502.03044.pdf) which introduces an attention based image caption generator. The model changes its attention to the relevant part of the image while it generates each word.

![attention_over_time](https://user-images.githubusercontent.com/51900952/118377582-b8f5f180-b5eb-11eb-8c7d-2fc18dcdc496.jpg)

## Getting Started

### Prerequisites
First, clone this repo and download the dataset there are many open source datasets available for this problem, like Flickr 8k (containing8k images), Flickr 30k (containing 30k images), MS COCO (containing 180k images), etc.  I have used the Flickr 8k dataset which you can download from here or by this [drive link](https://drive.google.com/drive/folders/1kye2WaLsWwsMdZ1TMKgpAkCgaf8kXq_y?usp=sharing) I have used the Flickr 8k dataset which you can download from here. This dataset contains 8000 images each with 5 captions 

```txt
https://github.com/Navu4/Image-Captioning
```
 
 
#### Install dependencies and Libraries required using requirements.txt
```txt
pip install -r requirements.txt
```

Run the Image_Captioning_using_VGG.ipynb or Image_captioning_using_Inception.ipynb to Create,Evaluate and Predict [Model](https://github.com/Navu4/Image-Captioning/tree/main/model_weights) 

I have Implemented Image-Captioning using Attention Mechanism in which Encoder is implemented using to difference State of Art Model i.e. VGG16 and InceptionV3. The link of the notebook is given below. 

#### Implementation of Image Captioning using Inception as a Encoder.
```txt
https://github.com/Navu4/Image-Captioning/blob/main/Image_captioning_using_Inception.ipynb
```

#### Implementation of Image Captioning using Inception as a Encoder.
```
https://github.com/Navu4/Image-Captioning/blob/main/Image_Captioning_using_VGG.ipynb
```
