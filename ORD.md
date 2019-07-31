**What Can We Do ?** in genuTilities **ORD**

|Method	|Input	|Description |
|:-|:-|:-|
|PCA	|RawData (X,Y)	|PCA creates a new set of orthogonal variables that contain the same information as the original set. It rotates the axes of variation to give a new set of orthogonal axes, ordered so that they summarize decreasing proportions of the variation.|
|CA	|RawData (X,Y)	|CA or reciprocal averaging, finds (like PCA) a set of synthetic variables that summarise the original set. The underlying model assumes chi-squared dissimilarities among records (cases).|
|RDA	|RawData (X,Y)	|RDA is similar to canonical correlation analysis but allows the user to derive a specified number of synthetic variables from one set of (independent) variables that explain as much variance as possible in another (independent) set. It is a multivariate analogue of regression.|
|CCA	|RawData (X,Y)	|CCA for summarising the joint variation in two sets of variables (like redundancy analysis); combination of correspondence analysis and multivariate regression analysis. The underlying model assumes chisquared dissimilarities among records (cases).|
|PCoA	|Distance Matrix (X)	|PCoA Multidimensional scaling comprises various algorithms to determine a set of synthetic variables that best represent the pairwise distances between records. The original method is principal coordinates analysis (PCoA; based on PCA).|
|DCA	|RawData (X,Y)	|DCA is a multivariate statistical technique widely used by ecologists to find the main factors or gradients in large, species-rich but usually sparse data matrices that typify ecological community data.|

Ordination
------------
[Ordination - wiki](https://en.wikipedia.org/wiki/Ordination_(statistics)) **Ordination** or **gradient analysis**, in [Multivariate](https://en.wikipedia.org/wiki/Multivariate_statistics) [Analysis](https://en.wikipedia.org/wiki/Multivariate_analysis), is a method complementary to **data clustering**, and used mainly in exploratory data analysis (rather than in hypothesis testing). Ordination orders objects that are characterized by values on **multiple** variables (multivariate objects) so that similar objects are near each other and dissimilar objects are farther from each other. Such relationships between the objects, on each of several axes (one for each variable), are then characterized numerically and or graphically. Many ordination techniques exist, including principal components analysis (**PCA**), non-metric multidimensional scaling (**NMDS**), correspondence analysis (**CA**) and its derivatives (detrended CA (**DCA**), canonical CA (**CCA**)), **BrayCurtis** ordination, and redundancy analysis (**RDA**), among others.

*So, Ordination is one kinds of **Multivariate Statistical**. Here is the Common Multivariate Statistical Tools:*

|Technique|Aims|Modal|AnyType|Input|
|:-|:-|:-|:-|:-|
|PCA|Exploratory|Linear||RawData|
|CA|Exploratory|Unimodal||RawData|
|DCA|Exploratory|Unimodal||RawData|
|PCoA|Exploratory|AnyDM|Distance Metric|Distance Matrix|
|NMDS|Exploratory|AnyDM|Distance Metric|Distance Matrix|
|Hierarchical Clustering|Exploratory|AnyDM|Distance Metric|Distance Matrix|
|K-Means Clustering|Exploratory|AnyDM|Distance Metric|Distance Matrix|
|CCorA|Interpretive|Linear||RawData|
|CIA|Interpretive|AnyORD|Ordination|Ordination|
|PA|Interpretive|Any||Any|
|RDA|Interpretive|Linear||RawData|
|dbRDA|Interpretive|AnyDM|Distance Metric|Distance Matrix|
|CCA|Interpretive|Unimodal||RawData|
|PRC|Interpretive|Linear||RawData|
|GLM|Interpretive|AnyLF|Link Function|RawData|
|Mantel Test|Interpretive|Any||Distance Matrix|
|ANOSIM|Interpretive|Any||Distance Matrix|
|PERMANOVA|Interpretive|Any||Distance Matrix|
|DFA|Discriminatory|Linear||RawData|
|LDA|Discriminatory|Linear||RawData|
|PLSDA|Discriminatory|Linear||RawData|
|OPLSDA|Discriminatory|Linear||RawData|
|SVM|Discriminatory|AnyKF|Kernel function|RawData|
|RF|Discriminatory|Any||RawData|

Multivariate Analysis
------------
Multivariate statistics is a subdivision of statistics encompassing the simultaneous observation and analysis of more than one outcome variable. The application of multivariate statistics is multivariate analysis. Multivariate statistics concerns understanding the different aims and background of each of the different forms of multivariate analysis, and how they relate to each other. The practical application of multivariate statistics to a particular problem may involve several types of univariate and multivariate analyses in order to understand the relationships between variables and their relevance to the problem being studied.

In addition, multivariate statistics is concerned with multivariate probability distributions, in terms of both how these can be used to represent the distributions of observed data.

how they can be used as part of statistical inference, particularly where several different quantities are of interest to the same analysis. Certain types of problems involving multivariate data, for example simple linear regression and multiple regression, are not usually considered to be special cases of multivariate statistics because the analysis is dealt with by considering the (univariate) conditional distribution of a single outcome variable given the other variables.

Multivariate analysis(MVA) is based on the statistical principle of multivariate statistics, which involves observation and analysis of more than one statistical outcome variable at a time. In design and analysis, the technique is used to perform trade studies across multiple dimensions while taking into account the effects of all variables on the responses of interest.

Uses for multivariate analysis include:

design for capability (also known as capability-based design)
inverse design, where any variable can be treated as an independent variable
Analysis of Alternatives (AoA), the selection of concepts to fulfil a customer need
analysis of concepts with respect to changing scenarios
identification of critical design-drivers and correlations across hierarchical levels.
Multivariate analysis can be complicated by the desire to include physics-based analysis to calculate the effects of variables for a hierarchical “systemofsystems”. Often, studies that wish to use multivariate analysis are stalled by the dimensionality of the problem. These concerns are often eased through the use of surrogate models, highly accurate approximations of the physicsbased code. Since surrogate models take the form of an equation, they can be evaluated very quickly. This becomes an enabler for largescale MVA studies: while a Monte Carlo simulation across the design space is difficult with physics-based codes, it becomes trivial when evaluating surrogate models, which often take the form of responsesurface equations.
