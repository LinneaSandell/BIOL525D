---
title: "Project_sandell_macpherson"
author: "Linnea Sandell & Ailene MacPherson"
date: '2017-07-10'
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
setwd("/Users/Linnea/Documents/PhD/Projects/BIOL525D/")
```

## Necessary programs

```{bash}
# Update the OS
sudo apt-get update

# Install essential programs

sudo apt-get -y install cmake
sudo apt-get -y install build-essential
sudo apt-get -y install parallel
sudo apt-get -y install zip
sudo apt-get -y install zlib1g-dev
sudo apt-get -y install libncurses5-dev
sudo apt-get -y install git
sudo apt-get -y install liblzma-dev
mkdir bin
cd bin
  wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u112-b15/jdk-8u112-linux-x64.tar.gz

tar xzf jdk-8u112-linux-x64.tar.gz
tar -xf prinseq-lite-0.20.4.tar

cd ~
```
