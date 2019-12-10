Legend now has a textcolor kwarg
-------------------------------------

The `Axes.legend` method now has a `textcolor` keywork argument. The 
`textcolor`argument can either be a single color, which adjusts the color of 
all of labels. Alternatively, it can be a list or tuple, allowing the color of
the label texts to be set individually. Finally, it can be set to `linecolor`,
`markerfacecolor`, or `markeredgecolor` so that the label text can be set to 
the colors of the lines or markers. 