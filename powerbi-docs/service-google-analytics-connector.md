---
title: 'Service van derden: Google Analytics-connector voor Power BI Desktop'
description: 'Service van derden: Google Analytics-connector voor Power BI Desktop'
author: davidiseminger
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-desktop
ms.topic: conceptual
ms.date: 07/27/2018
ms.author: davidi
LocalizationGroup: Connect to data
ms.openlocfilehash: 20deb3f0b2f42bfcde66cb685fd6242f7b4a4be3
ms.sourcegitcommit: f01a88e583889bd77b712f11da4a379c88a22b76
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 07/27/2018
ms.locfileid: "39327011"
---
# <a name="google-analytics-connector-for-power-bi-desktop"></a>Google Analytics-connector voor Power BI Desktop
> [!NOTE]
> Het inhoudspakket van Google Analytics en de connector in Power BI Desktop zijn afhankelijk van de rapportage-API van Google Analytics Core. Als zodanig kunnen de functies en beschikbaarheid in de loop van de tijd worden gewijzigd.
> 
> 

U kunt verbinding maken met Google Analytics-gegevens met de **Google Analytics**-connector. Volg deze stappen om verbinding te maken:

1. In **Power BI Desktop** selecteert u op het lint **Start** de opties **Gegevens ophalen**.
2. Selecteer **Online services** in het venster **Gegevens ophalen**, uit de categorieën in het linkerdeelvenster.
3. Selecteer **Google Analytics** in de selecties in het rechterdeelvenster.
4. Selecteer onderin het venster **Verbinding maken**.  
   ![](media/service-google-analytics-connector/tps_googleanalytics_1.png)

Er verschijnt een dialoogvenster waarin wordt uitgelegd dat de connector een service van derden is en u wordt gewaarschuwd over hoe functies en beschikbaarheid na verloop van tijd kunnen veranderen.  
![](media/service-google-analytics-connector/tps_googleanalytics_2.png)

Wanneer u **Doorgaan** selecteert, wordt u gevraagd zich aan te melden bij Google Analytics.  
![](media/service-google-analytics-connector/tps_googleanalytics_3.png)

Wanneer u uw referenties invoert, verschijnt een venster met de melding dat Power BI offline toegang wil. Dit is hoe u **Power BI Desktop** gebruikt voor toegang tot uw Google Analytics-gegevens.  

Zodra u akkoord gaat, geeft **Power BI Desktop** weer dat u bent aangemeld.  
![](media/service-google-analytics-connector/tps_googleanalytics_5.png)

Selecteer **Verbinding maken** en uw Google Analytics-gegevens zijn verbonden met **Power BI Desktop** en de gegevens worden geladen.  
![](media/service-google-analytics-connector/tps_googleanalytics_6.png)

## <a name="changes-to-the-api"></a>Wijzigingen in de API
Hoewel er wordt geprobeerd om updates uit te brengen in het geval van wijzigingen, is het mogelijk dat de API zodanig wordt gewijzigd dat dit van invloed is op de resultaten die worden gegenereerd. In sommige gevallen is het mogelijk dat bepaalde query's niet meer worden ondersteund. Vanwege deze afhankelijkheid kunnen er geen garanties worden gegeven voor de resultaten van uw query's bij gebruik van deze connector.

Zie voor meer informatie over wijzigingen in de Google Analytics-API het bijbehorende [wijzigingslogbestand](https://developers.google.com/analytics/devguides/changelog).

