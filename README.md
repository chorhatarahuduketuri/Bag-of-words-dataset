# Bag of Words Dataset Analysis
https://archive.ics.uci.edu/ml/datasets/bag+of+words

>Dua, D. and Karra Taniskidou, E. (2017). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science. 

I would like to be able to use at least a level of basic NLP in my projects, so it makes sense to learn and practice how to, and it makes sense to begin with a fairly straightforward and common dataset, so that I can focus on the techniques, tools, and methodology. 

In addition to wanting to learn about this cool thing called NLP, I have specific abilities I want, which is useful for coming up with my own projects. Specifically, I want to be able to characterise pieces of text into different classes, such that I can: 
1. Group different pieces of text into different classes, which I can later look at and identify/figure out what they are.
2. Be able to use this knowledge later classify new pieces of text based on what I already know (or determine if they are a new class).

Each of those is a project unto itself so for now I'll start with 1, and that's what this analysis will be. 

To that end, I've selected the Bag of Words dataset from the UCI repository (renound for it's neat and tidy datasets), which is a popular first datset for this, contains five distinct sub-sets of text data to use as sub-sets, or to find sub-sets inside of (though I'm only using one of them - the infamous enron dataset, since the other two are both far too large for either github or the machines I have available to me). 

The enron dataset as presented here is heavily processed, anonymised, and reduced. I will focus on the enron dataset as it is presented here, and see what I can find. 