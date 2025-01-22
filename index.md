## Course Schedule


#### Week One: Introduction:R Studio, and Spatial Data Visualization

###### Weekly Resources:

Virtual Materials:
  - [Leaflet Overview](https://rstudio.github.io/leaflet/)
  

###### Class Overview:

- Tuesday January 14: Course Overview and Class Conversation

- Tuesday January 16: R Mapping Demo [QMD Source Code](https://raw.githubusercontent.com/Stat534/MappingDemo/refs/heads/main/MappingDemo.qmd)

---

#### Week Two: Spatial Data Visualization, Projections & Distances, Point Process Intro

###### Weekly Resources:

Virtual Materials:
  - [ggmap](https://cran.r-project.org/web/packages/ggmap/readme/README.html)

Reading:
  - Chapter 1

[HW 1: Due Thursday January 30](https://github.com/Stat534/HW/blob/main/HW1.md) ([Quarto Source Code](https://raw.githubusercontent.com/Stat534/HW/refs/heads/main/HW1.qmd))
  

###### Class Overview:

- Tuesday January 21: R Mapping Demo: Part II [QMD Source Code](https://raw.githubusercontent.com/Stat534/MappingDemo/refs/heads/main/MappingDemo.qmd)
  - [R Mapping Demo Key](https://raw.githubusercontent.com/Stat534/MappingDemo/refs/heads/main/MappingDemo_Key_github.qmd)

- Thursday January 23: Project & Distances + Point Process Intro
  - [Projection and Distance: PDF](https://github.com/Stat534/Lectures/blob/main/Distance_Projections.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/Lectures/refs/heads/main/Distance_Projections.Rmd))
---

#### Course Description

Statistical methods of spatial data analysis, stationary and nonstationary random fields, covariance structures, geostatistical models and analysis, spatial point process models and analysis, spatial lattice models and analysis. An emphasis will be placed on:

1. Creating maps and other data visualization products with spatial data, 

2. Identifying differences between the three common spatial data types: point process, geostatistical, and areal data,

3. Using statistical software and either Bayesian or classical statistical techniques to analyze spatial point process, geostatistical, and areal data structures, and


## Learning Outcomes:
At the end of the course students will understand

1. point process theory and applications including homogeneous and non-homogeneous Poisson point processes

2. geostatistics including semivariogram estimation and kriging 

3. spatial autoregression including covariance estimation, spatial logistic and Poisson models, simultaneous autoregressive models, conditional autoregressive models.

## Course Syllabus

A downloadable PDF of the course syllabus is available: [Download PDF Syllabus](https://github.com/Stat534/syllabus/blob/main/STAT534.pdf)


## Prerequisites

- Required: STAT 412, STAT 512, and STAT 422
- Preferred: STAT 506, extensive experience with R, and an understanding or interest in Bayesian statistics

## Textbooks

- Hierarchical Modeling and Analysis for Spatial Data, Second Edition, by Bannerjee, Carlin, and Gelfand. While the second edition is preferred, the first edition will suffice.
- Animal Movement: Statistical Models for Telemetry Data, by Hooten, Johnson, McClintock, and Morales. _Optional_

## Office Hours

- Tuesday 8:30 - 9:15
- Tuesday 12:30 - 2
- Thursday 8:30 - 9:15

## Additional Resources
Analysis and data visualization will be implemented with R

## Course Policies

#### Grading Policy

- **25%** of your grade will be determined by homework assignments. Collaboration is encouraged on homework assignments, but everyone should complete their own assignments. 

- **75%** of your grade will be determined by a series of three exams and applied projects.


#### Collaboration
University policy states that, unless otherwise specified, students may not collaborate on graded material. Any exceptions to this policy will be stated explicitly for individual assignments. If you have any questions about the limits of collaboration, you are expected to ask for clarification.

In this class students are encouraged to collaborate on homework assignments, but exams and projects should be completed without collaboration.

####  Academic Misconduct
Section 420 of the Student Conduct Code describes academic misconduct as including but not limited to plagiarism, cheating, multiple submissions, or facilitating others’ misconduct. Possible sanctions for academic misconduct range from an oral reprimand to expulsion from the university.

#### Disabilities Policy

Federal law mandates the provision of services at the university-level to qualified students with disabilities. If you have a documented disability for which you are or may be requesting an accommodation(s), you are encouraged to contact the Office of Disability Services as soon as possible.



### Approximate Course Outline

1. Course Intro & Preliminaries:
  - R
  - Plotting spatial data
  - Linear Models and Bayesian Inference
2. Point Process Data
3. Point Referenced Data
4. Areal Data



<!---
#### Week Two: Linear Models and Bayesian Inference

##### Weekly Materials
- Suggested Reading: Hierarchical Modeling and Analysis for Spatial Data (HMASD), Chapter 5: Basics of Bayesian Inference

- Weekly Notes: [PDF](https://github.com/Stat534/CourseIntro/blob/main/LM.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/CourseIntro/main/LM.Rmd))

###### Class Overview:
- Thursday January 16: Intro to R Studio and Leaflet. _(Interactive Demo)_
    - [Leaflet Demo](https://stat534.github.io/DataViz/) ([Download Repo](https://classroom.github.com/a/vIyJnLok))

- Tuesday January 21: Linear Models Overview

- Thursday January 23: Linear Models + Bayes Intro

---

#### Week Three: Bayes and Stan 

##### Weekly Materials
- Suggested Reading: [Gramacy: Surrogates Ch 5.1](https://bookdown.org/rbg/surrogates/chap5.html#chap5gpprior)

- Virtual Materials: [R Stan Installation Guidelines](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started)

- Weekly Notes: [PDF](https://github.com/Stat534/Bayes_Stan/blob/main/Bayes_Stan.pdf) ([RMD Source](https://github.com/Stat534/Bayes_Stan/blob/main/Bayes_Stan.Rmd))

###### Class Overview:

- Tuesday January 28: Bayes Theorem + Bayesian overview

- Thursday January 30: Visual Overview of Bayesian Analysis & Stan Demo  _(Interactive Demo)_ ([Stan Demo](https://stat534.github.io/stan_demo/)) ([Download Repo](https://classroom.github.com/a/bfUddJmO))

---

#### Week Four: Linear Algebra and Conditional Multivariate Normal

##### Weekly Materials
- [HW 1 due end of day Monday February 1](https://github.com/Stat534/Homework1/blob/main/HW1.md) ([Download Repo](https://classroom.github.com/a/X6CC6Yy7))

- Suggested Reading: [Gramacy: Surrogates Ch 5.1](https://bookdown.org/rbg/surrogates/chap5.html#chap5gpprior)

- Virtual Materials: 

- Weekly Notes: [PDF](https://github.com/Stat534/GP/blob/main/LinearAlgebraFoundations.pdf) ([Download Repo](https://github.com/Stat534/GP/blob/main/LinearAlgebraFoundations.Rmd))

###### Class Overview:

- Tuesday February 4: Linear Algebra Recap & Mathematical exploration of Multivariate Normal Distribution

- Thursday February 6: Correlated Normal Demo _(Interactive Demo)_ [Conditional Normal Demo]( https://stat534.github.io/conditionalnormal_demo/) ([Download Repo](https://classroom.github.com/a/IbT2Azly))

---

#### Week Five: Gaussian Processes and GP regression

##### Weekly Materials
- [Project 1 Proposal due end of day Monday February 8](https://stat534.github.io/Project_one/) ([Download Repo](https://classroom.github.com/a/EegbM3LV))
- [HW 2 due end of day Monday February 15](https://github.com/Stat534/homework2/blob/main/HW2.md) ([Download Repo](https://classroom.github.com/a/JE-jzwTJ))

- Suggested Reading:  HMASD Ch.1 Overview of Spatial Data Problems

- Weekly Notes: 
  - [PDF](https://github.com/Stat534/GP/blob/main/GP_Theory.pdf) ([Rmd Source](https://raw.githubusercontent.com/Stat534/GP/main/GP_Theory.Rmd))
  - [PDF (Part 2)](https://github.com/Stat534/GP/blob/main/GP_Theory2.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/GP/main/GP_Theory2.Rmd))
  

###### Class Overview:

- Tuesday February 11: Theory of Gaussian Processes 

- Thursday February 13: GP in 2D & GP demo _(Interactive Demo)_ [GP Demo](https://stat534.github.io/GP_Demo/) ([Download Repo](https://classroom.github.com/a/kjqDRStf))

---

#### Week Six: Projections, Distance Calculations, and Spatial Graphics

##### Weekly Materials
- Project 1: Introduction,  Research Question, and Data viz due end of day Monday February 22
- [HW 3 due end of day Wednesday February 24](https://github.com/Stat534/homework_three/blob/main/HW3.md) ([Download Repo](https://classroom.github.com/a/RNzftvcT))

- Suggested Reading: HMASD Ch.2 Basics of Point Referenced Models

- Weekly Notes: 
  - [PDF](https://github.com/Stat534/Projects_Viz_Notation/blob/main/Cartography.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/Projects_Viz_Notation/main/Cartography.Rmd))

###### Class Overview:

- Tuesday February 18: Projections and Distance Calculations

- Thursday February 20: Spatial data in R ([ggmap reference](https://github.com/dkahle/ggmap))

---

#### Week Seven: Spatial Statistics Fundamentals

##### Weekly Materials

- Suggested Reading:  HMASD Ch.2 Basics of Point Referenced Models

- Weekly Notes:  
  - [Spatial Notation and Variograms(PDF)](https://github.com/Stat534/SpatialNotation/blob/main/Notation.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/SpatialNotation/main/Notation.Rmd))
  - [Spatial EDA: Lecture (PDF)](https://github.com/Stat534/Spatial_EDA/blob/main/SpatialEDA.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/Spatial_EDA/main/SpatialEDA.Rmd))

###### Class Overview:

- Tuesday February 25: Stationarity and Variograms


- Thursday February 27: Fitting variograms and covariance functions & Spatial EDA: Lecture

---

#### Week Eight: Fitting Geostatistical Models

##### Weekly Materials


- Project 1: Introduction,  Research Question, and Data viz + Data Analysis due end of day Monday March 15

- [HW 4 due end of day Wednesday March 10](https://github.com/Stat534/homework_four/blob/main/HW4.md) ([Download Repo](https://classroom.github.com/a/lfKoEq5y))

###### Class Overview:

- Tuesday March 4: Spatial EDA  _[interactive demo](https://stat534.github.io/Spatial_EDA/)_ ([Download Repo](https://classroom.github.com/a/psZzmMIk)) 

- Thursday March 6: Spatial EDA _[interactive demo]_ + [Other model fitting options](https://github.com/Stat534/Other_Software/blob/main/Model-Fitting-Demo.md) ([RMD Source](https://raw.githubusercontent.com/Stat534/Other_Software/main/Model%20Fitting%20Demo.Rmd))

---


#### Week Nine: Fitting Geostatistical Models, part 2

##### Weekly Materials

- Weekly Notes: 
  - [Spatial prediction / model comparison](https://github.com/Stat534/spatial_prediction/blob/main/spatial_prediction.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/spatial_prediction/main/spatial_prediction.Rmd))
  - [Anisotropy + other covariance structure](https://github.com/Stat534/Anisotropy/blob/main/Covariance_Anisotropy.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/Anisotropy/main/Covariance_Anisotropy.Rmd))
  - [Spatial GLMS](https://github.com/Stat534/spatial_glms/blob/main/spatial_glms.pdf)


###### Class Overview:

- Tuesday March 11: Anisotropy + other covariance structure

- Thursday March 13: Spatial prediction / model comparison

---


#### Week X: Spring Break

##### Weekly Materials


###### Class Overview:

- Tuesday March 18: No Class
- Thursday March 20: No Class

### Areal Data

#### Week Ten: Spatial GLMS / Areal Data Intro

##### Weekly Materials

- Weekly Notes: 
  - [Spatial GLMs](https://github.com/Stat534/spatial_glms/blob/main/spatial_glms.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/spatial_glms/main/spatial_glms.Rmd))
  - [Areal Data Intro](https://github.com/Stat534/Areal_Intro/blob/main/areal_data.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/Areal_Intro/main/areal_data.Rmd))


###### Class Overview:

- Tueday March 25: Spatial GLMS 
  - [GLMs Video (watch first)](https://montana.techsmithrelay.com/clfE)
  - [Spatial GLMs Video](https://montana.techsmithrelay.com/EGuG)
  - Project 1: Introduction,  Research Question, and Data viz + Data Analysis due (Update existing repo)

- Thursday March 27: Spatial GLMs __interactive demo__ & Areal Data Intro 

---

#### Week Eleven: Areal Data: Intro 

##### Weekly Materials


- Weekly Notes: 
  - [Areal Data Association](https://github.com/Stat534/areal_association/blob/main/areal_association.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/areal_association/main/areal_association.Rmd))
  - [Areal Data Modeling: Intro](https://github.com/Stat534/areal_modeling/blob/main/areal_modeling.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/areal_modeling/main/areal_modeling.Rmd))

###### Class Overview:

- Tuesday April 1:
    
- Thursday April 3:
  
---

#### Week Twelve: Areal Data Modeling

##### Weekly Materials

- Suggested Reading: 
  - [Areal Models in Stan](https://mc-stan.org/users/documentation/case-studies/icar_stan.html)
  - _optional_ [Spatial autoregressive models for statistical inference from ecological data](https://eprints.qut.edu.au/115891/1/115891.pdf)
- Weekly Notes: 
   - [Spatial Autoregressive Models](https://github.com/Stat534/areal_modeling/blob/main/ar_models.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/areal_modeling/main/ar_models.Rmd))
   - [Fitting AR Models](https://github.com/Stat534/areal_demo/blob/main/part2.pdf)

###### Class Overview:

- Tuesday April 8: [_interactive demo: fitting areal data models, part 1_](https://stat534.github.io/areal_demo/) ([Download Repo](https://classroom.github.com/a/E_HQB7Zf))

- Thursday April 10:

---

#### Week Thirteen: Point Process Data

##### Weekly Materials

- Suggested Reading: 
  - HMASD 8.1 - 8.3 
  - [spatstat overview](https://cran.r-project.org/web/packages/spatstat/vignettes/getstart.pdf)

- Weekly Notes:
  - [Point Process Intro](https://github.com/Stat534/pp_intro/blob/main/PP_Intro.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/pp_intro/main/PP_Intro.Rmd))

###### Class Overview:

- Tuesday April 15:

- Thursday April 17: __asynchronous virtual class: spatstat overview__
  - [spatstat intro](https://github.com/Stat534/spatstat_intro/blob/main/spatstat_demo.md) ([Video Overview](https://montana.techsmithrelay.com/xbDF)) 

---


#### Week Fourteen: 

##### Weekly Materials

- Suggested Reading: 

- Weekly Notes: 
  - [Point Process Test Statistics](https://github.com/Stat534/pp_intro/blob/main/PP_Hyp.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/pp_intro/main/PP_Hyp.Rmd))
  - [K statistic](https://github.com/Stat534/pp_intro/blob/main/k.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/pp_intro/main/k.Rmd))
  -  [NHPP](https://github.com/Stat534/pp_modeling/blob/main/NHPP.pdf) ([RMD Source](https://raw.githubusercontent.com/Stat534/pp_modeling/main/NHPP.Rmd))
 

###### Class Overview:

- Tuesday April 22: 

- Thursday April 24

---


#### Week Fifteen: 

##### Weekly Materials

- Weekly Notes: 
  - [PP Modeling](https://github.com/Stat534/pp_modeling/blob/main/spatstat2.pdf) ([RMD Source Code](https://raw.githubusercontent.com/Stat534/pp_modeling/main/spatstat2.Rmd)) 
  - [LGCP Demo](https://github.com/Stat534/pp_modeling/blob/main/lgcp_demo.md)

###### Class Overview:

- Tuesday April 29: 

- Thursday April 31: 

---


#### Week Sixteen: 
 

###### Class Overview:

- Tuesday May 6, 10 - 11:50 Final Exam

---
-->
