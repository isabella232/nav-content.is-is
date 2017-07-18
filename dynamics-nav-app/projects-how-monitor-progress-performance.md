---
title: "Hvernig á að: Fylgjast með framvindu og afköstum"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 05b990dd93ddff12581efdc2918ada69681482a1
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-monitor-job-progress-and-performance"></a>Hvernig á að: Fylgjast með framvindu og afköstum
Þegar verk er unnið er efni, forði og annar kostnaður notuð og þetta þarf að bóka á verkið. Verk í vinnslu (VÍV) er eiginleiki þar sem hægt er að meta fjárhagslegt virði verka í fjárhag eftir því sem verkinu miðar áfram. Oft er kostnaður bókaður áður en verk er reikningsfært. Þegar aðeins kostnaður hefur verið bókaður verður fjárhagsyfirlitið ónákvæmt. Frekari upplýsingar eru í [Að skilja VÍV-aðferðir](projects-understanding-wip.md)

Til að rekja gildi í fjárhagnum er hægt að reikna út VÍV og bóka gildið í fjárhag.

VÍV má reikna út byggt á eftirfarandi:

- Kostnaðargildi
- Sölugildi
- Auðkennanlegur kostnaður
- Prósentum lokið
- Samningi lokið

Til að skoða niðurstöður með annarri aðferð er hægt að breyta aðferðinni og reikna Verk í vinnslu á nýjan leik. Engin takmörk eru á því hversu oft VÍV er reiknað. VÍV er aðeins reiknað en er ekki bókað í fjárhag. Þegar VÍV hefur verið reiknað út er hægt að bóka það í fjárhag.

## <a name="to-create-a-job-wip-method"></a>Til að búa til VÍV-aðferð fyrir verk  
Hægt er að búa til VÍV-aðferð sem endurspeglar þarfir fyrirtækisins. Þegar búið er að stofna það, er hægt að velja það sem sjálfgefna VÍV-reikningsaðferð fyrir verk sem verða notuð í fyrirtækinu.  

**Athugasemd** Þegar búið er að nota nýju aðferðina til að stofna VÍV-færslur, er ekki hægt að eyða aðferðinni eða breyta henni.  

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **VÍV-aðferðir verks** og velja síðan viðeigandi tengil.  
2. Veljið aðgerðina **Nýtt** og fyllið svo út reitina eins og þörf krefur. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.  
3. Glugganum er lokað.   
4. Til að gera þessa nýju aðferð að sjálfgefinni aðferð skal velja **Leita að síðu eða skýrslu** uppi í hægra horninu, slá inn **Uppsetning verka** og velja síðan viðeigandi tengil.  
5. Í reitnum **Sjálfgefin vÍv-aðferð** veljið aðferðina af listanum.

## <a name="to-define-a-wip-method-for-a-job"></a>Til að skilgreina VÍV aðferð fyrir verk  
Þegar nýtt verk er stofnað þarf að tilgreina hvaða VÍV-aðferð skuli eiga við. Í sumum tilfellum er þegar búið að stilla sjálfgefna VÍV-aðferð verka.

1. Uppi í hægra horninu skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Verk** og velja svo viðeigandi tengil.
2. Valið er **Nýtt** aðgerð. Nánari upplýsingar eru í [Hvernig á að: Stofna verk](projects-how-create-jobs.md).  
3. Í glugganum **Verkspjald** skal velja VÍV-aðferð úr listanum í reitnum **VÍV-aðferð**. Ef sjálfgefin aðferð hefur verið skilgreind er hægt að velja annan valkost ef þess gerist þörf.  

## <a name="to-calculate-wip"></a>Útreikningur VÍV  
Hægt er að ákvarða VÍV-upphæð sem bóka skal á efnahagsreikning fyrir árslokaskýrslu. Þetta má gera með því að nota keyrsluna **Verkreikna VÍV**.  

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Verk - Reikna VÍV** og velja síðan viðeigandi tengil.  
2. Veljið aðgerðina **Reikna VÍV**.
3. Í glugganum **Verk - Reikna VÍV** þarf að fylla reitina út eins og þörf krefur.
4. Velja hnappinn **Í lagi**.  

**Til athugunar**: Keyrslan reiknar einungis út VÍV. Er ekki bókað í fjárhag. Til að gera það verður að keyra keyrsluna **Bóka VÍV á fjárhag** þegar VÍV hefur verið reiknað. Nánari upplýsingar má finna hér á eftir.

## <a name="to-post-wip"></a>Til að bóka VÍV  
Þegar VÍV hefur verið reiknað er hægt að bóka það á efnahagsreikning fyrir árslokaskýrslu. Þetta má gera með því að nota keyrsluna **Bóka VÍV á fjárhag**.

1. Uppi í hægra horninu skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Verk - Bóka VÍV í fjárhag** og velja svo viðeigandi tengil.  
2. Í glugganum **Verk - Bóka VÍV í fjárhag** skal fylla reitina út eins og þörf krefur.  
3. Velja hnappinn **Í lagi**.

## <a name="to-view-job-usage-estimates-and-post-updates"></a>Til að skoða áætlanir um verknotkun og bóka uppfærslur  
Skoða má verknotkun allt að lokum verkefnis í einu skrefi. Til þess er notuð keyrslan **Verk - Reikna eftirstandandi notkun** fyrir alla verkhluta allt að og með lokum verks.  

Á þennan hátt má rekja og bera saman upprunalega áætlun við raunverulegar niðurstöður og gera breytingar eða bæta við færslum eftir þörfum. Taka má dæmi af notanda sem hefur áætlað að verk taki 10 klukkustundir en það hefur þegar tekið 15 klukkustundir. Hann getur bætt klukkustundunum fimm við færslubókarlínu sem fyrir er eða búið til nýja færslubókarlínu til að skilgreina þessa fimm tíma sem yfirvinnu, sem er önnur tegund vinnu. Raunkostnaður og verð eru reiknuð út, sem svo er hægt að bóka í færslubókina.  

**Til athugunar**: Birgðafærslur stofna færslur í birgðahöfuðbók og minnka birgðamagn. Keyrslan **Bóka birgðabreytingar** færir kostnaðinn úr birgðum í fjárhag. Forðafærslur stofna forðafærslur.  

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Verkbækur** og velja síðan viðeigandi tengil.  
2. Veljið viðeigandi verkbók og veljið svo aðgerðina **Reikna eftirstandandi notkun**.  
3. Í glugganum **Verk - Reikna eftirstandandi notkun** skal slá inn númer skjalsins og bókunardagsetninguna sem færa skal í bókina og velja svo hnappinn **Í lagi**.  
4. Uppfærið bókina með þeim breytingum sem kann að vera þörf á.  
5. Veljið **Bókun**.

## <a name="to-view-job-ledger-entries"></a>Verkdagbókarfærslur skoðaðar:
Allar færslur sem tengjast verki eru skráðar í verkdagbækur og tölusettar í réttri röð, byrjað á 1. Í verkdagbókinni er hægt að fá yfirlit um verkfærslurnar.    

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Verkdagbækur** og velja síðan viðeigandi tengil.
2. Valin er viðeigandi dagbók og síðan skal velja aðgerðina **Verklínur**.

Í glugganum **Verkfærslur** er hægt að fara yfir færslur sem tengjast verki.  

## <a name="see-also"></a>Sjá einnig
[Unnið með verkefni](projects-manage-projects.md)  
[Fjármál](finance-setup.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)         
[Stjórna sölu](sales-manage-sales.md)      
[Unnið með Dynamics NAV](ui-work-product.md)  
