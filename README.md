# The CCXT Crypto Currency Trade Finder Notebook

The Crypto Trade Finder Notebook makes it easy to analyze the performance of cryptocurrency trading with Jupyter Notebook, Lab, or Hub. Simply install a few required tools, select the market, time period, and exchange you want to analyze, and the notebook takes care of the rest. The analysis is based on technical indicators, and you can easily access a list of all indicators and get help on any individual one. The results of your analysis are beautifully visualized, giving you a clear understanding of your trades' performance. With just a few clicks, you can gain valuable insights into the world of cryptocurrency trading.

## What is Jupyter Notebook

Jupyter Notebook is an open-source web-based interactive computing platform that allows you to create and share documents that contain live code, equations, visualizations, and narrative text. It's often used in data science and machine learning, but it can be used in many other domains as well.

High-Performance Computing (HPC) refers to the use of supercomputing systems to solve complex computational problems. Jupyter Notebook can be used in conjunction with HPC systems to perform computationally intensive tasks. For example, you can use Jupyter Notebook to write code that runs on a cluster of HPC machines to process large datasets. This can be useful when you need to perform a large number of calculations in parallel or when you need access to more computational resources than a single machine can provide.

In conclusion, Jupyter Notebook is a tool for interactive computing and data analysis, while HPC is a field that involves using powerful computing systems to solve complex problems. The two can be combined to perform complex computations on large datasets, making Jupyter Notebook a valuable tool for HPC applications

## Installing Jupyter Notebook

Install Docker:

    On Windows: Download the Docker Desktop for Windows from the official website and follow the installation instructions.
    On Mac: Download the Docker Desktop for Mac from the official website and follow the installation instructions.
    On Linux: Follow the instructions specific to your distribution from the official Docker website.

Start Docker: Once installed, start the Docker application on your computer.

Pull the datascience Docker image: Open the terminal or command prompt and run the following command to pull the datascience Docker image:

bash

docker pull jupyter/datascience-notebook

Run the Docker image: Run the following command to start a Jupyter server with the datascience environment:

bash

docker run -p 8888:8888 jupyter/datascience-notebook

Connect to Jupyter: Once the command has completed, it will output a URL that you can use to access Jupyter in your web browser. The URL will look similar to this:

ruby

    http://127.0.0.1:8888/?token=<unique-token>

    Start using Jupyter: Open the URL in your web browser and start using Jupyter. You can create new notebooks, open existing notebooks, and run code in the datascience environment.

That's it! Now you should be able to run Jupyter using the datascience Docker image on your local machine.
