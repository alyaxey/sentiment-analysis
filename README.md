# SemEval-2017 Task 5 solution

https://www.aclweb.org/anthology/S17-2089/

Author - Oleksii Sliusarenko. The solution is implemented in python notebook - [solution.ipynb](solution.ipynb). You can see explanations, comments and results there. Note that some files used here are available for research purposes only, for example MaxDiff Twitter Sentiment Lexicon from this resource: <https://www.svkir.com/resources.html#manual_lexicons_BWS>.

## Installation

Execute these steps to download and install anaconda python:

```
wget https://repo.anaconda.com/archive/Anaconda3-5.3.1-Linux-x86_64.sh
bash Anaconda3-5.3.1-Linux-x86_64.sh -b -p ~/anaconda
```

Execute these steps to create and activate a separate working environment:

```
. ~/anaconda/bin/activate
conda create -n sentiment_analysis python=3.6
. activate sentiment_analysis
```

Install python libraries or requirements:

```
# for macos only:
export CFLAGS=-stdlib=libc++
pip install -r requirements.txt
```

## Usage

Launch python notebook and open solution.ipynb in your browser:

```
jupyter notebook
```
