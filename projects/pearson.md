## Pearson's correlation diagram for data in mining company in Javasript

**Project description:** Using the [d3.js](https://d3js.org/) library I develeped a small javascript program that recives a csv file and allows to select n ammount of materials, calculates their pearson corelation number and then graphs it. I only was assigned the logic side of this project. 

### 1. Assess assumptions on which statistical inference will be based

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

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
