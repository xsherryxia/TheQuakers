Something about the ETAS model:  
* The ETAS model is based on point process modelling of the seismicity and based on 3 assumptions:  
--the background seismicity follows he Poisson process;  
--the number of aftershocks are exponentially proportional to the magnitude M;  
--decrease of aftershocks follows modified Omori law (the power law).  

* Prof. Stark's slides give the function of conditional intensity at time t given the history up to t.  
--（a complex function could be found on slide 21)  
--Turn on alarms when the conditional intensity is above some threshold.  

* By fitting to the data, the ETAS model determines the parameters by the maximum likelihood method. Thus we can predict the incidence of the earthquake, conforming to regional diversity.  
--you may find this on <http://www.ism.ac.jp/~ogata/12ISM_NL_WEBver/earthquakeForecast_E.html>  
--so that means, ETAS returns the MLE of the parameters of the model (mu, K, c, alpha, p); in addition to these, the R ETAS function also returns D, q, and gamma.  

* There are also programs called ETAS, ETASIM(for simulation with data) and RETAS, etc, other than R. (see attachment in email)
