# Histogram
 A graphical representation of a variable in the shape of bars, where the surface of each bar is proportional to the frequency of the represented values
### Characteristics
- Similar to a [[Bar Graph]], but a histogram groups numbers into ranges
- Used for [[Continuous]] variables
- The height of each bar shows how many fall into each [[Range]]
- The range of each bar is also called the [[Class Intervals]]
- We use the [[Class Marks]] to identify each interval.

### How to construct it
1. Consists of rectangular bars of equal width
2. No space between two consecutive bars
3. Usually used with vertical bars
4. The height of each bar represents the [[Frequency Distributions]] of the corresponding observation
5. The Horizontal Axis represents Categories and the Vertical Axis, Frequencies.

## Example
Table:

| Ages   | Class Mark | $\boldsymbol{f}$ |
| ------ | ---------- | --- |
| 20-30  | 25         | 2   |
| 30-40  | 35         | 4   |
| 40-50  | 45         | 4   |
| 50-60  | 55         | 5   |
| 60-70  | 65         | 3   |
| 70-80  | 75         | 1   |
| 80-90  | 85         | 0   |
| 90-100 | 95         | 1   | 
Histogram:
```chart
type: bar
labels: [25, 35, 45, 55, 65, 75, 85, 95]
series:
- title: "Ages of patinets entering the hospital"
  data: [2, 4, 4, 5, 3, 1, 0, 1]
 ```