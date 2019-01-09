# Homework Assignment 1
I'd like for each of you to complete the assignment as a jupyter notebook
that you will turn in and that I can then evaluate to see if it works. Please
email to me your notebook by class on Wednesday

**Question 1:** The variance of a sample of $n$ numbers, $Y_1, Y_2, ..., Y_n$,
 is calculated as
$$s^2 = \frac{1}{n-1} \sum_{i=1}^{n} (Y_{i} - \bar{Y})^2$$
where $\bar{Y}$ is the average of the $Y_is$. Write a function that will compute the sample variance of a list of numbers using this formula. Show that your 
function is working properly by using the `statistics` module which has a function
called `statistics.variance()`

**Question 2:** Write a function that will compute the reverse complement of
a DNA sequence which has been stored as a string. If you are unsure of what that
even means take a look at this [wikipedia page](https://en.wikipedia.org/wiki/Complementarity_(molecular_biology)) on DNA complimentarity. **Hint:** while the reversal 
is simple enough, the complimentation might not be. Try using a Dictionary for this.
To show that your function is working reverse complement the sequence "TACAGAT".

**Question 3:** Write a function that will simulate rolling a 6-sided die using
the functions available in the `random` module. Now using your function, perform
an experiment in which you simulate 1000 rolls of your die. What is the average
of those 1000 rolls? Does this result make sense to you? 


