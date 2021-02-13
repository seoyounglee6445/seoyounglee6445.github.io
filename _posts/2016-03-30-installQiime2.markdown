---
layout: post
title:  "install Qiime2"
date:  2021-02-14 19:45:31 +0530
categories: micro
author: "sy"
---


You need Anaconda / Python before install Qiime2 <br>   
install python <br>
Anaconda : https://www.anaconda.com/products/individual#download-section   (Window / mac / linux ) <br> 
install process ( reference site :https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart )  <br> 
command line : sha256sum Anaconda3-2019.03-Linux-x86_64.sh <br>
command line : bash Anaconda3-2019.03-Linux-x86_64.sh <br>
command line : source ~/.bashrc <br>


--------- Install Qiime2 --------- <br>

reference : https://qiime2.org/ <br>
install qiime2 <br>
linux for  <br>
wget https://data.qiime2.org/distro/core/qiime2-2020.11-py36-linux-conda.yml <br>
conda env create -n qiime2-2020.11 --file qiime2-2020.11-py36-linux-conda.yml <br>
or  <br>
mac for  <br>
wget https://data.qiime2.org/distro/core/qiime2-2020.11-py36-osx-conda.yml <br>
conda env create -n qiime2-2020.11 --file qiime2-2020.11-py36-osx-conda.yml <br>
conda activate qiime2-2020.11 <br>

--------- Qiime2 tutorial ---------<br>

https://docs.qiime2.org/2020.11/tutorials/moving-pictures/ <br>
