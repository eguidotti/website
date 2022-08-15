---
title: 'Coding for Data Science and Data Management'
summary: MSc Data Science for Economics, University of Milan, Italy &nbsp;&middot;&nbsp; 2019/2020
authors: [Nicolò Cesa-Bianchi, admin, Stefano Montanelli]
date: '2019-12-01'
type: book
---

<style>
  table td, table th {padding: 10px;}
</style>

This course is part of the [MSc in Data Science for Economics, University of Milan, Italy](https://dse.cdl.unimi.it/en). Academic year 2019/2020.

## Description

The course aims at providing technical skills about coding/scripting aspects for data analysis and to manage persistent data storage of sources and results involved in analysis. On the one side, the Python programming language and the R framework are illustrated. The goal is to deal with essential notions about data structures and control structures of both Python and R. On the other side, the goal is to present the core notions of relational databases, such as keys, integrity, and primary/foreign key constraints, as well as the SQL language for data definition, manipulation, and query. Recent and innovative NoSQL solutions are also discussed, with special focus on a document-oriented system called MongoDB.

## Course structure

The course is divided in three modules:

- R (Emanuele Guidotti)
- Python (Nicolò Cesa-Bianchi)
- Databases (Stefano Montanelli)

## Syllabus (R module)

### Introduction to the R framework and R Studio

   - Installation
   - Comments
   - Variable assignment 
   - Functions 
   - Extension packages 
   - R help, StackOverflow, Google

### Basic Data Types 

   - `numeric` 
   - `integer` 
   - `complex`
   - `logical`  
   - `character`

### Basic Data Structures
   
   - `vector` 
   - `matrix` 
   - `data.frame` 
   - `list` 
   - `environment`

### Basic operations
   
   - Subsetting 
   - Arithmetics

### Time Series
   
   - The `zoo` package
   - The `xts` package

### Control Structures
   
   - `if-else` 
   - `for` loops, `while` loops, `repeat`, `break` 
   - `apply`, `lapply`, `sapply`

### Custom Functions
   
   - Code quality and modularity
   - How to implement R functions  

### Speeding up the code
   
   - The `Rcpp` package 
   - References to parallel computing 

### Data Acquisition
   - Local & Remote files
   - R packages
   - RESTful APIs
   - Web scraping

### Data visualization

  - Base plotting system
  - The `ggplot2` package  
  - The `plotly` package

### Building interactive interfaces, documents and websites
    
  - R Shiny 
  - Rmarkdown 
  - Rbookdown 
  - Rblogdown 

### Building R packages
    
  - Roxygen 
  - Base packages 
  - Rcpp packages 
  - R Shiny packages

### If time allows...
    
  - Debugging in Rstudio 
  - Connect R to Python: the `reticulate` package
  - Connect R to databases: the `RMySQL`, `RSQLite`, `RMongo` packages
  - Q&A

## Exam (R module)

Create an R package which deals with task(s) of your choice. The aim of the project is to asses your ability in dealing with the R programming language. You are __free__ to choose the task(s) you __like__ most.

The project is an __individual project__, even if you are strongly encouraged to work in groups and help each other. Please do take advantage of online resources and note that copying code snippets is totally fine. On the other hand, copying the whole project or most of it is (obviously) not allowed.

### Delivery

Upload the code to your repository[^1] available at <https://github.com/unimi-dse>. The package must include a `README.md` file containing a short description of the package and how to use it. 

[^1]:	to set up the repository create an account on GitHub and email me with your GitHub username. The email must be sent from your University address and use _"DSE Coding Midterm"_ as subject. On the other hand, I suggest to create your GitHub account using your personal email address. 

### Deadline

16 February 2020, 23:59.

### Evaluation

#### Passing grade (18/30)

The package must be installed with the following command:

```r
devtools::install_github("unimi-dse/ID")
```

where `ID` is the ID of your repository. If the package cannot be installed or raises errors, the exam is failed.

#### Additional points (9/30)

The package must deal with some of the following topics. Choose the topics you like most. In any case, max 9 points can be earned.

| title                 | description                                                  | points |
| --------------------- | ------------------------------------------------------------ | ------ |
| Data Acquisition      | Import data via local/remote files, R packages, APIs or web scraping. | 3      |
| Data Visualization    | Visualize data with `ggplot2` or `plotly`                    | 3      |
| Data Analysis         | Use R packages to perform some kind of data analysis. The complexity of the analysis is not relevant. The aim is to show your ability to work with R packages. | 3      |
| Interactive Interface | Build an interactive interface with `shiny`                  | 3      |
| Code Optimization     | Speed up the code using `Rcpp` or parallel computing         | 3      |

#### Additional Points (3/30)

Up to 3 additional points are assigned based on:

| title         | description                                                  | point |
| ------------- | ------------------------------------------------------------ | ----- |
| README        | Use the Markdown syntax to provide a high quality `README.md` file. | 1     |
| Documentation | Document your functions using `roxygen2`. It must be possible to access the documentation of your function(s) using the standard syntax `?functioname`. If you are developing an interactive interface you still need to document the function that runs the interface. | 1     |
| Code quality  | Coding style and modularity.                                 | 1     |

#### Laude (30/30 with honors)

If you achieve 30/30 in the previous steps, honors can be awarded based on the code quality.

## Useful links

https://www.unimi.it/en/education/degree-programme-courses/2020/coding-data-science-and-data-management
