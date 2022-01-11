# Rock Art Detection


This Repo is about my bachelor thesis.
Therefore, I implemented a detection for archaeological rock art in digital images.

## Problem

With the increasing amount of digital images, archaeologists need to find a way to manage their data.
For example the [__Doro! Nawas Database__](http://araf.studiumdigitale.uni-frankfurt.de/) (VFG, Goethe-Univerity Frankfurt am Main [04.04.2019]) contains a vast number of rock art images.

For that reason I invetigated automatic AI solutions for reliable image detection.

## Strategy

I trained __Faster RCNN Inception Resnet V2__ with Tensorflow by four classes:

classes:

- Engraved animal (ea)
- Engraved track (et)
- Painted Human (ph)
- Painted Ainmal (pa)




## Sample pictures
The prictures are modified from the [__Doro! Nawas Database__](http://araf.studiumdigitale.uni-frankfurt.de/) (VFG, Goethe-Univerity Frankfurt am Main [04.04.2019]).

The trained neural network detected the diffrent classes in the test dataset:

![Doro! Nawas Database, VFG, Goethe-Univerity Frankfurt am Main [04.04.2019]](img/raEa.jpg)

![Doro! Nawas Database, VFG, Goethe-Univerity Frankfurt am Main [04.04.2019]](img/raEt.jpg)

![Doro! Nawas Database, VFG, Goethe-Univerity Frankfurt am Main [04.04.2019]](img/raPh.jpg)

![Doro! Nawas Database, VFG, Goethe-Univerity Frankfurt am Main [04.04.2019]](img/raPa.jpg)

## Results

Artificial intelligence, such as CNN's are pioneering and helpfully tools for automatic image detection.
This type of image processing is of great importance for many domains such as archaeology.

## Cite

@bachelorsthesis{bachelorsthesis,
author       = {Wei{\ss}mann, Julius},
title        = {Maschinelles Lernen in der Felsbildarch\"aologie},
school       = {Johann Wolfgang Goethe-Universit\"at Frankfurt am Main},
year         = 2019,
address      = {Offenbach},
month        = 05,
}

## Licence

CC BY 2.0

