# Please refer following order for better understanding
1. **CVRDE_lab_session.pdf** - Which contains instructions whileinstalling vs-code and anaconda environments. Please carefully read the instructions and follow the figures in it. And $\textcolor{red}{\text{red}}$ color refers to references to download.
1. **Ann_sigmoid.ipynb, Ann_relu.ipynb** - Two layered ANN from Scratch using sigmoid and relu activations.
1. **torch_basics.ipynb**- 
    - Give the torch basics like how to add two tensors, how to calculate gradients, 
    - What if we call **.backward()** for second time and how to retrieve this. Most importantly **.grad.zero_()**
    - Please refer this file along with **Ann_torch.ipynb, gd_types.ipynb** files for better understanding of **.grad.zero_()**
1. **Ann_torch.ipynb** - Same like **Ann_sigmoid.ipynb** and **Ann_relu.ipynb** files  but instead we use **.backward()** function and we use **.grad.zero_()** function to clear the buffer of gradients (Please refer along with **torch_basics.ipynb** file for better understanding).
1. **gd_types.ipynb** - Same like **Ann_torch.ipynb** along with other optimizers like 
    - **Momentum, ADAM, RMS Prop** and **Nesterov momentum** along with equations. 
    - Finally it contains SGD (batches). So please try SGD along with momentum.
1. **loss_visualization.ipynb** -
    - It contains 
    -Two visualizations of Regression losses (**Mean Square error (MSE)** and **Mean Absolute Error (MAE)**) 
    - Two visualizations of Classification losses (**Binary Cross Entropy (BCE)** and **Focal losses**)
    - Please try these with other optimization techniques.
1. **torch_backprop.ipynb** - This contains **backprop** operation along with examples of computation graphs.
1. **torch_classification.ipynb** - Contains classification problem which uses moon dataset. The following is the pipeline:
    - Import dependencies
    - Generate synthetic data (moon dataset)
    - Split the dataset into 70: 20: 10 ratio of train validation and test datsets.
    - Load the model into batches.
    - train the model.
    - Evaluate the loss and Accuracy metric.$$Accuracy = (\frac{\text{total samples predicted correctly }}{\text{total no. of samples}})$$ 
1. **torch_Regression.ipynb** - Contains Regression problem which uses sine wave. The following is the pipeline:
    - Import dependencies
    - Generate synthetic data (Sine wave)
    - Split the dataset into 70: 20: 10 ratio of train validation and test datsets.
    - Load the model into batches.
    - train the model.
    - Evaluate the loss for both training and validattion datasets.


``` Please carefully read instructions and install environments of conda and vscode.```


Install dependencies using 

#
**pip install -r requirements.txt**
#

