---
title: 生命周期数据导出指南
description: 导出产品生命周期信息指南
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546747"
---
# <a name="lifecycle-data-export-guidance"></a>生命周期数据导出指南
本文档介绍如何使用产品导出文件。

## <a name="query-information"></a>查询信息
在 Excel 文档中，有一些字段可帮助标识产品表中填充的数据。

### <a name="end-of-support"></a>支持结束
支持结束值将按产品的支持结束日期或发布结束日期筛选产品。

可能的值： 全部（无筛选），年，范围。

### <a name="family"></a>系列
系列值按层次结构（即“系列”）中的父级筛选产品。

可能的值：全部（无筛选），系列名称

### <a name="group"></a>Group
组值将父级（系列）产品筛选为特定组。

可能的值：全部（无筛选），组名

## <a name="table-columns"></a>表列
产品表由定义产品、版本、发布和相应支持日期的列组成。

> [!NOTE]
> 每个产品、版本和发布的组合都占据一行。

### <a name="product"></a>产品
产品名称。

### <a name="edition"></a>Edition
当产品包含版本时，将填充版本列。 如果没有产品版本，此字段将为空。

### <a name="release"></a>发布
当产品包含多个发布时，将填充发布列。
当产品只有一个发布时，此字段将为空。

### <a name="support-policy"></a>支持策略
此字段定义产品遵循的支持策略。

可能的值：“固定”[](/lifecycle/policies/fixed)，“现代”[](/lifecycle/policies/modern)，“组件”

### <a name="start-date"></a>开始日期
产品的支持开始日期。

### <a name="mainstream-date"></a>主流日期
当支持策略为 **固定** 或 **组件** 时，这是产品的主流结束日期。 
  
当支持策略为 **现代** 时，这将为空。

### <a name="extended-end-date"></a>扩展结束日期
当支持策略为 **固定** 或 **组件** 时，此日期为产品的扩展结束日期。 

当支持策略为 **现代** 时，这将为空。

### <a name="retirement-date"></a>停用日期
当支持策略为 **固定** 或 **组件** 时，这将为空。

当支持策略为 **现代** 时，这将是产品的停用日期。

### <a name="release-start-date"></a>发布开始日期
发布的支持开始日期。 当产品只有一个发布时，此字段将为空。
 
### <a name="release-end-date"></a>发布结束日期
发布的支持结束日期。
当产品只有一个发布时，此字段将为空。

### <a name="docs-url"></a>文档 URL
指向扩展文档的 URL。
