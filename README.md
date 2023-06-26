# FinTech ETF Performance Analysis

In this project, you will leverage the power of SQL, Python, and the Voilà library to create a financial database and web application. The goal is to gain insights into the ETF's performance and visualize the data through interactive visualizations.

---

## Technologies

The technologies used in this project include:

   * Python 3.7
   * JupyterLab 3.5.3
   * Pandas 1.5.3
   * hvPlot 0.8.4
   * SQLAlchemy 1.4.39
   * Voilà 0.3.4
---

## Installation Guide

Open your terminal and install JupyterLab as shown below:

```python
  python -m ipykernel install --user --name
```

Next, install the packages hvplot and geoviews with the following code:

```python
  conda install -c pyviz hvplot geoviews
```

Lastly, install SQLAlchemy and Voilà:

```python
     pip install aqlalchemy
     pip install -c conda-forge voila
```


---

## Usage

Clone the repository and Launch Jupyter Notebook by executing the following command in your terminal:

```python
  jupyter lab
```

In the Jupyter Notebook interface, navigate to the project directory and open the etf_analyzer.ipynb file.

Execute each cell in the notebook sequentially to run the analysis and generate the visualizations.

In the first part of the project, you will view the daily returns and cumulative return of the PYPL asset.

Additionally, you can access the closing prices for PYPL that are greater than 200 and view the top 10 daily returns for PYPL.

The notebook also includes a step to join each table in the portfolio into a single DataFrame. This allows you to calculate the annualized returns for the portfolio and the cumulative returns of the ETF portfolio.

Lastly, you can visualize the cumulative return values of the ETF portfolio in an interactive line plot.

Explore the interactive visualizations to gain insights into the ETF data and analyze the performance of the portfolio.

To open the application in a Web page run the following command in the terminal:

```python
  voila <relative-path-to-etf_analyzer.ipynb>
```

This will display the web page with the interactive application.

![Web Application Screenshot](WebAppScreenshot.png)


---


## Contributors

* Ana Martelo (anafilipamartelo@gmail.com)

---

## License

MIT
