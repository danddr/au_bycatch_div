# Austrian BG-trap bycatch: order-level diversity

First analysis of order-level diversity (richness, Shannon exp(H), Diptera share)
by year, season and trap type.

## Files
- `austria_bycatch_diversity.Rmd`: analysis and report (master file)
- `austria_bycatch_diversity.R`: script generated from the Rmd with knitr::purl()
- `austria_bycatch_diversity.pdf`: rendered report

## Data
The data are not included in this repository. Place `austria_insect_taxdiv.xlsx`
in the same folder as the Rmd, then render with:

    rmarkdown::render("austria_bycatch_diversity.Rmd")
