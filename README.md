Gaussian and Binomial distributions Python Package for Machine Learning and Data Science
[![CircleCI](https://circleci.com/gh/google/pybadges.svg?style=svg)](https://circleci.com/gh/google/pybadges)
![pypi](https://img.shields.io/badge/pypi-0.0.2-green)
![versions](https://img.shields.io/badge/python-3.6%20%7C%203.7%20%7C%203.8-blue)
![licence](https://img.shields.io/badge/licence-MIT%20license-orange)

# neha_probability_distribution

**neha_probability_distribution** is a Python module/package for [Machine Learning](https://expertsystem.com/machine-learning-definition/) and [Data Science](https://en.wikipedia.org/wiki/Data_science) built for Gaussian and Binomial distributions. This package is distributed under the [MIT License](https://opensource.org/licenses/MIT).

## Installation.
To install simply run(Commandline);
```
pip install neha-probability-distribution
```
or 
```
conda install neha-probability-distribution
```
PyPI link: https://pypi.org/manage/project/neha-probability-distribution/

## Testing.
For this test version of the package I would recommend running it on a [Virtual Environment](https://docs.python-guide.org/dev/virtualenvs/)
```
pip install -i https://test.pypi.org/simple/ neha-probability-distribution/
```
TestPyPI link: https://test.pypi.org/project/neha-probability-distribution/

### Sample python test code.
On your commandline run below python code after installation.
```
>>> from distributions_gauss_bi import Gaussian, Binomial
>>> Gaussian(38,17)
>>> Binomial(0.4, 35)
```

## Gaussian and Binomial distribution overview
### 1. Gaussian distribution (also known as Normal distribution) 
- In probability theory, a normal distribution is a type of continuous probability distribution for a real-valued random variable. The general form of its probability density function is The parameter is the mean or expectation of the distribution; and is its standard deviation. 
### 2. Binomial distribution.
- In probability theory and statistics, the binomial distribution with parameters n and p is the discrete probability distribution of the number of successes in a sequence of n independent experiments, each asking a yes–no question, and each with its own boolean-valued outcome: success/yes/true/one (with probability p) or failure/no/false/zero (with probability q = 1 − p). <br>

#### Further Resources.
If you would like to review the Gaussian (normal) distribution and binomial distribution, here are a few resources:
* [Gaussian Distribution](https://en.wikipedia.org/wiki/Normal_distribution)
* [Binomial Distribution](https://en.wikipedia.org/wiki/Binomial_distribution)
