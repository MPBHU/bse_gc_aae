# Advanced Applied Econometrics -- Spring 2023

#### Maximilian Blesch, Jonas Jessen, Peter Haan, Renke Schmacker, Hannes Ullrich, Felix Weinhardt

### Course organization

- The course takes place on Fridays (in general), 9:00 - 12:00 at DIW Berlin (Room 2.3.020, Popper
    Room).
- All material can be found here:https://github.com/hannesullrich/BSE_GC_AAE
- PhD: Credit points: 9 ECTS
- Master: Credit points: 6 ECTS
- First session: April 21, 2023
- Final session: July, 14, 2023
- Exam: July, 21, 2023
- Compulsory reading in bold.
- PhD Evaluation: if this course is taken for credits, the final grade will be determined by
    - 3 problem sets (to be completed in groups of max. 2 participants), weighted 1/4 each,
    - a final exam, weighted 1/4.
- Master Evaluation: TBC
    - 2 problem sets out of 3 (to be completed in groups of max. 2 participants)
    - a final exam, weighted

### Course objectives

- Discuss central methods and current advances in applied econometrics.
- Provide insights into empirical strategies (especially, identification) in important papers in the Labour,
    Public & IO literatures.
- Discuss in-depth a variety of econometric frameworks and their core assumptions for causal and
    counterfactual analysis. Give students an understanding of why and when adding structure informed
    by economic theory can be important.
- Establish basic estimation techniques & numerical methods such as simulation and numerical inte-
    gration.




## Lectures

### 1 Introduction (April 21, PH)

- **Organization**
- **Methodology fights** Angrist and Pischke (2010), Frijters (2013), Halle (2022),Heckman (2010), Keane (2010), Rust (2010), Rust (2014), Wolpin (2013)
- **Basics discrete choice** van Soest (1995), Train (2009)

#### References


-   Angrist, Joshua and Jörn Pischke (2010), "The Credibility Revolution in Empirical Economics: How Better Research Design is Taking the Con out of Econometrics,\" *Journal of Economic Perspectives* 24 (2), 3-30.

- Frijters, Paul (2013) “The Limits of Inference Without Theory”, *Economic Record* 89, 429-432.

- **Haile, Phil (2022), Models, Measurement, and the Language of Empirical Economics, slides at https://www.dropbox.com/s/8kwtwn30dyac18s/intro.pdf**

- Heckman, Jim J. (2010), “Building Bridges Between Structural and Program Evaluation Approaches to Evaluating Policy,” *Journal of Economic Literature* 48(2), 356-398.

- Judd, Kenneth L. (1998), *Numerical Methods in Economics*, MIT Press, Cambridge, MA.

- Keane, Michael P. (2010), “Structural vs. Atheoretic Approaches to Econometrics,” Journal of Econometrics156, 3-20.

- Rust, John (2010), “Comments on: ‘Structural vs. atheoretic approaches to econometrics’ by Michael Keane,” *Journal of Econometrics* 156 (1), 21-24.

- Rust, John (2014), “The Limits of Inference with Theory: A Review of Wolpin,” *Journal of Economic Literature* 52 (3), 820-850.

- Train, Kenneth E. (2009), Discrete Choice Methods with Simulation, Cambridge University Press.

- **van Soest, Arthur (1995), “Structural models of family labor supply: A discrete choice approach”, *Journal of Human Resources* 30 (1), 63-88.**

- Wolpin, Kenneth I. (2013), The limits of inference without theory, MIT Press.


### 2 Omitted Variable Bias, Assessing Models, Fisher Inference, Stata (FW 28.4.)

In this session, we will cover different topics of general interest, before turning to more specific methods.
These are (a) sometimes we are just left with the OLS. Can we learn anything from coefficient movements
and the stability of our estimates when including or excluding more controls?, (b) in this course we will not
talk about inference much but here is one powerful method for inference in experiments (that can also be
applied in non-experimental settings) that works without distributional assumptions, its Fisher inference...,
(c) for both topics we will use Stata, so this is being introduced alongside.

- Assessing endogeneity problems in OLS through coefficient movements
- Fisher inference
- Introduction to Stata software


#### References


- Oster, Emily, (2019), Unobservable Selection and Coefficient Stability: Theory and Evidence, **Journal of Business & Economic Statistics, 37**(2).

