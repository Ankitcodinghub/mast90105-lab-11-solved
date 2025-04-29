# mast90105-lab-11-solved
**TO GET THIS SOLUTION VISIT:** [MAST90105 Lab 11 Solved](https://www.ankitcodinghub.com/product/mast90105-lab-and-workshop-problems-for-week-11-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112925&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MAST90105 Lab 11 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
The Lab and Workshop this week covers problems arising from Modules 7 and 8.

1 Lab

1. How good are confidence intervals? If we repeat the experiment a large number of times we expect 95% of the confidence intervals for contain the parameter values. We can check this using simulations. Enter the following commands:

x = t.test(rnorm(10)) x names(x) x$conf.int

f=function(t){x=t.test(rnorm(t));as.vector(x$conf.int)}; f(10);

f(20);

t &lt;- as.matrix(rep(10,100));

C &lt;- t(apply(t,1,f)); #this is a trick so we don’t have to program matplot(C,type=”l”);#a matrix plot abline(0,0)#includes a line at 0

Each column of the matrix C is the lower and upper bounds of a 95% confidence interval. From your plot determine how many of these intervals contain the true mean zero. Is it close to 95%? You can check as follows:

num = (C[, 1] &lt; 0) &amp; (C[, 2] &gt; 0) sum(num)/nrow(C)

c. Plot this density with the posterior density obtained in lectures from a uniform prior.

d. Find a 95% posterior probability interval from your posterior distribution and compare this to the one from lectures.

2 Workshop

3. Let X ∼ binomial(1,p) and let X1,…,X10 be a random sample of size 10. Consider a test of H0 : p = 0.5 against H1 : p = 0.25. Let . Define the critical region as C = {y : y &lt; 3.5}.

a. Find the value of α the probability of a Type I error. Do not use a normal approximation. (Hint: Use pbinom).

b. Find the value of β, the probability of a Type II error. Do not use a normal approximation.

c. Simulate 200 observations on Y when p = 0.5. Find the proportion of cases when H0 was rejected. Is this close to α?

d. Simulate 200 observations on Y when p = 0.25. Find the proportion of cases when H0 was not rejected. Is this close to β?

4. A ball is drawn from one of two bowls. Bowl A contains 100 red balls and 200 white balls; Bowl B contains 200 red balls and 100 white balls. Let p denote the probability of drawing a red ball from the bowl. Then p is unknown as we don’t know which bowl is being used.To test the simple null hypothesis H0 : p = 1/3 against the simple alternative that p = 2/3, three balls are drawn at random with replacement from the selected bowl. Let X be the number of red balls drawn. Let the critical region be C = {x : x = 2,3}. Using R, what are the probabilities α and β respectively of Type I and Type II errors?

5. Let Y ∼ binomial(100,p). To test H0 : p = 0.08 against H1 : p &lt; 0.08, we reject H0 and accept H1 if and only if Y ≤ 6. Using R,

a. Determine the significance level α of the test.

b. Find the probability of a Type II error if in fact p = 0.04.

6. Let p be the probability a tennis player’s first serve is good. The player takes lessons to increase p. After the lessons he wishes to test the null hypothesis H0 : p = 0.4 against the alternative H1 : p &gt; 0.4. Let y be the number out of n = 25 serves that are good, and let the critical region be defined by C = {y : y ≥ 13}.

a. Define the power function to be K(p) = P(Y ≥ 13;p). Graph this function for 0 &lt; p &lt; 1.

b. Find the value of α = K(0.40)

c. Find the value of β when p = 0.6, (β = 1 − K(0.6))

7. Let X1,…,X10 be a random sample of size n = 10 from a distribution with p.d.f. f(x;θ) = exp(−(x − θ)), θ ≤ x &lt; ∞.

a. Show that Y1 = min(Xi) is the maximum likelihood estimator of θ.

b. Find the p.d.f. of Y1 and show that E(Y1) = θ + 1/10 so that Y1 − 1/10 is an unbiased estimator of θ.

c. Compute P(θ ≤ Y1 ≤ θ + c) and use this to construct a 95% confidence interval for θ.

8. A random variable X is said to have a Pareto distribution with parameters, x0 and β, if its cdf is

a. What is the pdf of X?

b. Suppose U1,··· ,Un are a random sample from the uniform distribution on (0,X) where X is the unknown parameter. Suppose that X has a Pareto prior distribution with parameters x0,β. Calculate the posterior distribution of X. (Hint: Consider carefully the values of the posterior pdf which are strictly positive, noting that both the joint distribution of the sample and the prior distribution pdf’s have to be positive.)

c. Find a 100(1 − α) % posterior probability interval for X.

9. If a newborn baby has a birth weight that is less than 2500 grams we say the baby has a low birth weight. The proportion of babies with birth weight is an indicator of nutrition for the mothers. In the USA approximately 7% of babies have a low birth weight. Let p be the proportion of babies born in the Sudan with low birth weight. Test the null hypothesis H0 : p = 0.07 against the alternative H1 : p &gt; 0.07. If y = 23 babies out of a random sample of n = 209 babies had low birth weight, , using a suitable approximation, what is your conclusion at the significance levels

a. α = 0.05?

b. α = 0.01?

c. Find the p-value of this test. (Recall the p-value is the probability of the observed

value or something more extreme when the null hypothesis is true).

Helpful R output

qnorm(c(0.95, 0.99)) ## [1] 1.644854 2.326348

pnorm(2.269)

## [1] 0.9883658

10. Let pm and pf be the respective proportions of male and female white crowned sparrows that return to their hatching site. Give the endpoints for a 95% confidence interval for pm − pf, given that 124 out of 894 males and 70 out of 700 females returned. (The Condor, 1992 pp.117-133.). Does this agree with the conclusion of the test of H0 : pm = pf against H1 : pm 6= pf with α = 0.05?
