# Brain Cancer Gene Expression using Neural Networks

Our objective is to use neural networks to predict the class of gene expression in Brain Cancer dataset.

# Table of Contents

[Dataset](#dataset)

[Model](#model-training)

[Presentation](#presentation)

# Dataset

You can download the [Brain cancer gene expression (GSE50161) - CuMiDa](https://www.kaggle.com/datasets/brunogrisci/brain-cancer-gene-expression-cumida) dataset directly from Kaggle, or you can download it in CSV format from [here](https://sbcb.inf.ufrgs.br/cumida) as shown in the following screenshot:

![Screenshot 2023-04-06 at 3 03 07 PM](https://user-images.githubusercontent.com/92266474/230482877-ca8a4463-5517-4d9b-ab08-f86ec51598e3.png)

The number of classes and their distribution is as follows:

![Freq](/Screenshots/freq.png)

# Model Training

The selected model is a simple Neural Network with 6 layers. This was a design choice made by several experiments. Hyperparameter tuning was performed on the selected model to attain the optimum parameters to obtain best training and test accuracies while maintaining a consistently lowering training loss. 

The model layers were defined as shown in the following screenshot:

![model-layers](/Screenshots/model.png)

Additional model parameters were employed for better training:

![model-additional-parameters](/Screenshots/model-additional-parameters.png)

The model summmary is shown in the following screenshot:

![model-summary](/Screenshots/model-summary.png)

The training accuracy and loss were plotted using Plotly as shown below:

![training-acc-loss](/Screenshots/training-acc-loss.png)

The test accuracy of the final model was 61% as shown below:

![test-acc](/Screenshots/test-acc.png)


# Presentation

The presentation can be found [here](/Presentation/BrainCancerPPT.pptx).
