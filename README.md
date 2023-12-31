# BankMkt  
# THE BANK MARKETING INSIGHT  
The dataset was generated by Paulo Cortez and Sérgio Moro, they are PhDs in Data Mining, of Minho University and Lisbon Portugal respectively in 2014. Data related to remote direct marketing campaigns (via telephone) of a Portuguese banking institution, which is available in the link at https://archive.ics.uci.edu/ml/datasets/bank+marketing. There are four datasets available in the link; however, there is solely the dataset names bank-full.csv dataset would be utilized in the project. [1] 
There is total 45211 observations in this dataset, which has been through 17 variables that includes demographic information of respondents and their engagement information to the bank. Regarding to the variable information and encoding, following is the explanation of 17 variables in the dataset:    
•	Age: the numeric variable which indicates the age of customers  
•	Job: indicates the clients’ type of job, with categorical as: admin, blue collar, entrepreneur, housemaid, management, retired, self-employed, services, student, technician, unemployed, and unknown.  
•	Marital: shows the marital status of customers, with categorical as: divorced, married, single, unknown. The divorced option means divorced or widowed.  
•	Education: is the education level of clients, which is categorized four options: primary, secondary, tertiary, and unknown.  
•	Default: this is the answer for question: “Does the client have credit in default?” with three answers: no, yes, unknown.  
•	Housing: this is the data for the question: “Does the client have housing loan?” with three answers: no, yes, unknown.  
•	Loan: with the question “Does the client have personal loan?” and three options: yes, no, unknown.  
# The following are variables which relate to the last contact of the current marketing campaign:  
•	Contact: it shows the contact communication type with three options: cellular, telephone, and unknown.  
•	Day: indicates the date of when receiving the call which varies from day 1 to day 31.  
•	Month: shows the month that the call approaches which has 12 options with 12 months, varies from January to December.  
•	Duration: it shows the duration of this last call, in seconds as numeric.  
•	Campaign: is the number of contacts performed during the marketing campaign and for this client, shown by numeric.  
•	Pdays: the number of days that have elapsed since the client was last contacted as part of a previous marketing campaign. A value of 999 indicates that the client was not contacted in any previous campaigns.  
•	Previous: the total number of marketing contacts made with this client prior to this campaign with numeric type.  
•	Poutcome: the result of the previous marketing campaign for this client, with four options: failure, success, other, unknown.  
•	Y: the result of question “Has the client subscribed a term deposit?”, with two options: yes or no.  

# R packages for data analysis and machine learning  
The document contains a list of R packages [12] and libraries used for data analysis and machine learning, including mice, dplyr, ggplot2, plotrix, coefplot, psych, caret, rpart, rattle, rpart.plot, RColorBrewer, party, partykit, pROC, randomForest, and gbm.  
•	The "mice" package, developed by van Buuren and Groothuis-Oudshoorn (2011), provides multiple imputation methods for missing data. It offers a flexible and easy-to-use tool for handling missing values and enables researchers to perform reliable analyses without losing a significant amount of data [13].  
•	The "dplyr" package, developed by Wickham et al. (2021), is a grammar of data manipulation that provides a set of tools for efficiently manipulating datasets. It offers a fast and easy way to perform common data manipulation tasks such as filtering, selecting, and summarizing data [14].  
•	The "ggplot2" package, developed by Wickham (2016), is a data visualization package that provides a powerful and flexible system for creating graphics. It allows users to easily create complex plots with a minimal amount of code, making it a popular choice for visualizing data in research [15].  
•	The "plotrix" package, developed by Lemon (2006), provides a range of specialized plots and charts that are not available in base R. It includes functions for creating polar plots, 3D scatter plots, and pie charts, among others [16].  
•	The "coefplot" package, developed by Landerer (2021), provides a convenient way to visualize regression coefficients and other model parameters. It enables researchers to compare multiple models and assess their relative importance [17].  
•	The "psych" package, developed by Revelle (2021), provides a wide range of functions for data analysis and visualization. It includes functions for descriptive statistics, correlation analysis, factor analysis, and reliability analysis, among others [18].  
•	The "caret" package, developed by Kuhn (2021), provides a streamlined interface for data splitting, pre-processing, and model training. It is designed to simplify the process of building and evaluating predictive models in R [19].  
•	The "rpart" package, developed by Therneau et al. (2021), provides a popular implementation of decision trees in R. It is widely used in data mining and machine learning tasks, and provides a flexible and interpretable approach to modeling complex relationships in data [20].  
•	The "rattle" package, developed by Williams and Liaw (2021), provides a graphical user interface for building and evaluating decision trees in R. It includes a range of interactive tools for exploring and visualizing data, making it a popular choice for data mining tasks [21].  
•	The "rpart.plot" package, developed by Milborrow (2019), provides an enhanced plotting function for decision trees created using the rpart package. It offers a range of customization options and enables researchers to create high-quality plots for presentations and publications [22].  
•	The "RColorBrewer" package, developed by Neuwirth (2014), provides a range of color palettes for use in data visualization. It includes a range of color schemes designed to be perceptually uniform and easy to interpret [23].  
•	The "party" package, developed by Hothorn et al. (2021), provides an alternative implementation of decision trees in R. It offers a more flexible and powerful approach to modeling complex relationships in data and includes a range of advanced features such as conditional inference trees and model-based recursive partitioning [24].  
•	The "partykit" package, developed by Hothorn et al. (2021), provides a set of tools for working with decision tree objects created using the party package. It includes functions for converting rpart objects to BinaryTree objects, and for visualizing decision trees using ggplot2 [25].  
•	The "pROC" package, developed by Robin et al. (2011), provides functions for creating and evaluating receiver operating characteristic (ROC) curves in R. It is widely used in medical research and other similar fields [26].  

