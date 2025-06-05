# 6-Human-Emotion-Classification-Using-Transfer-Learning
Background: Emotion recognition from facial images is a core component in affective computing, essential in security surveillance, and healthcare systems.
Research Objective: To investigate and compare the performance, generalization capability, and architectural trade-offs of VGG16 and ResNet50 on a 6-class human emotion classification task using transfer learning
Dataset Source: Kaggle
Classes: Anger, Disgust, Fear, Happy, Sad, Pain
Preprocessing: Uniform resizing to 224×224 pixels
Image normalization using vgg16.preprocess_input() which scales pixel values to match ImageNet statistics.
Train-Test Split: 80/20 ratio
Stratified sampling to preserve class distribution

