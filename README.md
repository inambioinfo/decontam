# decontam

Contaminant identification from marker-gene and metagenomics data.

### Installation

The decontam package is currently only available as a source package through github, and the following instructions assume that you can compile R packages. This means that you ust have installed R, and that you have the R tool-chain, which requires the [Xcode comnand-line tools](http://railsapps.github.io/xcode-command-line-tools.html) on the Mac and [Rtools](https://cran.r-project.org/bin/windows/Rtools/) on Windows.

The easiest installation method uses the `devtools` package:

```S
library(devtools)
devtools::install_github("benjjneb/decontam")
```

Alternatively you can install frmo source by hand. First download the zipped package and unzip it (or expand the tarball).

Start a fresh R session, and enter the following.

```S
install.packages("path/to/dada2",
                 repos = NULL,
                 type = "source",
                 dependencies = c("Depends", "Suggests","Imports"))
```

### Documentation

An [introductory vignette](vignettes/decontam_intro.html) demonstrating how to use the decontam package to identify contaminants.

Coming soon: Full publication with benchmarking demonstrating how `decontam`inating your data removes kit contaminants, reduces batch effects, and prevents false-positive assocations.

### Other Resources

Bugs and difficulties in using decontam are welcome on [the issue tracker](https://github.com/benjjneb/decontam/issues).

Planned feature improvements are also publicly catalogued at on the "Issues" page for decontam: https://github.com/benjjneb/decontam/issues
