---
title: "Trustworthy Platform | Microsoft Docs"
description: "Security home page"
author: "robinarh"
manager: "robinarh"
ms.date: "03/21/2018"
ms.topic: "topic"
ms.prod: ""
ms.service: "CommonDataService"
ms.technology: "CommonDataService"
keywords: "CDS, security, RLS"
audience: "Developer"
ms.assetid: c8428002-66e9-46b7-bc3b-0bb4cde2ec52
ms.reviewer: robinr
ms.author: robinr
---

# Trustworthy Platform

[!INCLUDE [](../includes/new-version.md)]


The Common Data Service provides a security framework to help protect your data. All applications that use the Common Data Service, such as Microsoft PowerApps, Microsoft Power BI, and Microsoft Flow, are subject to the security that is defined in the security framework.

Common Data Service security is based on role-based security. Data in the Common Data Service can be secured at several levels:

+ **Database level** – Admins can define which users can perform all administrative operations in the Common Data Service. For more information, see [Security model](security-model.md).
+ **Entity level** – Admins can define which users have access to entities, and what actions those users can take on those entities. For more information, see [Security model](security-model.md).
+ **Record level** – Admins can use policies to define which records a user has access to in a given entity. For more information, see [Security model](security-model.md).