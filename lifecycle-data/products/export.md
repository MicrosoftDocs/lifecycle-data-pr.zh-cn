---
title: 生命周期数据导出
description: 导出产品生命周期信息
ms.date: 08/21/2020
layout: ContentPage
ms.openlocfilehash: 56cab0b1a87b24a963dd5c252a0199dfabb08767
ms.sourcegitcommit: 37ac01a1d5492bb2bf54cbd018ea34074db8c998
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/01/2020
ms.locfileid: "940786"
---
# <a name="lifecycle-data-export"></a><span data-ttu-id="f296d-103">生命周期数据导出</span><span class="sxs-lookup"><span data-stu-id="f296d-103">Lifecycle data export</span></span>

> [!IMPORTANT]
> <span data-ttu-id="f296d-104">此页面正在开发中。</span><span class="sxs-lookup"><span data-stu-id="f296d-104">This page is under development.</span></span>

## <a name="export-all-products"></a><span data-ttu-id="f296d-105">导出所有产品</span><span class="sxs-lookup"><span data-stu-id="f296d-105">Export all products</span></span>
<span data-ttu-id="f296d-106">通过单击以下选项导出所有产品的生命周期数据：</span><span class="sxs-lookup"><span data-stu-id="f296d-106">Export lifecycle data for all products by clicking below:</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="f296d-107">导出所有产品</span><span class="sxs-lookup"><span data-stu-id="f296d-107">Export All Products</span></span>](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export)

## <a name="export-products-by-family-and-group"></a><span data-ttu-id="f296d-108">按系列和组导出产品</span><span class="sxs-lookup"><span data-stu-id="f296d-108">Export products by Family and Group</span></span>
<span data-ttu-id="f296d-109">选择一个系列，然后选择要导出的组。</span><span class="sxs-lookup"><span data-stu-id="f296d-109">Select a Family and then a Group to export.</span></span> <span data-ttu-id="f296d-110">注意：选择 "分组值" 时将开始 "导出"。</span><span class="sxs-lookup"><span data-stu-id="f296d-110">Note: Export will begin when Group value is selected.</span></span> 

