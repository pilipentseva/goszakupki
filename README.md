# Working with Russian procurement data

As part of my project, I am trying to work with Russian procurement data. Here I will document the process of that not to forget and be able to ammend the mistake later on. 

# Downloading the data

In 2022, the zakupki.gov.ru website can't be accessed outside from Russia, so I am starting with using VPN which pretends that I am located in Russia. The best way to download the data is by using ftp server. For this server there are log in keys present in my code. For my project I download data for Moscow and from folders notifications, protocols and contracts. I download the whole timeframe of data, so from 2013 to 2022 for the federal law FZ 44. This selection is driven by nature of my  project, code for FZ 223 will look defirently.

The code used for downloading the data is located in the code folder and called 
