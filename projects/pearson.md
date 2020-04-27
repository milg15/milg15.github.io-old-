## Pearson's correlation diagram for data in mining company in Javasript

**Project description:** Using the [d3.js](https://d3js.org/) library I develeped a small javascript program that recives a csv file and allows to select n ammount of materials, calculates their pearson corelation number and then graphs it. I only was assigned the logic side of this project. 

### 1. Why Javascript?

```javascript
if (isAwesome){
  return true
}
```

### 2. How to calculate the Pearson Correlation Coefficient

Running this function inside a loop. This will return the value that we'll need to show and create the graph.

```javascript
  let coefficient = (n * sumXY - (sumX * sumY))
       / (Math.sqrt((n * sumX2 - Math.pow(sumX, 2)) *
         (n * sumY2 - Math.pow(sumY, 2))));
```

### 3. Graph used - Correlogram

A correlogram or correlation matrix allows to analyse the relationship between each pair of numeric variables of a dataset. This is a very useful type of graph for comparing the pearson coefficient. 

For more details see [d3.js - Correlogram](https://www.d3-graph-gallery.com/correlogram.html).

### 4. What I learned

Before creating this I haven't been using Javascript to this level before. I had to learn about async and sync request for readning the file. I also understood how to manage different js files and I tested the d3 library which have many usages I didn't knew till then. 

<img src="../images/portfolio_pearson_1.jpg?raw=true"/>
