# finlib

## Library is no longer maintained

With this library you can: gather fundamental data, historical price data, earnings data, as well as compute financial ratios. This library is built upon yahoofinancials by user JECSand, and adds significant functionality as well as hopefully simplicity.

# DISCLAIMER
Use at your own risk. The author will not, in any way whatsoever, be responsible for your use of the information produced or contained with this library. This library is not intended to be a source of advice with respect to investment. Accordingly, any decision made in connection with funds, instruments, or transactions and the use of the library will not be the responsibility of the author. Additionally, the author cannot guarantee the validity of any figures, quantitative, or qualitative measures produced by this library.

# Dependencies
yahoofinancials + yf dependencies (pytz and bs4)

https://github.com/JECSand/yahoofinancials

pandas

https://pandas.pydata.org/

requests

https://pypi.org/project/requests/2.7.0/


# Module Methods

*Getting data*

- get_balance_sheet()
- get_income_statement()
- get_cash_flow_statement()
- get_key_statistics()
- get_historical_eps()
- get_price_data()

*Getting current figures*

- share_price()
- market_value()
- earnings_per_share()
- pe_ratio()
- enterprise_value()
- beta()
- cost_of_equity()
- short_ratio()

*Getting figures that accept year arguments*

- revenue(year)
- total_expenses(year)
- operating_expenses(year)
- liquid_assets(year)
- total_debt(year)
- tax(year)
- interest(year)
- depreciation(year)
- cost_of_revenue(year)
- total_receivables(year)
- total_assets(year)
- total_capital(year)
- total_equity(year)
- capital_expenditues(year)
- net_income(year)
- gross_profit(year)
- ebit(year)
- ebitda(year)
- quick_ratio(year)
- income_continuing_operations_margin(year)
- net_margin(year)
- return_on_assets(year)
- return_on_capital(year)
- return_on_equity(year)
- cash_flow_operations(year)
- free_cash_flow(year)
- gross_profit_margin(year)
- operating_profit_margin(year)
- net_profit_margin(year)

