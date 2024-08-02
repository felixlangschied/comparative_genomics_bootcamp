# Data Analysis Project

A template for data analysis projects for the Applied Bioinformatics Group at Goethe University Frankfurt.

## How to use

Contributors create a directory for each analysis in the `analysis` directory. Here they can create `data` and `figures` in the exploratory part of the analysis (see `example1`). During the exploratory phase, metadata must be recorded in the filenames of the `data` and `figures`, respectively.

Once a milestone of an analysis is reached the resulting dataset or figure must be copied into the `shared_data` or `final_figures` directory of the project. Each final dataset or final figure must be accompanied by a metadatafile that states:
  - path to the the script that was used to generate the data/figure
  - input data
  - variables

## Open Questions

  - How to handle large datasets/analyses (path to filesystem?, can we share symbolic links via GitHub?)
  
