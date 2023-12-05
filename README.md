# Research - Automated Essay Grading
> A Deep Learning model that predicts the score of a given input essay. 

Developed an innovative Auto Essay Grading system over a one-year period, employing cutting-edge Deep Learning and Natural Language Processing (NLP) techniques. The primary objective of this research initiative was to enhance student learning outcomes while alleviating the workload on teachers. Implemented a Hybrid Approach that seamlessly integrates rule-based and machine-learning methodologies to achieve a comprehensive and accurate essay evaluation.

Utilized a Multi-Layer Perceptron (MLP) to construct the grading model, incorporating various preprocessing techniques to transform words into vectors. The system evaluates essays based on grammar, style, content, and the underlying intent behind student writing. Significantly contributed to the education technology landscape by creating a solution that not only assesses essays but also provides detailed feedback for improvement.

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
