# url_bib_utils
Frequently used abbreviations of conf/journals when writing references by latex

## How to use

1. Clone, or copy and paste `url_bib_utils.sty` into your latex workspace. Note that the name should be same with the name in the step 2 

2. Add the below command in your latex main file, i.e. `${YOUR_BIBTEX_FILE}.tex`

```
$ \usepackage{url_bib_utils}
```

3. Replace the journal/booktitle part in each bibtex with correct abbreviation

For example, in `${YOUR_BIBTEX_FILE}.bib`, change the journal as follows:

**Before**

![before_using_abbrev](before_using_abbrev.PNG)

**After**

![after_using_abbrev](after_using_abbrev.PNG)

And it works! 

