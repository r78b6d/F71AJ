java c
F71AJ Financial Economics II
Coursework 2023/2024
Assignment:  Please  answer the following questions. Please read the R script. for this project provided on the Canvas course webpage alongside these instructions.Consider anon-dividend paying stock with price process St  and a European put option on this asset.   The current asset price is  S0   =  100.00.   The expiry  date of the put option is in six months time, the strike price is K =  120.00,  and the risk-free rate of interest (with continuous compounding) is 0.025 per annum (2.5%).  The expected rate of return of the underlying asset is µ = 0.05 per annum (5%), and its volatility is σ = 0.2 per annum (20%).  That is we have
for small δt.
1.  Model  the  stock  price with  a  one  period Binomial model  with  u  =  1.05  and d =  1.05−1  to ﬁnd the price of the put  option  at time  0.   Use  R to ﬁnd the numerical answer.  In your report you must give details of the various steps in your calculation and provide the R code for those steps.             [1 mark]
2.  Consider now a three period Binomial model for the asset price to ﬁnd the price of the put option at time 0. To ﬁnd u and d in this model, calibrate your model to the parameters of the underlying  asset such that  the  equivalent martingale measure gives equal probabilities for upward and downward movements.  Again, use R for all calculations and include the R code in your answer.          [4 marks]
3.  Comment on the diferences between the prices calculated in parts 1 and 2.    [3 marks]
For the rest of this assignment assume that the share price is modelled as a geometric Brownian motion, that is,

where Wt  is a standard Brownian Motion under the probability measure P.
4.  Use the Black-Scholes formula to ﬁnd the price of the put option.  All calculations must be done in R and the R code needs to be part of your answer.                  [2 marks]
5.  Use Monte-Carlo Simulations to obtain a numerical approximation of the price of the put option. Provide all R code. Decide on a reasonable number of simulations, and justify your answer. You should aim to make your simulations as eﬃcient as possible without compromising accuracy.                  [6 marks]
6.  Comment on your answers to parts 2, 4 and 5.             [2 marks]
7.  Write an R function to simulate one path of the share price process S in the time interval [0, T] with M subintervals, that is, δt = T/M.  Use the following function template
"MC_share_price" <- function(S0, sigma, mu, T, M) {
...
return(S)
}[4 marks]
8.  Simulate one path of S under the real world probability measure P for M = 100 using your R function MC_share_price. Then calculate the price of the European put option at each time point 0, δt,2δt, . . . T with the share prices S0 , Sδt,..., ST given by the simulated path.  Create two plots:  one for the simulated path of S and one for the path of the put option price p(St, t).     [5 marks]
9.  Comment on the two plots created in part 8.           [3 marks]
[Total 30 marks]
Submission of Assignment
1.  The deadline for submission is
Monday 18 March 2024 at 3:30pm (UK Time).
2.  You must submit by 3:30pm on 18 March 2024 via the assignment link on the Canvas coursepage:
(a)  代 写F71AJ Financial Economics II Coursework 2023/2024R
代做程序编程语言an electronic copy of your report (.docx or .pdf format are accepted).
(b)  The full program listing of your R code included in your report as an ap- pendix. Your report should clearly state which part of your R code you used to answer a speciﬁc result in your report.
(c)  a signed Declaration of Authorship (available via the assignment link on the Canvas course webpage).  The report will not be marked if the declaration is missing.
The ﬁrst submission is ﬁnal.
Project Guidelines
1. Page limit: The assignment counts for 30% of the total mark, so is not intended to be a large project.  Please be as succinct as possible in your answers, while still addressing the questions being asked.  Your report should be at most two pages of A4 (excluding the R code).  The font size should not be less than 11pt.
2.  You must change the line
last_four_digits_of_student_id = 1111
in the R script. for this assignment. The number 1111 must be replaced with the last four digits of your student ID number
3.  Your name and student id should be included on the ﬁrst page of your report.
Working together?Working in groups is encouraged.  It can be very useful to share ideas with other people. However, each report must be your own work and not contain material that has been copied from other students. In particular:Coursework reports must be written up seperately in student’s own words and the R code in their coursework must be their own code.  If some text or code in the coursework has been taken from other sources, these sources must be properly referenced. You must also acknowledge who you have collaborated with.Failure to reference work that has been obtained from other sources or to copy the words and/or code of another student is plagiarism and if detected, the case be dealt with according to the University’s disciplinary procedures.Students must never give hard or soft copies of their coursework reports or code to another student.  Students must always refuse any request from another student for a copy of their report and/or code.Sharing a coursework report and/or code with another student is collusion, and if detected, this will be reported in line with the University’s Plagiarism Policy.Full  details  of the  University’s  plgiarism  policy  guidance  and  further  guidance  are available at https://www.hw.ac.uk/uk/services/academic-registry/academic-integrity/ academic-misconduct.htm.
Late SubmissionsCoursework that  is  submitted  late will  be  dealt with  according to the  University’s policy on late submission of coursework.  Coursework that is submitted late up to a maximum of ﬁve working days will be subject to a 30% deduction from the awarded mark. For example, if the awarded mark for coursework is 6, and it was submitted late, then the mark for that piece of coursework would be 6  0.7 = 4.2.  Any coursework submitted more than ﬁve days late will be awarded a mark of zero.  It is recognised however that in exceptional circumstances (e.g.  illness) a project will legitimately be late.  Students so afected should submit a Mitigating Circumstances application and inform. the course leader and MSc programme director as soon as possible.
Remember to back up your work regularly.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
