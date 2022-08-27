[![dataobservatory](https://img.shields.io/badge/ecosystem-dataobservatory.eu-3EA135.svg)](https://dataobservatory.eu/)


You can read this documentation in a book form on [https://curators.dataobservatory.eu/](https://curators.dataobservatory.eu/)

## Folders

**root** - The two articles, `_bookdown.yml` and `_output.yml` for book structural data, `01-xxx.Rmd`, `02-xxx.Rmd` files for each chapter (as text).

**bib** - please save here individual BibTex entries.  The consolidated entries will should be placed in one of the main `.bib` files in the root folder. The pandoc / knitr / RStudio workflow can have hickuups with bib files, so try to save individual files first in `bib/xyz.bib`. The literature review items should be added to the `surveyharmonization.bib` file, making sure that at least the title={}, author={} and the year={} fields are not empty, i.e. if there is only a date ={2022-05-06} field, you create a year = {2022} field, too.

**css** - formatting template for HTML or EPUB or Kindle outputs. 

**latex** - formatting templates for TeX or PDF output.

**docx** - formatting template for docx output.

**not_included** - user's scrap directory, excluded by `.gitignore`.  Please put your non-synchronized scaps and code doodles here.

**png** - the directory for png files, preferably in the correct size,  and in multiple aspect ratios, i.e. 6:4 or 4:6, 16:9, 12:6.  The long side should not be more than 1500 px for in-text illustrations.

**jpg** - the directory for jpg files, prefereably in the correct size, and in multiple aspect ratios, i.e. 6:4 or 4:6, 16:9, 12:6.  The long side should not be more than 1500 px for in-text illustrations.

**R**: folder for R language code.

## Contributor Covenant Code of Conduct

You must abide the [CONTRIBUTOR COVENANT CODE OF CONDUCT](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) pledging to make participation in our community a harassment-free experience for everyone, regardless of age, body size, visible or invisible disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, caste, color, religion, or sexual identity and orientation. (See [translations](https://www.contributor-covenant.org/translations/) and [FAQ](https://www.contributor-covenant.org/faq/).)
