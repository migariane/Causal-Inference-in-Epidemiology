# Causal Inference in Epidemiology: a little overview

During the last 30 years, the **Modern Epidemiology** has been able to identify some important limitations of classic epidemiologic methods when the focus is to explain the main effect of a risk factor on a disease or outcome. 

1. non collapsibility of the odds and hazard ratios, 
2. impact of paradoxical effects due to conditioning on colliders, 
3. selection bias related with the vague understanding of the effect of time on exposure and outcome and,  
4. effect of time dependent confounding and mediators, 
5. etc.

To control for confounding, the classical epidemilogic methods require making the assumption that the effect measure is constant across levels of confounders included in the model. Alternatively, James Robins in 1986 showed that using **standardization** implemented through the use of the **G-formula** allowed to obtain unconfounded marginal estimation of the causal average treatment effect (ATE) under causal assumptions.    

The most commonly used estimator for a binary treatment effect is the risk difference or ATE. The ATE estimation relies on parametric modelling assumptions. Therefore, the **correct model specification** is crucial to obtain unbiased estimates of the true ATE.  

However, Mark van der Laan and collaborators have developed a double-robust estimation procedure to reduce bias against misspecification. The **targeted maximum likelihood estimation (TMLE)** is a semiparametric, efficient substitution estimator. **TMLE** allows for data-adaptive estimation while obtaining valid statistical inferencebased on the **targeted minimum loss-based estimation** and **machine learning algorithms** to minimize the risk of model misspecification.  

Evidence shows that **TMLE** provides the less unbiased estimate of the ATE compared with other double robust estimators.  

The R notebook (**TMLE.nb.html**) will gide you step by step through the implentation of the Targeted Maximum Likelihood Estimation (TMLE). 
Please, download and open it in you favorite browser or alternatively visit the following link:  
http://migariane.github.io/TMLE.nb.html   
Hope you will enjoy it.    
Best regards,    
Miguel Angel Luque Fernandez  
**:-)**

