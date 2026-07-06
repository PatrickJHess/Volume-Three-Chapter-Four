# Financial Python
## 📚 Volume: The Term Structure Of Interest Rates

### ✨ Chapter Four: Nelson and Siegel Estimates of the Term Structure of Interest Rates

Estimating zero prices with Ordinary Least Squares (OLS) allowed us to calculate spot and forward rates for discrete future dates. 🗓️📉 While these estimates provided valuable insight into current market conditions and future expectations, they lacked the granularity needed for pricing financial instruments that mature on intermediate dates, necessitating interpolation to bridge the gaps. 🌉

Furthermore, standard OLS estimation solves the normal equations without imposing any theoretical financial restrictions on the results. 🧮⚠️ This flexibility is a desirable attribute if the goal is purely relative valuation—identifying bonds that are empirically cheap or expensive 💰🔍—but it becomes a distinct drawback when building a generalized pricing model. Non-coincident bond prices lead to relative price discrepancies compared to their theoretical present values.

A model that brings economic structure to the estimation process can eliminate these implausible values. 🏛️ The Nelson-Siegel model achieves this by offering a parsimonious mathematical solution grounded in three core characteristics of the term structure: 🌊📐

* **The Level 📏**

* **The Slope 📐**

* **The Shape 〰️**

* **The Scale Factor ⚖️**

This chapter introduces and estimates the Nelson-Siegel model. 🚀 Future volumes will utilize this framework (along with the Svensson extension, where appropriate) to accurately price financial instruments. 🔮💼
