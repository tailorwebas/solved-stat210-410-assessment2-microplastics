Download Link: https://assignmentchef.com/product/solved-stat210-410-assessment2-microplastics
<br>
Microplastics are found in almost all marine and fresh water environments, where they pose a potential risk to fish and crustaceans. Therefore, the effects of microplastics on aquatic organisms are currently the subject of intense research. Here we have a dataset containing 200 seawater samples collected at different sites around a bay in Sweden. The dataset is saved as Mplastics.csv. There are 5 variables included in the study:

<ul>

 <li>PE = polyethylene microplastics (<em>µg/m</em><sup>3</sup>)</li>

 <li>PP = polypropylene microplastics (<em>µg/m</em><sup>3</sup>)</li>

 <li>PS = polystyrene microplastics (<em>µg/m</em><sup>3</sup>)</li>

 <li>temp = water temperature at each site (Celsius)</li>

 <li>larvae = number of fish larvae of a single species per 100 <em>m</em><sup>3</sup></li>

 <li>Use the R function pairs to plot the data. Summarise the information available from the plot. [15 marks]</li>

</ul>

NB: save Rfunctions.R (available from Topic 2 block) to your working directory.

<ul>

 <li>Fit a model of the form</li>

</ul>

Print the table of regression coefficients and write down the least squares regression equation.

<ul>

 <li>Which variables are significant predictors of fish larvae density in this model, at a 5%level? Write down and test appropriate hypotheses.</li>

</ul>

<em>Now drop the non-significant terms and refit the model using only the explanatory variables that are significant. This is referred to as the final model.</em>




<ul>

 <li>Print the table of regression coefficients and write down the least squares regressionequation for the final model.</li>

</ul>




<ul>

 <li>Find and interpret the 95% confidence intervals for the regression coefficients in the finalmodel. [10 marks]</li>

 <li>Produce the diagnostic plots for the final model and explain what can be understoodfrom the plots. [10 marks]</li>

 <li>Using the final model, estimate <em>mean fish larvae density </em>and the 95% CI for the estimate when [15 marks]

  <ul>

   <li>temperature = 17.5, PE = 300, PP = 50, PS= 80.5 and</li>

   <li>temperature = 20.5, PE = 300, PP = 50, PS= 80.5</li>

  </ul></li>

</ul>

NB: You may not need to include values for all 4 predictor variables, depending on your final model.

Comment on the reliability of these predictions.

<ul>

 <li>Write a concise, informative conclusion based on your analysis and results.</li>

</ul>