# rstats-ed

Inspired by the [Using Julia in the classroom](https://julialang.org/teaching/) page and suggestion by [@Peter_Griffin](https://community.rstudio.com/u/peter_griffin)'s [post](https://community.rstudio.com/t/big-data-with-microsoft-open-r/13183/18?u=mine) on RStudio Community as well as the [Learn the tidyverse](https://www.tidyverse.org/learn/) page.

The goal is to create a repository where one can discover courses and learning materials for learning and teaching R.

This is a user curated list and is bound to be non-comprehensive at all times. If you have suggestions for courses to add, please submit a pull request or add an issue.

## Online courses

### MOOCs

- [Statistics with R](https://www.coursera.org/specializations/statistics) Coursera Specialization: Mine Çetinkaya-Rundel, Merlise Clyde, Colin Rundel, David Banks. 5 courses: Introduction to Data and Probability, Inferential Statistics, Linear Regression and Modeling, Bayesian Statistics, and Capstone.

- [JHU Data Science](https://www.coursera.org/specializations/jhu-data-science) Coursera Specialization: This Specialization covers the concepts and tools you'll need throughout the entire data science pipeline, from asking the right kinds of questions to making inferences and publishing results. In the final Capstone Project, you’ll apply the skills learned by building a data product using real-world data. 

- [Chromebook Data Science](http://jhudatascience.org/chromebookdatascience/): Chromebook Data Science (CBDS) is a free, massive open online educational program offered through Leanpub to help anyone who can read, write, and use a computer to move into data science.


### Other learning resources

- [RStudio Cloud Primers](https://rstudio.cloud/learn/primers): RStudio Cloud is a free, cloud based version of the RStudio IDE. Packaged within RStudio Cloud are primers, which are collections of interactive tutorials made with learnr. These primers teach the basics of R and the Tidyverse.

- [DataCamp's R offerings](https://www.datacamp.com/courses/tech:r): DataCamp offers interactive R (and Python, Sheets, SQL, and shell) courses on topics in data science, statistics and machine learning following a "learn by doing" philosophy. Courses run interactively in the browser.

- [LinkedIn Learning offerings](https://www.linkedin.com/learning/topics/r?contentBy=LINKEDIN_LEARNING&entityType=COURSE&software=R~RStudio&sortBy=RECENCY&trk=insiders_215756_learning): LinkedIn Learning (previously lynda.com) offers beginner, intermediate, and advanced courses in R, as well as Python, SQL, Java, C, PHP, Javascript and other languages. All courses are offered as downloadable video content and are used in many universities.

## University courses teaching R

### 2018

- [STA 112 - Better Living with Data Science](http://www2.stat.duke.edu/courses/Fall18/sta112.01/) - Duke University; [Mine Çetinkaya-Rundel](https://github.com/mine-cetinkaya-rundel/). Data Science course for first year undergraduates with little to no computing background. Combines techniques from statistics, math, computer science, and social sciences, to learn how to use data to understand natural phenomena, explore patterns, model outcomes, and make predictions. Data wrangling, exploratory data analysis, predictive modeling, data visualization, and effective communication of results. Discussions around reproducibility, data sharing, data privacy.

- [Data Science for Public Management](https://statsf18.classes.andrewheiss.com/) - Brigham Young University; [Andrew Heiss](https://github.com/andrewheiss). Data science and statistics class for Master of Public Administration (MPA) students with little math or computing experience. Uses [ModernDive](https://moderndive.com/), [DataCamp](https://www.datacamp.com/), [R for Data Science](http://r4ds.had.co.nz/), and [OpenIntro Statistics](https://www.openintro.org/stat/textbook.php?stat_book=os) to cover tidyverse data wrangling, inference, and hypothesis testing. All projects and in-class examples use data related to public affairs, administration, and policy.

- [Data Visualization](https://datavizf18.classes.andrewheiss.com/) - Brigham Young University; [Andrew Heiss](https://github.com/andrewheiss). Data visualization class for Master of Public Administration (MPA) students with some experience with R. Uses Alberto Cairo's [*The Truthful Art: Data, Charts, and Maps for Communication*](https://www.amazon.com/Truthful-Art-Data-Charts-Communication/dp/0321934075), Kieran Healy's [*Data Visualization: A Practical Introduction*](http://socviz.co/), Claus Wilke's [*Fundamentals of Data Visualization*](https://serialmentor.com/dataviz/), and [R for Data Science](http://r4ds.had.co.nz/) to cover principles of graphic design and fundamentals of visualizing data with ggplot2.

- [Reproducible & Collaborative Data Science](https://espm-288.carlboettiger.info) - UC Berkeley, [Carl Boettiger](https://github.com/cboettig/). Data Science course for first year graduate students in both the natural and social sciences.  A modular, flipped-classroom approach that combines reading, exercises and videos based on [R for Data Science](http://r4ds.had.co.nz/) and [DataCamp](https://www.datacamp.com/) with more open-ended assignments to replicate, extend, and sometimes challenge key results from the scientific literature on global change.  Note: an upper-division undergraduate version of the course is also being developed under the title [Data Science for Global Change Ecology](https://espm-157.carlboettiger.info)

- [Statistical Computing](http://www2.stat.duke.edu/~cr173/Sta523_Fa18) - Duke University, [Colin Rundel](https://github.com/rundel). Statistical programming with R and its interfaces with custom code development for central statistical models. Best practices and software development for reproducible results, selecting topics from: use of markup languages, understanding data structures, design of graphics, object oriented programming, vectorized code, scoping, documenting code, profiling and debugging, building modular code, and version control- all in contexts of specific applied statistical analyses. 

- [DSCI 521: Computing Platforms for Data Science](https://github.com/UBC-MDS/public/tree/master/courses/521_platforms) - University of British Columbia, Tiffany Timbers. How to install, maintain, and use the data scientific software "stack". The Unix operating system, integrated development environments (Jupyter and RStudio), and problem solving strategies.

- [CT5102: Programming for Data Analytics](https://github.com/JimDuggan/CT5102) - NUI Galway, [Jim Duggan](https://github.com/JimDuggan): A module that is part of the [M.Sc. Computer Science (Data Analytics)](http://www.nuigalway.ie/courses/taught-postgraduate-courses/msc-in-computer-science-data-analytics.html#course_overview). There are twelve topics, and these will be updated as the course progresses. The course structure has main three elements: (1) Base R (Vectors, Functions, Lists, Matrices and Data Frame), (2) Data Science, with the tidyverse packages in R (ggplot2, dplyr, readr, tidyr, lubridate and stringr), (3) Advanced R, including closures, object systems (S3, S4 and RC), and building packages.

- [A Jupyter + R ( + mybinder.org) tutorial for social scientists](https://github.com/InfantLab/NotebookDemos) - Goldsmiths, University of London, [Caspar Addyman](https://github.com/InfantLab/) - A self taught or one session class taught to our Masters Level Advanced Methods class. Using an online notebook shared using MyBinder, it goes through basics of editing code and markdown in Jupyter notebooks, how to host these on MyBinder with fixed date snapshots for reproducibility. It provides very simple examples of loading local or remote data files, filtering and graphing with tidyverse and running simple statistical tests using ezANOVA 

- [Microsoft Research Data Science Summer School](http://ds3.research.microsoft.com) - Microsoft Research New York, [Jake Hofman](http://jakehofman.com). An intensive, eight-week hands-on introduction to data science for college students in the New York City area focused on increasing diversity in computer science. Students learn Git, Bash, and R, focusing on concepts in statistics, modeling, and machine learning. All [coursework](https://github.com/msr-ds3/coursework) is available on Github. Students produce an original group research project at the end of the program. Projects from the past several years are available [here](https://www.microsoft.com/en-us/research/academic-program/data-science-summer-school/#!projects), along with corresponding data and code.

### 2017

- [Modeling Social Data](http://modelingsocialdata.org/syllabus) - Columbia University, [Jake Hofman](http://jakehofman.com). One semester class for upper division undergraduate and first year graduate students that focuses on data-driven modeling for large-scale, social data. Material draws on statistics, computer science, and the social sciences. R is the primary language taught for the course, students gain experience collecting, cleaning, analyzing, and modeling with the tidyverse and related tools. All slides, code, and student-scribed notes are [available](http://modelingsocialdata.org/syllabus) on Github. Students complete a final project in small groups where work on an original research problem of their choice.