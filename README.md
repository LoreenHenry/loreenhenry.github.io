## Loreen Henry
```
# Welcome to my website.
```
#
```
### UT Dallas <www.utdallas.edu>
```

### Tree Assignment
```
An R plot that looks like a tree and has brownish color: 
```
+     geom_segment(aes(x = x1, y = y1, xend = x2, yend = y2),
+                  lineend = "round",
+                  color="burlywood3", # Set Fall color?
+                  data=na.omit(points)) +
+     coord_fixed (ratio = 1) +
+     theme(legend.position="none",
+           panel.background = element_rect(fill="white"),
+           panel.grid=element_blank(),
+           axis.ticks=element_blank(),
+           axis.title=element_blank(),
+           axis.text=element_blank())


```
![An R plot that looks like a tree, brownish color](https://loreenhenry.github.io/Tree1.png "a tree")


![Shape, Color, and Line in Data Visualization](https://github.com/LoreenHenry/Spring.git)
