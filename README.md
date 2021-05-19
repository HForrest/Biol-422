# Biol-422

### Activwatch data analysis

A class project made more effcient. The assigment was to analyze this data in Excel, but a jupyter notebook is an easier way to do this.

This figure is a polar chart of activity over time. The rotational axis is a 24h clock and the radial axis is the activity measurment from the phillips activwatch, units unknown.

![Polar act](https://github.com/HForrest/Biol-422/blob/main/polar_act.png?raw=true)

This figure shows activity over time, but activity is color, daily time is theta, and day of the week is the r axis.
![Heatmap](https://github.com/HForrest/Biol-422/blob/main/WeeklyHeatmap.png)

This figure is a line chart, giving more granular resolution than the polar chart. The overall shapes are less exagerated in this figure, but it doesn't give the same sense of cyclical movement like the polar chart does.

![Mean Actogram](https://github.com/HForrest/Biol-422/blob/main/mean_act.png?raw=true)

This is a figure that shows the activity over the natural log of the light intensity. Uniformly, activity seems to increase with light intensity until the log of light intensity hits 0, at whihc point activity plataeus. The line is a rolling average with a period of 50 observations.

![Light Activity](https://github.com/HForrest/Biol-422/blob/main/light_act.png?raw=true)

This figure is a classic actogram. An actogram shows patterns in activity over the day, with each line down progressing one day, left to right progressing through that day, and the line itself showing the magnitude of the activity. Black days are weekdays, and grey days are weekends. Activity was transformed with a Min-Max feature scale to compress the magnitude.

![Actogram](https://github.com/HForrest/Biol-422/blob/main/actogram.png?raw=true)

