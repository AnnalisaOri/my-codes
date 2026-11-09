# Annalisa Ori   

## Introduction  
I am Annalisa Ori, 25 years old, and since I was a child, I have always been fascinated by numbers and by how reality can be explained through them.
Driven by this interest, I hold a Bachelor's degree in Mathematics from the University of Parma and a Master's degree in Statistical and Economic Sciences from the University of Milano-Bicocca. My academic path has allowed me to develop a solid understanding of fundamental theories as well as their practical applications: Mathematics gave me rigour, attention to precision and a habit of abstract thinking, while Statistics taught me to work with real data, uncertain and imperfect as it is. 

I've brought this approach into the workplace through two very different experiences. 
At PwC Italy, as a Risk Capital and Reporting intern, I saw first-hand how quantitative analysis becomes a practical tool for measuring and managing risk. 
At Barilla, as a Customer Data Analyst Intern, I worked with customer and market data, turning it into insights to support business decisions. 

I am always looking for opportunities to expand my knowledge and analytical skills. 

On this channel, I share my personal projects developed during my years of study.



## Index  
- [Introduction](#Introduction) 
- [Projects](#Projects)  
- [Education](#Education)  
- [Certifications](#Certifications)
- [Contacts](#Contacts)

---

## Projects 

###  Master’s Thesis, "Macroeconomic Conditioning of Loss Given Default under IFRS9: Evidence from the Italian Banking System" 
**Description:** This project develops IFRS 9 satellite models that link Loss Given Default (LGD) to macroeconomic conditions across four portfolio segments: Corporate, SME, Retail and Financial Institutions. The methodology is inspired by practices commonly adopted by financial institutions for forward-looking expected credit loss modelling: logit and Beta transformations of LGD, a structured selection of macroeconomic drivers and lags, diagnostic testing, and probability-weighted scenarios (baseline, adverse, positive) calibrated on Bank of Italy projections and EBA/ESRB stress-test shocks. The analysis uses only public, aggregated ECB data (31 quarterly observations) and is implemented in SAS.

**Main findings:** the two-quarter lagged change in the 3-month Euribor is the most robust driver across all segments (significant at the 1% level), with adjusted R² between 0.52 and 0.64. Oil prices and the BTP yield add segment-specific information, and a COVID dummy captures heterogeneous effects. The results are in-sample and show that macroeconomic variables explain a relevant, but not exhaustive, share of LGD dynamics

**File pdf (English version only):** [Master’s Thesis](https://github.com/AnnalisaOri/Progetti/blob/main/ORI_TESI.pdf)



### Binomial Option Pricing Model: From Discrete Time to Black-Scholes
This repository presents a comprehensive, computational analysis of the Binomial Option Pricing Model (BOPM)—the essential discrete-time framework for derivatives valuation. Implemented using Python simulations in a Jupyter Notebook, this project bridges fundamental theoretical concepts with practical quantitative finance.

**Key Focus Areas and Computational Demonstrations:** The code starts by modeling a simplified two-period market and gradually generalizes the framework to multiple time steps, offering a transparent view of core financial principles:

**No-Arbitrage Principle**: We demonstrate the fundamental condition under which a market is free from riskless profit opportunities.

**Market Completeness and Replication:** The project illustrates how a derivative's payoff can be perfectly replicated by a dynamic portfolio of the underlying stock and a risk-free bond, which ensures market completeness and unique asset pricing.

**Convergence to Black-Scholes:** By increasing the number of time steps, the Python implementation clearly showcases the celebrated limit of the binomial model—its numerical convergence to the continuous-time Black-Scholes-Merton formula.

**Jupiter Notebook:** [Analysis and Phyton code](https://github.com/AnnalisaOri/Progetti/blob/main/binomial_model_to_black_scholes.ipynb)




### Excel Project - For the Insurance Economics exam

**Description:** The Excel file is organized to follow the different topics of the course:
1. **Non-Life Insurance**
   - **Claims reserving – Chain-Ladder method**: based on a Run-Off triangle of paid claims.
   - **Separation method**: the reserve is recalculated by separating frequency (number of claims) from severity (average claim amount).  
   - **Technical account for P&C**: using financial statement data (premiums, reserves, paid claims, expenses) to calculate earned premiums and claims, final reserves, loss ratio, expense ratio, and combined ratio. 


2. **Life Insurance**  
   - **Unit Linked**: calculation of premium loadings, allocation across funds, and determination of the minimum fund share so that the payable capital in case of a claim exceeds the minimum guarantee.
   - **Revaluable mixed insurance**: calculation of the annual pure premium (highlighting risk and savings components), mathematical reserves, and capital revaluation (with constant or revaluable premium) based on the returns of the separate account. 
   - **Cliquet and Best-Of revaluation**: comparison of the two capital revaluation mechanisms under a guaranteed minimum rate and variable returns.

**File Excel:**  [File Excel](https://github.com/AnnalisaOri/Progetti/blob/main/assicurazionieng.xlsx)



### DSGE CEE Model with and without Investment Adjustment Costs

**Description:** This project was developed as part of a Macroeconomics course group assignment. We implement and analyze a Christiano-Eichenbaum-Evans (CEE) DSGE model in two alternative specifications: CEE model with and without investment adjustment costs. In particolar the models exclude real money balances and assume a monetary authority (ECB) that sets the nominal interest rate according to a Taylor rule. The objective is to implemente the models using MATLAB (Dynare) and to study the implications of investment adjustment costs for the model dynamics and to evaluate the model's ability to replicate the observed behavior of capacity utilization, compared then with the empirical measure obtained from the Federal Reserve Economic Data (FRED) database.

**Code and analysis:**
[Dynare implementation with investment adjustment costs](https://github.com/AnnalisaOri/Progetti/blob/main/gruppo2_modello1.mod)

[Dynare implementation without investment adjustment costs](https://github.com/AnnalisaOri/Progetti/blob/main/gruppo2_modello2.mod)

[pdf with graphs and results](https://github.com/AnnalisaOri/Progetti/blob/main/Progetto_gruppo2.pdf)






### Analysis of a Time Series: ROAD TRAFFIC TRENDS IN MINNESOTA

**Description:** The aim of this project is to analyze road traffic in Minnesota, USA, in relation to various factors such as weather conditions, temperature, and holidays/weekends. Initially, I conducted an exploratory analysis of the time series, checking for normality, stationarity, and the presence of trends and seasonality. Subsequently, I developed several models, including simple linear regression, ARIMA, SARIMA, and regARIMA. Finally, I selected the best model and used it to forecast traffic trends.

**Dataset:** [Data](https://github.com/AnnalisaOri/Progetti/blob/main/Metro_Interstate_Traffic_Volume.csv)

**R Code and analysis:** [Quart document](https://github.com/AnnalisaOri/Progetti/blob/main/Minnesotaeng.pdf)

**Functions:** [Arch Test](https://github.com/AnnalisaOri/Progetti/blob/main/FN%20-%20ARCHTest.txt)
[PortmanteauQ test](https://github.com/AnnalisaOri/Progetti/blob/main/FN%20-%20AutoPortmanteauQ.txt)
[Sarima](https://github.com/AnnalisaOri/Progetti/blob/main/FN%20-%20PerfMetr_SARIMA.txt)
[Sequence of dates](https://github.com/AnnalisaOri/Progetti/blob/main/FN%20-%20Sequence%20of%20dates.txt)
[Custom aggregate](https://github.com/AnnalisaOri/Progetti/blob/main/FN%20-%20TS_custom_aggregate.txt)






###  Bachelor’s Thesis: Dynamics of Predation and Competition Models

**Description:** Modeled the dynamics of three populations using systems of ordinary differential equations, analyzed their evolution with mathematical tools for qualitative study of differential models, and visualized the results through numerical simulations in MATLAB.

**File pdf (Italian version only):** [Bachelor’s Thesis](https://github.com/AnnalisaOri/Progetti/blob/main/Tesi%20triennale)

**Codice latex:** [latex](https://github.com/AnnalisaOri/Progetti/blob/main/latex.tex)

**Some MATLAB code for creating graphs.:** 

[Picture 2.28](https://github.com/AnnalisaOri/Progetti/blob/main/Figura2-28.m)

[Numerical simulation 1 with 3D phase plane for equilibrium E2](https://github.com/AnnalisaOri/Progetti/blob/main/sim1_E2stabile.asv)

[2D phase plane for the y–z subsystem](https://github.com/AnnalisaOri/Progetti/blob/main/piano_yz_specialista.m)


### SIRS MODEL

**Description:**  The spread of certain pandemics, such as COVID-19, can be modeled—under simplifying assumptions—using a variant of the classical SIR model. Unlike the SIR model, the SIRS model accounts for the possibility that individuals may lose immunity over time and become susceptible to infection again. Using the theory of dynamical system stability, I studied the temporal evolution of the system.

**File pdf (Italian version only):** [Sirs](https://github.com/AnnalisaOri/Progetti/blob/main/SIRS.pdf)

**Some MATLAB code for creating graphs:** 

[Numerical simulation](https://github.com/AnnalisaOri/Progetti/blob/main/Simulazione_2%5C3D.m)

[Phase portrait 1](https://github.com/AnnalisaOri/Progetti/blob/main/ritrattodifase1.m)



---

## Education
- High School Diploma at Liceo Scientifico Giacomo Ulivi, Parma; 2015–2020; graduated with 100/100 cum laude
- Bachelor’s Degree in Mathematics (L35) at University of Parma; 09/2020–03/2024; grade: 105/110
- Master’s Degree in Statistical and Economic Sciences (curriculum: Insurance and Financial Markets, LM82) at University of Milano-Bicocca; 09/2024-10/2026; grade: 110/110 cum laude

---
## Certifications
- IELTS, GENERAL TRAINING
  
  Overall Band Score: 7
  
  CEFR level :C1
  
  Date : 22/09/2025
  
  Test report form number : 25IT510906ORIA010G

  

## Contacts
- LinkedIn: [@AnnalisaOri](https://www.linkedin.com/in/annalisa-ori-92b436292)
- Email: annalisaori1@gmail.com


