---
title: "Nanoflow Call"
parent: "action-call-activities"
menu_order: 30
tags: ["studio pro"]
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

{{% alert type="warning" %}}
This activity can only be used in **Nanoflows**.
{{% /alert %}}

## 1 Introduction

The Nanoflow call activity can be used to call another [nanoflow](nanoflows). Arguments can be passed to the nanoflow and the result can be stored in a variable.

{{% alert type="info" %}}

See [Common Properties](microflow-element-common-properties) for properties that all activities share (e.g. caption). This page only describes the properties specific to the action.

{{% /alert %}}

## 2 Action Properties

### 2.1 Nanoflow

The nanoflow that is called by this activity.

### 2.2 Arguments

For each parameter of the nanoflow you have to supply an argument of the same type. The values of the arguments are expressed using [expressions](expressions).

## 3 Output Properties

### 3.1 Return Type

The data type of the result of the called nanoflow. The return type is defined by the called nanoflow.

### 3.2 Variable Name

The name of the variable that will contain the result of the called nanoflow.
