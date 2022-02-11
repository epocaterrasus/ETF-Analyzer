# ETF Analyzer

This project explores the SQL database ```etf.db``` which include the following stock information(timestamp, open, high, low, close, volume, and daily returns) for the following companies:

* Gold State Resources (GOST)
* Goldman Sachs (GS)
* Google (GOOG)
* Square (SQ)

In this project we run several SQL queries using CRUD operations to select, isolate and join several bits and pieces of our database. We proceed to graph different scenarios using hvPlot and lastly use Voila to create a web visualization of our Jupyter Notebook.
---

## Technologies

The following technologies were used to build and deploy this application:

* Python - Version 3.9.7
* Anaconda (Which includes Jupyter Lab and Pandas)
* hvPlot
* SQLAlchemy
* Voila

---

## Installation and Usage Guide

### 1. Install Python 3.9.7

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Anaconda Installation Files](https://www.anaconda.com/products/individual "Anaconda Installation Files")

If you require assistance installing it, you can follow the following videos for guidance
* [Youtube Video Python Installation Guide - Windows](https://www.youtube.com/watch?v=uSVl7gRXP80 "Python Installation Video - Windows") 
* [Youtube Video Python Installation Guide - Mac](https://www.youtube.com/watch?v=r6bBaj797t8 "Python Installation Video - Mac") 
 
### 2. Install Anaconda and required dependencies

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Python Installation Guide](https://www.python.org/downloads/release/python-397/ "Python Installation Guide")

For installing Anaconda, you can follow the following videos for guidance
* [Youtube Video Anaconda Installation Guide - Windows](https://www.youtube.com/watch?v=g6ln1dAt-RI "Anaconda Installation Video - Windows") 
* [Youtube Video Anaconda Installation Guide - Mac](https://www.youtube.com/watch?v=oWVTO_69U4c "Anaconda Installation Video - Mac")

For installing SQL Alchemy, you can follow the following link for guidance
* [SQL Alchemy Installation Guide](https://pypi.org/project/SQLAlchemy/ "SQL Alchemy Installation Guide")

For installing Voila, you can follow the following link for guidance
* [SQL Alchemy Installation Guide](https://voila.readthedocs.io/en/stable/install.html "SQL Alchemy Installation Guide")

### 3. Downloading the ETF Analyzer Repository

Navigate to your desired location where you would like to save the documents for this application. You can do this by using the ```cd``` command followed by a space and the file path inside quotations ```" file path "```. In my example I have gone to Desktop.

![image](https://user-images.githubusercontent.com/94983278/149385012-181d1769-0af6-487e-8e04-823a28f2c3ed.png)

Clone this project's repository from GitHub using the following command 

```https://github.com/epocaterrasus/ETF-Analyzer.git```

### 4. Opening the file on Jupyter Notebook

Being in the folder created when you downloaded the repository type ```jupyter lab```, this should open a window in your predetermined browser with Jupyter Lab. In the left corner you can see the files inside the repository, open the ```etf_analyzer.ipynb``` which contains all steps and notes followed to analyze this dataset pair.

To run the Voila Notebook, run the following command on GitBash ```voila etf_analyzer.ipynb``` and a window will appear in your browser with the Notebook as an HTML
---

### Images

* Example Image of our Voila WebApp

![image](https://user-images.githubusercontent.com/94983278/153617628-7943cb18-1be8-4521-bfd0-3f88b6f31754.png)
---

## Contributors

Edgar Pocaterra - epocaterra@protonmail.ch / +1 806 283 5455

---

## License

MIT License

Copyright (c) 2022 epocaterrasus

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