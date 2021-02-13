---
layout: post
title:  "install Qiime2"
date:  2021-02-24
categories: micro
author: "sy"
---


You need Anaconda / Python before install Qiime2 
install python 
Anaconda : https://www.anaconda.com/products/individual#download-section   (Window / mac / linux ) 
install process ( reference site :https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart )
command line : sha256sum Anaconda3-2019.03-Linux-x86_64.sh
command line : bash Anaconda3-2019.03-Linux-x86_64.sh
command line : source ~/.bashrc


----------------------------------------------------------Install Qiime2 ----------------------------------------------------------------

reference : https://qiime2.org/
install qiime2
linux for 
wget https://data.qiime2.org/distro/core/qiime2-2020.11-py36-linux-conda.yml
conda env create -n qiime2-2020.11 --file qiime2-2020.11-py36-linux-conda.yml
or 
mac for 
wget https://data.qiime2.org/distro/core/qiime2-2020.11-py36-osx-conda.yml
conda env create -n qiime2-2020.11 --file qiime2-2020.11-py36-osx-conda.yml
conda activate qiime2-2020.11

---------------------------------------------------------- Qiime2 tutorial ----------------------------------------------------------------

https://docs.qiime2.org/2020.11/tutorials/moving-pictures/
