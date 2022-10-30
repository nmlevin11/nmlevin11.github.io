One important part of building a regression model is determining what variables to use in a regression model. Three resources that I read to inform my plan going forward for selecting variables for a model are listed at the end of this blog post. One key takeaway I found from those resources is that variable selection can be complicated and subjective, and there is no one-size-fits-all answer for it.

The steps, thoughts, and ideas I plan to take with me for variable selection in the future are:  

1. Talk with a subject matter expert (SME) if one is available. Get their explanations on what the variables are and how they may relate to the response variable of interest and each other. Understand what their goals are. Is prediction an important use for their model or are there other priorities? Are there clearly established relationships between any of the predictors and the response that can allow us to skip those variables in the selection process and just include them in the final model?

2. Start with exploratory data analysis (EDA.) Get a feel for trends in graphs and simple number summaries. Possibly identify variables that could benefit from a transformation to make a more linear trend of it with the response, Look for highly correlated variables that could create an unstable model.

3. Make any transformations that come to light as appropriate based on the EDA, experience, or conversations with the SME.

4. Pick a couple of methods that make sense for the situation, and consider not just sticking with the classic forward, backward, or best subset selection. Look at penalized options like LASSO as well. My preference from the stepwise options is backward selection. My preference of the penalized options is the LASSO, as it is one I have at least a small amount of experience with. Among the tree-based methods and others more commonly used for big data sets with lots of predictors, I will for the time-being need to rely on the recommendations from coursework and try multiple options to see what provides the best results in different situations.

5. Take a good look at the best performing sets of variables and do some interpretation of what those combinations are saying. Does one make more sense logically? Is one more cost effective to get measurements and data for in future data sets? Given all of the information gathered from experts, experience, and the variable selection process what makes sense to proceed with?

In summary, my main take away from delving a little into variable selection is to be more thoughtful and conscious of every step and decision along the way. Think critically when I need to, expansively when I need to, and above all else, understand what I'm doing and why all along the way.

Resources that helped me question whether I know anything about variable selection at all:
(https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5969114/)
[https://www.biostat.jhsph.edu/~iruczins/teaching/jf/ch10.pdf]
https://link.springer.com/content/pdf/10.1057/jt.2009.26.pdf
