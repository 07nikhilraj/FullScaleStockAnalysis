# FullScaleStockAnalysis
Using Data Mining methods and ML models to predict future behavior of stocks.

Github takes too long to render the notebooks with large size. To view .ipynb file
👉🏼👉🏼👉🏼
**[Click here](https://nbviewer.org/github/07nikhilraj/FullScaleStockAnalysis/blob/master/project.ipynb)** 👈🏼👈🏼👈🏼

We are using a financial dataset from yahoo finance. The Dataset consists of attributes like: Date, Open, High, Low, Close, Volume, OpenInt.

We have analyzed the behavior of stocks and predict its future, considering how it performed in the last couple of years and what factors affected it. 

### Techniques Used: 
* Moving Average
  * Linear Moving Average
  * Exponential Moving Average
* ### Correlation Matrix: 
  ![1](https://user-images.githubusercontent.com/86933754/176680149-b1f567a1-2933-49a9-88b2-7e5a21908f01.png)


* ### Monte Carlo Algorithm
  ![3](https://user-images.githubusercontent.com/86933754/176680421-e799fbd0-d731-4e9b-b0ae-f7f9a8697816.png)
  This helps us in Risk Analysis. Monte Carlo simulation produces distributions of various possible outcome values. 

* ### LSTM ML model
  ![4](https://user-images.githubusercontent.com/86933754/176680491-fc212081-048b-41fc-9ccd-e7443ed25502.png)
  LSTMs help us to predict the direction of stock trends correctly!


## Outcome
We used different stock analysis techniques. Each technique gave a different result. We used the Moving Average Technique to predict stocks’ future closing/opening price and observed that exponential M.A was more responsive than Linear M.A. Also, when one wants to invest for long term investment, they should go for a smoother curve since it is more resistant to sharp price jumps. Choosing a stock depends on the individual. A graph of M.A. with more zigzags is riskier. We then used the coefficient matrix to find the relations between different stocks. We concludedthat Google and Microsoft have the most correlated daily profit, whereas Tesla & Walmart have the least. Then, we formed portfolios and calculated the Sharpe ratio offered by each company. Walmart had the highest Sharpe ratio compared to others and thus is the most preferred stock. Monte Carlo Algorithm gave us all the possible paths our stock could have traveled from the opening day. We used a histogram to find the most probable path of that stock and distinguished stocks as risky or stable. Apple. Microsoft, TSMC, Johnson & Johnson, and Walmart & Nestle were some of the stable stocks. We then used the LSTM Machine Learning model to predict the closing stock price of Google, and we could see that LSTMs are good when it comes to predicting stock price behavior and not exact values. 
