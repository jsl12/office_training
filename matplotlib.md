## [matplotlib](https://matplotlib.org/stable/index.html) (from [NumFOCUS](https://numfocus.org/))

### Basic
```
import matplotlib.pyplot as plt

fig, ax = plt.subplots()
ax.plot(df)
```

### [Tutorials](https://matplotlib.org/stable/tutorials/index.html)

### Intro
<img src="https://matplotlib.org/stable/_images/anatomy.png" style="width: 450px;"/><br>
- [Usage Guide](https://matplotlib.org/stable/tutorials/introductory/usage.html#sphx-glr-tutorials-introductory-usage-py)
- [Lifecycle of a Plot](https://matplotlib.org/stable/tutorials/introductory/lifecycle.html#sphx-glr-tutorials-introductory-lifecycle-py)
    - [pyplot.close](https://matplotlib.org/2.1.0/api/_as_gen/matplotlib.pyplot.close.html)

### Objects
- [`matplotlib.figure.Figure`](https://matplotlib.org/stable/api/figure_api.html?highlight=figure#matplotlib.figure.Figure)
- [`matplotlib.axes.Axes`](https://matplotlib.org/stable/api/axes_api.html?highlight=axes#matplotlib.axes.Axes)
    - [`matplotlib.axes.Axes.plot`](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.plot.html#matplotlib.axes.Axes.plot)
    - [`matplotlib.axes.Axes.grid`](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.grid.html)
- [`matplotlib.dates`](https://matplotlib.org/stable/api/dates_api.html?highlight=date)<br>
<img src="https://matplotlib.org/stable/_images/inheritance-7cb5b23aab984ea1bec93197eb094f726f9f3799.png" style="height: 200px;"/><br>
    - [`matplotlib.dates.DateFormatter`](https://matplotlib.org/stable/api/dates_api.html#matplotlib.dates.DateFormatter)
    - [`matplotlib.dates.ConciseDateFormatter`](https://matplotlib.org/stable/api/dates_api.html#matplotlib.dates.ConciseDateFormatter)
    - [`matplotlib.dates.WeekdayLocator`](https://matplotlib.org/stable/api/dates_api.html?highlight=weekdaylocator#matplotlib.dates.WeekdayLocator)
    - [`matplotlib.dates.MonthLocator`](https://matplotlib.org/stable/api/dates_api.html?highlight=weekdaylocator#matplotlib.dates.MonthLocator)

### Layout
[Tight Layout](https://matplotlib.org/stable/tutorials/intermediate/tight_layout_guide.html) or 
[Constrained Layout](https://matplotlib.org/stable/tutorials/intermediate/constrainedlayout_guide.html)

### Colors
- [Colors Tutorial](https://matplotlib.org/stable/tutorials/colors/colors.html)
- [List of Named Colors](https://matplotlib.org/stable/gallery/color/named_colors.html)
