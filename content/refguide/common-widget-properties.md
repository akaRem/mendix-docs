---
title: "Common Widget Properties"
parent: "common-widgets"
menu_order: 90
tags: ["studio pro"]
---

These are properties that are shared by many widgets. For a complete list of properties, take a look at the relevant widget.

## Behavior Properties

### Required 

This property indicates whether this widget must be filled in by the end user or not. If set to true, this widget can not be left empty and a message will be shown if the end user presses the *Save* button.

_Default value:_ False

### Required message 

This property determines the message that is shown to the end user if the widget is empty and the *Required* property is set to true. This is a translable text. See [Translatable Texts](translatable-texts).

{{% alert type="info" %}}

For example, if an address field is required, the required message for the text box of the address could be something like "The address is required."

{{% /alert %}}

## Common Properties {#common-properties}

### Tab index 

The tab index influences the order in which the end-user navigates through the page using the tab key. By default tab indices are zero and the tab order is determined automatically by the client system. A value of minus one (-1) means that the widget will be skipped when tabbing through the page.

_Default value:_ 0

{{% alert type="info" %}}Tab index is not supported on native mobile pages.{{% /alert %}}

{{% snippet file="refguide/Name+Property.md" %}}

{{% snippet file="refguide/Class+Property.md" %}}

{{% snippet file="refguide/Style+Property.md" %}}

## Data Source Properties

{{% snippet file="refguide/Attribute+Path+Property.md" %}}

## Visibility Properties

{{% snippet file="refguide/Visibility+Property.md" %}}

{{% snippet file="refguide/Visibility+Property+With+Module+Roles+Simple.md" %}}

## Editability Properties

{{% snippet file="refguide/Editable+Property.md" %}}

### Condition

A widget can be made editable based on the value of an attribute of the enclosing data view. The attribute must be of type Boolean or enumeration. For each value, you specify whether the widget is editable. Upon opening the page and upon changing the condition attribute the edit state of the widget will be updated.

Example: you do not have to ask for the marriage date if the end-user indicates that he or she is not married.
