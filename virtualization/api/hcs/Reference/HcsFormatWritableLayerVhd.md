---
title: HcsFormatWritableLayerVhd
description: HcsFormatWritableLayerVhd
author: faymeng
ms.author: qiumeng
ms.topic: article
ms.prod: virtualization
ms.service: virtualization
ms.date: 06/09/2021
---
# HcsFormatWritableLayerVhd

## Description

This function creates and formats a partition that is intended to be used as a writable layer for a container.

## Syntax

```cpp
HRESULT WINAPI
HcsFormatWritableLayerVhd(
    _In_ HANDLE vhdHandle
    );
```

## Parameters

`vhdHandle`

The handle to an unmounted virtual hard disk.

## Return Values

The function returns [HRESULT](./HCSHResult.md).

## Requirements

|Parameter|Description|
|---|---|
| **Minimum supported client** | Windows 10, version 1809 |
| **Minimum supported server** | Windows Server 2019 |
| **Target Platform** | Windows |
| **Header** | ComputeStorage.h |
| **Library** | ComputeStorage.lib |
| **Dll** | ComputeStorage.dll |