<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128576996/17.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T540964)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->


# Pivot Grid for Web Forms - How to Aggregate Data by the Field's First Value

This example shows how to aggregate data by the field's first value.

<!-- default file list -->
## Files to look at

* [WebForm1.aspx](./CS/AspPivot_CustomAggregates/WebForm1.aspx) (VB: [WebForm1.aspx](./VB/AspPivot_CustomAggregates/WebForm1.aspx))
* [WebForm1.aspx.cs](./CS/AspPivot_CustomAggregates/WebForm1.aspx.cs) (VB:[WebForm1.aspx.vb](./VB/AspPivot_CustomAggregates/WebForm1.aspx.vb))
<!-- default file list end -->

## Overview

This example adds the FirstValue([ProductName]) expression to the _First Sold Product_ field. The expression returns the first sold product by _Sales Persons_ in each product category.

![first value function](images/image.png)

| Calculated Field | Expression |
| --- | --- |
| First Sold Product | ``` FirstValue([ProductName]) ``` |

Call the [CriteriaOperator.RegisterCustomFunction](https://docs.devexpress.com/CoreLibraries/DevExpress.Data.Filtering.CriteriaOperator.RegisterCustomFunction(DevExpress.Data.Filtering.ICustomFunctionOperator)) method to register a custom function in your project (see [WebForm1.aspx.cs](./CS/AspPivot_CustomAggregates/WebForm1.aspx.cs#L9)/[WebForm1.aspx.vb](./VB/AspPivot_CustomAggregates/WebForm1.aspx.vb#L11)).

## Documentation

## More Examples


