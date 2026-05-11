# Chapter Highlights

**Key Topics Covered**

* **Estimating the term structure with Nelson-Siegel model**  
    
  * Defining the model.  
  * Accessing data for specific dates from FEDInvest page of TreasuryDirect site.  
  * Estimating the model.  
  * Using the model to estimate forward rates.  
    

    
* **Python concepts:**  
    
  * SciPy optimize module estimtes Nelson and Siegel model  
  * NumPy arrays  
  * Pandas  
  * Accessing bond price data from FEDInvest page of TreasuryDirect    
  * Custom modules.  
    * accruded\_interest  
    * create_payoff_matrix   
    * one\_y\_axis  
    * FEDInvest
    * cleanFEDInvest

## ***Background***

This chapter's examples and discussions rely on the **Pandas** and **NumPy** libraries.

* **Pandas** is introduced in [*A Quick Introduction to Pandas*](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/An_Introduction_To_Pandas.html#a-quick-introduction-to-pandas).  
* **NumPy** is introduced in [*A Quick Introduction to NumPy*](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-

**The chapter includes Five  sections:**

1. *Why Nelson and Siegel*  
     
   * develops the model  
   * describes the parameters
   * relation of parameters to spot rates of interest

   

2. The Jupyter notebook *Accessing Treasury Bill Prices From Treasury Direct Website*  
   * devlops the function FEDInvest that sends a post reqyest to FEDInvest page and returns data for a specified data  
   * cleans up the data returned data of FEDInvest

   

3. The Jupyter notebook *Estimating The Nelson and Siegel Model*  
    * estimates the Nelson and Siegel model with data from the FEDInvest page of TreasuryDirect  
    * usees model estimates to calculate forward rates for arbitrary dates   
    * uses model estimates to calculate par yields for arbitrary dates  
    
 
4. *Chapter Summary*  
5. *Imported Functions*

