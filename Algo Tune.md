Module 14 Algo Trading
  ## Tuning Algo observations.

I tuned the training algorithm by adjusting both the size and the rolling windows. By changing the date slice, the algo performed better at different segments.  By altering the rolling windows, it increased the sensitivity of the lead and lag varibles. Sometimes making it too sensitive.

The following is the baseline:

![Alt text for the image](https://github.com/t-sullivan/Module-14/blob/main/baseline.png?raw=true)





And the adjusted rolling time frame:

![Alt text for the image](https://github.com/t-sullivan/Module-14/blob/main/modified%20baseline.png?raw=true)





Additionally, when running the Logistic Regression it out performed the SVC model during certain time periods.  It out performed during the market rally, but then under performed signifacntly on the vertical increase. You can see the performance below in the following figure.

![Alt text for the image](https://github.com/t-sullivan/Module-14/blob/main/logistic_regression.png)
