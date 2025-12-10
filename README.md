# Machine-Learning-Project
## How to Run
1. Place `random_stock_market_dataset.csv` in the same folder as the notebook.  
2. Open `dropout_demo.ipynb` in Jupyter Notebook or VS Code.  
3. Run all cells to reproduce the experiment and visualize results.

## Description
Dropout randomly turns off neurons during training to prevent overfitting.  
This simple experiment shows that the model with dropout has smoother validation loss  
and usually generalizes better than the one without.

## References
- Srivastava et al. (2014). *Dropout: A Simple Way to Prevent Neural Networks from Overfitting.* JMLR.  
- TensorFlow Documentation: https://www.tensorflow.org/api_docs/python/tf/keras/layers/Dropout  
- Machine Learning Mastery  *Dropout for Neural Networks*  
- Towards Data Science  *Understanding Dropout in Neural Networks*

## License
MIT License © 2025

# Dropout in Neural Networks  Stock Market Classification Demo

This project demonstrates how dropout helps prevent overfitting in neural networks.  
Two models are trained on a stock market dataset  one **with dropout** and one **without**  
to compare their performance in predicting whether the next day's closing price will increase.

## Dataset
- File: random_stock_market_dataset.csv  
- Target: Binary label (1 if next-day Close > today's Close, else 0)

## What's Included
- dropout_demo.ipynb  main notebook (comparison experiment)
- dropout_tutorial.pdf  tutorial with explanations and references
- LICENSE  project license (MIT)
- README.md  this file

## Requirements
To run this project, install:
Anaconda For Libraries
Jupyter Notebook for Python Code
PDF Reader For Tutorial




