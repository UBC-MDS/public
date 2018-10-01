# DSCI 521: Computing Platforms for Data Science

How to install, maintain, and use the data scientific software "stack". The Unix operating system, integrated development environments, and problem solving strategies.

## Course Learning Outcomes

By the end of the course, students are expected to:
1. Use the Unix command line to navigate their computer's filesystem.
2. Define and distinguish between absolute file paths and relative file paths.
3. Effectively use local and remote version control software (e.g., Git and GitHub) to organize projects and manage file versions.
4. Create, edit and run reproducible literate Python and R code documents (e.g., reports and presentations) using Jupyter and RMarkdown.
5. Write and edit Markdown and in-line LaTeX syntax within literate code documents.
6. Define and correctly use a project working directory.
7. Diagnose and troubleshoot programming and development environment problems, and explain how such problems can be avoided.


## Assessments

This is an __assignment-based course__. You'll be evaluated as follows:

| Assessment       | Weight  | Location |
|------------------|---------|----------|
| MDS Policies quiz  | 2%      | At home, on Canvas |
| Lab 1 - Introduction to MDS homework and practice with Jupyter Notebooks | 13%   | Submit to Github |
| Lab 2 - Creating webpages/blogs with Git and GitHub | 15%  |   Submit to Github |
| Lab 3 - Introduction to RStudio and RMarkdown for reports and presentations | 15%     | Submit to Github |
| Lab 4 - RStudio projects and driving Git from RStudio | 15%     | Submit to Github |
| Quiz 1           | 20%     |  On Canvas and written in your lab room |
| Quiz 2           | 20%     |  On Canvas and written in your lab room |

Tip: Use the lecture learning objectives as beacons when studying for your quizzes!

## Course preparation
Follow the installation guide for the UBC Master of Data Science Software Stack here: https://ubc-mds.github.io/resources_pages/installation_instructions/

