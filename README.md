# ess-view

## Summary

A minor-mode to view *R* dataframes within a spreadsheet software.


## Why use ess-view?

*Cleaning Data* is one of the most boring part of the data analysis process; during this process
I find it useful to be able to have a look at the dataframes I'm working with.
Great tools already exist for doing this within R/ess (eg [DT](http://rstudio.github.io/DT/) or [ess-R-data-view](https://github.com/myuhe/ess-R-data-view.el)),
but when working with quite big datasets I personally prefer to use a spreadsheet software.
 The *ess-view* minor mode simply provides functions to create a temporary csv copy of the dataframe of interest and then calls an external spreadsheet software to view it.
 
## Installing

You will need Emacs 24+, `make` and [Cask](https://github.com/cask/cask) to
build the project.

    cd ess-view
    make && make install



## Usage

	
Within the cursor inside a buffer running a *R* process, simply hit

    C-x w

 and you will be asked for the name of the object (dataframe) to view... it's a simple as that!



## Contributing

Yes, please do! See [CONTRIBUTING][] for guidelines.

## License

See [COPYING][]. Copyright (c) 2016 boccigionata.


[CONTRIBUTING]: ./CONTRIBUTING.md
[COPYING]: ./COPYING
