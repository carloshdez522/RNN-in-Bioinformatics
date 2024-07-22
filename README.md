# RNN in Bioinformatics
**Authors:** Carlos Alfredo Hernández Alvarez, Anabel Abreu Llanes

**ORCID:** [0009-0006-6749-1686](https://orcid.org/0009-0006-6749-1686), [0009-0003-7264-3785](https://orcid.org/0009-0003-7264-3785)

## Project Description
This paper presents a guide on the use of Recurrent Neural Networks (RNN) for stock price prediction using historical data. RNNs, and specifically Long Short-Term Memory (LSTM), are neural network architectures designed to handle sequences of data, making them ideal for tasks where temporal context is crucial, such as in time series and bioinformatics.

## Objetive
The main objective is to show how RNNs can be used, specifically through the LSTM (Long Short-Term Memory) architecture, to predict company stock prices from historical data. This deep learning technique is especially useful in the field of bioinformatics, where data sequences, such as DNA sequences or biomedical data time series, are common and require advanced methods for analysis and prediction.

## Recommendations
- **Use of Adequate Computational Resources:**
The Recurrent Neural Networks (RNN) model with LSTM architecture presented in this notebook was trained using Google's Tensor Processing Units (TPU) with 300 GB of RAM, freely available in the Google Colab environment. This high level of computational resources allows handling large volumes of data and training complex models efficiently.

- **Memory Requirements:**
It is not recommended to run this notebook in an environment with less than 50 GB of RAM due to the high computational requirements of the model and the volume of data processed. An environment with limited resources can result in long run times and possible crashes due to lack of memory.

- **Use of the Trained Model:**
For those who wish to use the trained model without having to retrain it, they can download the model files and their weights from the Google Colab environment. The notebook includes specific instructions on how to load the previously trained model using the `save_models` and `load_models` functions. This allows predictions to be made without the need for extensive computational resources, taking advantage of the work previously done.

## Contributions
Contributions are welcome. If you find any bugs or have suggestions for improvement, please create a pull request or open an issue in the repository.

## Code Usage
To run the project and get results:

1. Clone this repository on your local machine.
2. Open the `RNN in Bioinformatics.ipynb` file in Jupyter Notebook or Google Colab.
3. Follow the instructions and execute the code cells to perform the simulation.
4. Explore the obtained results and adjust the parameters as needed.
