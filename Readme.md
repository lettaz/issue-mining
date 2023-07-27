# An Exploratory Study on what defines a feature from issue label as feature and their characteristics

This is a step by step guide to recreate the dataset and experiments that we performed for this paper.

# Setting up the Anaconda Environment

1) `conda env create --file environment.yml`

2) `conda activate plot`

3) `jupyter notebook`

## Seed data analysis

We got our preliminary dataset result.csv[/result.csv] which already had data on repositories with labels named feature from SEART using the GUI https://seart-ghs.si.usi.ch/

### Steps to reproduce our seed data

1) Execute the code in the file **seed_data_analysis** to fetch all the repos with label named feature and having more than 500 stars with totalIssues greater than 20.


## Methodology 1

The research was broken into two methodology to achieve result, see the folder methodology 1[/methodology1]

1) Execute the code in the file **Documentation.md** to fetch all the repos using Gherkin and having more than 500 stars.

2) Execute the code in the file **Analytics_on_repo.md** to extract all the meta level statistics on the spec files identified in step 1.

## Methodology 2

Execute the file **Parsing_feat_files.md** to perform statistics on the meta stats extracted from the spec files in the previous step.

The *repo_stats.json* is a json file that contains all the meta stats for each feature file in each repository.

## Visualisation

The visualisation of the pipelines are the .png files visible across different folders in the project.
