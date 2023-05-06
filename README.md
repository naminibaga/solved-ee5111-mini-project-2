Download Link: https://assignmentchef.com/product/solved-ee5111-mini-project-2
<br>
<h1>1           Performance of MLE</h1>

The aim of this exercise is to study the variation in the performance of MLE with increase in the number of samples. Consider the following equation:

<em>x<sub>i </sub></em>= <em>A </em>+ <em>n<sub>i                                                </sub>i </em>= 1<em>,…,N                                                           </em>(1)

where <em>A </em>is scalar and <em>n<sub>i </sub></em>are the noise samples. Compute the maximum likelihood estimate of <em>A </em>for the following cases:

<ol>

 <li><em>n<sub>i </sub></em>∼N(0<em>,</em>1). In this case, use the following expression derived in class:</li>

</ol>

<em>.</em>

√

<ol start="2">

 <li><em>n<sub>i </sub></em>∼ <em>Lap</em>(0<em>,</em>1<em>/ </em>2), i.e., Laplace distribution with zero mean and unit variance. In this case, the MLE is derived as:</li>

</ol>

<em>A</em><sup>ˆ </sup>= <em>median</em>(<em>x<sub>i</sub></em>)<em>.</em>

<ol start="3">

 <li><em>n<sub>i </sub></em>∼ <em>Cauchy</em>(0<em>,γ</em>). Use <em>γ </em>= <sup>p</sup>2<em>C<sub>g </sub></em>where <em>C<sub>g </sub></em>= 1<em>.</em> The closed form solution for MLE is not available and hence, MLE should be computed through numerical evaluation. Use Newton Raphson or any other appropriate numerical method.</li>

</ol>

Repeat the above experiments for <em>N </em>= 1<em>,</em>10<em>,</em>100<em>,</em>1000<em>,</em>10000 and for <em>A </em>= 1 and <em>A </em>= 10. Here, <em>N </em>is the number of samples considered for estimation. Present the following for each noise distribution:

<ol>

 <li>Tabulate the values of E[<em>A</em>ˆ] against the number of samples for both values of <em>A</em>. What do you infer?</li>

 <li>Tabulate the values of <em>V ar</em>(<em>A</em>ˆ) against the number of samples for both values of <em>A</em>. What do you infer?</li>

 <li>Plot the CDF of the estimate for <em>N </em>= 1<em>,</em>10<em>,</em>100<em>,</em>1000<em>,</em>10000 samples for <em>A </em>= 1. Ensure that you take enough realizations to get a smooth CDF. What can you say about the CDF? Justify. Do you observe the following relation?</li>

</ol>

√

<em>N</em>(<em>A</em><sup>ˆ </sup>− <em>A</em><sub>0</sub>) ∼N(0<em>,I</em>(<em>A</em>)<sup>−1</sup>)

Here, <em>I </em>denotes the Fisher information.

1

<ol start="4">

 <li>Plot the PDF of the estimate for <em>N </em>= 1<em>,</em>10<em>,</em>100<em>,</em>1000<em>,</em>10000 samples for <em>A </em>= 1. Ensure that you take enough realizations to get a smooth PDF. What can you say about the PDF convergence?</li>

</ol>