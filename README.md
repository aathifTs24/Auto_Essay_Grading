# Research - Automated Essay Grading
> A Deep Learning model that predicts the score of a given input essay. 

This project constitutes a one-year research initiative at my university, focusing on the domains of deep learning and natural language processing (NLP). I have developed a model utilizing multilayer perceptron (MLP) and NLP techniques to assess and grade essays written by secondary students. The accompanying screenshot illustrates the final output of the model

### Performance
The accuracy is calculated by **Quadratic Weighted Kappa(QWK)**, which measures the agreement between two raters. My model achieves a **QWK score of 0.80** combined of 8 topics. The model architecture consists of 2 MLP (multi-layer perceptron) layers with a Dense output layer.

### How to Grade
Choose a topic from the eight available options, each with its own scoring range. Write an essay on the selected topic for evaluation. Once you submit the essay, you can review the assigned grade and receive feedback to enhance your writing.


<img src="https://github.com/aathifTs24/Auto_Essay_Grading/blob/main/pictures/Screenshot%202023-12-05%20165013.png" width="100%">
<img src="https://github.com/aathifTs24/Auto_Essay_Grading/blob/main/pictures/prompt.png" width="100%">
<img src="https://github.com/aathifTs24/Auto_Essay_Grading/blob/main/pictures/output.png" width="100%">



## Requirements
- Tensorflow
- Keras
- Django
- Gensim
