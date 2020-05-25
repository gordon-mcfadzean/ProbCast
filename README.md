# ProbCast
ProbCast is an R Package (under continuous development) by researchers at the University of Strathclyde. It is a collection of functions for probabilistic forecasting (mainly wrappers for existing models), cross-validation, evaluation and visualisation. Central to ProbCast is the data class "MultiQR", for storing the results of multiple quantile regression, and methods for working with MultiQR objects.

See package documentation for details and the script "Example.R" to see ProbCast in action.

## Set-up

You can install the latest version of ProbCast using:

    # install.packages("devtools")
    library(devtools)
    install_github("jbrowell/ProbCast") 

## Usage

The package includes a script `Example.R` which demonstrates much of ProbCast's functionallity.

## Guide for Contributors
Contributors should follow the following guidelines:
- Open new branches when adding new functinoality, or making changes to exisig functions
- Raise *issues* when adding functionality, and identifying and fixing bugs
- Use rogygen to include documentation with each new function. Include helpful notes on all inputs, outputs, and wokrings of the function
- Include helpful comments throughout code
- Add yourself as @author to functions that you have "ownership" of
- Invite others to review pull requests (check for documentation, back compatability, confilcts...)
 
