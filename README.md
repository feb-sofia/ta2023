# Introduction to Text Analytics 2023

## Schedule

The classes will take place online using skype: https://join.skype.com/FTOd38dr1Bpf

- Mo. 18:00-19:30, starting 20th November 2023
- We. 18:00-19:30

## Setup

An easy way to set up Python on your computer is to use conda. If you don't have a working
conda installation, I recommend [Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html).


After installing Anaconda, clone the GitHub repository of the course on your local computer.
If you don't have a working git installation, check the installation guides:

- [Windows](https://git-scm.com/download/win)
- [Other operating systems](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

and the [tutorial on cloning repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository?platform=windows).

Open Anaconda, create a new conda environment with Python 3.8, and open the Anaconda command prompt.
Change the directory to the project directory where the `requirements.txt` file is located and run pip install.

```shell
pip install -r requirements.txt
```

After installing the requirements, run the following line to download the spacy English language models.

```shell
python -m spacy download en
```
