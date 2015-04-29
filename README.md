# TraderDaddy
Automatically trade Bitcoin and other cryptocurrency for profit.


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
