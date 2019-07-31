# genuTilities
Some helpful scripts

## Statistics in R
### Ordination
[Ordination - wiki](https://en.wikipedia.org/wiki/Ordination_(statistics)) **Ordination** or **gradient analysis**, in [Multivariate](https://en.wikipedia.org/wiki/Multivariate_statistics) [Analysis](https://en.wikipedia.org/wiki/Multivariate_analysis), is a method complementary to **data clustering**, and used mainly in exploratory data analysis (rather than in hypothesis testing). Ordination orders objects that are characterized by values on **multiple** variables (multivariate objects) so that similar objects are near each other and dissimilar objects are farther from each other. Such relationships between the objects, on each of several axes (one for each variable), are then characterized numerically and or graphically. Many ordination techniques exist, including principal components analysis (**PCA**), non-metric multidimensional scaling (**NMDS**), correspondence analysis (**CA**) and its derivatives (detrended CA (**DCA**), canonical CA (**CCA**)), **BrayCurtis** ordination, and redundancy analysis (**RDA**), among others.

**What Can We Do ?** in genuTilities [ORD](https://github.com/Genut/genuTilities/blob/master/ORD.md)

|Method	|Input	|Description |
|:-|:-|:-|
|PCA	|RawData (X,Y)	|PCA creates a new set of orthogonal variables that contain the same information as the original set. It rotates the axes of variation to give a new set of orthogonal axes, ordered so that they summarize decreasing proportions of the variation.|
|CA	|RawData (X,Y)	|CA or reciprocal averaging, finds (like PCA) a set of synthetic variables that summarise the original set. The underlying model assumes chi-squared dissimilarities among records (cases).|
|RDA	|RawData (X,Y)	|RDA is similar to canonical correlation analysis but allows the user to derive a specified number of synthetic variables from one set of (independent) variables that explain as much variance as possible in another (independent) set. It is a multivariate analogue of regression.|
|CCA	|RawData (X,Y)	|CCA for summarising the joint variation in two sets of variables (like redundancy analysis); combination of correspondence analysis and multivariate regression analysis. The underlying model assumes chisquared dissimilarities among records (cases).|
|PCoA	|Distance Matrix (X)	|PCoA Multidimensional scaling comprises various algorithms to determine a set of synthetic variables that best represent the pairwise distances between records. The original method is principal coordinates analysis (PCoA; based on PCA).|
|DCA	|RawData (X,Y)	|DCA is a multivariate statistical technique widely used by ecologists to find the main factors or gradients in large, species-rich but usually sparse data matrices that typify ecological community data.|

.......... to be continue .........

Contact
------------
Contact me if you have any problem.

- Author:   Kidult X
- Email:    <xjtbiol20@gmail.com>
