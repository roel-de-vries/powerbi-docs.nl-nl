---
title: SQL Database Auditing-inhoudspakket
description: SQL Database Auditing-inhoudspakket voor Power BI
author: SarinaJoan
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-service
ms.topic: conceptual
ms.date: 08/10/2017
ms.author: sarinas
LocalizationGroup: Connect to services
ms.openlocfilehash: ce1769d343f5a5923b1a436a2cc0c97428f74152
ms.sourcegitcommit: 60fb46b61ac73806987847d9c606993c0e14fb30
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 10/25/2018
ms.locfileid: "50101130"
---
# <a name="sql-database-auditing-content-pack-for-power-bi"></a>SQL Database Auditing-inhoudspakket voor Power BI
Met het Power BI-inhoudspakket voor Azure [SQL Database Auditing](/azure/sql-database/sql-database-auditing/) kunt u de activiteit van uw database begrijpen en meer inzicht krijgen in afwijkingen die kunnen wijzen op problemen voor het bedrijf of vermoedelijke beveiligingsschendingen. 

Maak verbinding met het [SQL Database Auditing-inhoudspakket](https://app.powerbi.com/getdata/services/sql-db-auditing) voor Power BI.

>[!NOTE]
>Het inhoudspakket importeert gegevens van alle tabellen waarvan de naam AuditLogs bevat en voegt deze toe aan een tabel met één gegevensmodel met de naam AuditLogs. De laatste 250.000 gebeurtenissen worden opgenomen en de gegevens worden dagelijks vernieuwd.

## <a name="how-to-connect"></a>Verbinding maken
1. Selecteer **Gegevens ophalen** onder in het linkernavigatievenster.
   
   ![](media/service-connect-to-azure-sql-database-auditing/pbi_getdata.png) 
2. Selecteer in het vak Services de optie Ophalen.
   
   ![](media/service-connect-to-azure-sql-database-auditing/pbi_getservices.png) 
3. Selecteer **SQL Database Auditing** \> **Ophalen**.
   
   ![](media/service-connect-to-azure-sql-database-auditing/sqldbaudit.png)
4. In het venster Verbinding maken met SQL Database Auditing:
   
   - Voer de Azure Table Storage-accountnaam of de URL in waar uw logboeken worden opgeslagen.
   
   - Voer de naam in van de SQL-server die u wilt benaderen. Voer \* in om auditlogboeken voor alle servers te laden.
   
   - Voer de naam van de SQL-database in die u wilt benaderen. Voer \* in om auditlogboeken voor alle databases te laden.
   
   - Voer de naam van de Azure-tabel in die de logboeken bevat die u wilt benaderen. Voer \* in om de auditlogboeken te laden van alle tabellen waarvan de naam AuditLogs bevat.
   
   >[!IMPORTANT]
   >Het is verstandig om altijd een expliciete tabelnaam op te geven, ook als alle auditlogboeken in één tabel zijn opgeslagen.
   
   - Voer de begindatum in van de auditlogboeken die u wilt benaderen. Voer \* in om auditlogboeken te laden zonder een lagere tijdslimiet of 1d om auditlogboeken van de afgelopen dag te laden.
   
   - Voer de einddatum in van de auditlogboeken die u wilt benaderen. Voer \* in om auditlogboeken te laden met een bovenste tijdslimiet.
   
   ![](media/service-connect-to-azure-sql-database-auditing/dbauditing_param.png)
5. Selecteer voor verificatiemethode de optie **Sleutel** en voer uw **Account-sleutel in** \> **Aanmelden**.
   
   ![](media/service-connect-to-azure-sql-database-auditing/pbi_sqlauditing3.png)
6. Nadat de gegevens in Power BI zijn geïmporteerd, ziet u een nieuw dashboard, een nieuw rapport en een nieuwe gegevensset in het navigatiedeelvenster aan de linkerzijde. Nieuwe items zijn gemarkeerd met een geel sterretje \*.
   
   ![](media/service-connect-to-azure-sql-database-auditing/pbi_sqldbauditingnewdash.png)

**Wat nu?**

* [Stel vragen in het vak Q&A](consumer/end-user-q-and-a.md) boven in het dashboard.
* [Wijzig de tegels](service-dashboard-edit-tile.md) in het dashboard.
* [Selecteer een tegel](consumer/end-user-tiles.md) om het onderliggende rapport te openen.
* Als uw gegevensset is ingesteld op dagelijks vernieuwen, kunt u het vernieuwingsschema wijzigen of de gegevensset handmatig vernieuwen met **Nu vernieuwen**

## <a name="next-steps"></a>Volgende stappen
[Gegevens ophalen voor Power BI](service-get-data.md)
[Wat is Power BI?](power-bi-overview.md)
