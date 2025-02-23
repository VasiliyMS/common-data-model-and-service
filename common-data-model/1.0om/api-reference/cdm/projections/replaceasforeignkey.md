---
title: Operation Replace as Foreign Key | Microsoft Docs
description: API reference for CdmOperationReplaceAsForeignKey.
author: violivei
ms.service: common-data-model
ms.reviewer: v-iap 
ms.topic: article
ms.date: 02/24/2021
ms.author: violivei
---

# CdmOperationReplaceAsForeignKey

Replacing all input attributes with a foreign key attribute. A `is.linkedEntity.identifier` trait will be added to the attribute linking the foreign key to an attribute on the source. For a detailed description and a list of use cases for this operation refer to [this page](../../../../sdk/projections/replaceasforeignkey.md).

```csharp
public class CdmOperationReplaceAsForeignKey extends CdmOperationBase
```

*CdmProjection extends CdmObjectDefinition in Python.*

## Constructors

|Name|Description|
|---|---|
|**CdmOperationReplaceAsForeignKey(CdmCorpusContext)**<br/>*ctx*: The corpus context.<br/>|Initializes a new instance of the [CdmOperationReplaceAsForeignKey](replaceasforeignkey.md) class.|

## Properties

|Name|Type|Description|
|---|---|---|
|Reference|string|An attribute from the input attributes set that will be referenced by this foreign key.
|ReplaceWith|[CdmTypeAttributeDefinition](..\typeattribute.md)|The foreign key attribute that will be added to the end of the input attributes list.

## Common properties

|Name|Type|Description|
|---|---|---|
|Condition|string|A string condition that is evaluated at runtime to determine if the operation will run or not. If the condition evaluates to false, only this operation will not run.
|Explanation|string|The operation's explanation.
|SourceInput|bool?|Property of an operation that defines if the operation receives the input from previous operation or from source entity. If true, this operation receives the attributes coming from the source entity while if false, receives the attributes coming from the previous operation. In case this property is not set, it defaults to `!runSequentially`.

## Methods

|Name|Description|Return Type|
|---|---|---|
|**GetName()**|See [CdmObjectDefinition.GetName()](../cdmobjectdefinition.md#methods).|string|
|**IsDerivedFrom(string, [ResolveOptions](../../utilities/resolveoptions.md))**|See  [CdmObject.IsDerivedFrom(...)](../cdmobject.md#methods).|bool|
|**Copy([ResolveOptions](../../utilities/resolveoptions.md), [CdmObject](../cdmobject.md))**|See [CdmObject.Copy(...)](../cdmobject.md#methods).|[CdmObject](../cdmobject.md)|
|**Validate()**|See [CdmObject.Validate()](../cdmobject.md#methods).|bool|
