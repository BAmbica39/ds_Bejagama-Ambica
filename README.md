# 🔑 Key Findings

## 1. Trade Size vs Market Sentiment
- Traders place **larger trades during Extreme Greed and Fear phases**, reflecting emotionally driven risk-taking.  
- Average trade size peaks in **Extreme Greed**, followed by **Fear**, while trades are smaller in neutral or moderate Greed phases.  
- This confirms that **sentiment strongly influences risk exposure**.  

## 2. Closed PnL (Profit and Loss)
- **Median Closed PnL is near zero** across all sentiment categories.  
- Extreme gains/losses appear mostly as **outliers** during Fear and Extreme Greed.  
- More consistent profitability is seen in **moderate Greed phases**, not in highly emotional markets.  

## 3. Daily Total PnL
- **Greed periods contribute to steady cumulative gains** over time.  
- **Extreme Fear and Extreme Greed phases show volatile swings**, with both large wins and large losses, but limited sustained profitability.  

## 4. Predictive Modeling Insights
- Logistic regression and other models show:  
  - **Market sentiment has a slight positive effect** on predicting profitable trades.  
  - **Trade size alone has a small negative effect** – meaning big trades don’t guarantee higher profitability.  
  - Predicted probability of profitable trades clusters near **0.5**, reflecting **uncertainty and randomness** in outcomes.  

## 5. Correlation Heatmap Insights
- **Trade Size vs Closed PnL**: weak positive correlation (**0.14**) – larger trades are slightly more likely to move with PnL, but not strongly.  
- **Sentiment vs PnL**: near-zero correlation (**0.0092**) – raw correlation doesn’t show strong predictive power, but modeling still extracts value.  
- **Trade Size vs Sentiment**: slightly negative correlation (**-0.024**) – sentiment alone doesn’t dictate trade size in a linear way, but extremes drive riskier behavior.  
- Overall: correlations are weak, confirming that **PnL is influenced by non-linear and contextual market dynamics**, not simple linear relationships.  

---

# 📊 Insights and Patterns
- **Sentiment-driven behavior**: Traders increase trade size in extreme sentiment conditions.  
- **Volatility risk**: Extreme Fear/Greed create sporadic large outliers but not stable gains.  
- **Moderate Greed = safer phase**: More reliable environment for steady profitability.  
- **Trade size ≠ profitability**: Large trades increase exposure but not predictive of success.  
- **Sentiment > Size in predictive value**: Models show sentiment adds more value than trade size in anticipating profitable trades.  
- **Heatmap confirms weak direct correlations**, suggesting the need for **advanced models** to capture non-linear sentiment-performance dynamics.  

---

# ✅ Conclusion
Traders are **highly influenced by sentiment**, taking bigger risks during **Extreme Fear/Greed**, which results in **volatile outcomes with outliers**.  
Consistent profits are more likely in **moderate Greed phases**, where emotional extremes are absent.  
**Sentiment plays a stronger predictive role than trade size**, but correlations are weak, highlighting the complexity of market behavior.  

### 📌 For strategy design:
- **Favor moderate Greed periods for steady gains**.  
- **Apply strong risk management** in extreme sentiment phases.  
- **Combine sentiment with other features** (not just size) to build more effective predictive models.  
