---
title: Életciklus-adatok exportálása
description: Termék életciklus-adatok exportálása
ms.date: 01/06/2021
layout: ContentPage
ms.openlocfilehash: 4a27cd96ddaa1b3d128d9f1d711504d88c28e36e
ms.sourcegitcommit: f24c8653f7fd67e5b3f9f41e17b47edcecb5856e
ms.translationtype: HT
ms.contentlocale: hu-HU
ms.lasthandoff: 01/06/2021
ms.locfileid: "1367566"
---
# <a name="lifecycle-data-export"></a>Életciklus-adatok exportálása

## <a name="export-all-products"></a>Az összes termék exportálása
Az életciklus-adatok exportálása az összes termékre az alábbi gombra kattintva:

> [!div class="nextstepaction"]
> [Minden termék exportálása](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export)

## <a name="export-products-by-family-and-group"></a>Termékek exportálása család és csoport szerint
Jelöljön ki egy családot, majd az exportálandó csoportot. Megjegyzés: Az exportálás a Csoportos érték kijelölésétekkor kezdődik. 

> [!div class="op_multi_selector" title1="Család" title2="Csoport"]
> - [(.NET | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='.NET'))
> - [(.NET | .NET)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='.NET',group='.NET'))
> - [(Azure | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure'))
> - [(Azure | AI)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='AI'))
> - [(Azure | Azure)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Azure'))
> - [(Azure | Adatbázisok)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Databases'))
> - [(Azure | Egyéb)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Other'))
> - [(Dynamics | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics'))
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
> - [(Dynamics | Egyéb)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Other'))
> - [(Kifejezés | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Expression'))
> - [(Expression | Expression)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Expression',group='Expression'))
> - [(Microsoft 365 | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365'))
> - [(Microsoft 365 | Vállalati mobilitás + biztonság)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365',group='Enterprise%20Mobility%20%2B%20Security'))
> - [(Microsoft 365 | Identitáskezelés)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365',group='Identity%20Management'))
> - [(Microsoft Connected Services Framework | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Connected%20Services%20Framework'))
> - [(Microsoft Connected Services Framework | Csatlakoztatott szolgáltatások keretrendszere)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Connected%20Services%20Framework',group='Connected%20Services%20Framework'))
> - [(Microsoft Customer Care Framework | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Customer%20Care%20Framework'))
> - [(Microsoft Customer Care Framework | Ügyfélszolgálati keretrendszer)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Customer%20Care%20Framework',group='Customer%20Care%20Framework'))
> - [(Microsoft Edge | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Edge'))
> - [(Microsoft Edge | Edge)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Edge',group='Edge'))
> - [(Microsoft Internet Explorer | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Internet%20Explorer'))
> - [(Microsoft Internet Explorer | Internet Explorer)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Internet%20Explorer',group='Internet%20Explorer'))
> - [(Microsoft Office | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office'))
> - [(Microsoft Office | Client)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Client'))
> - [(Microsoft Office | Security)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Security'))
> - [(Microsoft Office | Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Server'))
> - [(Microsoft Servers | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers'))
> - [(Microsoft Servers | BizTalk Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='BizTalk%20Server'))
> - [(Microsoft Servers | Commerce Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Commerce%20Server'))
> - [(Microsoft Servers | Content Management Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Content%20Management%20Server'))
> - [(Microsoft Servers | Host Integration Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Host%20Integration%20Server'))
> - [(Microsoft Servers | Intelligent Application Gateway)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Intelligent%20Application%20Gateway'))
> - [(Microsoft Servers | Security)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Security'))
> - [(Microsoft System Center | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20System%20Center'))
> - [(Microsoft System Center | System Center)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20System%20Center',group='System%20Center'))
> - [(Silverlight | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Silverlight'))
> - [(Silverlight | Silverlight)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Silverlight',group='Silverlight'))
> - [(SQL Server | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server'))
> - [(SQL Server | Power BI)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server',group='Power%20BI'))
> - [(SQL Server | SQL Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server',group='SQL%20Server'))
> - V[(Visual Studio | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Visual%20Studio'))
> - [(Visual Studio | Visual Studio)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Visual%20Studio',group='Visual%20Studio'))
> - [(Windows | Minden)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows'))
> - [(Windows | Client)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Client'))
> - [(Windows | IoT)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='IoT'))
> - [(Windows | Mobile)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Mobile'))
> - [(Windows | Security)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Security'))
> - [(Windows | Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Server'))

## <a name="export-products-by-end-of-support-date"></a>Termékek exportálása a támogatás dátumának végéig
Válasszon ki egy évet, ahol a támogatás végét elérő termékek láthatóak. Megjegyzés: Az exportálás akkor kezdődik, amikor az Év érték van kiválasztva.

> [!div class="op_single_selector"]
> - [Következő 12 hónap](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportMonths=12))
> - [Következő 6 hónap](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportMonths=6))
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
