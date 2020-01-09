Textcolor for legend labels
---------------------------

The text color of legend labels can now be set by passing a parameter 
``textcolor`` to `~.axes.Axes.legend`. The ``textcolor`` keyword can be:
 
* A single color (either a string or RGBA tuple), which adjusts the color of 
  all of labels.
* A list or tuple, allowing the color of each label text to be set 
  individually. 
* ``linecolor``, which sets the color of each label to match the corresponding 
  line color.
* ``markerfacecolor``, which sets the color of each label to match the 
  corresponding marker face color 
* ``markeredgecolor``,  which sets the color of each label to match the 
  corresponding marker edge color