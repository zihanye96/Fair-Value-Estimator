# Fair Value Estimator for Stock Investing

This notebook automates my valuation process when picking stocks. All information about the stock is pulled from [Morningstar](https://www.morningstar.com/). I use a PE-based valuation method that works best for non-speculative stocks (pricing speculative stocks is subjective by nature). More details about how to use the notebook are contained in the notebook. Special thanks to [Esther Baek](https://github.com/ebaek) for showing me how to use Selenium, which was crucial for the web scraping part of this project.

# Python and Required Packages

To be able to run this notebook, you will need to have Python and Anaconda installed on your computer. Please refer to [this guide](https://jupyter.readthedocs.io/en/latest/install.html) for instructions.

After installing Python, we need to install the packages that this notebook uses. To do this on Mac OS, please open your terminal (in the applications folder) and paste this line:

`pip install ipython numpy pandas matplotlib seaborn selenium`
 
# Things to Keep in Mind 

Buying a stock when it's cheap is only one part of the equation. Here are other considerations when buying a stock:

1. The company needs to have a "moat", something like a competitive advantage that allows the company to be profitable and grow. A good indicator of a strong moat is if return on invested capital (ROIC) is consistently high (15\%+).
2. Ideally, the company has a good balance sheet, with enough cash or short term investments to cover short-term debt and (hopefully) long-term debt. That way, the company can survive short-term or unexpected setbacks (ex. a recession induced by global pandemic). If a company you invest in goes bankrupt, you will likely lose your entire investment.
3. Make sure you understand the business so you know when to sell. If the company's "story" changes (ex. the industry has been disrupted by an innovative new player) and your initial investment thesis no longer holds, you don't want to be holding on to a losing stock. 

