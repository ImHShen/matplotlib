Textcolor for legend labels
---------------------------

The text color of legend labels can now be set by passing a parameter 
``textcolor`` to `~.axes.Axes.legend`. The ``textcolor`` keyword can be 
either a single color, which adjusts the color of all of labels. Alternatively, 
it can be a list or tuple, allowing the color of the label texts to be set 
individually. Finally, it can be set to ``linecolor``, ``markerfacecolor``, or 
``markeredgecolor`` so that the label text can be set to the colors of the lines
or markers. 