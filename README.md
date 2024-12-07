## Facial Recognition Using One-shot Siamese Neural Network

This project implements a convolutional neural network (CNN) using a **Siamese Neural Network** architecture for facial recognition  
with **one-shot learning**. The network is trained to determine whether two facial images belong to the same person.  

This approach is particularly effective in scenarios where data for each class is limited.  

The implementation utilizes **PyTorch Lightning** and the **Labelled Faces in the Wild (LFW-a)** dataset, focusing on the core concepts  
of **similarity learning** and **feature extraction**.  

&nbsp;  
### **Objectives**

- Implement a **Siamese Neural Network** for **one-shot learning** using PyTorch.
- Train the network to compare facial image pairs and classify them as identical or non-identical.
- Perform hyperparameter tuning for key parameters, including learning rates, dropout, batch sizes, and epochs, to optimize the model.
- Evaluate the network’s performance using metrics such as accuracy, loss, and convergence trends.
- Analyze and compare different frameworks to identify trade-offs in terms of performance and usability.

&nbsp;  
### **Dataset Analysis**

**[Labeled Faces in the Wild (LFW-a)](https://vis-www.cs.umass.edu/lfw/index.html)**
  - Contains 5,749 individuals, with 3,202 utilized for this task.
  - Images resized to **105x105x1** for network input.
  - **Data split**:
    - **Training**: 1,760 pairs (1,100 identical, 660 non-identical).
    - **Validation**: 20% the training set (440 pairs).
    - **Test***: 1,000 pairs (500 identical, 500 non-identical).
   



