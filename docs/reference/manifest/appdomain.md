---
title: AppDomain element in the manifest file
description: ''
ms.date: 05/15/2019
localization_priority: Normal
---

# AppDomain element

Specifies an additional domain that will be used to load pages in the add-in window.

**Add-in type:** Content, Task pane, Mail

## Syntax

```XML
<AppDomain>string</AppDomain>
```

> [!IMPORTANT]
> 1. The value of the **AppDomain** element must include the protocol (e.g., `<AppDomain>https://myappdomain</AppDomain>`).
> 2. Do *not* put a closing slash, "/", on the value.

## Contained in

[AppDomains](appdomains.md)

## Remarks

**AppDomain** elements should be used to specify any additional domains other than the one specified in the [SourceLocation element](sourcelocation.md). For more information, see [Office Add-ins XML manifest](/office/dev/add-ins/develop/add-in-manifests).