> [!div class="op_multi_selector" title1="家长" title2="Group"]
> - [ ( .NET |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'.NET')
> - [ ( .NET | .NET) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'.NET'%20and%20parent/parent/name%20eq%20'.NET')
> - [ (Azure |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure')
> - [ (Azure |AI) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'AI')
> - [ (Azure |Azure) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Azure')
> - [ (Azure |数据库) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Databases')
> - [ (Azure |其他) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Azure'%20and%20parent/parent/name%20eq%20'Other')
> - [ (Dynamics |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics')
> - [ (Dynamics |Dynamics) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics')
> - [ (Dynamics |Dynamics 365) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20365')
> - [ (Dynamics |Dynamics AX) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20AX')
> - [ (Dynamics |Dynamics C5) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20C5')
> - [ (Dynamics |Dynamics CRM) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20CRM')
> - [ (Dynamics |Dynamics GP) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20GP')
> - [ (Dynamics |Dynamics NAV) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20NAV')
> - [ (Dynamics |Dynamics POS) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20POS')
> - [ (Dynamics |Dynamics RMS) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20RMS')
> - [ (Dynamics |Dynamics SL) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Dynamics%20SL')
> - [ (Dynamics |其他) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Dynamics'%20and%20parent/parent/name%20eq%20'Other')
> - [ (表达式 |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Expression')
> - [ (表达式 |表达式) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Expression'%20and%20parent/parent/name%20eq%20'Expression')
> - [ (Microsoft 365 |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365')
> - [ (Microsoft 365 |企业移动性 + 安全性) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365'%20and%20parent/parent/name%20eq%20'Enterprise%20Mobility%20%2B%20Security')
> - [ (Microsoft 365 |身份管理) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20365'%20and%20parent/parent/name%20eq%20'Identity%20Management')
> - [ (Microsoft 连接的服务框架 |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Connected%20Services%20Framework')
> - [ (Microsoft 连接的服务框架 |连接的服务框架) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Connected%20Services%20Framework'%20and%20parent/parent/name%20eq%20'Connected%20Services%20Framework')
> - [ (Microsoft 客户维护框架 |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Customer%20Care%20Framework')
> - [ (Microsoft 客户维护框架 |客户维护框架) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Customer%20Care%20Framework'%20and%20parent/parent/name%20eq%20'Customer%20Care%20Framework')
> - [ (Microsoft Edge |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Edge')
> - [ (Microsoft Edge |边缘) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Edge'%20and%20parent/parent/name%20eq%20'Edge')
> - [ (Microsoft Internet Explorer |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Internet%20Explorer')
> - [ (Microsoft Internet Explorer |Internet Explorer) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Internet%20Explorer'%20and%20parent/parent/name%20eq%20'Internet%20Explorer')
> - [ (Microsoft Office |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office')
> - [ (Microsoft Office |客户端) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Client')
> - [ (Microsoft Office |安全) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Security')
> - [ (Microsoft Office |服务器) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Office'%20and%20parent/parent/name%20eq%20'Server')
> - [ (Microsoft Servers |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers')
> - [ (Microsoft Servers |BizTalk Server) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'BizTalk%20Server')
> - [ (Microsoft Servers |Commerce Server) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Commerce%20Server')
> - [ (Microsoft Servers |内容管理服务器) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Content%20Management%20Server')
> - [ (Microsoft Servers |主机集成服务器) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Host%20Integration%20Server')
> - [ (Microsoft Servers |智能应用程序网关) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Intelligent%20Application%20Gateway')
> - [ (Microsoft Servers |安全) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20Servers'%20and%20parent/parent/name%20eq%20'Security')
> - [ (Microsoft System Center |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20System%20Center')
> - [ (Microsoft System Center |System Center) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Microsoft%20System%20Center'%20and%20parent/parent/name%20eq%20'System%20Center')
> - [ (Silverlight |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Silverlight')
> - [ (Silverlight |Silverlight) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Silverlight'%20and%20parent/parent/name%20eq%20'Silverlight')
> - [ (SQL Server |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server')
> - [ (SQL Server |Power BI) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server'%20and%20parent/parent/name%20eq%20'Power%20BI')
> - [ (SQL Server |SQL Server) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'SQL%20Server'%20and%20parent/parent/name%20eq%20'SQL%20Server')
> - [ (Visual Studio |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Visual%20Studio')
> - [ (Visual Studio |Visual Studio) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Visual%20Studio'%20and%20parent/parent/name%20eq%20'Visual%20Studio')
> - [ (Windows |所有) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows')
> - [ (Windows |客户端) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Client')
> - [ (Windows |IoT) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'IoT')
> - [ (Windows |移动) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Mobile')
> - [ (Windows |安全) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Security')
> - [ (Windows |服务器) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export?$filter=parent%20ne%20null%20and%20parent/parent%20ne%20null%20and%20parent/parent/parent%20ne%20null%20and%20parent/parent/parent/name%20eq%20'Windows'%20and%20parent/parent/name%20eq%20'Server')

## <a name="export-products-by-end-of-support-date"></a><span data-ttu-id="f296d-171">按支持日期结尾导出产品</span><span class="sxs-lookup"><span data-stu-id="f296d-171">Export products by end of support date</span></span>
<span data-ttu-id="f296d-172">选择一年以查看支持结束的产品。</span><span class="sxs-lookup"><span data-stu-id="f296d-172">Select a year to see products reaching the end of support.</span></span> <span data-ttu-id="f296d-173">注意：选择 "年份值" 时将开始 "导出"。</span><span class="sxs-lookup"><span data-stu-id="f296d-173">Note: Export will begin when Year value is selected.</span></span>

> [!div class="op_single_selector"]
> - [2002](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2002))
> - [2003](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2003))
> - [2004](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2004))
> - [2005](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2005))
> - [2006](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2006))
> - [2007](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2007))
> - [2008](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2008))
> - [2009](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2009))
> - [2010](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2010))
> - [2011](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2011))
> - [2012](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2012))
> - [2013](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2013))
> - [2014](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2014))
> - [2015](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2015))
> - [2016](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2016))
> - [2017 年](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2017))
> - [2018 年](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2018))
> - [2019 年](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2019))
> - [2020 年](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2020))
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