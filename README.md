Aircraft Damage Classification and Captioning
This project integrates computer vision and natural language processing to automate aircraft damage assessment. It employs VGG16, a pretrained convolutional neural network, for image classification, fine-tuned with a custom fully connected layer. Additionally, BLIP (Bootstrapped Language-Image Pretraining) is utilized for image captioning and summarization, encapsulated within a custom TensorFlow Keras layer to generate textual descriptions of detected damages.

Key Features
Image Classification: Fine-tuned VGG16 model for aircraft damage detection.

Image Captioning & Summarization: BLIP-based transformer model to generate textual descriptions.

Custom Keras Layer: Seamless integration of BLIP for text generation within the TensorFlow framework.

Transfer Learning: Utilizes pretrained weights for improved performance and reduced training time.

Deep Learning & NLP: Combines vision and language models for a comprehensive damage assessment pipeline.

Technologies Used
TensorFlow, Keras – Model training and deep learning optimizations

VGG16 – Feature extraction and classification

BLIP (Hugging Face Transformers) – Image-to-text generation

Matplotlib, PIL – Image processing and visualization

This project demonstrates a multi-modal AI approach for automated damage analysis, bridging the gap between computer vision and NLP for real-world aviation safety applications.