- Altonji, J. G., Elder, T. E., & Taber, C. R. (2005). Selection on Observed and Unobserved Variables: Assessing the Effectiveness of Catholic Schools. Journal of Political Economy, 113(1), 151--184.

- Alwyn Young, Channeling Fisher: Randomization Tests and the Statistical Insignificance of Seemingly Significant Experimental Results, **The Quarterly Journal of Economics, 134**(2),May 2019.

- **Scott Cunningham (2018), Causal Inference: The Mixtape, Chapter “Randomization In-
ference”**,https://mixtape.scunning.com/04-potential_outcomes#randomization-inference.


### 3 Panel Data/Fixed Effects (May 5, RS)

- Fixed effects and first differences: identification and interpretation
- Application to panel settings and beyond

#### References


- Raj Chetty, Adam Looney, and Kory Kroft (2009), Salience and Taxation: Theory and Evidence, *American Economic Review, 99* (4), 1145-1177.

- **Scott Cunningham (2018), Causal Inference: The Mixtape, Chapter “Panel Data”,** https://mixtape.scunning.com/08-panel_data.

- Jens Hainmueller and Dominik Hangartner (2019), Does Direct Democracy Hurt Immigrant Minorities? Evidence from Naturalization Decisions in Switzerland, *American Journal of Political Science, 63* (3), 530-547.


### 4 Difference-in-difference (May 12 and 19, RS)

- Canonical DID model
- Event study framework, two-way fixed-effects
- Potential issues: Staggered treatment, parallel trends, inference

#### References

- Joshua D. Angrist and J ̈orn-Steffen Pischke (2008), Mostly Harmless Econometrics: An Empiricist’s Companion, Chapter 5.2, Differences-in-differences: Pre and Post, Treatment and Control.

- Martha J. Bailey and Andrew Goodman-Bacon (2015), The War on Poverty’s Experiment in Public Medicine: Community Health Centers and the Mortality of Older Americans, *American Economic Review, 105* (3): 1067ˆa€“1104.

- Marianne Bertrand, Esther Duflo, Sundhil Mullainathan (2004), How much should we trust differences-in-differences estimates? *Quarterly Journal of Economics, 119* (1):249-275.

- **Scott Cunningham (2018), Causal Inference: The Mixtape, Chapter “Difference-in-Differences”**,https://mixtape.scunning.com/09-difference_in_differences.

- Jonathan Roth, Pedro H. C. Sant’Anna, Alyssa Bilinski, John Poe (2022), “What’s Trending inDifference-in-Differences? A Synthesis of the Recent Econometrics Literature,”https://www.jonathandroth.com/assets/files/DiD_Review_Paper.pdf


### 5 IV (May 26 and June 2, FW)

- Introduction: The Wald estimator, IV with homogeneous treatment effects, assessment of instruments
- LATE: can we learn anything when treatment effects are heterogeneous?
- Stata implementations
- Essential references in bold

#### References

- **Cunningham, Scott (2018), Causal Inference: The Mixtape, Chapter “Instrumental Variables”**,https://mixtape.scunning.com/07-instrumental_variables.

- **Imbens, Guido W. 2010. “Better LATE Than Nothing: Some Comments on Deaton (2009) and Heckman and Urzua (2009).” *Journal of Economic Literature, 48* (2): 399- 423.**

- **Marbach, M., & Hangartner, D. (2020). Profiling Compliers and Noncompliers for Instrumental Variable Analysis. *Political Analysis, 28*(3).**

- **Angrist, Joshua, et al. “Multiple Experiments for the Causal Link between the Quantity and Quality of Children.” *Journal of Labor Economics, 28*(4), 2010.**

- Angrist, Joshua D., and William N. Evans. “Children and Their Parents’ Labor Supply: Evidence from Exogenous Variation in Family Size.” *The American Economic Review, 88* (3), 1998

- Acemoglu, Daron, Simon Johnson, and James A. Robinson. 2001. “The Colonial Origins of Comparative Development: An Empirical Investigation.” *American Economic Review, 91* (5): 1369-1401.

- Lundborg, Petter, Erik Plug, and Astrid W ̈urtz Rasmussen. 2017. “Can Women Have Children and a Career? IV Evidence from IVF Treatments.” *American Economic Review, 107* (6): 1611-37.
