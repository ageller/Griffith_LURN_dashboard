# Griffith LURN dashboard
A dashboard to show data from Prof. James Griffith's urology project.  The directory `flexdashboard` contains code to create the dashboard; please see the `README.md` file in that directory for more information.  I also tested creating many different figures and tables within the `jupyter` directory.

To run these files, you need to create a `data/` directory and populate that with the (currently synthetic) patient time-series data.

The code requires the following standard R libraries:
```
ggplot2
flexdashboard
gt
dplyr
tidyr
cowplot
```

The code also requires the `lurn` package developed by Prof. Griffith, which can be found here: [https://github.com/jameswgriffith/lurn](https://github.com/jameswgriffith/lurn).

For testing in the Jupyter notebook I also installed the following libraries (not used in the dashboard):
```
ggradar 
viridis
```

I personally installed all these libraries within a `conda` environment called `r4-griffith-wsl`.





