# Causal Inference in Epidemiology: a little overview

During the last 30 years, the **modern epidemiology** has been able to identify some important drawbacks of the classic epidemiologic methods. **Causal Inference and the Neyma-Rubin Potential Outcomes framework** have provided the theory and statistical methods needed to identify recurrent problems in observational epidemologic research, such as:  

1. non collapsibility of the odds and hazard ratios, 
2. impact of paradoxical effects due to conditioning on colliders, 
3. left truncation, 
4. prevalent cases,  
5. selection bias related with the vague understanding of the effect of time on exposure and outcome and,  
6. effect of time dependent confounding and mediators. 
7. Etc.

To control for confounding, the classical epidemilogic methods require making the assumption that the effect measure is constant across levels of confounders included in the model. Alternatively, James Robins in 1986 showed that using **standardization** implemented through the use of the **G-formula** allowed to obtain unconfounded marginal estimation of the causal average treatment effect (ATE) under causal assumptions.    

The most commonly used estimator for a binary treatment effect is the risk difference or ATE. The ATE estimation relies on parametric modelling assumptions. Therefore, the **correct model specification** is crucial to obtain unbiased estimates of the true ATE.  

However, Mark van der Laan and collaborators have developed a double-robust estimation procedure to reduce bias against misspecification. The **targeted maximum likelihood estimation (TMLE)** is a semiparametric, efficient substitution estimator. **TMLE** allows for data-adaptive estimation while obtaining valid statistical inferencebased on the **targeted minimum loss-based estimation** and **machine learning algorithms** to minimize the risk of model misspecification.  

Evidence shows that **TMLE** provides the less unbiased estimate of the ATE compared with other double robust estimators.  

The R notebook (**TMLE.nb.html**) will gide you step by step through the implentation of the Targeted Maximum Likelihood Estimation (TMLE).   
Hope you will enjoy it.    
Best regards,    
Miguel Angel Luque Fernandez  
**:-)**

