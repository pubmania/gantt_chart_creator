> __Note__
> While this was useful when I created it, there were limitations to creating gantt this way. It is still useful for creating quick gantt but for anything more detailed I have been using the Jupyter Notebook based gantt which works better and looks great. That is the one I now use more frequently and notebook itself can be found here: https://github.com/pubmania/python_based_gantt_chart_notebook

# Gantt Chart Creator
An html based Gantt chart creator using the [timeline vis javascript library](http://visjs.org/docs/timeline/) and [papaparse javascript library](http://papaparse.com/).

The aim of this tool is to enable creation of Gantt Chart by providing start and end dates for each task in plain text separated by comma.

Alternatively, a simple copy paste of excel columns into the textarea will also provide desired result.

The current interface does make use of the flexibility offered by vis timeline library to customise the look and feel of Gantt Chart by providing custom css. The sample data and sample custom css will help user to understand what to modify and how.

# Demo
This code repository is live for single input [HERE](https://pubmania.github.io/gantt_chart_creator/Gantt_single_input.html). This is the one I will be maintaining going forward.

Another older version with separate tasks and groups entries can be seen [HERE](https://pubmania.github.io/gantt_chart_creator/Gantt.html).

# Release Notes
## 11-04-2018
1. Added Screenshot button. The button utilises [html2canvas javascript](http://html2canvas.hertzen.com/) library to take a screenshot of the Gantt Chart which can be saved with a right click.
2. Fixed code to ensure only one Gantt Chart is created on click of "Create Gantt" button.

# To Do
* Create different configuration items on the front end to modify the various aspects of timeline.
* Read a saved csv to create the Gantt.
* Add color-picker for different Custom CSS elements to make it customisable using the GUI.
