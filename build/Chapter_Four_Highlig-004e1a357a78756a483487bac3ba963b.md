# ✨ Chapter Highlights

## 📈 Financial Concepts
    
* Defining the Nelson-Siegel model 📐  
* Accessing data for specific dates from the TreasuryDirect FEDInvest page 🏛️  
* Estimating the model's parameters (Level, Slope, Shape, and Scale) 🧮  
* Using the model to estimate spot 📍 & forward rates ⏭️  
    

    
## 🐍 Python Concepts 
    
  * **SciPy**: Using the optimize module to estimate the Nelson-Siegel model ⚙️  
  * **NumPy arrays & Pandas DataFrames 🐼**  
  * **Web Scraping**: Accessing live bond price data via POST requests 🌐    
  * **🧩 financial_quant package** 📦

### 📚 Background & Prerequisites
This chapter's examples and discussions rely heavily on the Pandas, NumPy, and datetime libraries. The following introductory materials are recommended for context:

* [**🐼 Pandas**: A Quick Introduction to Pandas](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/An_Introduction_To_Pandas.html#a-quick-introduction-to-pandas)

* [**🔢 NumPy**: A Quick Introduction to NumPy](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/An_Introduction_To_NumPy.html#a-quick-introduction-to-numpy)

* [**SCiPy Optimize Modules**: Tutorial](https://docs.scipy.org/doc/scipy/tutorial/optimize.htmll) 

## 🗺️ Chapter Outline
This chapter is divided into the following five distinct sections:

* **❓ Why Nelson and Siegel**: Develops the model framework, describes the core parameters, and explains their relationship to spot rates of interest.

* **🌐 Accessing Treasury Bill Prices From Treasury Direct Website (Jupyter Notebook)**: Develops the FEDInvest function that sends a POST request to the FEDInvest page to return data for a specified date, and cleans the resulting dataset.

* **💻 Estimating The Nelson and Siegel Model (Jupyter Notebook)**: Estimates the Nelson-Siegel model using the data from TreasuryDirect. It then uses these estimates to calculate forward rates and par yields for arbitrary future dates.

* **📝 Chapter Summary**: A concise recap of the primary financial takeaways and computational results.

* **📦 Imported Functions**: describes the functions imported from financial_quant package.
