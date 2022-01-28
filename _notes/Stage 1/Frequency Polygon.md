# Frequency Polygon
A graph that represents the ==same set of data as a histogram==.
It uses lines to join the midpoints of each interval. The heights of the points represent [[Frequency Distributions]].
### How to construct it
1. Calculate the midpoint of each interval (aka. [[Class Marks]])
2. Plot the midpoints on a grid, making sure to number the x-axis with a scale that will include the intervals
3. Join the plotted midpoints with the lines

**Pro Tip:** A frequency polygon usually extends 1 unit bellow the smallest interval value and 1 unit beyond the greatest interval value. This extension gives the frequency polygon an appearance of having a starting point and an ending point, which provides a view of the distribution of data.
## Example
Table:

| Minutes    | Class Mark | $f$ |
| ---------- | ---------- | --- |
| \[60-70)   | 65         | 2   |
| \[70-80)   | 75         | 5   |
| \[80-90)   | 85         | 17  |
| \[90-100)  | 95         | 23  |
| \[100-110) | 105        | 25  |
| \[110-120) | 115        | 4   |
| \[120-130) | 125        | 4   | 
Chart:
```chart
type: line
labels: [55, 65, 75, 85, 95, 105, 115, 125, 135]
series:
- title: "Frequency Polygon"
  data: [0, 2, 5, 17, 23, 25, 4, 4, 0]
```