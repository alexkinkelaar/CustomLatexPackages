# CustomLatexPackages
Implementations for personal custom latex packages


## outlinesExtended
Extends the original `outlines` package, including changing the default implementation such that the first four outline levels are defaulted to `enumerate` lists. In addition, the outline environment is extended to allow for two additional levels not available within the original `outlines` package. These additional levels are set to `itemize` lists.

It is important to understand that LaTeX will not allow for any more than four nested `enumerate` lists - thus if one wishes to change one of the latter lists to an `enumerate`, they must also change one of the initial lists to an `itemize`. Trying to compile with too many `enumerate` lists will throw an error. 
