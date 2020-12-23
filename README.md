# Module to manipulate graph.
![Eslint](https://github.com/actions/JSGraph/workflows/Eslint/badge.svg)
Author : [jeanaymeric@gmail.com](mailto:jeanaymeric@gmail.com")

JsDoc : [https://jean-aymeric.github.io/JSGraph/](https://jean-aymeric.github.io/JSGraph/)
### I used the board game ___Les aventuriers du rail Europe___ to experiment with it.
The board game is published by [Days of wonder](https://www.daysofwonder.com/)

![Game board of Les aventuriers du rail Europe](lesaventuriersdurail.jpg)
### Three algorithms are implemented :
- **Prim** with the function getPrimTree()
- **Kruskal** with the function getKruskalTree()
- **Boruvka** with the function getBoruvkaTree()

### There's also a function to calculate the weight of a graph : getTotalWeight()

All the function take a graph parameter.

It's an array of edges. Edge's constructed like this :
|Key|Type|Description|
|----|----|-|
|weight|string|The edge's weight |
|nodes |array |The 2 edge's nodes in string| |

Edge's example :
```
{
    "weight": 3,
    "nodes": [
        "Paris",
        "Frankfurt"
    ]
}
```
