
<center><img width="800" src="images/ct.jpeg"></center>

# Federal University of Rio Grande do Norte
## Technology Center
### Graduate Program in Electrical and Computer Engineering
#### Department of Computer Engineering and Automation 
##### PEEC2318 Machine Learning

#### References

- :books: Godoy, Daniel. Deep Learning with PyTorch - Step by Step. [[Link]](https://pytorchstepbystep.com/)
- :books: Tam, Adrian. Deep Learning with PyTorch. [[Link]](https://machinelearningmastery.com/deep-learning-with-pytorch/)
- :books: Cristina, Stefania; Saeed, Mehreen. Building Transformer with Attention. [[Link]](https://machinelearningmastery.com/transformer-models-with-attention/)
- :books: Huyen, Chip. Designing Machine Learning Systems. [[Link]](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/)


**Week 01**: Course Outline [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week01/outline.pdf)
- Detailed breakdown of the course structure and content, exploring various aspects and applications of Machine Learning.
- Motivation, Syllabus, and other issues.
-  🎉 GitHub Education Benefits
        - GitHub Education Pro: Get access to the GitHub Education Pro pack by visiting [GitHub Education](https://education.github.com/pack)
    - 📖 Learning Resources 
        - GitHub Learning Game: Check out the interactive Git learning game at [GitHub Learning Game](https://learngitbranching.js.org/)
        - Basic Python: Enhance your Python skills through the [Kaggle Python course](https://www.kaggle.com/learn/python).
    - AI Python for Beginners: Learn Python programming fundamentals and how to integrate AI tools for data manipulation, analysis, and visualization. [Andrew Ng](https://www.deeplearning.ai/short-courses/ai-python-for-beginners/)

**Week 02**: Machine Learning Fundamentals [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week02/fundamentals.pdf)
- Motivation: how advances in Machine Learning are helping bridge the gap between AI's current capabilities and human cognitive abilities, highlighting limitations and future directions for AI systems.
- Overview of Machine Learning fundamentals, including an exploration of semi-supervised learning, active learning, and weak supervision.
- Discussion on Moravec's Paradox: examining the difference in cognitive complexity between tasks easily handled by AI versus tasks natural to humans.
- Self-supervised learning: Introduction to pretext tasks, where models are trained on unlabeled data, and their application in Natural Language Processing (NLP).

Key Concepts:
- Semi-supervised Learning: Training a model using both labeled and unlabeled data.
- Active Learning: A model that actively seeks human-labeled data for improved accuracy.
- Weak Supervision: Using weakly labeled data generated through heuristics or external knowledge sources.
- Self-Supervised Learning: Training models on pretext tasks to build representations from unlabeled data, with applications in NLP.

**Week 03**: Visualizing Gradient Descent [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week03/week03.pdf)
- In this week's lesson, we explore the Gradient Descent algorithm, a fundamental method for optimizing machine learning models. The focus is on understanding how gradient descent works and its application in training a linear regression model. We also examine the use of PyTorch for implementing these concepts, visualizing the steps, and critically evaluating key aspects of gradient-based optimization.

**Week 04**: Rethinking the training loop: a simple classification problem [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week04/week04.pdf)
- [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week04/week04a.ipynb) **Rethinking the training loop**:
    - build a function to perform training steps, implement our own dataset class, use data loaders to generate mini-batches
    - build a function to perform mini-batch gradient descent, evaluate our model
    - save / checkpoint our model to disk
    - load our model from disk to resume training or to deploy
- [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week04/week4b.ipynb) **Going Classy**:
    - define a class to handle model training
    - implement the constructor method
    - understand the difference between public, protected, and private methods of a class
    - integrate the code we’ve developed so far into our class
    - instantiate our class and use it to run a classy pipeline
- [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week04/week04c.ipynb) **A simple classification problem**:
    - build a model for binary classification
    - understand the concept of logits and how it is related to probabilities
    - use binary cross-entropy loss to train a model
    - use the loss function to handle imbalanced datasets
    - understand the concepts of decision boundary and separability

**Week 05**: Machine Learning and Computer Vision - Part I [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week05/Week05.pdf)
- [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week05/Week05.ipynb) **From a shallow to a deeep-ish clasification model**:
    - data generation for image classification
    - transformations using torchvision
    - dataset preparation techniques
    - building and training logistic regression and deep neural network models using PyTorch
    - focusing on various activation functions like Sigmoid, Tanh, and ReLU 