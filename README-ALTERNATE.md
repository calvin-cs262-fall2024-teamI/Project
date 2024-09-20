# Day Trading Tracker
## Problem Statement
The stock market is an invaluable medium in generating wealth and creating financial freedom. However, human emotion is an intrinisic hurdle when dealing with stocks, be it in the short or long term. Additionally, involvement entails a strong understanding of trading/investment strategies on top of market mechanics. As such, an excellent tool is that which allows you to track your trades and facillitate a negative feedback loop - where discrepencies between your perfromance and that of your goals can be evaluated, leading to revision in strategy or behaviour. 
## Vision Statement
The main purpose of our program is to create a portable, mobile application that allows users who are involved in the stock market to log their trades and receive pertinent metrics on their performance. Self-reflection is key to growth, and being aware of your performance is cruicial to understanding whether your are doing the right things or bring attention to mistakes that need correction. Explicitly tracking each trade is the best feedback loop and enhances accountability, resolving any bias or personal emotions that can affect ones view on their performance. Presented in a mobile format, the key benefit in this application is that it is another tool that can be added to a repetoire with incredible accessibility. Some brokerages provide similar services, but their applications fail to provide key insightful metrics, suggest feedback, present information in a streamlined format, or have multiple research components within a single environment. Our application addresses all these issues, and in the spirit of accessibility, providing a medium to research stocks via an integrated screener and create personal watchlists (assuming we find an adequate API).
## Components
- Trade logger - Information stored in database
  - Stock name (ticker), buy/sell prices, shares traded, long/short trade
  - User can also input initial capital
  - Users can input own strategies they used then select them when logging a trade (e.g. trendline support, ascending triangle pattern, etc.) 
- Performance metrics
  - Overall profit/loss (with equity curve)
  - Winning trade percentage
  - Average winning trade
  - Average losing trade
  - Biggest winning trade
  - Biggest losing trade
  - Average trade share size
  - Trade frequency per day
  - Biggest consecutive winning/losing streak
- Feedback - Need to determine if realistic
  - Will output hardcoded suggestions based on logic from performance, examples below
    - Winning percentage over 50% but still negative profit/loss can suggest that losing trades need to be cut early
    - Long losing streak can suggest scaling down shares size
    - Losing 50% of initial capital can suggest taking a break and paper trading (fake money)
- Screener
  - Provide ability to search for stock and present relevant information
  - Create watchlists from here
  - Add desired stocks to watchlist
- Watchlist viewer
  - View user created watchlists in tabular format