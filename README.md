# Awesome Forex [![Awesome](https://awesome.re/badge.svg)](https://github.com/ForexiaPro/awesome-forex#readme)

Free data, open-source libraries, charting, backtesting, broker APIs, calendars and learning material for the foreign exchange market, for traders who build their own tools.

Only free, working, maintained resources. Paid services appear only where their free tier or documentation is useful on its own. Nothing here is a recommendation to trade.

## Contents

- [Central Bank Data](#central-bank-data)
- [Market and Economic Data](#market-and-economic-data)
- [Positioning Data](#positioning-data)
- [Calendars](#calendars)
- [Python Libraries](#python-libraries)
- [JavaScript Libraries](#javascript-libraries)
- [R Libraries](#r-libraries)
- [Charting](#charting)
- [Backtesting](#backtesting)
- [Broker APIs](#broker-apis)
- [Learning](#learning)

## Central Bank Data

- [ECB Data Portal](https://data.ecb.europa.eu/) - The European Central Bank's statistics, including its euro reference exchange rates and policy rates, with an API (it replaced the Statistical Data Warehouse).
- [Bank of England Database](https://www.bankofengland.co.uk/boeapps/database/) - Bank Rate, sterling exchange rates and money market series, downloadable as CSV.
- [Federal Reserve H.10](https://www.federalreserve.gov/releases/h10/) - The Fed's weekly release of noon buying rates in New York for major currencies, with history.
- [Bank of Canada Valet API](https://www.bankofcanada.ca/valet/docs) - A keyless JSON and CSV API for the Bank of Canada's exchange rates and interest rates.
- [SNB Data Portal](https://data.snb.ch/) - The Swiss National Bank's interest rates, exchange rates and balance sheet data.
- [BOJ Time-Series Data Search](https://www.stat-search.boj.or.jp/) - The Bank of Japan's statistics, including policy rates and the yen's effective exchange rate.
- [RBA Statistics](https://www.rba.gov.au/statistics/) - The Reserve Bank of Australia's cash rate history and exchange rate tables.
- [InterestRateDecision.com Open Data](https://interestratedecision.com/central-bank-data/?via=awesome) - Every policy rate decision of ten central banks since 2008 and the next meetings, as CSV and JSON, free with a link (by the maintainers of this list).
- [Central Bank Interest Rates](https://github.com/Interest-Rate-Decision/central-bank-interest-rates#readme) - The same decisions as a versioned dataset on GitHub, updated automatically (by the maintainers of this list).

## Market and Economic Data

- [FRED](https://fred.stlouisfed.org/) - The St. Louis Fed's database of US and international economic series, exchange rates included, with a free API key.
- [BIS Data Portal](https://data.bis.org/) - The Bank for International Settlements' exchange rates, policy rates and credit statistics for most countries.
- [BIS Triennial Survey](https://www.bis.org/statistics/rpfx22.htm) - The reference survey of FX market turnover by currency, instrument and country.
- [IMF Data](https://data.imf.org/) - International Monetary Fund datasets, including exchange rates and reserves by country.
- [DBnomics](https://db.nomics.world/) - One API over economic series from dozens of providers, central banks among them.
- [Frankfurter](https://frankfurter.dev/) - A free, open-source API for the ECB's daily reference rates, which can be self-hosted.
- [Dukascopy Historical Data](https://www.dukascopy.com/swiss/english/marketwatch/historical/) - Free tick and candle history for FX pairs from a Swiss bank's feed; check its terms before redistributing.
- [HistData.com](https://www.histdata.com/) - Free one-minute and tick FX history in CSV and MetaTrader formats.
- [Alpha Vantage](https://www.alphavantage.co/documentation/) - An API with FX rates and daily candles on a free tier with rate limits.

## Positioning Data

- [CFTC Commitments of Traders](https://www.cftc.gov/MarketReports/CommitmentsofTraders/index.htm) - The weekly report of futures positions by trader type, currency futures included; public domain.
- [CFTC Public Reporting Environment](https://publicreporting.cftc.gov/) - The same reports as a queryable API with history.

## Calendars

- [FOMC Meeting Calendar](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) - The Federal Reserve's own schedule of meetings, statements and minutes.
- [ECB Monetary Policy Meetings](https://www.ecb.europa.eu/press/calendars/mgcgc/html/index.en.html) - The ECB Governing Council's meeting calendar.
- [Forex Factory Calendar](https://www.forexfactory.com/calendar) - A widely used economic calendar with impact ratings, forecasts and results.
- [Investing.com Economic Calendar](https://www.investing.com/economic-calendar/) - A global economic calendar with filters by country and importance.
- [InterestRateDecision.com Calendar](https://interestratedecision.com/calendar/?via=awesome) - Central bank rate decisions only, with times in your own zone and an iCalendar feed (by the maintainers of this list).

## Python Libraries

- [pandas-datareader](https://github.com/pydata/pandas-datareader#readme) - Reads FRED, World Bank, OECD and other sources straight into pandas.
- [fredapi](https://github.com/mortada/fredapi#readme) - A client for FRED and ALFRED, including the vintages of revised series.
- [yfinance](https://github.com/ranaroussi/yfinance#readme) - Downloads Yahoo Finance prices, FX pairs included; an unofficial client, so it can break when Yahoo changes.
- [TA-Lib](https://github.com/TA-Lib/ta-lib-python#readme) - Python bindings for the TA-Lib library of 150-plus technical indicators.
- [ta](https://github.com/bukosabino/ta#readme) - Technical indicators in pure pandas and NumPy, with no C dependency.
- [cot_reports](https://github.com/NDelventhal/cot_reports#readme) - Downloads every type of CFTC Commitments of Traders report into pandas.
- [MetaTrader5](https://pypi.org/project/MetaTrader5/) - MetaQuotes' package for reading prices and placing orders through a running MetaTrader 5 terminal on Windows.
- [ib_async](https://github.com/ib-api-reloaded/ib_async#readme) - A synchronous and asynchronous framework for the Interactive Brokers API, the successor of ib_insync.
- [QuantStats](https://github.com/ranaroussi/quantstats#readme) - Performance and risk reports (drawdowns, Sharpe, monthly returns) for a strategy's returns.
- [pyfolio-reloaded](https://github.com/stefan-jansen/pyfolio-reloaded#readme) - Portfolio and risk analytics with tear sheets, maintained fork of pyfolio.
- [Interest Rate Decisions](https://github.com/Interest-Rate-Decision/interest-rate-decisions#readme) - A keyless client for central bank rates, next meetings and decisions since 2008, in Python and JavaScript (by the maintainers of this list).

## JavaScript Libraries

- [dukascopy-node](https://github.com/Leo4815162342/dukascopy-node#readme) - Downloads Dukascopy's historical tick and candle data from Node.js or a command line.
- [trading-signals](https://github.com/bennycode/trading-signals#readme) - Technical indicators in TypeScript, with arbitrary-precision versions.
- [prop-firm-rules](https://github.com/PropSim-Enterprise/prop-firm-rules#readme) - Evaluates prop firm challenge rules (profit target, daily and overall loss, trading days) against an account's history (by the maintainers of this list).

## R Libraries

- [quantmod](https://github.com/joshuaulrich/quantmod#readme) - Downloads, charts and models financial series in R, FX from several sources included.
- [TTR](https://github.com/joshuaulrich/TTR#readme) - Technical trading rules and indicators for R.
- [fredr](https://github.com/sboysel/fredr#readme) - A tidy R client for the FRED API.
- [tidyquant](https://github.com/business-science/tidyquant#readme) - Brings quantmod, TTR and performance analytics into the tidyverse.

## Charting

- [Lightweight Charts](https://github.com/tradingview/lightweight-charts#readme) - TradingView's open-source HTML5 canvas library for fast financial charts.
- [KLineChart](https://github.com/klinecharts/KLineChart#readme) - A customizable candlestick chart with no dependencies and mobile support.
- [mplfinance](https://github.com/matplotlib/mplfinance#readme) - Candlestick and OHLC charts for Matplotlib.
- [OpenCharts](https://github.com/dylanpersonguy/OpenCharts#readme) - A self-hosted charting app built on Lightweight Charts, with indicators and drawing tools (by the maintainers of this list).

## Backtesting

- [vectorbt](https://github.com/polakowo/vectorbt#readme) - Vectorized backtesting on pandas and NumPy, fast enough to test thousands of parameter sets.
- [Backtesting.py](https://github.com/kernc/backtesting.py#readme) - A small, readable Python backtester with interactive result charts.
- [backtrader](https://github.com/mementum/backtrader#readme) - An event-driven Python backtester with live broker connections; widely used, though updates are now rare.
- [bt](https://github.com/pmorissette/bt#readme) - Flexible backtesting of portfolio strategies built from reusable blocks.
- [Zipline Reloaded](https://github.com/stefan-jansen/zipline-reloaded#readme) - The maintained fork of Quantopian's event-driven backtester.
- [LEAN](https://github.com/QuantConnect/Lean#readme) - QuantConnect's open-source engine for backtesting and live trading in Python and C#, FX included.
- [NautilusTrader](https://github.com/nautechsystems/nautilus_trader#readme) - A high-performance event-driven engine in Rust with a Python API, for backtesting and live trading on the same code.

## Broker APIs

- [OANDA v20 REST API](https://developer.oanda.com/rest-live-v20/introduction/) - Prices, candles and order placement for OANDA accounts, with a free practice account.
- [Interactive Brokers TWS API](https://www.interactivebrokers.com/campus/ibkr-api-page/twsapi-doc/) - Interactive Brokers' API for market data and orders across asset classes, FX included.
- [MetaTrader 5 Python Integration](https://www.mql5.com/en/docs/python_metatrader5) - The documentation of the MetaTrader5 package's functions.
- [cTrader Open API](https://help.ctrader.com/open-api/) - The API of cTrader-based brokers for prices, accounts and trading.
- [Saxo OpenAPI](https://www.developer.saxo/) - Saxo Bank's REST and streaming API, with a free simulation environment.
- [Twelve Data](https://twelvedata.com/docs) - A market data API with FX quotes and history on a limited free tier.

## Learning

- [The Fed Explained](https://www.federalreserve.gov/aboutthefed/the-fed-explained.htm) - The Federal Reserve's own guide to how it sets policy.
- [ECB Explainers](https://www.ecb.europa.eu/ecb-and-you/explainers/html/index.en.html) - Short ECB articles on interest rates, inflation and the euro.
- [COT Explanatory Notes](https://www.cftc.gov/MarketReports/CommitmentsofTraders/ExplanatoryNotes/index.htm) - The CFTC's definitions of every field in the Commitments of Traders report.
- [Babypips School of Pipsology](https://www.babypips.com/learn/forex) - A free, beginner-friendly course on forex from the ground up.
- [Machine Learning for Trading](https://github.com/stefan-jansen/machine-learning-for-trading#readme) - The notebooks of Stefan Jansen's book, from data sourcing to backtesting.
- [How to Trade Interest Rate Decisions](https://interestratedecision.com/how-to-trade-interest-rate-decisions/?via=awesome) - A guide built on measured price reactions to central bank decisions, the ones that went against the first move included (by the maintainers of this list).
- [COT Report Guide](https://forexiapro.com/cot-report/?via=awesome) - How to read the Commitments of Traders report for currencies (by the maintainers of this list).
- [Forex Sessions Guide](https://forexiapro.com/forex-sessions/?via=awesome) - When the Asian, London and New York sessions open and how activity changes between them (by the maintainers of this list).

## Contributing

Suggestions are welcome: read the [contribution guidelines](contributing.md) first.

## Footnotes

Entries marked "by the maintainers of this list" come from the Forexia network and are listed by the same rules as everything else; they are placed after the alternatives in each section.

Part of the Forexia network: [InterestRateDecision.com](https://interestratedecision.com/?via=awesome) · [Forexia Academy](https://forexiapro.com/courses?via=awesome) · [TradingSignalBot](https://tradingsignalbot.com/?via=awesome) · [PropSim](https://propsim.markets/?via=awesome) · [OpenCharts](https://github.com/dylanpersonguy/OpenCharts)
