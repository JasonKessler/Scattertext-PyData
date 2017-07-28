# Scattertext-PyData
Notebooks for the Seattle PyData 2017 talk on Scattertext

[![Watch the PyData talk here](https://img.youtube.com/vi/H7X9CA2pWKo/0.jpg)](https://www.youtube.com/watch?v=H7X9CA2pWKo)

A guide to using the python package [Scattertext](http://github.com/JasonKessler/scattertext).  If you feel so moved, please star it, fork it, or even contribute!

Check out the introductory presentation [here](https://github.com/JasonKessler/Scattertext-PyData/raw/master/PyData2017Kessler.pptx).

# Using the notebooks
The notebooks look best in Chrome.

## Slow but interactive way
In order to use these notebooks, please execute the following commands, please clone this repo and run (in Python 3):
```
$ git clone https://github.com/JasonKessler/Scattertext-PyData
$ pip3 install scattertext agefromname
$ cd Scattertext-PyData
$ jupyter notebook
```
## Fast and non-interative way
* [First Notebook](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-1.ipynb) how to use Scattertext to visualize differences in document types.
[![Conventions-Visualization.html](https://jasonkessler.github.io/2012conventions0.0.2.2.png)](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-1.ipynb)
* [Second Notebook](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-2.ipynb) how to use Scattertext and AgeFromName to understand how lanugage, gender and political party intersect.
[![Gender and Party](https://github.com/JasonKessler/Scattertext-PyData/raw/master/img/genderandparty.png)](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-2.ipynb)
* [Third Notebook](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-3.ipynb) how to use Scattertext to visualize how the same word or semantic type is discussed different between document categories. In this case, we explore how "jobs" is discussed differently by Republicans and Democrats.
[![Word representations](https://github.com/JasonKessler/Scattertext-PyData/raw/master/img/gensim_similarity.png)](https://nbviewer.jupyter.org/github/JasonKessler/Scattertext-PyData/blob/master/PyData-Scattertext-Part-3.ipynb)


