# R Mastery Journey

Welcome to R Mastery Journey, a comprehensive, day-by-day structured course designed to help you master R programming from absolute beginner to advanced practitioner. This repository contains detailed notes, code examples, exercises, and projects for a complete learning experience.

---

## Table of Contents

1. [Course Overview](#course-overview)
2. [Learning Objectives](#learning-objectives)
3. [Target Audience](#target-audience)
4. [Prerequisites](#prerequisites)
5. [Course Structure](#course-structure)
6. [Daily Learning Format](#daily-learning-format)
7. [Week-by-Week Breakdown](#week-by-week-breakdown)
8. [Installation Guide](#installation-guide)
9. [How to Use This Repository](#how-to-use-this-repository)
10. [Resources and References](#resources-and-references)
11. [Contributing](#contributing)
12. [License](#license)

---

## Course Overview

R Mastery Journey is a 90-day intensive program that takes you from complete beginner to proficient R programmer. The course is structured to provide daily learning objectives, hands-on practice, and real-world projects that build upon each other progressively.

### What Makes This Course Different

- **Structured Daily Content**: Each day has a specific focus with clear objectives
- **Hands-On Practice**: Every lesson includes practical exercises and code examples
- **Progressive Learning**: Concepts build on previous lessons systematically
- **Real-World Projects**: Apply your skills to actual data analysis scenarios
- **Reproducible Research**: Learn to create R Markdown documents and reports
- **Industry-Relevant Skills**: Focus on tools and techniques used in professional settings

---

## Learning Objectives

By completing this course, you will be able to:

### Fundamental Skills
- Understand R programming syntax and fundamental concepts
- Work with different data types: numeric, character, logical, factor
- Master data structures: vectors, matrices, data frames, lists
- Write clean, efficient, and well-documented R code
- Understand control flow: conditional statements and loops
- Create and use custom functions with proper error handling

### Data Manipulation
- Import and export data from various file formats (CSV, Excel, JSON, databases)
- Clean and preprocess messy datasets
- Transform and reshape data using tidyverse packages
- Handle missing values and outliers effectively
- Merge, join, and aggregate datasets
- Perform string manipulation and regular expressions

### Data Analysis
- Conduct exploratory data analysis (EDA)
- Calculate descriptive statistics and summary measures
- Perform hypothesis testing and statistical inference
- Build linear and logistic regression models
- Understand correlation and covariance analysis
- Apply time series analysis techniques

### Data Visualization
- Create publication-quality plots using ggplot2
- Design interactive visualizations with plotly
- Build dashboards using Shiny
- Customize themes, colors, and aesthetics
- Create maps and spatial visualizations
- Develop effective data storytelling techniques

### Advanced Topics
- Write efficient code with apply family functions
- Understand functional programming in R
- Work with dates and times using lubridate
- Perform text mining and sentiment analysis
- Build machine learning models using caret and tidymodels
- Create reproducible reports with R Markdown

---

## Target Audience

This course is designed for:

### Complete Beginners
- No prior programming experience required
- Step-by-step guidance through R fundamentals
- Gentle learning curve with extensive examples

### Students
- Learning data analysis or statistics for coursework
- Preparing for research projects or thesis work
- Building foundational skills for advanced studies

### Professionals
- Transitioning into data science or analytics roles
- Enhancing existing skill set with R programming
- Seeking to automate data workflows and reporting

### Researchers
- Academic researchers needing statistical analysis tools
- Scientists working with experimental or observational data
- Anyone requiring reproducible research methods

---

## Prerequisites

### Required
- A computer with Windows, macOS, or Linux
- Internet connection for installing packages
- Basic computer literacy (file management, using applications)
- Commitment to daily practice (1-2 hours per day recommended)

### Recommended (Not Required)
- Basic understanding of statistics (helpful but not mandatory)
- Familiarity with spreadsheet software like Excel
- Some exposure to programming concepts (variables, functions)

### Software Requirements
- R (version 4.0 or higher)
- RStudio Desktop (latest version)
- Git (for version control, optional but recommended)
- Text editor for viewing markdown files

---

## Course Structure

The course is organized into 13 weeks, with each week focusing on a major topic area. The structure progressively builds your skills from foundational concepts to advanced applications.

### Week 1-2: R Fundamentals (Days 1-14)
Introduction to R, RStudio, basic syntax, data types, and structures.

### Week 3-4: Data Manipulation (Days 15-28)
Working with real datasets, data cleaning, transformation using dplyr and tidyr.

### Week 5-6: Data Visualization (Days 29-42)
Creating plots with base R and ggplot2, customization, and best practices.

### Week 7-8: Statistical Analysis (Days 43-56)
Descriptive statistics, hypothesis testing, correlation, regression analysis.

### Week 9-10: Advanced Data Wrangling (Days 57-70)
String manipulation, date-time handling, working with complex data structures.

### Week 11-12: Machine Learning Basics (Days 71-84)
Introduction to predictive modeling, classification, clustering, model evaluation.

### Week 13: Capstone Project (Days 85-90)
Comprehensive real-world project incorporating all learned skills.

---

## Daily Learning Format

Each day follows a consistent structure to maximize learning efficiency:

### 1. Learning Agenda
Clear objectives for what you will learn and accomplish that day.

### 2. Conceptual Overview
Detailed explanation of the topic with theoretical background where necessary.

### 3. Code Examples
Practical, runnable code demonstrating each concept with extensive comments.

### 4. Hands-On Exercises
Practice problems ranging from simple to challenging to reinforce learning.

### 5. Real-World Application
How the day's concepts apply to actual data analysis scenarios.

### 6. Summary and Key Takeaways
Review of important points and preparation for the next day.

### 7. Additional Resources
Links to documentation, articles, and videos for deeper understanding.

---

## Week-by-Week Breakdown

### Week 1: Introduction to R and RStudio

**Day 1: Getting Started with R**
- Installing R and RStudio
- Understanding the RStudio interface
- Writing your first R script
- Using the console vs script editor
- Saving and organizing your work

**Day 2: Basic R Syntax and Operations**
- Arithmetic operations and mathematical functions
- Variable assignment and naming conventions
- Understanding R's case sensitivity
- Using comments effectively
- Basic error messages and debugging

**Day 3: Vectors and Basic Data Types**
- Creating vectors with c() function
- Numeric, character, and logical vectors
- Vector operations and recycling rule
- Accessing vector elements
- Vector functions: length(), sum(), mean()

**Day 4: Working with Vectors**
- Generating sequences with seq() and rep()
- Vector indexing and subsetting
- Logical indexing
- Named vectors
- Modifying vector elements

**Day 5: Matrices**
- Creating matrices
- Matrix operations: transpose, multiplication
- Accessing matrix elements
- Row and column operations
- Matrix functions: dim(), nrow(), ncol()

**Day 6: Data Frames Introduction**
- Creating data frames
- Understanding data frame structure
- Accessing columns and rows
- Adding and removing columns
- Basic data frame operations

**Day 7: Lists and Factors**
- Creating and working with lists
- Nested lists
- Factor variables and levels
- Ordered vs unordered factors
- Converting between data types

---

### Week 2: R Programming Fundamentals

**Day 8: Conditional Statements**
- if, else, and else if statements
- Nested conditionals
- ifelse() function
- switch() function
- Logical operators: AND, OR, NOT

**Day 9: Loops**
- for loops
- while loops
- repeat loops
- break and next statements
- Loop efficiency considerations

**Day 10: Writing Functions**
- Function syntax and structure
- Arguments and default values
- Return values
- Function scope and environments
- Best practices for function design

**Day 11: Advanced Functions**
- Anonymous functions
- Functions as arguments
- Returning multiple values
- Error handling: stop(), warning(), message()
- Function documentation

**Day 12: Apply Family Functions**
- apply() for matrices
- lapply() and sapply() for lists
- tapply() for grouped operations
- mapply() for multiple arguments
- When to use apply vs loops

**Day 13: Working with Packages**
- Installing packages from CRAN
- Loading packages with library()
- Understanding package dependencies
- Package management best practices
- Creating your first package structure

**Day 14: R Projects and Reproducibility**
- Creating RStudio projects
- Project organization best practices
- Relative vs absolute paths
- Using here package
- Version control basics with Git

---

### Week 3: Data Import and Export

**Day 15: Reading CSV Files**
- read.csv() vs read.table()
- Handling headers and separators
- Dealing with missing values
- Setting column types
- Large file considerations

**Day 16: Reading Excel Files**
- Using readxl package
- Reading multiple sheets
- Specifying cell ranges
- Handling formatted Excel data
- Writing to Excel with writexl

**Day 17: Working with Text Files**
- readLines() and writeLines()
- Reading fixed-width files
- Parsing custom text formats
- Handling different encodings
- Large text file strategies

**Day 18: Database Connections**
- Introduction to DBI package
- Connecting to SQLite databases
- Reading data with SQL queries
- Writing data to databases
- Best practices for database interactions

**Day 19: JSON and XML Data**
- Reading JSON with jsonlite
- Parsing nested JSON structures
- Working with XML data
- Converting between formats
- API data retrieval basics

**Day 20: Web Scraping Basics**
- Using rvest package
- Selecting HTML elements
- Extracting text and attributes
- Handling tables
- Ethics and legal considerations

**Day 21: Data Export**
- Writing CSV files
- Exporting to various formats
- Saving R objects with save() and saveRDS()
- Creating portable datasets
- Compression options

---

### Week 4: Data Cleaning with dplyr

**Day 22: Introduction to dplyr**
- Installing and loading tidyverse
- Understanding tidy data principles
- dplyr philosophy and syntax
- The pipe operator (%>%)
- Basic dplyr verbs overview

**Day 23: Selecting and Filtering**
- select() for choosing columns
- Helper functions: starts_with(), ends_with(), contains()
- filter() for row selection
- Multiple conditions
- slice() for position-based filtering

**Day 24: Arranging and Mutating**
- arrange() for sorting data
- Descending order
- mutate() for creating new variables
- Transforming existing variables
- transmute() for replacing variables

**Day 25: Summarizing Data**
- summarise() for aggregation
- Common summary functions
- n() for counting
- Combining multiple summaries
- Working with groups

**Day 26: Grouping and Aggregation**
- group_by() fundamentals
- Multiple grouping variables
- Grouped mutate operations
- ungroup() when needed
- Group-wise filtering

**Day 27: Joining Data Frames**
- inner_join() and left_join()
- right_join() and full_join()
- semi_join() and anti_join()
- Handling duplicate keys
- Multiple key columns

**Day 28: Advanced dplyr**
- across() for multiple columns
- Window functions
- Cumulative operations
- Row-wise operations with rowwise()
- dplyr performance tips

---

### Week 5: Data Reshaping with tidyr

**Day 29: Wide vs Long Data**
- Understanding data formats
- When to use each format
- pivot_longer() basics
- pivot_wider() basics
- Preserving data during reshaping

**Day 30: Advanced Pivoting**
- Multiple value columns
- Handling missing values
- Names patterns and separators
- Complex pivoting scenarios
- Performance considerations

**Day 31: Separating and Uniting**
- separate() for splitting columns
- unite() for combining columns
- Handling edge cases
- Regular expressions in separation
- Data type preservation

**Day 32: Handling Missing Data**
- Types of missing data
- drop_na() for removal
- fill() for imputation
- replace_na() for specific values
- complete() for adding missing combinations

**Day 33: Nested Data**
- nest() for creating list-columns
- unnest() for expanding
- Working with nested data frames
- Mapping functions over nested data
- When to use nested structures

**Day 34: Data Validation**
- Checking for duplicates
- Identifying inconsistencies
- Data type validation
- Range checks
- Creating validation reports

**Day 35: Putting It All Together**
- Real-world data cleaning pipeline
- Combining multiple operations
- Creating reusable cleaning functions
- Documentation and reproducibility
- Common pitfalls and solutions

---

### Week 6: Data Visualization with ggplot2

**Day 36: ggplot2 Fundamentals**
- Grammar of graphics philosophy
- Basic plot structure
- aes() for aesthetic mappings
- geom layers
- Your first ggplot

**Day 37: Scatter Plots and Line Plots**
- geom_point() for scatter plots
- Customizing point aesthetics
- geom_line() for trends
- Multiple layers
- Connecting points

**Day 38: Bar Charts and Histograms**
- geom_bar() for counts
- geom_col() for values
- Position adjustments: dodge, stack, fill
- geom_histogram() for distributions
- Binwidth and bins

**Day 39: Box Plots and Violin Plots**
- geom_boxplot() for distributions
- Outlier detection
- geom_violin() for density
- Combining box and violin plots
- Statistical annotations

**Day 40: Faceting**
- facet_wrap() for single variable
- facet_grid() for two variables
- Controlling scales
- Label customization
- Best practices for faceting

**Day 41: Themes and Customization**
- Built-in themes
- Creating custom themes
- Modifying theme elements
- Color scales
- Text formatting

**Day 42: Advanced ggplot2**
- Statistical transformations
- Coordinate systems
- Annotations and labels
- Saving plots with ggsave()
- Creating publication-ready figures

---

### Week 7: Statistical Analysis Foundations

**Day 43: Descriptive Statistics**
- Measures of central tendency
- Measures of dispersion
- Quantiles and percentiles
- summary() function
- Creating custom summary tables

**Day 44: Probability Distributions**
- Common distributions in R
- Density, distribution, quantile functions
- Random number generation
- Simulating data
- Q-Q plots for distribution checking

**Day 45: Hypothesis Testing Basics**
- Null and alternative hypotheses
- p-values and significance levels
- Type I and Type II errors
- One-sample t-test
- Interpreting results

**Day 46: Two-Sample Tests**
- Independent t-test
- Paired t-test
- Assumptions checking
- Non-parametric alternatives
- Effect sizes

**Day 47: ANOVA**
- One-way ANOVA
- Assumptions and diagnostics
- Post-hoc tests
- Visualization of ANOVA results
- Reporting results

**Day 48: Correlation Analysis**
- Pearson correlation
- Spearman and Kendall correlation
- Correlation matrices
- Visualization with corrplot
- Testing significance

**Day 49: Simple Linear Regression**
- lm() function basics
- Model formula syntax
- Coefficients interpretation
- R-squared and model fit
- Diagnostic plots

---

### Week 8: Advanced Statistical Modeling

**Day 50: Multiple Regression**
- Adding multiple predictors
- Categorical predictors
- Interaction terms
- Model comparison
- Stepwise selection

**Day 51: Model Diagnostics**
- Residual analysis
- Detecting outliers
- Checking assumptions
- Influential observations
- Transformation techniques

**Day 52: Logistic Regression**
- Binary outcome modeling
- Interpreting coefficients
- Odds ratios
- Model evaluation metrics
- ROC curves

**Day 53: Generalized Linear Models**
- GLM framework
- Link functions
- Poisson regression
- Overdispersion
- Model selection

**Day 54: Time Series Basics**
- ts objects in R
- Trend and seasonality
- Decomposition
- Autocorrelation
- Basic forecasting

**Day 55: Advanced Time Series**
- ARIMA models
- Model identification
- Forecasting
- Accuracy measures
- Real-world applications

**Day 56: Statistical Reporting**
- Creating comprehensive reports
- Tables with kable and gt
- Inline code results
- Reproducible analysis
- Best practices

---

### Week 9: String Manipulation

**Day 57: Base R String Functions**
- paste() and paste0()
- substr() and substring()
- nchar() and strsplit()
- grep() and grepl()
- Case conversion

**Day 58: stringr Package**
- str_detect() and str_subset()
- str_extract() and str_match()
- str_replace() and str_remove()
- str_split() and str_c()
- Consistent syntax benefits

**Day 59: Regular Expressions Basics**
- Pattern matching fundamentals
- Literal characters
- Character classes
- Quantifiers
- Anchors

**Day 60: Advanced Regex**
- Groups and backreferences
- Lookahead and lookbehind
- Non-greedy matching
- Complex patterns
- Debugging regex

**Day 61: Text Mining Introduction**
- Tokenization
- Stop words removal
- Word frequency
- Creating word clouds
- Text cleaning pipelines

**Day 62: Sentiment Analysis**
- Sentiment lexicons
- Calculating sentiment scores
- Visualizing sentiment
- Comparing across groups
- Limitations and considerations

**Day 63: String Applications**
- Cleaning messy text data
- Extracting information
- Standardizing formats
- Creating derived variables
- Real-world case studies

---

### Week 10: Date and Time Handling

**Day 64: Base R Date Functions**
- Date and POSIXct classes
- as.Date() and as.POSIXct()
- Date arithmetic
- Formatting dates
- Date sequences

**Day 65: lubridate Package**
- Parsing dates with lubridate
- ymd(), mdy(), dmy() functions
- Extracting components
- Date arithmetic simplified
- Time zones

**Day 66: Time Intervals and Periods**
- Intervals, durations, periods
- Calculating time differences
- Age calculations
- Business day calculations
- Fiscal periods

**Day 67: Working with Times**
- Time of day operations
- hms package
- Combining dates and times
- Midnight and noon handling
- Time precision

**Day 68: Date Visualization**
- Time series plots
- Calendar heatmaps
- Gantt charts
- Formatting axes
- Dealing with gaps

**Day 69: Date Applications**
- Event analysis
- Cohort analysis
- Survival analysis basics
- Seasonal patterns
- Real-world examples

**Day 70: Review and Practice**
- Comprehensive date-time exercises
- Common pitfalls
- Performance optimization
- Best practices
- Integration with other packages

---

### Week 11: Introduction to Machine Learning

**Day 71: ML Fundamentals in R**
- Supervised vs unsupervised learning
- Training and test sets
- Cross-validation
- Model evaluation metrics
- caret package introduction

**Day 72: Linear Regression for Prediction**
- Train-test split
- Model training
- Making predictions
- Evaluating performance
- Feature importance

**Day 73: Classification Basics**
- Logistic regression for classification
- Decision boundaries
- Confusion matrix
- Accuracy, precision, recall
- F1 score

**Day 74: Decision Trees**
- rpart package
- Growing trees
- Pruning
- Visualization with rpart.plot
- Variable importance

**Day 75: Random Forests**
- Ensemble methods
- randomForest package
- Tuning parameters
- Out-of-bag error
- Feature selection

**Day 76: K-Nearest Neighbors**
- KNN algorithm
- Choosing k
- Distance metrics
- Scaling features
- Strengths and limitations

**Day 77: Model Evaluation**
- Cross-validation techniques
- Hyperparameter tuning
- ROC and AUC
- Calibration plots
- Model comparison

---

### Week 12: Advanced ML and Visualization

**Day 78: Clustering**
- K-means clustering
- Hierarchical clustering
- Determining optimal clusters
- Visualization techniques
- Interpreting results

**Day 79: Dimensionality Reduction**
- Principal Component Analysis
- Interpretation of components
- Scree plots
- PCA for visualization
- When to use PCA

**Day 80: tidymodels Framework**
- Modern ML workflow
- recipes for preprocessing
- parsnip for models
- tune for hyperparameters
- workflows package

**Day 81: Interactive Visualizations**
- plotly package
- Converting ggplot to plotly
- Creating interactive plots
- Hover information
- Zooming and panning

**Day 82: Shiny Basics**
- Shiny app structure
- UI and server functions
- Reactive programming
- Input and output widgets
- Deploying apps

**Day 83: Advanced Shiny**
- Reactive expressions
- Observers
- Modules
- Theming
- Performance optimization

**Day 84: Dashboard Creation**
- flexdashboard package
- Layout options
- Multiple pages
- Interactive components
- Publishing dashboards

---

### Week 13: Capstone Project

**Day 85: Project Planning**
- Choosing a dataset
- Defining objectives
- Creating project structure
- Version control setup
- Timeline planning

**Day 86: Data Acquisition and Cleaning**
- Loading project data
- Exploratory analysis
- Data cleaning pipeline
- Validation checks
- Documentation

**Day 87: Analysis and Modeling**
- Statistical analysis
- Model building
- Feature engineering
- Model evaluation
- Iteration and refinement

**Day 88: Visualization and Reporting**
- Creating publication-quality plots
- Interactive visualizations
- Dashboard development
- Report writing
- Narrative construction

**Day 89: Finalization and Documentation**
- Code review and cleanup
- Comprehensive documentation
- README creation
- Reproducibility check
- Portfolio preparation

**Day 90: Presentation and Reflection**
- Final presentation preparation
- Sharing your work
- Reflecting on learning
- Next steps planning
- Celebrating completion

---

## Installation Guide

### Installing R

**Windows:**
1. Visit https://cran.r-project.org/bin/windows/base/
2. Download the latest version
3. Run the installer with default settings
4. Verify installation by opening R

**macOS:**
1. Visit https://cran.r-project.org/bin/macosx/
2. Download the appropriate .pkg file
3. Open and install the package
4. Verify in Terminal: type 'R' and press Enter

**Linux (Ubuntu/Debian):**
```bash
sudo apt update
sudo apt install r-base r-base-dev
```

### Installing RStudio

1. Visit https://www.rstudio.com/products/rstudio/download/
2. Download RStudio Desktop (Free version)
3. Install after R is installed
4. Open RStudio and verify R is detected

### Setting Up Your Environment

**Install Essential Packages:**
```r
# Core tidyverse packages
install.packages("tidyverse")

# Additional recommended packages
install.packages(c(
  "here",
  "janitor",
  "skimr",
  "DataExplorer",
  "plotly",
  "shiny",
  "rmarkdown",
  "knitr"
))
```

**Configure RStudio:**
1. Tools > Global Options > General
2. Uncheck "Restore .RData into workspace at startup"
3. Set "Save workspace to .RData on exit" to "Never"
4. Tools > Global Options > Code > Display
5. Check "Show margin" and set to 80

---

## How to Use This Repository

### Repository Structure
```
R-Mastery-Journey/
├── README.md
├── .gitignore
├── week-01/
│   ├── day-01/
│   │   ├── day-01-notes.Rmd
│   │   ├── day-01-exercises.R
│   │   └── day-01-solutions.R
│   ├── day-02/
│   └── ...
├── week-02/
├── datasets/
│   ├── raw/
│   └── processed/
├── resources/
│   ├── cheatsheets/
│   └── references/
└── projects/
    └── capstone/
```

### Daily Learning Routine

**Recommended Daily Schedule (1-2 hours):**

1. **Review (10 minutes)**
   - Quickly review previous day's notes
   - Check understanding of key concepts

2. **New Content (30-40 minutes)**
   - Open the day's .Rmd file
   - Read through notes and explanations
   - Run code examples line by line
   - Experiment with modifications

3. **Exercises (20-30 minutes)**
   - Complete exercises in the exercises file
   - Try solving without looking at solutions
   - Check your work against provided solutions

4. **Reflection (5-10 minutes)**
   - Note what you learned
   - Identify areas needing review
   - Prepare questions for further research

### Working with R Markdown Files

**Opening Files:**
1. In RStudio: File > Open File
2. Navigate to the day's folder
3. Select the .Rmd file

**Running Code:**
- Click "Run" button for individual chunks
- Ctrl/Cmd + Enter to run current line
- Ctrl/Cmd + Shift + Enter to run entire chunk

**Knitting Documents:**
- Click "Knit" button at top
- Choose output format (HTML recommended)
- View rendered document in browser

### Getting Help

**When Stuck:**
1. Read the error message carefully
2. Check the documentation: `?function_name`
3. Search online: "R [your question]"
4. Review relevant sections in notes
5. Try breaking the problem into smaller parts

**Useful Commands:**
```r
# Get help on a function
?mean

# Search for help
??regression

# View examples
example(lm)

# Check package functions
ls("package:dplyr")

# View vignettes
vignette("dplyr")
```

---

## Resources and References

### Official Documentation
- R Project: https://www.r-project.org/
- CRAN: https://cran.r-project.org/
- RStudio: https://www.rstudio.com/
- R Markdown: https://rmarkdown.rstudio.com/

### Recommended Books
- "R for Data Science" by Hadley Wickham and Garrett Grolemund
- "Advanced R" by Hadley Wickham
- "R Graphics Cookbook" by Winston Chang
- "The Art of R Programming" by Norman Matloff
- "Text Mining with R" by Julia Silge and David Robinson

### Online Courses
- DataCamp: Introduction to R
- Coursera: R Programming (Johns Hopkins)
- edX: Data Science with R
- RStudio Cloud Primers

### Cheat Sheets
Located in `resources/cheatsheets/`:
- Base R
- dplyr and tidyr
- ggplot2
- R Markdown
- stringr
- lubridate

### Community Resources
- Stack Overflow: r tag
- RStudio Community: https://community.rstudio.com/
- R-bloggers: https://www.r-bloggers.com/
- Twitter: #rstats hashtag

### Datasets for Practice
- Built-in R datasets: `data()`
- Kaggle: https://www.kaggle.com/datasets
- UCI Machine Learning Repository
- Google Dataset Search
- Data.gov

---

## Best Practices

### Code Style
- Use meaningful variable names
- Follow tidyverse style guide
- Comment your code appropriately
- Use consistent indentation (2 spaces)
- Keep lines under 80 characters

### Project Organization
- Use RStudio Projects for each analysis
- Separate raw and processed data
- Document your data sources
- Use version control (Git)
- Create README files

### Reproducibility
- Start scripts with required packages
- Set random seeds for reproducibility
- Use relative paths with here package
- Document your R and package versions
- Share sessionInfo() in reports

### Performance
- Vectorize operations when possible
- Avoid growing objects in loops
- Use data.table for large datasets
- Profile code with profvis
- Remove unused objects

---

## Contributing

This is a learning repository. If you find errors or have suggestions:

### Reporting Issues
1. Check if issue already exists
2. Create detailed issue description
3. Include code to reproduce problem
4. Specify R version and packages

### Suggesting Improvements
1. Fork the repository
2. Make your changes
3. Test thoroughly
4. Submit pull request with description

### Code of Conduct
- Be respectful and constructive
- Help others learn
- Share knowledge generously
- Accept feedback graciously

---

## Acknowledgments

This course draws inspiration from:
- The R Core Team for creating R
- RStudio for their excellent IDE and packages
- Hadley Wickham and the tidyverse team
- The R community for countless resources
- All the package developers whose work we use

---

## License

This repository is licensed under the MIT License. You are free to use, modify, and distribute the content for educational purposes.

### MIT License

Copyright (c) 2025 R Mastery Journey

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

## Contact and Support

For questions, suggestions, or collaboration:
- Create an issue in this repository
- Email: [your-email@example.com]
- LinkedIn: [your-profile]
- Twitter: @yourusername

---

## Progress Tracking

Track your progress through the course:

### Week 1: R Fundamentals
- [ ] Day 1: Getting Started
- [ ] Day 2: Basic Syntax
- [ ] Day 3: Vectors
- [ ] Day 4: Working with Vectors
- [ ] Day 5: Matrices
- [ ] Day 6: Data Frames
- [ ] Day 7: Lists and Factors

### Week 2: Programming Fundamentals
- [ ] Day 8: Conditionals
- [ ] Day 9: Loops
- [ ] Day 10: Functions
- [ ] Day 11: Advanced Functions
- [ ] Day 12: Apply Family
- [ ] Day 13: Packages
- [ ] Day 14: Projects

Continue through all 90 days...

---

## Final Notes

Learning R is a journey, not a destination. This course provides structure and guidance, but your success depends on consistent practice and curiosity. Don't hesitate to experiment, make mistakes, and learn from them. The R community is welcoming and helpful, so engage with others as you learn.

Remember: Everyone starts as a beginner. With dedication and practice, you will master R programming and unlock powerful data analysis capabilities.

Happy coding and welcome to the R community!

---

Last Updated: 2025
Version: 1.0
