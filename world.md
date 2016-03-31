# Hello world. I want to change job!

eth_trace_file = open("./trace")
price_file = open("./price_log")
btc_trace_file = open("./bitcoin_window_volumes.txt")
btc_trace = []
eth_trace = []
price = []
import pandas as pd
import math
import numpy as np
import numpy
%matplotlib inline
import matplotlib as mpl
import matplotlib.cm as cm
import matplotlib.pyplot as plt

for line in btc_trace_file.read().splitlines():
    if len(line.split("\t")) <2:
        continue
    btc_trace.append({"timestamp":line.split("\t")[0],
                  "value":float(line.split("\t")[1])})

for line in eth_trace_file.read().splitlines():
    #print line
    eth_trace.append({"timestamp":line.split("\t")[0],
                  "value":float(line.split("\t")[1])})

for line in price_file.read().splitlines():
    a = line.split("\t")
    price.append({"open": float(a[1]),
                  "high": float(a[2]),
                  "low": float(a[3]),
                  "close": float(a[4]),
                  "timestamp":a[0]})
                  
                  

Trade Flow Analysis: Analyzed the trade data information for US IG & HY corporate bonds desks and helped them better manage clients request and inventory.
So this is like a data analysis or data mining project. As one of the biggest broker-dealer in fixed income market, Citi does a lot of trades with our clients, like mutual funds, hedge funds, pension funds, etc. So we want to know if we can get any information from the trades we are doing with our clients. We want to answer questions like, if our clients are more informed player in the market, ie if they are buying the cheap bonds and selling the rich bonds, and if they have more expertise in one specific sector or specific time period. Or, from the bond's perspective, which bonds are more popular in the market and if the buy/sell activities at Citi would impact their prices in the coming days. 


Weekly Report: Published credit spread markets weekly reports on Citi Velocity to track market trends and model performance, and provide clients with insights of the market




Trading Strategy: Developed and implemented the desk’s corporate bond credit momentum strategy and CDS trading strategy. Both beat the index. 
momentum strategy: we actually should call this PD momentum, probability of default. ie in our portfolio, we should disregard the bonds that are deteriorating in the credits, i.e., the trend of their PD increase is largest. 




Model Implementation and Database Infrastructure: Re-implemented the desk’s core models for better efficiency, flexibility and robustness, and reduced the running time from several days to a few hours; Migrated the old database infrastructure to the new one


Of course, it makes the taxi services so convenient to normal people. And the idea is so innovative in the sense that, everyone could be the driver, as well as the passenger. They share the thing they have with others, so people could get a car anywhere, anytime in a matter of minutes. This sharing greatly improve people's daily lives. I think Uber is a leader in this new way of business and has gained great success here. 

As a customer, I think the fact that Uber can't make reservation actually makes me feel not so convenient. But I believe there is a reason that Uber doesn't do that. Yet, I still think we can make some comprise between those two. 



Questions:
Can you tell me more about the role and the team?
what's the future interview process?
What do you like and dislike most about the company?


Manager:
the structure of the team? What's a data scientist's role in the strategic finance team?
Can you introduce some of the past projects to me?







