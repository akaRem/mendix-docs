---
title: "Text Area"
parent: "input-widgets"
menu_order: 20
tags: ["studio pro"]
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

A text area can be used to display and/or edit a long text value that can be split over several lines.

{{% alert type="info" %}}

![](attachments/pages/text-area.png)

This text area allows the end-user to set the description of the product.

{{% /alert %}}

A text area must be placed in a data view or template grid and connected to an attribute of type String. The connected attribute is shown in blue and between brackets inside the text area.

## General Properties

### Grow Automatically

This property defines whether the text area grows automatically depending on the amount of text in it.

_Default value:_ No

{{% alert type="info" %}}Not supported on native mobile pages. On iOS, the text area will grow automatically.{{% /alert %}}

### Number of Lines

The number of lines determine how many lines the text area shows at the same time. If the text in the text area contains more lines you will have to use a scrollbar to see it all. This property is only shown if Grow automatically is set to No.

_Default value:_ 5

### Counter Message

This is the text displayed when typing in the text area. This text has 2 placeholders. The first placeholder shows the number of characters already typed and the second placeholder shows the maximum number of characters.

{{% alert type="info" %}}

You've used {1} characters of the {2} characters that are allowed.

{{% /alert %}}

{{% alert type="info" %}}Not supported on native mobile pages.{{% /alert %}}

### Text Too Long Message

This is the text displayed when the number of typed characters is higher than the maximum allowed number of characters.

{{% alert type="info" %}}Not supported on native mobile pages.{{% /alert %}}

### Maximum Length

This property indicates the maximum number of characters that can be typed in this text box.

| Value | Description |
| --- | --- |
| Attribute length | The maximum number of characters is the same as the maximum length of the connected attribute. |
| Unlimited | The maximum number of characters is unlimited. |
| Custom | The maximum number of characters is set by the user. |

_Default value: Attribute length_

### Placeholder Text

The placeholder text is shown when no text has been entered yet. It can be used to give a hint to the user what kind of text should be entered.

## Validation Properties

{{% snippet file="refguide/Widget+Validation.md" %}}

## Data Source Properties

{{% snippet file="refguide/Attribute+Path+Property.md" %}}

{{% snippet file="refguide/Label+Property.md" %}}

## Editability Properties

{{% snippet file="refguide/Editable+Property.md" %}}

{{% snippet file="refguide/Read+Only+Style.md" %}}

{{% snippet file="refguide/Condition+Property.md" %}}

## Visibility Properties

{{% snippet file="refguide/Visibility+Property.md" %}}

{{% snippet file="refguide/Visibility+Property+With+Module+Roles+Simple.md" %}}

## Events Properties

{{% snippet file="refguide/On+Change+Event.md" %}}

{{% snippet file="refguide/On+Enter+event.md" %}}

{{% snippet file="refguide/On+Leave+Event.md" %}}

## Common Properties

{{% snippet file="refguide/Name+Property.md" %}}

{{% snippet file="refguide/Class+Property.md" %}}

{{% snippet file="refguide/Style+Property.md" %}}

{{% snippet file="refguide/Tab+index+Property.md" %}}

## Read More

*   [Data view](data-view)
*   [Attributes](attributes)
