---
title: HcmBITerminatedApplicantEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# HcmBITerminatedApplicantEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmBITerminatedApplicantEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Applicant](#Applicant)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[Application](#Application)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[CorrespondenceAction](#CorrespondenceAction)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[CreatedSource](#CreatedSource)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[DateOfReceipt](#DateOfReceipt)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[Demographics](#Demographics)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[Department](#Department)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[EducationLevel](#EducationLevel)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[Employment](#Employment)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[Performance](#Performance)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[ExpiryDate](#ExpiryDate)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[GeographicLocation](#GeographicLocation)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[HiringManager](#HiringManager)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[Job](#Job)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[LodgingCost](#LodgingCost)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[Media](#Media)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[OtherCost](#OtherCost)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[Rating](#Rating)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[ReasonCode](#ReasonCode)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[Company](#Company)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[ApplicationStatus](#ApplicationStatus)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[ApplicantType](#ApplicantType)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[RecruitmentProject](#RecruitmentProject)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[TravelCost](#TravelCost)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[StartDate](#StartDate)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[TerminationDate](#TerminationDate)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[JobDetailValidFrom](#JobDetailValidFrom)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[JobDetailValidTo](#JobDetailValidTo)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[PersonDetailsValidFrom](#PersonDetailsValidFrom)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[PersonDetailsValidTo](#PersonDetailsValidTo)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[EmploymentDetailValidFrom](#EmploymentDetailValidFrom)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[EmploymentDetailValidTo](#EmploymentDetailValidTo)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="HcmBITerminatedApplicantEntity.md" target="_blank">HRM/HcmBITerminatedApplicantEntity</a>|

### <a href=#Applicant name="Applicant">Applicant</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Applicant attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Application name="Application">Application</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Application attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrespondenceAction name="CorrespondenceAction">CorrespondenceAction</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrespondenceAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreatedSource name="CreatedSource">CreatedSource</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreatedSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateOfReceipt name="DateOfReceipt">DateOfReceipt</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateOfReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Demographics name="Demographics">Demographics</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Demographics attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Department name="Department">Department</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Department attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EducationLevel name="EducationLevel">EducationLevel</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EducationLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Employment name="Employment">Employment</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Employment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Performance name="Performance">Performance</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Performance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpiryDate name="ExpiryDate">ExpiryDate</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpiryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeographicLocation name="GeographicLocation">GeographicLocation</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeographicLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HiringManager name="HiringManager">HiringManager</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HiringManager attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Job name="Job">Job</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Job attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LodgingCost name="LodgingCost">LodgingCost</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LodgingCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Media name="Media">Media</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Media attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OtherCost name="OtherCost">OtherCost</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OtherCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Rating name="Rating">Rating</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Rating attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonCode name="ReasonCode">ReasonCode</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicationStatus name="ApplicationStatus">ApplicationStatus</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplicantType name="ApplicantType">ApplicantType</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplicantType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecruitmentProject name="RecruitmentProject">RecruitmentProject</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecruitmentProject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TravelCost name="TravelCost">TravelCost</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TravelCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TerminationDate name="TerminationDate">TerminationDate</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TerminationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidFrom name="JobDetailValidFrom">JobDetailValidFrom</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobDetailValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobDetailValidTo name="JobDetailValidTo">JobDetailValidTo</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobDetailValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidFrom name="PersonDetailsValidFrom">PersonDetailsValidFrom</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PersonDetailsValidTo name="PersonDetailsValidTo">PersonDetailsValidTo</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PersonDetailsValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailValidFrom name="EmploymentDetailValidFrom">EmploymentDetailValidFrom</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmploymentDetailValidTo name="EmploymentDetailValidTo">EmploymentDetailValidTo</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmploymentDetailValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: HRM/HcmBITerminatedApplicantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>