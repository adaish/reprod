### My Reproducible Workflow TESTING 💻🍐⏰
![](https://img.shields.io/badge/progress-IN%20DEV-red.svg)

#### Data Science Workflow 

My initial dream personal foldering - python and r template mix for data science

    project/                Project Name
        data/               Data
            external/       External Data
            interim/        Interim processed Data
            processed/      Processed Data
            raw/            Raw Data
        notebooks/          Notebooks rmarkdown/jupyter
        references/         Document useful development links
        docs/               Store documents
        reports/            Reporting including figures and final reports
             graphs/        Graphs
        src/                Scripts
            munge/          Data Wrangling code
            test/           Testing dev code
            model/          Model code
            visualisation/  Visualise code
        lib/
        logs/
        README
        TODO

----

```r
install.packages('ProjectTemplate')
library('ProjectTemplate')
setwd('')
create.project('ProjectName')
load.project(ProjectName)
```

Project Folders from create.project(minimal = TRUE)
 - **data** where store raw data files (called in load.projects())
 - **doc** store any docs here
 - **graphs** store graphs
 - **munge** preprocessing or data munging code
 - **src** store final scripts (dev script move to munge folder)

R folder that are confusing
 - **cache** means where you store your data (need to use the cache() function for it to be useful) 
 - **config** means what are your settings (need to use DCF " format read.dcf())
 - **diagnostics** means scripts to deal with problems in data
 - **lib** files useful for functionality 
 - **logs** logging work (package log4r)
 - **profiling** benchmarking and timing code
 - **report** output report HTML / latex
 - **tests** test cases 
 
 
References
 - [R project template website]( http://projecttemplate.net/)
 - [R project github template](https://github.com/johnmyleswhite/ProjectTemplate)
 - [R project architecture](http://projecttemplate.net/architecture.html)
 
 - [Cookie Cutter Github](https://github.com/audreyr/cookiecutter)
 - [Cookie Cutter Project Template](https://cookiecutter.readthedocs.io/en/latest/overview.html)
