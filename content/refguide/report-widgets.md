---
title: "Report Widgets"
parent: "pages"
menu_order: 50
tags: ["studio pro"]
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

{{% alert type="warning" %}}Report widgets are not supported on native mobile pages.{{% /alert %}}

With reporting, you can create reports over the database data. Reporting is used for creating aggregated information (for example , the total sales per customer).

The difference between a data grid and a report grid is that the data shown in the report grid is not stored in the database. Each time a report is created, the data is retrieved from the database. Data for the reporting widgets is provided by [Datasets](data-sets).

A report can be presented on a [Page](page) in a tabular form using a [Report Grid](report-grid) widget. If the [Data Set](data-sets) corresponding to the report contains parameters, these can be specified by the user via the [Report Parameter](report-parameter) and [Report Date Parameter](report-date-parameter) widgets. Note that all of the report parameters are optional, so it is not obligatory to specify all parameters. The reports are generated at the moment when the end user clicks the [Report Button](report-button).
