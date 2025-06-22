# micrograd
Recreating [micrograd](https://github.com/karpathy/micrograd) from scratch. Implements backpropagation (reverse-mode autodiff) over a dynamically built DAG and a small neural networks library on top of it with a PyTorch-like API.
The gradients after backpropagation have been verified with PyTorch. 


The neural net trained using this achieved the below decision boundary on the moon dataset : 
![image](https://github.com/user-attachments/assets/ae9e3e61-1d2d-48ba-a553-89329829a3c3)

