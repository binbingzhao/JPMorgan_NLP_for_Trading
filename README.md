# JPMorgan_NLP_for_Trading
JPMorgan_News_Sentiment_in_China

### Reference: ChinaScope

## News Sentiment in China
### Using ChinaScope NLP for Trade Timing A-Shares
- Chinese-language sentiment has been another interesting challenge for Natural Language Processing (NLP) researchers and, as we shall see, the rewards are well worth the effort. In this report, we test the ChinaScope News Sentiment factor in standalone backtests as well as looking at optimal techniques for integration of what is essentially a high frequency signal into a more moderate turnover factor model.
- ChinaScope has available daily sentiment scores for the broader A-share market since 2017. Their NLP engine takes care of all the workflow, including tasks such as news sourcing, duplication removal, event tagging, entity detection and sentiment scoring.
- We focus on using the ChinaScope sentiment signal inside a more traditional portfolio setting, i.e., large caps (CSI300) with a monthly rebalance. The results from our standalone tests are strong (a Sharpe > 2 after t-costs) and in line with our English news tests in previous work, as well as compelling results we have seen in academia.
- Turnover of this factor is high (as it is for all sentiment-based strategies), but we think this kind of signal can still enhance most risk premia based portfolio when used to time existing trades.
- Instead of blending sentiment with slower factors in the cross-section (using a Z- score), we suggest using the higher frequency signal to Trade Time slower factors (we describe and demonstrate both approaches and backtests inside).
