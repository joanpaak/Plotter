# Plotter

A JavaScript class for creating SVG visualizations. Inspired by R's base plotting system.

See quick start and demos to get started.

## Quick start

First create an SVG element in your HTML document...

```
<svg id="plot1></svg>
```

...then you can, as an example, inititalize an empty plot like this:

```
let plot1 = new Plot(
    document.getElementById("plot1"),
    null,
    {
        xlim : [-10, 10],
        ylim : [0, 10]
    }
);
```