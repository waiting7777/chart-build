Chartbuilder :chart_with_upwards_trend:
============

Chartbuilder is a front-end charting application that facilitates easy creation of simple beautiful charts.

Chartbuilder is the user and export interface. [D4](https://github.com/heavysixer/d4) is the default charting framework.
Chartbuilder powers all chart creation on [Atlas](http://atlas.qz.com), a
charting platform developed by Quartz.

What's new in Chartbuilder 2.0
-------------------------
* The Chart Grid type. Use it to create small multiples of bars, lines, dots, or columns.
* The app has been rewritten in React.js, making it easier to add new chart types or use
third-party rendering libraries, like we are with D4.
* Chart edits are automatically saved to localStorage, and a chart can be
recovered by clicking the "load previous chart" button on loading the page.
* Data input now accepts csv formatted data as well as tsv formated data
* All UI elements belong to [Chartbuilder UI](https://github.com/Quartz/chartbuilder-ui),
a framework of flexible React components that you can use in other projects.

What Chartbuilder is not
-------------------------
+ A replacement for Excel
+ A replacement for Google Spreadsheet
+ A data analysis tool
+ A data transformation tool
