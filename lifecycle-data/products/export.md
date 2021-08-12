---
title: 生命周期数据导出
description: 导出产品生命周期信息
ms.date: 01/06/2021
layout: ContentPage
ms.openlocfilehash: bb0772b4fd406f9567737896de01daedeb25333b5d6846137f164c4ef86ed314
ms.sourcegitcommit: 1c28c95e7a2b743cff45216da63f72ffbad026ed
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/06/2021
ms.locfileid: "2498946"
---
# <a name="lifecycle-data-export"></a>生命周期数据导出

## <a name="export-all-products"></a>出口所有产品
单击以下功能导出所有产品的生命周期数据：

> [!div class="nextstepaction"]
> [出口所有产品](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export)

## <a name="export-products-by-family-and-group"></a>按“系列”和“组”导出产品
选择“系列”，然后选择要导出的“组”。 注意：选择“组”值时将开始导出。 

> [!div class="op_multi_selector" title1="系列" title2="组"]
> - [（.NET | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='.NET'))
> - [(.NET | .NET)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='.NET',group='.NET'))
> - [（Azure | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure'))
> - [(Azure | AI)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='AI'))
> - [(Azure | Azure)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Azure'))
> - [（Azure | 数据库）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Databases'))
> - [（Azure | 其他）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Other'))
> - [（Dynamics | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics'))
> - [(Dynamics | Dynamics)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics'))
> - [(Dynamics | Dynamics 365)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20365'))
> - [(Dynamics | Dynamics AX)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20AX'))
> - [(Dynamics | Dynamics C5)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20C5'))
> - [(Dynamics | Dynamics CRM)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20CRM'))
> - [(Dynamics | Dynamics GP)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20GP'))
> - [(Dynamics | Dynamics NAV)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20NAV'))
> - [(Dynamics | Dynamics POS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20POS'))
> - [(Dynamics | Dynamics RMS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20RMS'))
> - [(Dynamics | Dynamics SL)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20SL'))
> - [（Dynamics | 其他）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Other'))
> - [（Expression | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Expression'))
> - [(Expression | Expression)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Expression',group='Expression'))
> - [（Microsoft 365 | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365'))
> - [（Microsoft 365 | 企业移动性 + 安全性）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365',group='Enterprise%20Mobility%20%2B%20Security'))
> - [（Microsoft 365 | 标识管理）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365',group='Identity%20Management'))
> - [（Microsoft Connected Services Framework | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Connected%20Services%20Framework'))
> - [(Microsoft Connected Services Framework | Connected Services Framework)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Connected%20Services%20Framework',group='Connected%20Services%20Framework'))
> - [（Microsoft Customer Care Framework | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Customer%20Care%20Framework'))
> - [(Microsoft Customer Care Framework | Customer Care Framework)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Customer%20Care%20Framework',group='Customer%20Care%20Framework'))
> - [（Microsoft Edge | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Edge'))
> - [（Microsoft Edge | Edge）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Edge',group='Edge'))
> - [（Microsoft Internet Explorer | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Internet%20Explorer'))
> - [(Microsoft Internet Explorer | Internet Explorer)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Internet%20Explorer',group='Internet%20Explorer'))
> - [（Microsoft Office | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office'))
> - [（Microsoft Office | 客户端）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Client'))
> - [（Microsoft Office | 安全性）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Security'))
> - [（Microsoft Office | 服务器）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Server'))
> - [（Microsoft 服务器 | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers'))
> - [（Microsoft 服务器 | BizTalk Server）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='BizTalk%20Server'))
> - [（Microsoft 服务器 | Commerce Server）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Commerce%20Server'))
> - [（Microsoft 服务器 | Content Management Server）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Content%20Management%20Server'))
> - [（Microsoft 服务器 | Host Integration Server）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Host%20Integration%20Server'))
> - [（Microsoft 服务器 | Intelligent Application Gateway）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Intelligent%20Application%20Gateway'))
> - [（Microsoft 服务器 | 安全性）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Security'))
> - [（Microsoft System Center | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20System%20Center'))
> - [(Microsoft System Center | System Center)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20System%20Center',group='System%20Center'))
> - [（Silverlight | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Silverlight'))
> - [(Silverlight | Silverlight)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Silverlight',group='Silverlight'))
> - [（SQL Server | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server'))
> - [(SQL Server | Power BI)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server',group='Power%20BI'))
> - [(SQL Server | SQL Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server',group='SQL%20Server'))
> - [（Visual Studio | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Visual%20Studio'))
> - [(Visual Studio | Visual Studio)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Visual%20Studio',group='Visual%20Studio'))
> - [（Windows | 全部）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows'))
> - [（Windows | 客户端）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Client'))
> - [(Windows | IoT)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='IoT'))
> - [(Windows | Mobile)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Mobile'))
> - [（Windows | 安全性）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Security'))
> - [（Windows | 服务器）](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Server'))

## <a name="export-products-by-end-of-support-date"></a>在支持日期结束前导出产品
选择一年以查看支持结束的产品。 注意：选择“年份”值后将开始导出。

> [!div class="op_single_selector"]
> - [未来 12 个月](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportMonths=12))
> - [未来 6 个月](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportMonths=6))
> - [2016](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2016))
> - [2017](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2017))
> - [2018](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2018))
> - [2019](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2019))
> - [2020](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2020))
> - [2021](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2021))
> - [2022](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2022))
> - [2023](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2023))
> - [2024](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2024))
> - [2025](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2025))
> - [2026](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2026))
> - [2027](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2027))
> - [2028](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2028))
> - [2029](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2029))
> - [2030](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2030))
