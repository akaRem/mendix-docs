---
title: "Report Grid"
parent: "report-widgets"
menu_order: 10
tags: ["studio pro"]
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

{{% alert type="warning" %}}The template grid widget is not supported on native mobile pages.{{% /alert %}}

This shows the reported data in a grid.

## Data Source Properties

### Data Set

This is the dataset that determines the data that will be shown in the report grid.

## General Properties

### Use Paging

If the expected quantity of the data is too large to be displayed at once, **Use Paging** should be true so that the data is distributed over different pages.

### Page Size

If **Use Paging** is true, this property indicates the number of occurrences that is displayed on one page.

### Zoom

This property can refer to a page. When the user double-clicks an occurrence in the report, that page is displayed.

If the other page contains a report, the columns of the current report can be mapped to the parameters of the report in the other page.

### Column Widths

The widths of the columns are expressed as a percentage of the total width of the basic report. You can edit this property by dragging the border between the columns.

### Show Export Button

If this property is true, the **Export to Excel** button will be available for the user on the report grid.

### Generate Report on Page Load

If this property is false, the report grid will not show its data until the user presses the [Report Button](report-button). This is especially useful if the report uses parameters that should be specified by the user. 

## Common Properties

### Name, Class, Style

For details, see [Common Widget Properties](common-widget-properties).
