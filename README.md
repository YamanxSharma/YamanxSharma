# I'm Yaman Sharma 

**Statistics | Mathematics | Finance | AI & ML**

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=5B3DFF&width=435&lines=Statistical+Inference;Machine+Learning+Systems;Mathematical+Modeling:;Financial+Optimization)](https://git.io/typing-svg)

I specialize in applying advanced statistical modeling, mathematical finance, and computational methods to solve complex problems in trading, risk management, and investment strategies. My expertise lies at the intersection of **quantitative analysis, algorithmic trading, and machine learning**, where I develop robust models to extract signal from noise in financial markets.

## Core Focus Areas
- **Algorithmic Trading:** Design and backtest systematic strategies across asset classes
- **Portfolio Optimization:** Risk-adjusted allocation using stochastic and factor-based approaches
- **Derivatives Pricing:** Monte Carlo, PDE, and stochastic volatility models
- **Machine Learning in Finance:** Predictive modeling, alternative data integration, and NLP for market sentiment
  
*"Statistics is the grammar of science."* — Karl Pearson  

## 🔬 Core Toolkit  

**Statistical Computing**  
![statsmodels](https://img.shields.io/badge/-statsmodels-8A2BE2?style=flat-square&logo=statsmodels&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat-square&logo=matplotlib&logoColor=white)
![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)  

**Machine Learning**  
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikit-learn)  

**Mathematical Foundations**  
![Stochastic Processes](https://img.shields.io/badge/-Stochastic_Processes-2F4F4F?style=flat-square)
![Optimization](https://img.shields.io/badge/-Numerical_Optimization-8B008B?style=flat-square)  

## 📈 Analytical Workflow  

```python
from math import log, sqrt, exp
from scipy.stats import norm

def bs_price(S, K, T, r, σ, call=True):
    """Black-Scholes option pricing (compact)"""
    d1 = (log(S/K) + (r + σ**2/2)*T) / (σ*sqrt(T))
    d2 = d1 - σ*sqrt(T)
    return S*norm.cdf(d1) - K*exp(-r*T)*norm.cdf(d2) if call else \
           K*exp(-r*T)*norm.cdf(-d2) - S*norm.cdf(-d1)

# Example
print(f"Call Price: ${bs_price(100, 105, 1, 0.05, 0.2):.2f}")
```
## Let's Connect
<p align="left">
  <a href="https://www.linkedin.com/in/yaman-sharma-164b68244/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:sharma.yamandinesh@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="[Your GitHub URL]">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</p>
<!---
YamanxSharma/YamanxSharma is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
