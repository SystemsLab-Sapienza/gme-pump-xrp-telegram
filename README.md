This repository contains additional material for the paper:

[The Doge of Wall Street: Analysis and Detection of Pump and Dump Cryptocurrency Manipulations](https://dl.acm.org/doi/full/10.1145/3561300)

If you use this data, or use the findings from the paper, please cite:

```
@article{10.1145/3561300,
author = {La Morgia, Massimo and Mei, Alessandro and Sassi, Francesco and Stefa, Julinda},
title = {The Doge of Wall Street: Analysis and Detection of Pump and Dump Cryptocurrency Manipulations},
year = {2023},
issue_date = {February 2023},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {23},
number = {1},
issn = {1533-5399},
url = {https://doi.org/10.1145/3561300},
doi = {10.1145/3561300},
abstract = {Cryptocurrencies are increasingly popular. Even people who are not experts have started to invest in these assets, and nowadays, cryptocurrency exchanges process transactions for over 100 billion US dollars per month. Despite this, many cryptocurrencies have low liquidity and are highly prone to market manipulation. This paper performs an in-depth analysis of two market manipulations organized by communities over the Internet: The pump and dump and the crowd pump. The pump and dump scheme is a fraud as old as the stock market. Now, it has new vitality in the loosely regulated market of cryptocurrencies. Groups of highly coordinated people systematically arrange this scam, usually on Telegram and Discord. We monitored these groups for more than 3 years, detecting around 900 individual events. We report on three case studies related to pump and dump groups. We leverage our unique dataset of the verified pump and dumps to build a machine learning model able to detect a pump and dump in 25 seconds from the moment it starts, achieving the results of 94.5% of F1-score. Then, we move on to the crowd pump, a new phenomenon that hit the news in the first months of 2021, when a Reddit community inflated the price of the GameStop stocks (GME) by over 1,900% on Wall Street, the world’s largest stock exchange. Later, other Reddit communities replicated the operation on the cryptocurrency markets. The targets were DogeCoin (DOGE) and Ripple (XRP). We reconstruct how these operations developed and discuss differences and analogies with the standard pump and dump. We believe this study helps understand a widespread phenomenon affecting cryptocurrency markets. The detection algorithms we develop effectively detect these events in real-time and helps investors stay out of the market when these frauds are in action.},
journal = {ACM Trans. Internet Technol.},
month = {feb},
articleno = {11},
numpages = {28},
keywords = {fraud detection, cryptocurrencies, Pump and dump}
}
```
## The dataset

The dataset contains all the messages, files, videos, and images posted on the “OFFICIAL BUY & HOLD XRP” Telegram group. 
The pump events are listed inside the ```pump_telegram.csv``` file.
