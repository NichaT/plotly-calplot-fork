# Calendar Heatmap with Plotly
Making it easier to visualize and costumize time relevant or time series data with plotly interaction.

This plot is a very similar to the contribuitions available on Github and Gitlab profile pages and to [Calplot](https://github.com/tomkwok/calplot) - which is a pyplot implementation of the calendar heatmap, thus it is not interactive right off the bat.

The first mention I could find of this plot being made with plotly was in [this forum post](https://community.plotly.com/t/colored-calendar-heatmap-in-dash/10907/16) and it got my attention as something it should be easily available to anyone.

# Installation
``` bash
pip install plotly-calplot
```

# Examples
``` python
from plotly_calplot import calplot

fig = calplot(df, x="date", y="value")
fig.show()
# you can also adjust layout and your usual plotly stuff
```

<img src="https://github.com/brunorosilva/plotly-calplot/blob/main/assets/images/example.png?raw=true">
