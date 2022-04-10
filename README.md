
# FTX Grid Trading Bot

The program was designed to run the Grid Trading Strategy in [FTX exchange](https://ftx.com/referrals#a=6129389)
 
Grid trading strategy can follow [here](https://www.gridtradingcourse.com/articles/what-is-grid-trading.php).


It requires python 3.x and the following Python packages:
* [simplejson](https://pypi.org/project/simplejson/)
```
pip install ccxt simplejson
```

## Getting Started
The program is suggested to run in the Linux/Mac platform; also, you need to edit some parameters before program start. Follow the behind steps. 
1. Edit some config parameters in `sample.json` and rename it to `XXX.json`, where XXX is your trading symbol.
2. Go to the terminal and run the following command
```
python3 main.py XXX.json
```
3. If you want to run several accounts at the same time, just open another terminal and create another XXX.json file then run it. 