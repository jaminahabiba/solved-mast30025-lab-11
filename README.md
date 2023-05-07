Download Link: https://assignmentchef.com/product/solved-mast30025-lab-11
<br>



<ol>

 <li>We study the effect of various breeds and diets on the milk yield of cows. A study is conducted on9 cows and the following data obtained:</li>

</ol>

<table width="168">

 <tbody>

  <tr>

   <td width="50"> </td>

   <td width="47"> </td>

   <td width="40">Diet</td>

   <td width="32"> </td>

  </tr>

  <tr>

   <td width="50">Breed</td>

   <td width="47">1</td>

   <td width="40">2</td>

   <td width="32">3</td>

  </tr>

  <tr>

   <td width="50">1</td>

   <td width="47">18.8</td>

   <td width="40">16.7</td>

   <td width="32">19.8</td>

  </tr>

  <tr>

   <td width="50"> </td>

   <td width="47">21.2</td>

   <td width="40"> </td>

   <td width="32">23.9</td>

  </tr>

  <tr>

   <td width="50">2</td>

   <td width="47">22.3</td>

   <td width="40">15.919.2</td>

   <td width="32">21.8</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Express this as a two-factor model with no interaction in matrix form.</li>

 <li>Express this as a two-factor model with interaction in matrix form.</li>

 <li>Express the hypothesis that there is no interaction in terms of your parameters. Eliminateany redundancies.</li>

 <li>Input this data into R. Plot an interaction plot between breed and diet.</li>

 <li>Test for the presence of interaction.</li>

 <li>What is the degrees of freedom used for the interaction test?</li>

 <li>From the interaction model, what is the estimated amount of milk produced from breed 2 anddiet 3?</li>

 <li>Fit an additive model. What is the estimated amount of milk produced from breed 2 and diet3 now?</li>

 <li>Test the hypothesis (under the additive model) that the 2nd and 3rd diets are equivalent interms of milk produced.</li>

 <li>Find a 95% confidence interval, under the additive model, for the amount of milk producedfrom breed 2 and diet 3. Use both matrix calculations and the estimable function from the gmodels</li>

 <li>Find the same confidence interval under the interaction model.</li>

 <li>Why is the second interval wider than the first?</li>

</ul>

<ol start="2">

 <li>We study the growth of peas when fed three different types of fertilizer. A study is conductedwhere the samples are divided into 6 “blocks”, corresponding to different plots of land. The data is stored in the npk data frame in R. This data frame contains 5 variables:</li>

</ol>

block: label of the block of the sample

N: indicator (0/1) for the application of nitrogen

P: indicator (0/1) for the application of phosphate K: indicator (0/1) for the application of potassium yield: yield of peas in pounds/plot

<ul>

 <li>Fit an additive linear model with all variables; then repeat without the block variables. Doesthe fitted model change? Are the block variables significant?</li>

 <li>Fit a model with the fertilizer variables and all pairwise interaction terms. Are the interactionterms significant?</li>

 <li>Perform variable selection using stepwise selection with AIC, starting from the model with nointeraction terms (but considering them for inclusion). What do you find?</li>

 <li>What is the best treatment for peas, according to your final model? Find a 95% confidenceinterval for the yield of this treatment.</li>

</ul>

1

<ol start="3">

 <li>A study was conducted to determine the effect of the size of the root system on the growth ofDouglas-fir seedlings when they are planted out. Seedlings were obtained from three seed lots, and when they were planted out their root volume was classified as small (RV1), medium (RV2), or large (RV3). The heights of the seedlings were then measured at the end of the first growing season. The data from the experiment are given in the file csv.

  <ul>

   <li>How has randomisation and blocking been used in the design of this experiment?</li>

   <li>Generate two interaction plots for the data. Is there any evidence of an interaction?</li>

   <li>Fit a model with interaction to the data and use it to find the fitted means for each combinationof factor levels.</li>

   <li>Find a 95% confidence interval for the difference in height between a seedling with large rootvolume (RV3) and a seedling with medium root volume (RV2). Suppose that the seedling came from seed lot B349.</li>

   <li>Test for the presence of an interaction at the 5% significance level. Would it be meaningful tocheck the significance of the main effects? Why?</li>

   <li>Fit an additive model to the data using the lm command, and produce plots to justify the model assumption that the errors are normal and homoskedastic.</li>

  </ul></li>

 <li>Suppose that <strong>y </strong>∼ <em>MV N</em>(<em>µ</em><strong>1</strong><em>,</em>Σ), where</li>

</ol>

<em> .</em>

For what values of <em>ρ </em>are the sample mean and sample variance independent?

<ol start="5">

 <li>In the one-way classification model, show that any linear combination of ¯<em>y</em><sub>1 </sub>−<em>y</em>¯<em>,…,y</em>¯<em><sub>k </sub></em>−<em>y</em>¯<sub>· </sub>can be written as a linear combination of ¯<em>y</em><sub>1</sub><em>,…,y</em>¯<em><sub>k</sub></em>. Does the converse hold?</li>

</ol>

2