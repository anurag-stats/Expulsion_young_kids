# Expulsion_young_kids

Goal: Analyze the reasons for expulsion rates in young kids aged 3-6 years old based on standard test scores taken by teachers and young kids. The major indicators in consideration are test scores evaluating attributes like behavior, cognitive communication, language and PERM scores. The data was based on a simulated experiment where the simulation was run by a researcher (my client) in the field and was stratified by socio-economic status.

This was a project from when I worked at Statistical Consulting Service at the Ohio State University. All of the statistical and data analysis was done by me and I took into consideration the regular feedback from my client.

This was a project from when I worked at Statistical Consulting Service at the Ohio State University. All of the statistical and data analysis was done by me and I took into consideration the regular feedback from my client.

As mentioned before there were 4 major sttributes, based on which comparisons were analyzed:

1. Cognitive Communication
2. Language
3. Behavior
4. PERM Scores
   

The standardized test scores, within each category, were hypothesized to be collinear and did in fact seem so based on correlation analysis and linear regression, in order to analyze these factors factor analysis was used, which is the standard in the field and then additional comparisons were made.

We found significant differences in groups based on Language and PERM scores.

The secondary goal was that of testing heirarchical models, i.e. whether adding behavior to a model that contains Language variable explains significantly additional variability, we used ChiSquared tests for nested models (LRT) to test this. A better solution was recommended to incoporate and test different variables using a Bayesian model selection approach, which will be considered after running an actual experiment. This project's goal was to secure funding for a research proposal.

There is also an R-script which was rendered using the Rmd file.