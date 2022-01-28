# Bar Graph
A Bar graph is the ==simplest way== to represent [[Data]].
### Characteristics
- Consists of rectangular bars of equal width
- The space between the consecutive bars must be the same
- Bars can be marked both vertically and horizontally, but vertical ones are more common
- The height of the bars represent the frequency of the corresponding observation
- The Horizontal Axis represents Categories and the Vertical Axis, Frequencies

## Example
Table:

| Activities | No. of Children Involved |
| ---------- | ------------------------ |
| Dance      | 30                       |
| Music      | 40                       |
| Art        | 25                       |
| Cricket    | 20                       |
| Football   | 53                       | 

Bar Graph:
```chart
type: bar
labels: [Dance, Music, Art, Cricket, Football]
series:
- title: "Number of children involved"
  data: [30,40,25,20,53]
 ```