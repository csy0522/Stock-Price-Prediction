# Stock Price Prediction

This project predicts Apple's stock price by using Recurrent Neural Netowrk (RNN) + Long Shrot Term Memory (LSTM).

## Getting Started

Use any python IDE to open the project. I personally use Spyder from Anaconda.You can download both Anaconda or Spyder from the following links:
* [Anaconda](https://www.anaconda.com/distribution/) - The Data Science Platform for Python/R
* [Spyder](https://www.spyder-ide.org/) - The Scientific Python Development Environment

### Data

The data for this project is available on Kaggle which a huge community space for data scientists. Click the following link to download the dataset:
* [Stock_Price_Dataset](https://www.kaggle.com/tarunpaparaju/apple-aapl-historical-stock-data) - Kaggle Stock
### Installation

Before running the program, type the following command to install the libraries that the project depends on

```
pip install numpy, pandas, matplotlib, sklearn, tensorflow
```
Or simply type the following:

```
pip install -r requirements.txt
```

## Running the tests

- The description of each function is located on top of them. Please read them before running to understand the overall structure of the project. <br/>
- This project predicts the stock's Open, High, Low, and Close using combinations of different models and hyperparameters.<br/>
- The following shows the predictions of Open, High, Low, and Close using the basic model:

![Actual V.S Prediction](/data/Actual_vs_Prediction_Graph.png)

- The blue line is the actual stock price, and the red line is the prediction. <br/>
- For more detail, please read the descriptions on top of each function, and run **main.py**. Make sure to run it from an ide that's able to show graphs. The output will show more deails, including accuracy, loss, and more graphs.<br/>
- I also added a **ipynb** file for the main functionin in the **src** directory if you want to run it using [Jupyter Notebook](https://jupyter.org/)

## Deployment

Download any stock price charts from online (Ex: Kaggle) and insert the data to the model in order to test its accuracy.
* [Kaggle](https://www.kaggle.com/) - The Machine Learning and Data Science Community

## Built With

* [Python](https://www.python.org/) - The Programming Language

## Author

* **CSY** - [csy0522](https://github.com/csy0522)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
