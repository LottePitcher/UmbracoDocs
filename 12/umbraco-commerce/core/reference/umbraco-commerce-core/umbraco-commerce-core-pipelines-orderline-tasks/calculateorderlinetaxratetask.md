---
title: CalculateOrderLineTaxRateTask
description: API reference for CalculateOrderLineTaxRateTask in Umbraco Commerce
---
## CalculateOrderLineTaxRateTask

```csharp
public class CalculateOrderLineTaxRateTask : 
    PipelineTaskWithTypedArgsBase<OrderLineCalculationPipelineArgs, OrderLineCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;!0,!1&gt;](../../umbraco-commerce-common/umbraco-commerce-common-pipelines/pipelinetaskwithtypedargsbase-2.md)

**Namespace**
* [Umbraco.Commerce.Core.Pipelines.OrderLine.Tasks](README.md)

### Constructors

#### CalculateOrderLineTaxRateTask

```csharp
public CalculateOrderLineTaxRateTask(IOrderLineCalculator orderLineCalculator)
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderLineCalculation> Execute(OrderLineCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->