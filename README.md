java c
MKF5912 
One Sample T-test 
Question: Has the mean preference for teenagers before entering the theme park changed from the previous survey? 
Step 1: Formulate null and alternative hypotheses 
H0: The mean preference for teenagers before entering the theme park did not change from the previous survey 
H1: The mean preference for teenagers before entering the theme park changed from the previous survey 
Let’s   say   we    know    that    last   year   the    mean    preference    was    5.    Therefore   the   above   hypotheses can be rewritten   analytically   as: 
H0: μ =   5
H1: μ ≠ 5
Step 2: Test null hypothesis 
Look at One-Sample   t-test

and compare the significance (p-value) of t statistic with   α=0.05.   In our case: 0.177>0.05 =>   Do   NOT   reject   null   hypothesis. 
Conclusion: The mean preference for teenagers before entering the theme park did not change from the previous survey. (Though this year the   mean   preference   is 5.5   it   is   not significantly different from   5.0). 
Note: If    significance    of    t    statistic    would      be      lower    than      α=0.05      (for      instance,   0.03<0.05), then the null hypothesis would be rejected and the conclusion would be opposite. 
Independent Samples T-test 
Question: Do teenagers have different preference than adults before entering the park? 
Step 1: Formulate null and alternative hypotheses 
H0: Teenagers have the same mean preference before entering park as do adults 
H1: Teenagers have different mean preference before entering park as do adults 
The same hypotheses but written   analytically: 
H0: μ1    = μ2 
H1: μ1    ≠ μ2
Step 2: Test null hypothesis 
Look at   Independent Samples t-test

First   we   have   to   choose   which   t-test   to   use:   t-test   with   equal   variances   or   t-test   with not   equal variances. 
Step 2.1: Test the equality of variances between two populations 
H0: σ1(2)   = σ2(2)   (equal variances assumed)
H1: σ1(2)   ≠ σ2(2)   (equal variances   not assumed)
To test this   hypothesis we   look   at significance   of   F   statistic, which   is   0.703   in   our   case.    As    0.703>0.05    =>    we      cannot      reject      null      hypothesis      about      equality      of   variances. 
Conclusion: variances of two populations are the same and we   can   use the first   t-test   (with   equal   variances   assumed).   This   test   is   located   in   the   first   row   of   the   Independent Samples Test table. 
Note:   If this   significance would   be   lower than   0.05   (for   instance,   0.02<0.05), then we would reject null hypothesis and would use the second row of the table for t- test.
Step 2.2: Test the equality of means hypothesis 
H0: μ1    = μ2
H1: μ1 ≠ μ2
To   test   this   hypothesis   we   compare   the   significance   (p-value)   of   t   statistic   with   α=0.05.    In    our    case      0.006<0.05 =>    we      reject      null      hypothesis      of      equality      of means.Conclusion: Teenagers have different mean preference before entering park as do adults (teenagers   have   mean   preference   5.5   and   代 写MKF5912 One Sample T-testSQL
代做程序编程语言adults   have   4.0,   and   this   difference   is   significant).
Note:    The    above      example      involved      two-tailed      test.       However,    one      could      be   interested to use   one-tailed test.
One tailed test:
H0: μ1    ≤ μ2 (teenagers have lower mean preference than adults) 
H1: μ1      > μ2 (teenagers have higher mean preference than adults) If   you   use   one-tailed   test   you   have   to   adjust   p-value   by   dividing   it   by   2.   In   our   case   for   one-tailed   test   the   significance    p=0.006/2=0.003<0.05 =>      Reject    null   hypothesis.
Conclusion: Teenagers have higher mean preference before entering park than do adults (teenagers have mean   preference   5.5   and   adults   have   4.0).
Paired Samples T-test
Question: Is there a difference in the preference before and after visiting the Disney theme park for teenagers? 
Step 1: Formulate null and alternative hypotheses 
H0: Teenagers have the same preference before and after visiting Disney park 
H1: Teenagers have different preferences before and after visiting Disney park 
The   same   hypotheses   but   written   analytically   (D=Preference   After   –   Preference   Before):
H0: μD =   0
H1: μD ≠ 0
Step 2: Test null hypothesis 
Look at   Paired Samples   t-test

and compare the significance (p-value) of t statistic with   α=0.05.   In our case: 0.000<0.05 =>   reject   null   hypothesis.
Conclusion: The    preference    for    teenagers after visiting the theme park    is different from preference before entering park. (After=7.9    ≠    Before=5.5).
Note:   If you would   like to use one-tailed test, the   hypotheses will look   as follows
H0: μD ≤ 0
H1: μD > 0
p=0.000/2=0.000<0.05 =>   Reject null   hypothesis
Conclusion: The preference for teenagers after visiting the theme park is higher than preference before entering park. (After=7.9       >         Before=5.5).
ANOVA 
Question: Do    the    various    promotion    campaigns    differ in    terms    of generated sales? 
Step 1: Formulate null and alternative hypotheses 
H0: All promotions have the same influences on sales 
H1: At least one promotion level has different influence on sales 
The same hypotheses but written   analytically:
H0: μ1    = μ2      = μ3
H1: at least one mean is different 
Step 2: Test null hypothesis 
Look at   SPSS   output

and compare the significance (p-value) of   F statistic with   α=0.05.   In our case: 0.001<0.05 =>   reject   null   hypothesis.
Conclusion: Promotions    have influence       on       sales (the      means    of    sales      for   different levels of promotion are significantly different from   each   other).
Step 3: Determine the strength of effect To determine the   strength of effect we have to calculate eta-squared: η2 = SSX/SSY = 70   / 98 = 0.714 .    It    means    that    promotions    have    strong      effect      on   sales   (recall that η2    ∈   (0,1) ).
Step 4: Interpret the pattern of the relationship between variables 
More   intensive campaign leads to   higher   sales.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
