# Data Story on Happy Moments
It is an analysis of HappyDB database for answering the question, "What makes people happy?". HappyDB is a corpus of 100,000 crowd-sourced happy moments via Amazon's Mechanical Turk. Read more on https://arxiv.org/abs/1801.07746.

Here, I used "Text_Processing.Rmd" in doc folder to process HappyDB and manually removed unrelated and duplicated data. The processed file is named "processed_moments.csv" and located in the output folder. The analysis report is fully conducted by the file "Proj1.Rmd" in the doc folder. There are no additional data, fig, or header files in this project.

### Conclusion
- Children become the main source of happiness once after people become parents.
- If you know sports and video games, you can get along with single men very well.
- Friends, family, life achievement are the most common source of happiness across all groups.

### Prerequisites
Since the project was built in R. The latest version of R is needed. Installation of R packages tidyverse, tidytext, DT, scales,  wordcloud2, gridExtra, ngram, ggplot2, igraph, ggraph, grid is also needed.

### Author
Alexander Chen