## Lectures
| Lecture | Topic | Readings |
|:-------:|-------|--------------|
| 1 | [Introduction to MDS tools (Unix, Git/GitHub, Jupyter)](lectures/01_lecture-intro-MDS-tools/01_lecture1-intro-MDS-tools.ipynb)| <ul><li>[The Unix Shell: Navigating Files and Directories](https://swcarpentry.github.io/shell-novice/02-filedir/index.html) or [The shell](http://happygitwithr.com/shell.html)</li><li>[Introduce yourself to Git](http://happygitwithr.com/hello-git.html)</li><li>[Connect to GitHub](http://happygitwithr.com/push-pull-github.html)</li><li>[Jupyter Notebook Tutorial: The Definitive Guide](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook?utm_source=adwords_ppc&utm_campaignid=898687156&utm_adgroupid=48947256715&utm_device=c&utm_keyword=&utm_matchtype=b&utm_network=g&utm_adpostion=3o1&utm_creative=261400735633&utm_targetid=aud-390929969673:dsa-473406581035&utm_loc_interest_ms=&utm_loc_physical_ms=9001561&gclid=CjwKCAjw2rjcBRBuEiwAheKeLwdgCbm0w7Mu-oGjlAhbAkfVlCqhO5RhCxB9fXZWS94MGx57RwxA4RoCsFsQAvD_BwE)</ul> |
| 2 | [Getting groovy with Git and GitHub](lectures/02_lecture-git-github/02_lecture-git-github.ipynb) | <ul><li>[Excuse me, do you have a moment to talk about version control? by Jenny Bryan](https://peerj.com/preprints/3159/)</li><li>[Comparing commits across time](https://help.github.com/articles/comparing-commits-across-time/)</li><li>[Resolving a merge conflict using the command line](https://help.github.com/articles/resolving-a-merge-conflict-using-the-command-line/)</li><li>[nbdime – diffing and merging of Jupyter Notebooks](https://nbdime.readthedocs.io/en/stable/)</li></ul>  |
| 3 | [More Git, as well as mark-up languages, webpage basics and GitHub Pages](lectures/03_lecture-more-git-markup-web)  | <ul><li>[.gitignore](https://www.atlassian.com/git/tutorials/saving-changes/gitignore)</li><li>[Fork a repo](https://guides.github.com/activities/forking/)</li><li>[Set up keys for SSH for use with GitHub](http://happygitwithr.com/ssh-keys.html)</li><li>[Getting Started with GitHub Pages](https://guides.github.com/features/pages/)</li><li>[Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)</li><li>[HTML cheat sheet](https://www.w3schools.com/html/default.asp) (reference)</li><li>[LaTeX cheat sheet](http://users.dickinson.edu/~richesod/latex/latexcheatsheet.pdf) (reference)</li></ul> |
| 4 | [Introduction to RStudio and RMarkdown](lectures/04_lecture-intro-rstudio-rmarkdown) | <ul><li>[RStudio's panes](https://campus.datacamp.com/courses/working-with-the-rstudio-ide-part-1/orientation?ex=5)</li><li>[R Markdown Cheat Sheet](https://rmarkdown.rstudio.com/lesson-15.html) (reference) </li><li>[R Markdown Reference Guide](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf) (reference) </li><li>[R Markdown lessons from RStudio](https://rmarkdown.rstudio.com/lesson-1.html)</li><li>[R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/) (reference)</li><li>[R Markdown code chunk options](https://yihui.name/knitr/options/) (reference)</li></ul>  |
| 5 | [Using Jupyter notebooks and RMarkdown to create professional and reproducible presentations](lectures/05_lecture-reproducible-presentations/05_lecture-reproducible-presentations.Rmd) | <ul><li>[R Markdown presentations with ioslides](https://rmarkdown.rstudio.com/ioslides_presentation_format#overview)</li><li>[R Markdown presentations with xaringan](https://bookdown.org/yihui/rmarkdown/xaringan.html)</li><li>[Jupyter presentations with RISE](https://damianavila.github.io/RISE/)</li></ul> |
| 6 | [Let's talk about filenames and Data Science project organization](lectures/06_filename-project-organisation/06_filename-project-organisation.Rmd) | [Good Enough Practices in Scientific Computing](https://swcarpentry.github.io/good-enough-practices-in-scientific-computing/) |
| 7 | [RStudio projects and driving Git from RStudio](hlectures/07_lecture-rstudio-projects-git/07_lecture-rstudio-projects-git.Rmd)  | <ul><li>[Using RStudio Projects](https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects)</li><li>[Connect RStudio to Git and GitHub](http://happygitwithr.com/rstudio-git-github.html)</li><li>[Workflow: projects](http://r4ds.had.co.nz/workflow-projects.html)</li></ul> |
| 8 | [Reading the docs & getting help](lectures/08_lecture-reading-docs-getting-help/08_lecture-reading-docs-getting-help.Rmd) | <ul><li>[Three tips for posting good questions to R-help and Stack Overflow](https://www.r-bloggers.com/three-tips-for-posting-good-questions-to-r-help-and-stack-overflow/)</li><li>[How to create a Minimal, Complete, and Verifiable example](https://stackoverflow.com/help/mcve)</li></ul>  |

## Attributions

Materials were inspired, re-used and re-mixed from the following sources:
- [Software Carpentry](https://software-carpentry.org/), specifically the Unix Shell and Git lessons
- [Happy Git and GitHub for the useR by Jenny Bryan and the STAT 545 TAs](http://happygitwithr.com/)
- [Data 8: The Foundations of Data Science](http://data8.org/), specifically Lab 01
- [Data Carpentry Reproducible Science Workshop](https://datacarpentry.org/rr-organization1/)

## License

The UBC Master of Data Science DSCI 521: Computing Platforms for Data Science course materials here are licensed under the Creative Commons Attribution 2.5 Canada License ([CC BY 2.5 CA](https://creativecommons.org/licenses/by/2.5/ca/)). If re-using/re-mixing please provide attribution and link to this webpage.
