Ex8
===

Data Mining - Theerayut Sueverachai 1362467 -

The codes are divided into parts: Pre-processing Data, Visualisation, Topic Models, and Clustering. Please note that it is better to install all packages listed in "Install Reuters" section

••••For first part: Pre-processing Data••••

  • Line number 37-62 show the standard function used for pre-processing data without applying to any variables. The purpose of these lines are just to quicky see the results for each function.
  
  • Line number 65-79 are to show how to apply each function to a variable (in this case, varibale named tm) by using "tm_map" function.
  
  • Line number 82 is another very useful function ("TermDocumentMatrix") to apply any pre-processing techniques to dataset. This function is preferred and used for this exercise. Please note that line number 82-86 corresponds to one "TermDocumentMatrix" function.
  
  • Line number 87 is used to display the words whose frequencies are between 5000 and 10000 by using "findFreqTerms" function
  
••••For second part: Visualisation••••

  • It can be simply run from line number 98-103 to display word cloud. If there is an error - try run line number 93-94
  
••••For third part: Topic Models••••

  • Line number 108-119 are used to run LDA method to implement topic model. Please note that it might take time to finish executing
  
  • Line number 121-124 are used to run CTM method to implement topic model. Please note that it might take time to finish executing
  
••••For fourth part: Clustering••••

  • Line number 130-134 are used to run k-mean clustering. Please note that it takes very long to finish executing (around 15-30 minutes)
  
  • Line number 136-140 are used to run Hierarchical Agglomerative Clustering (HAC)
  
  • Line number 142-144 are used to run DBSCAN

