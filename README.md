# sta4102-assignment-3solved
**TO GET THIS SOLUTION VISIT:** [STA4102 Assignment 3Solved](https://www.ankitcodinghub.com/product/sta410-instructions-solutions-to-problems-1-and-2-are-to-be-submitted-on-quercus-pdf-files-only-you-are-strongly-encouraged-to-do-problems-3-6-but-these-are-not-to-be-submitted-for-gradi/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117148&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STA4102 Assignment 3Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Instructions: Solutions to problems 1 and 2 are to be submitted on Quercus (PDF files only). You are strongly encouraged to do problems 3–6 but these are not to be submitted for grading.

where V 1,···,V m are independent random vectors with E[V iV Ti ] = I.

(a) Suppose that the elements of each V i are independent, identically distribution random variables with mean 0 and variance 1. Show that Var(tr(b A) is minimized by taking the elements of V i to be ±1 each with probability 1/2.

(Hint: This is easier than it looks – Var(V TAV ) = E[(V TAV )2] − tr(A)2 so it suffices to minimize

.

Given our conditions on the elements of V i, V1,···,Vn, most of E(ViVjVkV`) are either 0 or 1. You should be able to show that

n

E[(V TAV )2] = Xa2iiE(Vi4) + constant

i=1

and find Vi to minimize E(Vi4) subject to E(Vi2) = 1.)

(b) We also noted that if B is a symmetric n×n matrix whose eigenvalues are less than 1 in absolute value then we have the following formula for the determinate of the matrix I − B:

!

and so we can estimate this determinant by

!

where r is “large enough”.

In linear regression, one measure of the leverage of a subset of ` observations (x1,y1),···,(x`,y`) is 1 − det(I − H11) where H11 is an ` × ` matrix defined in terms of the linear regression “hat” matrix as follows:

.

From above, we can estimate det(I − H11) by

!

for some r.

Show that we can compute H11V and V for k ≥ 2 using the hat matrix H as follows:

and



.

(c) On Quercus, there is a function leverage (in the file leverage.txt) that computes the leverage for a given subset of observations for a design matrix X. (This function uses the QR decomposition of X to compute HV i; the functions are qr, which computes the QR decomposition of X and qr.fitted. which computes Hy = QQTy.)

Suppose that yi = g(xi) + εi for i = 1,···,n for some smooth function g and consider the following two parametric models for g:

and

g2(x) = β0 + β1φ1(x) + ··· + β10φ10(x)

where φ1(x),···,φ10(x) are B-spline functions. Suppose that x1,···,x1000 are equally spaced points on [0,1] with xi = i/1000. The B-spline functions and the respective design matrices can be constructed using the following R code:

&gt; x &lt;- c(1:1000)/1000

&gt; X1 &lt;- 1

&gt; for (k in 1:5) X1 &lt;- cbind(X1,cos(2*k*pi*x),sin(2*k*pi*x))

&gt; library(splines) # loads the library of functions to compute B-splines

&gt; X2 &lt;- cbind(1,bs(x,df=10))

Note that both X1 and X2 are 1000 × 11 matrices. You can see the B-spline functions φ1(x),···,φ10(x) as follows:

&gt; plot(x,X2[,2])

&gt; for (i in 3:11) points(x,X2[,i])

2. Suppose that X1,···,Xn are independent Gamma random variables with common density

for x &gt; 0

where α &gt; 0 and λ &gt; 0 are unknown parameters.

(a) The mean and variance of the Gamma distribution are α/λ and α/λ2, respectively. Use these to define method of moments estimates of α and λ based on the sample mean and variance of the data x1,···,xn

(b) Derive the likelihood equations for the MLEs of α and λ and derive a Newton-Raphson algorithm for computing the MLEs based on x1,···,xn. Implement this algorithm in R and test on data generated from a Gamma distribution (using the R function rgamma). Your function should also output an estimate of the variance-covariance matrix of the MLEs – this can be obtained from the Hessian of the log-likelihood function.

Important note: To implement the Newton-Raphson algorithm, you will need to compute the first and second derivatives of lnΓ(α). These two derivatives are called (respectively) the digamma and trigamma functions, and these functions are available in R as digamma and trigamma; for example,

&gt; gamma(2) # gamma function evaluated at 2

[1] 1

&gt; digamma(2) # digamma function evaluated at 2

[1] 0.4227843

&gt; trigamma(2) # trigamma function evaluated at 2

[1] 0.6449341

Supplemental problems:

3. Consider LASSO estimation in linear regression where we define βbλ to minimize

n p

X T 2 X

(yi − y¯− xi β) + λ |βj|

i=1 j=1

and the set

.

We want to look at what happens to the LASSO estimate

(a) Show that minimizes

.

(b) Find the limit ofas λ ↓ 0 as a function of β. (What happens when β 6∈ C?) Use this to deduce that as λ ↓ 0,

p

where minimizes X|βj| on the set C.

j=1

(c) Show that is the solution of a linear programming problem. (Hint: Note that C can be expressed in terms of β satisfying p linear equations.)

4. Consider minimizing the function

g(x) = x2 − 2αx + λ|x|γ

where λ &gt; 0 and 0 &lt; γ &lt; 1. (This problem arises, in a somewhat more complicated form, in shrinkage estimation in regression.) The function |x|γ has a “cusp” at 0, which mean that if λ is sufficient large then g is minimized at x = 0.

(a) g is minimized at x = 0 if, and only if,

. (1)

Otherwise, g is minimized at x∗ satisfying g0(x∗) = 0. Using R, compare the following two iterative algorithms for computing x∗ (when condition (1) does not hold):

(i) Set x0 = α and define

(ii) The Newton-Raphson algorithm with x0 = α.

Use different values of α, γ, and λ to test these algorithms. Which algorithm is faster?

(b) Functions like g arise in so-called bridge estimation in linear regression (which are generalizations of the LASSO) – such estimation combines the features of ridge regression (which shrinks least squares estimates towards 0) and model selection methods (which produce exact 0 estimates for some or all parameters). Bridge estimates βb minimize (for some γ &gt; 0 and λ &gt; 0),

n p

X T 2 X γ

(yi − xi β) + λ |βj| . (2) i=1 j=1

See the paper by Huang, Horowitz and Ma (2008) (“Asymptotic properties of bridge estimators in sparse high-dimensional regression models” Annals of Statistics. 36, 587–613) for details. Describe how the algorithms in part (a) could be used to define a coordinate descent algorithm to find βb minimizing (2) iteratively one parameter at a time.

(c) Prove that g is minimized at 0 if, and only if, condition (1) in part (a) holds.

5. Suppose that A is a symmetric non-negative definite matrix with eigenvalues λ1 ≥ λ2 ≥ ··· ≥ λn ≥ 0. Consider the following algorithm for computing the maximum eigenvalue λ1:

Given x0, define for and .

Under certain conditions, µk → λ1, the maximum eigenvalue of A; this algorithm is known as the power method and is particularly useful when A is sparse.

(a) Suppose that v1,···,vn are the eigenvectors of A corresponding to the eigenvalues λ1,···,λn. Show that µk → λ1 if x = 0 and λ1 &gt; λ2.

(b) What happens to the algorithm if if the maximum eigenvalue is not unique, that is,λ1 = λ2 = ··· = λk?

6. (a) Suppose that A is an invertible matrix that can be written as I − B where B has its eigenvalues in the interval (−1,1). Show that

∞ tr(A−1) = X tr(Bk)

k=0

(where B0 = I).

(b) We can use Hutchinson’s method to estimate tr(A−1) by exploiting the formula in part (a), truncating the infinite series at some finite point r (where Bk = 0 for k &gt; r). The key lies in writing A = α(I − B) for some constant α and matrix B whose eigenvalues lie in

(−1,1); then

∞

tr(A−1) = α−1 X tr(Bk).

k=0

Suppose that λ1,···,λn &gt; 0 are the eigenvalues of A and define µ so that

.

In terms of µ, how would you define α and B?

(c) Suppose that A is symmetric positive definite with elements {aij : 1 ≤ i,j ≤ n}. Show that we can take µ in part (b) to be

.

(Hint: Show that µ = kAk∞.)
