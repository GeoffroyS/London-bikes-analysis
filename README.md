# London-bikes-analysis
Data exploration: TfL bikes usage in London

## Notes
Data is available [here](https://cycling.data.tfl.gov.uk/)

GitHub doesn't allow JS to run, so you won't see any plot using Bokeh (and hence, its JavaScript API...) in the notebook. Not to worry though, because I'll put these here!
Alternatively, and if you want to read through the code and be able to see the cells with their associated plots, you can see a rendered version of the Jupyter Notebook [on nbviewer](https://nbviewer.jupyter.org/github/GeoffroyS/London-bikes-analysis/blob/master/bikes_analysis.ipynb)

## "temporary title -> plots"
After concatenating all 52 csv files for the whole of 2018 (that's 1 per week), I plotted the number of bikes picked up / hour:
[bikes_per_hour_2018](https://i.imgur.com/HduxOoK.png)
That's for the whole year, but we can still notice the 2 spikes around 8am (going to work...) and 5-6pm (going home!). I mean, surely that's what these mean?

I then plotted the number of bikes picked up depending on the month:
[bikes_per_month_2018](https://i.imgur.com/QT6nhLH.png)
Obvious tendency to cycle more during warmer months.
