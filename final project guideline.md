This is under construction, but fairly well developed

- Form groups of 3 or 4.
- Your group will work from a common data set, but do different projects with it.
- Work together to identify, obtain, clean, and the data and discuss questions and potential data science approaches.  Then you will work separately on the analysis & report.
- You are encouraged to discuss your projects with each other to get ideas and solve problems.  But you are responsible for your own final product.
- Submissions:
  - Oral: 10 minute talk (to be scheduled sometime 12/2-12/12)
  - Written: Due 12/13 (except Bishwas - your stuff is due 12/10 b/c graduating student grades are due earlier)
    - Main - Juypter notebook
      - Text cells for description
      - Code cells for *key* steps only (see scripts below)
      - Graphics
      - Results
      - Code
        - Include short code snippets that do *interesting, key* data science steps in the notebook
        - You will probably have a bunch of code that does necessary but uninteresting stuff.  Don't clutter your "report" with it.  Place it into one or more .py script files and load it from the notebook via "import" or "%load" or "%run" or equivalent.
    - data - ideally the notebook will have code that downloads from internet source.  If impossible, include data file in your google drive folder.
    - scripts - for large/uninteresting blocks of code that will disrupt the notebook
- Requirements
  - Must use at least three supervised learning algorithms and compare performance
    - Don't use a decision tree (use a random forests instead)
  - Must must appropriate cross-validation
  - Must be thoroughly evaluated using appropriate performance metrics (accuracy, confusion matrices, cost matrices/functions, sensitivity, specificity, precision, F_beta, ROC, AUR, etc)
  - Must identify and tune hyperparameters
  - Clearly describe all major decisions you had to make (ex: imputation method, performance metric, feature engineering, etc)
  - Must screen for and correct poorly conditioned data (severe bias, missing data, anomalies such as incorrectly entered data, etc)
  - Provide class frequencies for original data

- Strong preferences (exceptions must receive my explicit approval)
  - categorical target variable(s)
    - because we focused mainly on classifiers in first semester
    - However, many continuous target variables can be converted into categorical variables by binning (ex: high, med, low)
  - high quality graphics



T 12/3/19 - in class
Prtestyon Ward
Nicholas Petela
Bishwas Ghimire


T 12/10/19

