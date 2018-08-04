Workshop PyConf Hyderabad 
=========================

**Time Series Analysis with Python**

**_With Applications of Machine Learning Algorithms_**

Session by Dr. Yves J. Hilpisch | The Python Quants GmbH

Hyderabad, 07. October 2017

(short link to this Gist: https://goo.gl/Dvwhe8)

<img src="http://hilpisch.com/images/tpq_bootcamp.png" width=300px>

Quote
-----

"Pichai said that as an 'AI first' company, this is a 'unique moment in time' for Google to combine hardware, software and artificial intelligence. 'It's radically rethinking how computing should work', he said."

_Business Standard, "Google Ramps up Hardware Business", 06. October 2017._


Resources
---------

* http://tpq.io
* http://hilpisch.com
* http://twitter.com/dyjh
* http://pyalgo.tpq.io
* http://certificate.tpq.io

**PyConf Hyderabad 50% Special under http://hydpy.tpq.io**

Slides
------

You find the introductory & overview slides under http://hilpisch.com/hydpy_workshop.pdf


Python
------

If you have either Miniconda or Anaconda already installed, there is no need to install anything new.

We are using Python 3.6. Download and install **Miniconda 3.6** from https://conda.io/miniconda.html if you do not have `conda` already installed.

In any case, you should execute the following lines on the shell/command prompt to create a new environment with the needed packages:

    conda create -n hydpy python=3.6
    (source) activate hydpy
    conda install numpy pandas=0.19 scikit-learn matplotlib
    conda install ipython jupyter
    jupyter notebook

Read more about the management of environments under https://conda.io/docs/using/envs.html

Agenda
------

<img src="http://hilpisch.com/finaince.png" width=300px>

We are going to cover the following topics:

* Reading Financial Time Series Data with pandas
* Working with pandas DataFrame objects
* Formulating a Financial Trading Strategy
* Vectorized Backtesting of the Trading Strategy
* Getting More Realistic by Considering Bid-Ask Spread
* Random Walk Hypothesis
* Prediction based on Classification Algorithm
* Out-of-Sample Performance of Fitted Model

Data
----

You find the data set used under http://hilpisch.com/eurusd.csv (as provided by FXCM Forex Capital Markets Ltd.).

Cloud
-----
Use this link to get a 10 USD starting credit on **[DigitalOcean](https://m.do.co/c/fbe512dd3dac)** when signing up for a new account.

Books
-----

Good book about everything important in Python data analysis: [Python Data Science Handbook, O'Reilly](http://shop.oreilly.com/product/0636920034919.do)

Good book covering object-oriented programming in Python: [Fluent Python, O'Reilly](http://shop.oreilly.com/product/0636920032519.do)


<img src="http://hilpisch.com/tpq_logo.png" width=250px>
