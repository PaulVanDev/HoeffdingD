
## [Adaptation of Hoeffding's D in Python](http://PaulVanDev.github.io/hoeffdingD)

Hoeffding’s test for dependence was proposed by Wassily Hoeffding (1948) as a test for two random variables
with continuous distribution functions.Hoeffding’s D is a nonparametric measure of the distance
between joint distribution, F(x, y) and product of marginal distributions, FX(x)FY(y).
The advantage of this statistic lies in the fact that it has more power to detect non-monotonic dependency structures 
compared to other more common measures (Pearson, Kendall, Sparman)



******************************************************************************************************************************************

References:

https://stackoverflow.com/questions/9270496/ideas-for-gpu-implementation-of-hoeffdings-d-dependence-coefficient/9322657#9322657
-> Code in matlab

http://support.sas.com/documentation/cdl/en/procstat/67528/HTML/default/viewer.htm#procstat_corr_details07.htm
-> Formula proposed by SAS
HoeffdingD is proposed as non-parametric correaltion method in SAS and in JMP softwares

https://github.com/pandas-dev/pandas/issues/22086
-> a request for hoeffdingD in pandas

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4539721/
-> more explanations on the need for non-pearson correlation methods


http://math.furman.edu/~dcs/courses/math47/R/library/Hmisc/html/hoeffd.html
-> statistical explanation

https://stats.stackexchange.com/questions/20011/can-the-mic-algorithm-for-detecting-non-linear-correlations-be-explained-intuiti
->more discussion and comparison with MIC algorithm - Mutual Information Coefficient

https://journal.r-project.org/archive/2018/RJ-2018-057/RJ-2018-057.pdf
