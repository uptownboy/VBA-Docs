---
title: Shapes.AddChart2 method (Excel)
keywords: vbaxl10.chm638096
f1_keywords:
- vbaxl10.chm638096
ms.prod: excel
ms.assetid: 2d4569df-2f77-40d5-5f81-859e13e0abb7
ms.date: 06/08/2017
localization_priority: Normal
---


# Shapes.AddChart2 method (Excel)

Adds a chart to the document. Returns a  **Shape** object that represents a chart and adds it to the specified collection.


## Syntax

_expression_. `AddChart2`_(Style,_ _XlChartType,_ _Left,_ _Top,_ _Width,_ _Height,_ _NewLayout)_

_expression_ A variable that represents a [Shapes](Excel.Shapes.md) object.


## Parameters



|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Style_|Optional|**Variant**|The chart style. Use "-1" to get the default style for the chart type specified in  **xlChartType**. |
| _XlChartType_|Optional|**Variant**|The type of chart.|
| _Left_|Optional|**Variant**|The position, in [points](../language/glossary/vbe-glossary.md#point), of the left edge of the chart, relative to the anchor.|
| _Top_|Optional|**Variant**|The position, in [points](../language/glossary/vbe-glossary.md#point), of the top edge of the chart, relative to the anchor.|
| _Width_|Optional|**Variant**|The width, in [points](../language/glossary/vbe-glossary.md#point), of the chart.|
| _Height_|Optional|**Variant**|The height, in [points](../language/glossary/vbe-glossary.md#point), of the chart.|
| _NewLayout_|Optional|**Variant**|If  **NewLayout** is **True**, the chart is inserted by using the new dynamic formatting rules (Title is on, and Legend is on only if there are multiple series).|

## Return value

 **SHAPE**


## See also


[Shapes Object](Excel.Shapes.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
