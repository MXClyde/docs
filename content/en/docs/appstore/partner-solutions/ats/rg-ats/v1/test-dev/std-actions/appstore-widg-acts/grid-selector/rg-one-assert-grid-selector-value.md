---
title: "Assert Grid Selector Value"
url: /appstore/partner-solutions/ats/rg-one-assert-grid-selector-value/
---

## 1 Description

Asserts the value of the checkbox and the radio button inside the Grid Selector Widget.

## 2 Supported Widgets

* Grid Selector

## 3 Usage

Pass the name of the widget, the column and row caption, and the value you want to assert.

## 4 Input Parameters

Name | Datatype | Required | Description
---- | -------- | ------- |---------------
Widget Name | String | Yes | The name of the widget.
Column Caption | String | Yes | The column caption of the checkbox cell you want to assert.
Row Caption | String | Yes | The row capion of the checkbox cell you want to assert.
Checked | Boolean | Yes | The value you want to assert (true or false).
