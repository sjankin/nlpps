# Natural Language Processing for Political Science #


#### Workshop on text analytics for political science

[Slava Mikhaylov](s.mikhaylov@essex.ac.uk), Institute for Analytics and Data Science, Department of Computer Science and Electronic Engineering, Department of Government, University of Essex  

### Overview

Data Science is an exciting new area that combines scientific inquiry, statistical knowledge, substantive expertise, and computer programming. One of the main challenges for businesses and policy makers when using big data is to find people with the appropriate skills. Good data science requires experts that combine substantive knowledge with data analytical skills, which makes it a prime area for social scientists with an interest in quantitative methods. This course focuses on one aspect of data science -- generating valuable insights from text using natural language processing.


### Preparing for the course

Before the course you should:

* Download and install [R](https://cran.r-project.org) _and_ [RStudio](http://www.rstudio.com) on your computer.
*	Install Rtools for Windows machines from CRAN (https://cran.r-project.org/bin/windows/Rtools/). If you are using OS X, you will need to to install XCode, available for free from the App Store. This will install a compiler (if you don't have a compiler installed) which will be needed when installing packages from GitHub that require compilation from C++ source code.
* Make sure you have at least R 3.3.3 installed. (The latest version of R, as of 23 May 2017, is 3.4.0.)
* Make sure your packages are up-to-date. From the command line, run `update.packages(ask = FALSE)`
* Install `quanteda` from CRAN. From the `Packages` pane in RStudio, or from the command line: `install.packages("quanteda")`
* Install `readtext` from GitHub, following [these instructions](https://github.com/kbenoit/readtext/blob/master/README.md)
* Try creating and "knitting" an RMarkdown file. You can run the attached [test.Rmd](start/test.Rmd) file, and if builds without error and looks like this [test.html](start/test.html) then you have successfully configured your system. If asked by RStudio, install all needed packages.
* Set up a GitHub account and install necessary packages following discussion in Hadley Wickham's "R Packages" [Git and GitHub chapter](http://r-pkgs.had.co.nz/git.html)



#### Instructions for use of course materials

You have three options for downloading the course material found on this page:  

1.  You can download the materials by clicking on each link.  

2.  You can "clone" repository, using the buttons found to the right side of your browser window as you view this repository.  This is the button labelled "Clone in Desktop".  If you do not have a git client installed on your system, you will need to [get one here](https://git-scm.com/download/gui) and also to make sure that [git is installed](https://git-scm.com/downloads).  This is preferred, since you can refresh your clone as new content gets pushed to the course repository.  (And new material will get actively pushed to the course repository at least once per day as this course takes place.)

3.  Statically, you can choose the button on the right marked "Download zip" which will download the entire repository as a zip file.

You can also subscribe to the repository if you have [a GitHub account](https://github.com), which will send you updates each time new changes are pushed to the repository. 






### Schedule

***

#### __*1: Overview and introduction to data science *__

* [Notes](day1/ME414_day1.pdf)



***

#### __*2: Replicability in social science*__  
R Markdown, R Notebooks, GitHub.
 
* [R Markdown](http://rmarkdown.rstudio.com)
* [R Notebooks](http://rmarkdown.rstudio.com/r_notebooks.html)
* [GitHub and RStudio](Hadley Wickham book “R packages”, chapter “Git and GitHub”: http://r-pkgs.had.co.nz/git.html)


***

#### __*3: Text scaling models*__ 
Naive Bayes, PCA, CA.


* [Notes](module3/text_scaling.pdf)
* [Text scaling](module3/RAP.nb.html)

#### Background
* Laver, Michael, Kenneth Benoit and John Garry. 2003. "Extracting Policy Positions from Political Texts Using Words as Data." _American Political Science Review_ 97: 311-331.
* Lowe, William. 2008. "Understanding Wordscores." _Political Analysis_ 16(4): 356-371.
* Greenacre, M. (2007). _Correspondence Analysis in Practice_, 2nd edition. Appendix A & B.
* Spirling, A. (2012), "U.S. Treaty Making with American Indians: Institutional Change and Relative Power, 1784-1911." _American Journal of Political Science_, 56: 84–97.
* Herzog, A. and K. Benoit (2015), "The most unkindest cuts: Speaker selection and expressed government dissent during economic crisis." _Journal of Politics_, 77(4):1157–1175.



***

#### __*4: Topic models*__ 
LDA, CTM, STM.

* [Notes](module4/topic_models.pdf)
* [Analysing topical structure in EU reports](module4/notebook.nb.html)

#### Background
* David Blei (2012). "Probabilistic topic models." _Communications of the ACM_, 55(4): 77-84.
* Blei, David, Andrew Y. Ng, and Michael I. Jordan (2003). "Latent dirichlet allocation." _Journal of Machine Learning Research_ 3: 993-1022.
* Blei, David (2014) "Build, Compute, Critique, Repeat: Data Analysis with Latent Variable
Models." _Annual Review of Statistics and Its Application_, 1: 203-232.
* Roberts, Stewart, Tingley, Lucas, Leder-Luis, Gadarian, Albertson, and Rand (2014). "Structural topic models for open-ended survey responses." _American Journal of Political Science_, 58(4): 1064-1082.
* Blei, D. and J. Lafferty "Topic Models." In _Text Mining: Classification, clustering, and applications_, A. Srivastava and M. Sahami (eds.), pp 71-94, 2009. Chapter available [here](http://www.cs.princeton.edu/~blei/papers/BleiLafferty2009.pdf).

***

#### __*5: Word embeddings*__
word2vec, text2vec.

* [Notes](module5/word_embedding.pdf)

#### Background
* Mikolov, Tomas et al. "Efficient Estimation of Word Representations in Vector Space."
* Goldberg, Yoav and Omer Levy "word2vec Explained: Deriving Mikolov et al.'s Negative-
Sampling Word-Embedding Method."
* Mikolov, Tomas; Sutskever, Ilya; Chen, Kai; Corrado, Greg S.; Dean, Jeff (2013). "Distributed representations of words and phrases and their compositionality." _Advances in Neural Information Processing Systems_.
* Levy, Omer; Goldberg, Yoav; Dagan, Ido (2015). "Improving Distributional Similarity with Lessons Learned from Word Embeddings." _Transactions of the Association for Computational Linguistics_.
* Pennington et al. "GloVe: Global Vectors for Word Representation."
* Huang et al. "Improving Word Representations via Global Context and Multiple Word Prototypes."

***

#### __*6: Textual patterns and quality assessment*__
keyness, similarity, distance, readability

* [Analysing textual patterns](module6/Lancet.nb.html)

***

#### __*7: Project discussion*__

* Prepare a presentation (using R Markdown) on a project that uses NLP. (Optional, group work.)
* Presentation and discussion of each project.
