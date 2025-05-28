
<center><img width="800" src="images/ct.jpeg"></center>

# Federal University of Rio Grande do Norte
## Technology Center
### Graduate Program in Electrical and Computer Engineering
#### Department of Computer Engineering and Automation 
##### PEEC2318 Machine Learning

#### References

- :books: Godoy, Daniel. Deep Learning with PyTorch - Step by Step. [[Link]](https://pytorchstepbystep.com/)
- :books: Tam, Adrian. Deep Learning with PyTorch. [[Link]](https://machinelearningmastery.com/deep-learning-with-pytorch/)
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
    - Reading: [Machines of Loving Grace](https://darioamodei.com/machines-of-loving-grace)

**Week 02**: Fundamentals and First Steps [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week02/week02.pdf)
- Nature of Human Intelligence versus Artificial Intelligence
- Types of Machine Learning
- :movie_camera: [ML Fundamentals and Decision Trees](https://github.com/ivanovitchm/ppgeecmachinelearning)
    - Study the material of weeks 2,3 and 4.

**Week 03**: Visualizing Gradient Descent [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week03/week03.pdf)
- This week's lesson focuses on understanding and visualizing the five core steps of the Gradient Descent algorithm: (1) initializing parameters randomly, (2) performing the forward pass to compute predictions, (3) calculating the loss, (4) computing gradients with respect to each parameter, and (5) updating the parameters using the gradients and a predefined learning rate. We implemented these steps manually and using PyTorch's autograd and optimizer tools, analyzing how different configurations affect convergence.


**Week 04**: Rethinking the Training Loop (Part I) [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week04/week04.pdf)

- Rethinking the Training Loop [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week04/week04a.ipynb)
    - **Implement the training function:** Create a dedicated function to execute training steps, implement a custom dataset class, and use data loaders to generate mini-batches.
    - **Perform mini-batch gradient descent:** Develop a routine for mini-batch gradient descent and evaluate your model’s performance.
    - **Ensure model persistence:** Save and checkpoint your model to disk, enabling you to resume training later or deploy the model.
- Going Classy [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week04/week4b.ipynb)
    - **Create a training class:** Define a robust class to handle model training.
    - **Implement the constructor:** Properly set up the class constructor.
    - **Handle method accessibility:** Understand and apply the differences between public, protected, and private methods.
    - **Integrate the code:** Organize and merge the previously developed code into the class structure.
    - **Execute the pipeline:** Instantiate the class and use it to run an efficient training pipeline.

**Week 05**: Rethinking the Training Loop (Part II) [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week05/week05.pdf)

- [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week05/week05c.ipynb) **A simple classification problem**:
    - build a model for binary classification
    - understand the concept of logits and how it is related to probabilities
    - use binary cross-entropy loss to train a model
    - use the loss function to handle imbalanced datasets
    - understand the concepts of decision boundary and separability

**Weeks 06 and 07**: Guided Project - Binary Classification Problem [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week0607/Project01.pdf)

**Weeks 08 and 09**: Machine Learning and Computer Vision - Part I [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week08/Week08.pdf)
- [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week08/Week08.ipynb) **From a shallow to a deep-ish clasification model**:
    - data generation for image classification
    - transformations using torchvision
    - dataset preparation techniques
    - building and training logistic regression and deep neural network models using PyTorch
    - focusing on various activation functions like Sigmoid, Tanh, and ReLU

**Week 10**: Machine Learning and Computer Vision - Part II [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week10/Week10.pdf)
- [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week10/Kernel.ipynb) **Kernel**
- [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/ppgeec2318/blob/main/lessons/week10/Week10.ipynb) **Convolutions**:
    - In this lesson, we’ve introduced convolutions and related concepts and built a convolutional neural network to tackle a multiclass classification problem.
        - Activation function, pooling layer, flattening, Lenet-5
        - Softmax, cross-entropy
        - Visualizing the convolutional filters, features maps and classifier layers
        - Hooks in Pytorch