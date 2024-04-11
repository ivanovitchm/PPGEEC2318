
<center><img width="800" src="images/ct.jpeg"></center>

# Federal University of Rio Grande do Norte
## Technology Center
### Graduate Program in Electrical and Computer Engineering
#### Department of Computer Engineering and Automation 
##### EEC2318 Machine Learning

#### References

- :books: Godoy, Daniel. Deep Learning with PyTorch - Step by Step. [[Link]](https://pytorchstepbystep.com/)
- :books: Tam, Adrian. Deep Learning with PyTorch. [[Link]](https://machinelearningmastery.com/deep-learning-with-pytorch/)
- :books: Cristina, Stefania; Saeed, Mehreen. Building Transformer with Attention. [[Link]](https://machinelearningmastery.com/transformer-models-with-attention/)
- :books: Huyen, Chip. Designing Machine Learning Systems. [[Link]](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/)


**Week 01**: Course Outline [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week01/outline.pdf)
- Detailed breakdown of the course structure and content, exploring various aspects and applications of Machine Learning.
- Motivation, Syllabus, and other issues.

**Week 02**: Fundamentals of Machine Learning [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week02/week02.pdf)
- Fundamentals and first steps about the study of Machine Learning models.

**Week 03**: Visualizing Gradient Descent [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week03/week03.pdf)
- Effective Theory Approach in Deep Learning: big-picture idea.
- Visualizing Gradient Descent: The lesson walks through the process of implementing gradient descent in a linear regression model, covering: Initialization and training of neural networks, viewing them as a set of parameters and functions. Detailed steps of gradient descent, including initializing parameters, computing predictions, computing loss, computing gradients, and updating parameters. The significance of learning rates and their influence on the gradient descent process.
- Gradient Descent with PyTorch
- Critical Evaluation and Key Takeaways

**Week 04**: Rethinking the training loop: a simple classification problem [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week04/week04.pdf)
- [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week04/week04a.ipynb) **Rethinking the training loop**:
    - build a function to perform training steps, implement our own dataset class, use data loaders to generate mini-batches
    - build a function to perform mini-batch gradient descent, evaluate our model
    - save / checkpoint our model to disk
    - load our model from disk to resume training or to deploy
- [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week04/week04b.ipynb) **Going Classy**:
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