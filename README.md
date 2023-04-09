# Module 3 Challenge - Crypto Arbitrage

## Program to analyze of historical trade data between Jan 01, 2018 and March 31, 2018 for Bitcoin on two exchanges, Bitstamp and Coinbase.

This is a command line interface run in python that analyzes the historical data of Bitcoin prices on two different exchanges, Bitstamp and Coinbase.

The program is structured in three phases; data collection, preparation and anaylsis. While running the program, it will highlight any arbitrage opportunities that existed between the two exchanges.

---
## Usage

To use this application, simply clone the repository and open jupyter lab from git bash by running the following command:

```python
jupyter lab
```

![example](Images/Jupyter Labs - File SS)


---
## Examples

Bitstamp Graph
![example](Images/Bitstamp Graph)

Coinbase Graph
![example](Images/Coinbase Graph)

Bitstamp vs Coinbase Graph
![example](Images/Bitstamp v Coinbase Graph)

Bitstamp vs Coinbase Arbitrage Spread (Early Dates)
![example](Images/Box Plot)


## Technologies ##

### **Hardware Used**

MacBook Air (13-inch, 2017)

    Processor 1.8 GHz Dual-Core Intel Core i5
    macOS Monterey version 12.6.3

![MacInfo](Images/mac_information.png)

### **Dependencies**

This project used python 3.11 with the following packages:

* [Path](https://docs.python.org/3/library/pathlib.html?highlight=path#module-pathlib) - From 'pathlib', Object-oriented filesystem paths, used to identify a file

* [pandas](https://pandas.pydata.org/docs/) - Software library written for the Python programming language for data manipulation and analysis.


### **Development Software**


anaconda Command line client 1.10.0

    conda 23.1.0
    Python 3.11.2

pip 23.0.1 from /usr/local/bin/python3/site-packages/pip (python 3.11)

    fire 0.3.1
    questionary 1.5.2

git version 2.37.2

Visual Studio Code Version: 1.76.2

---
## *Pre-Installation Guide*

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```
![Loan Qualifier Installs](Images/Fire_install.png)
![Loan Qualifier Installs](Images/Questionary_install.png)


---

## **Installation Guide**

In the terminal, go to the directory where you would like to install this application from the repository and enter the following command:

```python
git clone git@github.com:tmagee28/Columbia-Fintech-Challenge01-03-30-2023.git
```

---

## **Usage**

From terminal, the installed application is run from the installed directory by typing at prompt:

```python
  python3 app.py
```
![Python Code](Images/app_in_action.png)

The below will display examples of the steps to take promts the user should expect using multiple examples:

###    Example 1 - Candidate Qualifying for Multiple Loans

![Example](Images/Example_1_LC.png)
![Example](Images/Example_1_SaveCSV.png)
![Example](Images/Example_1_FileName.png)

###    Example 2 - Candidate Qualifying for Multiple Loans that does not want to save data

![Example](Images/Example_2_DNS_data.png)

###    Example 3 - Candidate not qualifying for any loans

![Example](Images/Example_3_DNQ.png)
---



---

## **Contributors**

### **Author**

Tommy Magee
[LinkedIn](https://www.linkedin.com/in/thomas-magee-2009a72a/)



### **BootCamp lead instructor**

Vinicio De Sola


---

## License

MIT License

Copyright (c) [2022] [Thomas 'Tommy' Magee]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

