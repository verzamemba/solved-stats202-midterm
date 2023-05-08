Download Link: https://assignmentchef.com/product/solved-stats202-midterm
<br>
<ol>

 <li>We define a new kind of discriminant analysis for a classification problem with a binary response. The classes have prior probabilities <em>π</em><sub>0 </sub>and <em>π</em><sub>1</sub>. Given the class, <em>k</em>, the conditional probability of the inputs <em>X</em><sub>1</sub><em>,…,X<sub>p </sub></em>is multivariate normal with a class-dependent mean <em>µ<sub>k </sub></em>and covariance matrix <em>σ<sub>k</sub></em><strong>Σ</strong>. The matrix <strong>Σ </strong>is common to both classes and <em>σ<sub>k </sub></em>is a classdependent constant. All parameters, <em>π<sub>k</sub></em>, <em>µ<sub>k</sub></em>, <em>σ<sub>k</sub></em>, for each class, as well as Σ, are set to their Maximum Likelihood estimates.

  <ul>

   <li><strong> </strong>Provide an equation describing the classifier’s decision boundary or discriminant. What would the boundary look like?</li>

   <li><strong> </strong>Why might this classifier be preferable to Linear Discriminant Analysis?</li>

   <li><strong> </strong>Why might this classifier be preferable to Quadratic Discriminant Analysis?</li>

  </ul></li>

 <li><strong> </strong>Compare leave-one-out cross validation to 10-fold cross validation, with reference to the bias-variance tradeoff.</li>

 <li><strong> </strong>A total of <em>n </em>samples were simulated from the following distribution</li>

</ol>

<em>X</em><sub>1</sub><em>,X</em><sub>2</sub><em>,X</em><sub>3</sub><em>,X</em><sub>4 </sub>∼ N(0<em>,</em>1) i.i.d.

where <em>f </em>is non-linear. Consider the following regression methods for <em>Y </em>: linear regression with predictors <em>X</em><sub>1</sub><em>, X</em><sub>2</sub><em>, X</em><sub>3</sub><em>, </em>and <em>X</em><sub>4</sub>, and 3-nearest neighbors regression. On the same plot, sketch a plausible learning curve for each method. A learning curve for regression shows the average test MSE as a function of <em>n</em>. Explain your reasoning.

<ol start="4">

 <li><strong> </strong>The clusterings below were produced by single-linkage hierarchical clustering and <em>k</em>-means clustering. Determine which one is which and explain your reasoning.</li>

 <li>We apply the Bootstrap to a dataset with <em>n </em>distinct observations <em>x</em><sub>1</sub><em>,…,x<sub>n</sub></em>.

  <ul>

   <li><strong> </strong>What is the probability that the <em>j<sup>th </sup></em>observation is included in a specific bootstrap sample?</li>

   <li>What is the expected value for the fraction of distinct observations in a specific bootstrap sample (i.e. the number of distinct observations from <em>x</em><sub>1</sub><em>,…,x<sub>n </sub></em>divided by <em>n</em>). Does this expectation converge as <em>n </em>grows large? Hints: (i) use the probability from part (a), (ii) lim<em><sub>n</sub></em>→∞(1 − 1<em>/n</em>)<em><sup>n </sup></em>= <em>e</em><sup>−1</sup>.</li>

  </ul></li>

 <li><strong> </strong>A group of 33 people were asked to report their happiness on a scale from 0 to 20. We apply a linear model with an intercept to regress happiness onto 2 predictors, the yearly income and the amount of money paid in taxes last year.</li>

</ol>

The <em>t</em>-statistics for income and taxes have corresponding <em>p</em>-values of 0<em>.</em>14 and 0<em>.</em>52, respectively. The RSS of the model is 30 and the sample variance of the happiness is 1.5.

What would you conclude about the relationship between happiness, income, and tax contributions?

<ol start="7">

 <li>(a) Identify which classifier among <em>k</em>-nearest neighbors with <em>k </em>= 15 and logistic regression would be more appropriate for each dataset below. Explain how one might adjust the True Positive rate of each method.</li>

</ol>

<em>Note: </em>Red circles are negative and blue triangles are positive.

(b) <strong> </strong>Each of the ROC curves below corresponds to one of the datasets in part (a). In each case, we applied the optimal classifier among <em>k</em>-nearest neighbors and logistic regression. Match each ROC curve to its corresponding dataset and explain your reasoning.







<h1>Cheat sheet</h1>

The sample variance of <em>x</em><sub>1</sub><em>,…,x<sub>n </sub></em>is:

<em>,</em>

The residual sum of squares for a regression model is:

<em>t</em><strong>-test:</strong>

The <em>t</em>-statistic for hypothesis <em>H</em><sub>0 </sub>: <em>β<sub>i </sub></em>= 0 is

<em>β</em>ˆ<em>i</em>

<em>t </em>=

SE(<em>β</em><sup>ˆ</sup><em><sub>i</sub></em>) <em>F</em><strong>-test:</strong>

<table>

 <tbody>

  <tr>

   <td width="312"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

The <em>F</em>-statistic for hypothesis <em>H</em><sub>0 </sub>: <em>β<sub>p</sub></em>−<em><sub>q</sub></em><sub>+1 </sub>= <em>β<sub>p</sub></em>−<em><sub>q</sub></em><sub>+2 </sub>= ··· = <em>β<sub>p </sub></em>= 0 is

<em>,</em>

where <em>RSS</em><sub>0 </sub>is the residual sum of squares for the null model <em>H</em><sub>0</sub>, and <em>RSS </em>is the residual sum of squares for the full model with all predictors. Asymptotically, the <em>F</em>-statistic has the <em>F</em>-distribution with degrees of freedom <em>d</em><sub>1 </sub>= <em>q </em>and <em>d</em><sub>2 </sub>= <em>n </em>− <em>p </em>− 1.

Minimum <em>F</em>-statistic to reject <em>H</em><sub>0 </sub>at a significance level <em>α </em>= 0<em>.</em>01

<table width="351">

 <tbody>

  <tr>

   <td width="35"> </td>

   <td width="32"> </td>

   <td width="79"> </td>

   <td width="142"><em>d</em><sub>1</sub></td>

   <td width="63"> </td>

  </tr>

  <tr>

   <td width="35"> </td>

   <td width="32"> </td>

   <td width="79">1</td>

   <td width="142">        2                     3</td>

   <td width="63">4</td>

  </tr>

  <tr>

   <td width="35"><em>d</em><sub>2</sub></td>

   <td width="32">1 1020</td>

   <td width="79">4052.18110.0448.096</td>

   <td width="142">4999.500   5403.3527.559               6.5525.849               4.938</td>

   <td width="63">5624.5835.9944.431</td>

  </tr>

  <tr>

   <td width="35"> </td>

   <td width="32">30</td>

   <td width="79">7.562</td>

   <td width="142">5.390               4.510</td>

   <td width="63">4.018</td>

  </tr>

  <tr>

   <td width="35"> </td>

   <td width="32">120</td>

   <td width="79">6.851</td>

   <td width="142">4.787               3.949</td>

   <td width="63">3.480</td>

  </tr>

 </tbody>

</table>

<strong>Logistic regression:</strong>

Logistic regression assigns to positive if the estimated conditional probability

<strong>LDA:</strong>

The log-posterior of class <em>k </em>given an input <em>x </em>is:

where <em>C </em>is a constant which does not depend on <em>k</em>.

<strong>QDA:</strong>

The log-posterior of class <em>k </em>given an input <em>x </em>in QDA is:

where <em>C </em>is a constant which does not depend on <em>k</em>.