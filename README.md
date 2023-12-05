# Research - Automated Essay Grading
> A Deep Learning model that predicts the score of a given input essay. 

This project constitutes a one-year research initiative at my university, focusing on the domains of deep learning and natural language processing (NLP). I have developed a model utilizing multilayer perceptron (MLP) and NLP techniques to assess and grade essays written by secondary students. The accompanying screenshot illustrates the final output of the model

### Performance
The accuracy is calculated by **Quadratic Weighted Kappa(QWK)**, which measures the agreement between two raters. My model achieves a **QWK score of 0.80** combined of 8 topics. The model architecture consists of 2 MLP (multi-layer perceptron) layers with a Dense output layer.

<img src="https://github.com/aathifTs24/Auto_Essay_Grading/blob/main/pictures/prompt.png" width="100%">
<img src="https://github.com/aathifTs24/Auto_Essay_Grading/blob/main/pictures/output.png" width="100%">
<img src="https://github.com/mankadronit/Automated-Essay--Scoring/blob/master/ScreenShots/SC3.png" width="100%">


## Requirements
- Tensorflow
- Keras
- Django
- Gensim
