---
title: "Tab Page"
parent: "tab-container"
tags: ["studio pro"]
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

## General Properties

{{% snippet file="refguide/Caption+Property.md" %}}

### Default tab page

The tab page with the property 'Default page' set to true will be open when the page is opened. If no tab page is the default page, the first tab page will be shown.

_Default value:_ False

### Refresh on show

This property indicates whether the contents of the tab page should be refreshed if the tab page is shown. It is true by default. Set this property to false if refreshing is an expensive operation or if you know that nothing will affect the information on the tab page.

_Default value:_ True

{{% alert type="info" %}}Not supported on native mobile pages.{{% /alert %}}

## Visibility Properties

{{% snippet file="refguide/Visible+Property.md" %}}
