# TraderDaddy
Automatically trade Bitcoin and other cryptocurrency for profit.



## v0.1.5 (2015-06-03)

Bugfixes:
- Missing dashboard on/off switch in some situations
- Stability improvements



## v0.1.4 (2015-05-31)

Features:
- Market ladders
- New layout / design
- Improved trading logic
- Separate budget for each exchange
- Separate risk tolerance for each exchange



## v0.1.3 (2015-05-03)

Bugfixes:
- Fixed more turn-off problems caused by Bittrex API throttling
- Fixed Bittrex market selection issue introduced in v0.1.2



## v0.1.2 (2015-05-02)

Bugfixes:
- Fixed turn-off problems caused by Bittrex API throttling



## v0.1.1 (2015-04-30)

Bugfixes:
- Check Rubycoin on Poloniex when enabling Juggernaut
- Reset risk/mode when Juggernaut is disabled
- Fixed Poloniex buy/sell cycling



## v0.1.0 (2015-04-28)

Bugfixes:
- Hide risk tolerance in Thor when Juggernaut is enabled
- Properly handle Bittrex API throttling
- Show markets under 30 days old
- Show markets with zero volume
- Copy/paste working on OSX
- Improved order placement
- Improved trading logic

Features:
- Show spread in market selection
- Show 24h change in market selection
- Dashboard updates every minute
- Budget is now per exchange
- Poloniex integration



## v0.0.7 (2015-03-29)

Bugfixes:
- Whitespace trimmed from API Key and API Secret
- Prevent budgets greater than available BTC
- Improved order placement
- Improved trading logic

Features:
- Markets sortable by volume / creation date
- Set risk tolerance for each market
- Set trading mode for each market
- Search market selection
- Filter markets by age



## v0.0.6 (2015-03-21)

Bugfixes:
- Fixed a bug that was causing buy and sell orders to not properly adjust



## v0.0.5 (2015-03-20)

Bugfixes:
- Fixed order adjustment
- Fixed start up lag
- Fixed navigation lag
- Changed precision to 8 decimal places
 


## v0.0.4 (2015-03-20)

Bugfixes:
- Fixed order adjustment
- Improved order spacing
- Improved trading logic
- Improved handling of low satoshi markets
- Don't sell RBY if it would put balance below 25,000

Features:
- Order adjustment timing based on risk tolerance
