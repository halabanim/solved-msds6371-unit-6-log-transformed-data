Download Link: https://assignmentchef.com/product/solved-msds6371-unit-6-log-transformed-data
<br>



<em>Plot the raw data, and also plot the data after a log transform.  After a log transform, do the data satisfy the assumptions better? </em>The data is in ex0525.csv or ex0525.xlsx. Perform this analysis in SAS. [Depending on where you find the data set, you may see the value <strong>&lt;&lt;12</strong>. Note that <strong>&lt;&lt;12 = 12</strong>.]

Regardless of whether the assumptions of the original data or log transformed data are met, please include a <strong>complete analysis</strong> on the <strong>log transformed</strong> data.

<ol>

 <li>State the Problem.</li>

 <li>Address the assumptions. Comment on each assumption.  (Use the visual test, as the Brown-Forsythe test will be overpowered due to the large sample size.  This simply means that it is able to detect very small effect sizes—here, differences in standard deviations—which may not be big enough to practically affect the test.)  Comment on your thoughts of the assumptions, but, in the end, assume there is not enough visual evidence to suggest the standard deviations of the log transformed data are different.</li>

 <li>Conduct the Test. (An example is in the UNIT 5 PowerPoint.)</li>

 <li>Write a conclusion. (An example is in the UNIT 5 PowerPoint.)</li>

 <li>State the Scope. (Can we generalize to the entire population or just the sample that was taken? Is there a causal relationship present?)</li>

</ol>

ADDITIONAL THINGS TO INCLUDE (for the logged data):

<ol>

 <li>Please also identify R<sup>2</sup></li>

 <li>Also specify the mean square error and how many degrees of freedom were used to estimate it.</li>

 <li>Provide the code to perform the ANOVA in R and a screen shot of the output.</li>

</ol>

<em><u>Looking to the future!</u></em><em>  This is not an additional problem.  Just FYI: The next step will be to look at these pairwise if we reject the H<sub>o</sub> to discover WHICH pairs have evidence of different means / medians. </em>

<ol start="2">

 <li>Use an extra sum of squares F-test (BYOA: Build Your Own ANOVA!) to use all the data (to increase the degrees of freedom and thus the power of the test!) to compare only the bachelor’s degree group (16) income to the more than bachelor’s degree group (&gt;16) income. Show your final ANOVA table and your 6-step complete analysis.  You will need to assume that the standard deviations of the log-transformed data are again equal to proceed here.  A two-sample t-test between these two groups (assuming equal standard deviations on logged data) yields a p-value of <strong>.1648</strong> (try it!), but it only uses 778 degrees of freedom (from a pooled t-test).  Make note again of how many degrees of freedom were used to estimate the pooled standard deviation in your extra sum of squares test.  You may use SAS or R.</li>

 <li>Now, suppose that you cannot assume the standard deviations are the same (for both the original or log transformed data). Conduct another complete analysis of the question in Chapter 5, problem 25 in <u>Statistical Sleuth</u>. Answer the question, “How strong is the evidence that at least one of the five population distributions (corresponding to the different years of education) is different from the others?”  This question should be answered in at least 1 or 2 sentences after providing a <strong>complete analysis</strong> without the assumption of equal standard deviations for the logged data (or for the original data).  Perform the test in SAS or R.</li>

</ol>