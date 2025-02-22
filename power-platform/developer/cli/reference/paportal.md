---
title: Microsoft Power Platform CLI paportal command group| Microsoft Docs
description: "Describes commands and parameters for the Microsoft Power Platform CLI paportal command group."
keywords: "pac cli"
ms.subservice: developer
author: kkanakas
ms.author: kartikka
ms.date: 9/15/2022
ms.reviewer: jdaly
ms.topic: reference
contributors: 
 - JimDaly
---
<!-- 
Do not edit this file. 
This file is generated by a program and any changes will be overwritten when this topic is re-generated.
Use the include files to add additional content to this topic.
-->
# pac paportal

Commands for working with Power Apps portal website

[!INCLUDE [paportal-intro](includes/paportal-intro.md)]

## Commands

|Command|Description|
|---------|---------|
|[pac paportal download](#pac-paportal-download)|Download portal website content from the current Dataverse Organization|
|[pac paportal list](#pac-paportal-list)|List all portal websites from the current Dataverse Organization|
|[pac paportal upload](#pac-paportal-upload)|Upload portal website content to current Dataverse Organization|


## pac paportal download

Download portal website content from the current Dataverse Organization

[!INCLUDE [paportal-download-intro](includes/paportal-download-intro.md)]


### Required Parameters

#### `--path` `-p`

Path where the website content will be downloaded

#### `--webSiteId` `-id`

Portal website id to download


### Optional Parameters

#### `--excludeEntities` `-xe`

Comma separated list of entity logical names to exclude downloading

#### `--includeEntities` `-ie`

Download only the entities specified for this argument in comma separated entity logical name

#### `--overwrite` `-o`

Portal website content to overwrite

This parameter requires no value. It is a switch.

[!INCLUDE [paportal-download-remarks](includes/paportal-download-remarks.md)]

## pac paportal list

List all portal websites from the current Dataverse Organization

[!INCLUDE [paportal-list-remarks](includes/paportal-list-remarks.md)]

## pac paportal upload

Upload portal website content to current Dataverse Organization

[!INCLUDE [paportal-upload-intro](includes/paportal-upload-intro.md)]


### Required Parameters

#### `--path` `-p`

Path from where the website content will be uploaded


### Optional Parameters

#### `--deploymentProfile` `-dp`

Deployment profile name to be used. Defaults to 'default'

[!INCLUDE [paportal-upload-remarks](includes/paportal-upload-remarks.md)]

[!INCLUDE [paportal-remarks](includes/paportal-remarks.md)]

### See also

[Microsoft Power Platform CLI Command Groups](index.md)<br />
[Microsoft Power Platform CLI overview](../introduction.md)