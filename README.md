# Data Science for Researchers

The primary goal of this package is to provide interactive tutorials to facilitate the creation of reproducible research products. 


## Installation

This package includes tutorials that require the `{learnr}` package to run correctly. 


**To install this package:**

```
devtools::install_github("dlapato/ds4research")
```


To begin a tutorial, run `learnr::run_tutorial("tutorial-name", package = "ds4e").

Example:

```
learnr::run_tutorial("penguin-intro", package = "ds4e")
```




## Acknowledgements 

This work is supported by the [VCU Libraries Affordable Course Content Award](https://guides.library.vcu.edu/acca) and [VCU Data Science Lab](https://research.vcu.edu/training/data-science-lab). This package accompanies an open educational resource (currently in development) that will be used for the graduate-level introductory data science courses, [OVPR611/HGEN611 Data Science I](https://osf.io/5gkrc) and [OVPR612/HGEN612 Data Science II](https://github.com/tpyork/hgen-612/tree/main/course-info). 


This package is a work in-progress. We are excited to continue development and to share our resources with other educators, researchers, and data enthusiasts. For course-related updates, please see our [ACCA project page](https://guides.library.vcu.edu/acca/2020#s-lg-box-25505475).
