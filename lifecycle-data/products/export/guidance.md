---
title: Életciklus-adatok exportálása útmutató
description: Termék életciklus-adatok exportálása útmutató
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: hu-HU
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546858"
---
# <a name="lifecycle-data-export-guidance"></a>Életciklus-adatok exportálása útmutató
Ez a dokumentum a termékexport fájl használatát ismerteti.

## <a name="query-information"></a>Információ a lekérdezésről
A Excel dokumentum olyan mezőket tartalmaz, melyekkel azonosíthatja a terméktáblába beolvasott adatokat.

### <a name="end-of-support"></a>A támogatás megszűnése
A terméktámogatás megszűnése érték a terméktámogatás záró dátuma vagy a kiadás záró dátuma szerint lesz szűrve.

Lehetséges értékek: Mind (nincs szűrő alkalmazva), Év és Tartomány.

### <a name="family"></a>Család
A családi érték szülőszintje szerint szűri a termékeket a család néven ismert hierarchiában.

Lehetséges értékek: Mind (nincs szűrő alkalmazva), Családnév

### <a name="group"></a>Csoport
A csoportérték a szülőszinten (családban) belüli termékeket egy adott csoportra szűri.

Lehetséges értékek: Mind (nincs szűrő alkalmazva), Csoportnév

## <a name="table-columns"></a>Táblázatoszlopok
A terméktábla a termék, kiadások, kibocsátások és a megfelelő támogatási dátumokat definiáló oszlopokból áll.

> [!NOTE]
> Minden termék, kiadás és kibocsátás kombinációhoz külön sort tartalmaz.

### <a name="product"></a>Termék
A termék neve.

### <a name="edition"></a>Kiadás
A kiadás oszlopot a rendszer akkor tölti ki, ha a termék kiadásokat tartalmaz. Ha nincs termékkiadás, ez a mező üres marad.

### <a name="release"></a>Kiadás
A kiadás oszlop akkor kerül feltöltésre, ha a termék több kiadást tartalmaz.
Ha a terméknek csak egy kiadása van, ez a mező üres marad.

### <a name="support-policy"></a>Támogatási szabályzat
Ez a mező határozza meg, hogy a termék mely támogatási szabályzatot követi.

Lehetséges értékek: [Rögzített,](/lifecycle/policies/fixed) [Modern](/lifecycle/policies/modern), Komponens

### <a name="start-date"></a>Kezdő dátum
Támogatási dátum indulása a termékhez.

### <a name="mainstream-date"></a>Alapvető dátum
Ha a támogatási szabályzat **Rögzített** vagy **Komponens**, akkor ez a termék alapvető záró dátuma.
  
Ha a támogatási szabályzat **Modern**, ez a mező üres marad.

### <a name="extended-end-date"></a>Kiterjesztett záró dátum
Ha a támogatási szabályzat **Rögzített** vagy **Komponens**, ez a termék kiterjesztett záró dátuma.

Ha a támogatási szabályzat **Modern**, ez a mező üres marad.

### <a name="retirement-date"></a>Kivezetés dátuma
Ha a támogatási szabályzat **Rögzített** vagy **Komponens**, ez üres marad.

Ha a támogatási szabályzat **Modern**, ez lesz a termék kivezetésének dátuma.

### <a name="release-start-date"></a>Kiadás kezdő dátuma
A kiadás támogatásának kezdési dátuma. Ha a terméknek csak egy kiadása van, ez a mező üres marad.
 
### <a name="release-end-date"></a>Kiadás záró dátuma
A kiadáshoz biztosított támogatás záró dátuma.
Ha a terméknek csak egy kiadása van, ez a mező üres marad.

### <a name="docs-url"></a>Dokumentumok URL-címe
A kiterjesztett dokumentáció URL-címe.
