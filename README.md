# kosher-pie
A knockout js pi chart component. CSS and HTML from [Lea Verou](https://www.smashingmagazine.com/2015/07/designing-simple-pie-charts-with-css/)

# Installation
```html
<script src='/path/to/knockout.js'></script>
<script src='/path/to/ko-pi-chart.js'></script>
```

# Usage
It's a knockout js component, so add it to you html like so
```html
<kosher-pie params="{ size: 200, percentage: 50 }"></kosher-pie>
```

Current parameters:

| Name | Type | Required | Explanation |
|------|------|----------|-------------|
| size | int  | true     | The size in px of the pie chart |
| percentage | int | true | how much of the pie chart is full (out of 100) |
| color1 | string |      | the fill color of the chart |
| color2 | string |      | the color of the pie slice |

All parameters can be constants
```html
<kosher-pie params="{ size: 200, percentage: 50 }"></kosher-pie>
```
or observables
```html
<kosher-pie params="{ size: sizeOfChart, percentage: currentPercentage }"></kosher-pie>
```

Please see examples folder for working example


# Limitations
Only one pie slice is currently availible. I want to change this.
