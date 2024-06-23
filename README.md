# finian (finian.ai)
Finian provides near real-time insights to enhance confident decision-making by integrating your personal trading history with up-to-the-minute market data, company financial reports and the latest news, all accessible at your fingertips. Potentially replaces scanners, backtesters and other traditional tools used by financial traders and investors.

## Architecture
GenAI Assistant Front End (Finian): Acts as the main interface and orchestrator, utilizing outputs from the other components to provide integrated insights.

Examples:
* If I would have stayed 5 minutes longer in my trades, how much more or less would I have made overall? on Average? Which trades would have been more profitable? Etc.
* What were the last 3 EPS scores for xyz stock?
* Using my EV calculation, which companies in the pharmeceutical industry are currently undervalued/overvalued?
* Using the 

Component 1 - Personal Transaction Data Model: Uses generative AI trained with personal transaction data to answer specific queries about individual trading history.

Examples:
* What securities did I trade the most in July 2023?
* How much did I pay in locate fees during these dates?
* Based on my trading patterns, what is the average time I stay in a security?

Component 2 - Market Data Model: Utilizes generative AI trained with market data from public APIs like Yahoo Finance to analyze and provide insights into market trends.

Examples:
* What did xyz close at, what was the high, what the low, etc?
* What is the short interest in xyz company?
* What time of the day does the nasdaq tend to have the biggest moves?

Component 3 - News Aggregator Model: Employs generative AI trained with financial news from sources such as FinViz and Yahoo Finance to aggregate and analyze news relevant to financial markets.

Examples:
* What were the top stories for security xyz last week?
* Which 3 companies in the mining and raw materials sectors have had the most news coverage in the last week?
* Sentiment, etc.

Component 4 - Company Profiler Model: Uses generative AI trained with information from public reporting sources like the Edgar database to profile and analyze companies.
* What were the last 3 EPS scores for company abc?
* Over the past 5 years, which quarters were most profitable for the top performing companies in x sector(s)?

