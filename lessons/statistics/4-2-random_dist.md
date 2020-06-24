[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

sample = np.random.random(1000)
sample_pmf = thinkstats2.Pmf(sample)
thinkplot.pmf(sample_pmf, linewidth = 0.07)

sample_cdf = thinkstats2.Cdf(sample)
thinkplot.cdf(sample_cdf)