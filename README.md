# Strategy6_GOLDM_Trending
Logic of the strategy:
This is a directional strategy of GOLDM works with small sl and targets.

Type:Intraday
Supertrend:12,3
Timeframe:15m
Capital Requirement:300k inr
Segment:Futures

Rules brief:
When supertrend is above/below the close buy/sell 1 lot of GOLDM. After the tgt is hit, exit. If sl is hit, take opposite side two position with doubling the initial sl and tgt, running it on a while loop till it takes 5 entries.

Set1
Conditions:
1.Supertrend below close of previous and previous to previous candle
2. Time >= 1700

Position:
Buy,1lot,GOLDM,Fut

Sl-30 points
Tgt-150 points

Incase the tgt is hit exit the strategy.
If sl is hit sell two lots of GOLDM Fut, new sl will be 60 points, new tgt will be 300pts.
Run this simulation untill 5 positions.(meaning sl getting hit for the 4th time.)

Create same position for the opposite side(i.e supertrend above close, Sell 1 lot of GOLDM Future.)


Disclaimer :  I am not a SEBI registered investment or financial advisor. Don't deploy our strategies purely based on past performance only. We are not responsible for your profit or loss. Although this strategy is fully automated, you are advised to keep a track on your account to monitor any deviations or errors. As option selling involves market risks, Please consult your financial advisor before investing.


Disclaimer: This is a algorithmic strategy which is also my personal project which is coded on tradetron, for codes ping me up.
