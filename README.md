This is a forked project with attempt for modification, below is the README by the original author Lxbinary
# MT5_to_Python

the repository show 2 ways to transfer data from mt5 to python.
description will be in Russian, if necessary, use Google translate


## MT5
in the folder / mt5 / MQL5 / everything you need to work with all source codes!

terminal from Alpari MT5 Version 5.00 build 1940

<p align="center">
  <img src="https://github.com/Lxbinary/MT5_to_Python/raw/master/img/mt5.png" width="400"/>
</p>
* Advisor sends data when Close is changed for selected instruments
* If you leave the list of instruments empty, it will send for all pairs from the market overview


## Python
made 2 examples:
1) direct receipt and processing of data
2) and test send speed. I have sockets and radishes time from sending from the terminal to receiving in python faster than 0.001 sec (those are very fast and there is no difference at this level)
<p align="center">
  <img src="https://github.com/Lxbinary/MT5_to_Python/raw/master/img/redis_bench.png" width="400"/> &nbsp &nbsp
  <img src="https://github.com/Lxbinary/MT5_to_Python/raw/master/img/socket_bench.png" width="400"/>
</p>

I myself settled on the version with Redis mk:
+ one terminal for many scripts is enough. (work is done as with a single database).
+ in speed, for my needs, more than fast and not inferior to socke

## Install
### Redis
If under Windows: https://github.com/MicrosoftArchive/redis/releases

## Contacts
Telegram: @Lxbinary
