# Duke Masters of Statistical Science Portfolio

This folder contains files that were modified between the Big Data Bowl Submission and my submission for my Duke MSS portfolio project. These files are:

1.  `TOCQ Calculation.ipynb`: The notebook containing the functions required to calculate **TOCQ**, the code for calculating **TOCQ** for the provided data, and code to save the results into a CSV. This notebook also contains the `plot_play` function used to create play plotting GIFs.
    -  This notebook has been modified by changing the radius `r` used for calculating **TOCQ**.   
2.  `Big Data Bowl Visualizations.Rmd`: The R-markdown file used to create the visualizations other than the play plotting GIF.
    -  This R-markdown file has been modified with added visualizations and changing the visualizations to account for the new data.
4.  Four variations of the `.csv` files `full_dictionary` and `games_dictionary`, which store player/team combinations of **TOCQ** scores and game/player combinations of **TOCQ** scores, respectively.
    -  Files with suffix `_constant.csv` are **TOCQ** calculations with constant radius $r = 1.5$.
    -  Files with suffix `_44.csv` are **TOCQ** calculations with varying radius $r = \max(1, 1 + s\*t + 0.5\*a*t)$ for player speed $s$, player acceleration $a$, and frame rate $t = 0.1$.
    -  **This is the radius chosen for the analysis:** Files with suffix `_54.csv` are **TOCQ** calculations with varying radius $r = \max(1.25, 1.25 + s\*t + 0.5\*a*t)$ for player speed $s$, player acceleration $a$, and frame rate $t = 0.1$.
    -  Files with suffix `_64.csv` are **TOCQ** calculations with varying radius $r = \max(1.5, 1.5 + s\*t + 0.5\*a*t)$ for player speed $s$, player acceleration $a$, and frame rate $t = 0.1$.
5.  `Portfolio Slides.ppt`: The powerpoint presentation of slides for the portfolio.
6.  `Portfolio Report.pdf`: The final portfolio report as a .pdf file.
7.  Figures and Tables: A folder containing the figure and table `png` files for the portfolio slides and report.