# References  
[1] Cortez, P. & Moro, S. (2014). Bank Marketing Data Set. UCI Machine Learning Repository. University of California, Irvine, School of Information and Computer Sciences. Retrieved from https://archive.ics.uci.edu/ml/datasets/bank+marketing.    
[12] Jeni LA, Cohn JF, De La Torre F. (2013). Facing Imbalanced Data Recommendations for the Use of Performance Metrics. Int Conf Affect Comput Intell Interact Workshops. DOI: 10.1109/ACII.2013.47.  
[13] R Core Team (2021). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. URL https://www.R-project.org/   
[14] Buuren, S. van, Groothuis-Oudshoorn, K. (2011). mice: Multivariate Imputation by Chained Equations in R. Journal of Statistical Software, 45(3), 1-67. URL http://www.jstatsoft.org/v45/i03/  
[15] Wickham, H. (2016). ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York. ISBN 978-3-319-24277-4, https://ggplot2.tidyverse.org/  
[16] Harrell Jr, F. E. (2018). Hmisc: Harrell Miscellaneous. R package version 4.2-0. https://CRAN.R-project.org/package=Hmisc    
[17] Lemon, J. (2006). Plotrix: A package in the red light district of R. R-News, 6(4), 8-12. URL http://CRAN.R-project.org/doc/Rnews/    
[18] Lander, J. P. (2021). coefplot: Plots Coefficients from Fitted Models. R package version 1.2.0. https://CRAN.R-project.org/package=coefplot    
[19] Revelle, W. (2021). psych: Procedures for Psychological, Psychometric, and Personality Research. R package version 2.2.4. https://CRAN.R-project.org/package=psych  
[20] Kuhn, M. (2021). caret: Classification and Regression Training. R package version 6.0-90. https://CRAN.R-project.org/package=caret  
[21] Therneau, T. (2021). rpart: Recursive Partitioning and Regression Trees. R package version 4.1-15. https://CRAN.R-project.org/package=rpart  
[22] Williams, G., & Martinez, N. (2017). rattle: Graphical User Interface for Data Science in R. Journal of Open Research Software, 5(1), 19. https://doi.org/10.5334/jors.151  
[23] Milborrow, S. (2019). rpart.plot: Plot 'rpart' Models: An Enhanced Version of 'plot.rpart'. R package version 3.1.2. https://CRAN.R-project.org/package=rpart.plot  
[24] Neuwirth, E. (2014). RColorBrewer: ColorBrewer Palettes. R package version 1.1-2. https://CRAN.R-project.org/package=RColorBrewer  
[25] Hothorn, T., Hornik, K., & Zeileis, A. (2006). Unbiased Recursive Partitioning: A Conditional Inference Framework. Journal of Computational and Graphical Statistics, 15(3), 651-674. https://doi.org/10.1198/106186006X133933  
[26] Hothorn, T., Zeileis, A., Hornik, K. (2021). partykit: A Toolkit for Recursive Partytioning. R package version 1.2-7. https://CRAN.R-project.org/package=partykit  
