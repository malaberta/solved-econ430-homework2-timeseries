Download Link: https://assignmentchef.com/product/solved-econ430-homework2-timeseries
<br>
All problems require detailed worked out solutions to receive full credit, and are all worth the same. For this homework you will fit a forecasting model with both trend and seasonal dummies. You may choose any data of your choice provided your time-series data suggest the presence of both, trend and seasonality.

The assignment that you will submit, consists of a written report which includes answers to questions below (including plots), and R/Python source code.

Your report needs to be typed (no limit on the number of pages) and will consist of 5 parts: I. (5%) Introduction (describe the data, provide some background on the topic, etc.).

<ol>

 <li>(75%) Results (answers and plots). Consists of two parts:

  <ol>

   <li>Modeling and Forecasting Trend (5% each)

    <ul>

     <li>Show a time-series plot of your data.</li>

     <li>Does your plot in (a) suggest that the data are covariance stationary? Explain your answer.</li>

     <li>Plot and discuss the ACF and PACF of your data.</li>

     <li>Fit a linear and nonlinear (e.g., polynomial, exponential, quadratic + periodic, etc.) model to your series. In one window, show both figures of the original times series plot with the respective fit.</li>

     <li>For each model, plot the respective residuals vs. fitted values and discuss your observations.</li>

     <li>For each model, plot a histogram of the residuals and discuss your observations.</li>

     <li>For each model, discuss the associated diagnostic statistics (<em>R</em><sup>2</sup>, <em>t</em>−distribution, <em>F</em>−distribution, etc.)</li>

     <li>Select a trend model using AIC and one using BIC (show the values obtained from each criterion). Do the selected models agree?</li>

     <li>Use your preferred model to forecast <em>h</em>-steps (at least 16) ahead. Your forecast should include the respective uncertainty prediction interval. Depending on your data, <em>h </em>will be in days, months, years, etc.</li>

    </ul></li>

   <li>Modeling and Forecasting Seasonality (6% each)

    <ul>

     <li>Construct and test (by looking at the diagnostic statistics) a model with a full set of seasonal dummies.</li>

    </ul></li>

  </ol></li>

</ol>

– 2 –

<ul>

 <li>Plot the estimated seasonal factors and interpret your plot.</li>

 <li>In order to improve your model, add the trend model from problem 1 to your seasonal model. We will refer to this model as the full model. For the full model, plot the respective residuals vs. fitted values and discuss your observations.</li>

 <li>Interpret the respective summary statistics including the error metrics of your full model.</li>

 <li>Use the full model to forecast <em>h</em>-steps (at least 16) ahead. Your forecast should include the respective prediction interval.</li>

 <li>Plot the STL decomposition plot, and based on it, choose between an additive and multiplicative seasonal adjustment. Perform the correction, and plot the seasonally adjusted series. Based on this adjustment, would your trend model from problem 1 still be appropriate? Explain your answer in detail.</li>

</ul>

<ul>

 <li>(5%) Conclusions and Future Work (state your conclusion regarding your final model and fore-cast, and provide some insight as to how it could be improved).</li>

</ul>

<ol>

 <li>(5%) References (include the source of your data and any other resources).</li>

 <li>(10%) R/Python Source code. Your code needs to include proper comments to help e.g., anon-R/Python expert understand and run your code. If you do not submit your code, you will not receive credit for the assignment.</li>

</ol>