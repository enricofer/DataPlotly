.. intro:

Data Plotly
===========
Data Plotly is a python plugin for QGIS that allows the creation of `D3 <https://d3js.org/>`_
like plots thanks to the `Plotly library <https://plot.ly/>`_ and the python API.

Plots are totally **dynamic** so the user can easily get may information by hovering
the mouse on the plot. For each plot tons of customization are available.

.. figure:: /img/intro/scatter_example.png
  :scale: 70%
  :align: center

  simple plot example


DataPlotly embrace the idea of **plot container**, in other words the user can create
different plot types and overlay them in the same plot canvas or load them in
different plot canvas.

.. figure:: /img/intro/example.png
  :scale: 70%
  :align: center

  different plot type in the same map canvas

Each plot type has its own configurations and customizations: it is very easy for
the user to choose the best solution that fits all the needs.

Besides the interactive plot canvas, plots can be exported as `png` static images
or as pure `html` files. `html` files be opened with a browser keeping in that way
the plot *interactivity* (e.g. zooming in or out and getting hovering information).

Finally, **plot raw html code** can be copied and pasted somewhere else, for example
in html frame of the QGIS map composer or in an external website.

`Plotly library <https://plot.ly/>`_ javascript code is saved in the local plugin
folder so the plugin is usable also without any Internet connection.
