---
title: "Navigation List"
parent: "container-widgets"
menu_order: 70
tags: ["studio pro"]
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

{{% alert type="warning" %}}The navigation list widget is not supported on native mobile pages.{{% /alert %}}

A navigation list can be used to attach an action to an entire row. Such a row is called a navigation list item.

{{% alert type="info" %}}

![](attachments/pages/navigation-list.png)
A navigation list with three empty rows.

{{% /alert %}}

## Common properties

{{% snippet file="refguide/Class+Property.md" %}}

{{% snippet file="refguide/Style+Property.md" %}}

## Navigation list item

Each row in the navigation list is a navigation list item. A navigation list item can be associated with an action. Conditional visibility is available for list items.

## General

### Action

Action defines what action is performed when a navigation list item is 'clicked'. This can either be opening a page or calling a microflow. For opening a page see [Opening Pages](opening-pages) and for calling a microflow see [Starting Microflows](starting-microflows). Microflows attached to a navigation list item have no Confirmation or Advanced microflow settings.

## Visibility properties

{{% snippet file="refguide/Visibility+Property.md" %}}

{{% snippet file="refguide/Visibility+Property+With+Module+Roles+Simple.md" %}}
