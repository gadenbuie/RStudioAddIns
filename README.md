RStudioAddIns
=======

What is it intended for?
-----------
`RStudioAddIns` will contain several shortcuts designed to facilitate common tasks for data analysis within RStudio.

What does it currently contain?
-----------
* `Quick View Data Frame` allows you to highlight either a data frame, or code which generates a data frame, in the Source window of RStudio.  When bound to a key board shortcut, it facilitates rapidly viewing data.

    [![Demonstration of Functionality](http://img.youtube.com/vi/unImIIvn0Ho/0.jpg)](https://youtu.be/unImIIvn0Ho)

Installation
------------

```
if (!requireNamespace("devtools", quietly = TRUE))
  install.packages("devtools")

devtools::install_github("digital-dharma/RStudioAddIns")
```

I'd like to contribute - How do I do so?
------------
Please do - Simply submit a pull request.

Acknowledgements
-----------
It's a dynamic time for data science and analytics.  Special thanks to the following groups for providing example / underlying code.

* [RStudio Team](https://www.rstudio.com/) - [AddIn Examples](https://github.com/rstudio/addinexamples)
* [David Holstius](https://github.com/holstius) - [copydat Package](https://github.com/BAAQMD/copydat)
