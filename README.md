# chess_analytics
What over 20,000 games of chess can tell us

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.
For this project, I used Jupyter notebooks.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using a database of over 20,000 online chess games played on Lichess servers to answer the following questions:

1. Which chess openings lead to the greatest number of wins for white? How about for black? Do rated games affect the opening used?
2. Do time controls affect the winner? Is there a bias towards white or black winner as the number of turns increases?
3. Can we predict the winner based on multiple factors other than player rating? How does this compare to predictions based on player rating only?

## File Descriptions <a name="files"></a>

All the code is in 1 Jupyter notebook available here to showcase work related to the above questions.  The notebook uses headers to mark down each section, beginning
with exploratory data analysis, and ending with chess game winner prediction using logistic regression.  
Markdown cells were used to provide further information about each section.


## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://rbernas.medium.com/chess-analytics-40d9bafe6559).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Lichess and Kaggle for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/datasnaek/chess).   
