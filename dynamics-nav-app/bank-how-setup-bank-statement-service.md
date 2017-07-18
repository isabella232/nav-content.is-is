---
title: "Hvernig á að: Setja upp Envestnet Yodlee bankastreymisþjónustu"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 270568214afd2ca8af15f0fa7640337c77ec2f1e
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-the-envestnet-yodlee-bank-feeds-service"></a>Hvernig á að: Setja upp Envestnet Yodlee bankastreymisþjónustu
Hægt er að flytja inn rafræn bankayfirlit frá bankanum til að fylla fljótlega út gluggann **Greiðsluafstemmingarbók** þannig að hægt sé að jafna greiðslur og stemma af bankareikninginn. Nánari upplýsingar er að finna í [Jafna greiðslur sjálfkrafa og stemma af bankareikninga](receivables-apply-payments-auto-reconcile-bank-accounts.md).

**Athuga skal að**: Þá Envestnet Yodlee Banka Feeds þjónustupöntunarinnar eða banki anther provider á feed þjónustu kunna að vera tiltækar í kerfinu. Tengiliður félaginn Microsoft ef notaður er bankareikningur feed þjónustu til að flytja inn bankayfirlit.

Þegar búið að virkja bankastreymisþjónustu, verður að tengja viðkomandi netbankareikning sem eru í streymið kemur úr. Þú býrð til tengla frá bankareikningum í netbankareikninga í mismunandi eftirfarandi aðstæður:

- Bankareikningur er ekki til í Dynamics NAV fyrir netbankareikning þinn. Því er stofnarðu bankareikning með því að búa til tengil úr netbankareikningi.
- Bankareikningur er til í Dynamics NAV sem þú vilt tengja úr netbankareikningi.
- Tengdar bankareikning þarf að aftengja af því þú vilt hætta að nota bankastreymisþjónustuna fyrir reikninginn..
- Netbankareikningar hafa breyst og þú vilt uppfæra upplýsingarnar um bankareikninga í Dynamics NAV.

Þegar bankastreymisþjónustan er virkjuð, geturðu sett upp bankareikning til að flytja sjálfvirkt inn nýja bankayfirlitin í **Greiðsluafstemmingarbók** gluggann á tveggja tíma fresti. Færslur fyrir greiðslur sem þegar hafa verið bókaðar sem jöfnuð og/eða stemmt af í **Greiðsluafstemmingarbók** glugganum verða ekki fluttar inn. Sjá frekari upplýsingar í “Til að virkja sjálfvirkan innflutning bankayfirlits” hlutann.

**Athugaðu**: Ef þú notar uppsetningaraðstoðina setja upp fyrirtæki þá geta sum skrefin í eftirfarandi ferlum verða framkvæmd sjálfvirk þegar þú ert kominn í uppsetninguna fyrir bankareikning fyrirtækis. Nánari upplýsingar eru í [Velkomin í Dynamics NAV](across-get-started.md).

## <a name="to-enable-the-bank-feed-service"></a>Til að virkja bankastreymisþjónustu
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **bankareikning** og velja síðan viðkomandi tengil.
2. Opnið bankareikning sem á að nota fyrir bankastreymisþjónustuna.
3. Í á **Bankareiknings** glugganum í á **infflutningssnið BankaYfirlits** er valinn YODLEEBANKFEED .  

Bankastreymisþjónusta verður virkjuð þegar þú tengir bankareikning við tendan netbankareikning. Sjá næsta ferli..  

## <a name="to-create-a-new-linked-bank-account"></a>Stofna nýjan tengdan bankareikning
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **bankareikning** og velja síðan viðkomandi tengil.
2. Valinn er viðeigandi bankareikningur og síðan valið **stofna nýjan tengdan bankareikning**. **Stofnun tengla fyrir Bankareiknings** opnast eftir smá stund.

    **Athuga skal að**: Þessi gluggi sýnir raunverulegt vefsíðu fyrir Bankastreymisþjónustu Envestnet Yodlee. Hugtök og virkni í glugganum mega ekki vera þau sömu og í þessu efnisatriði.  
3. Í á **Stofnun tengla fyrir netbankareikninga** glugga í á **Tengja Reikning** flipanum, skal nota leitaraðgerðina til að finna banka þar sem þú ert með einn eða fleiri netbankareikninga.
4. Veljið nafn banka. **Skrá inn** svæðinu opnast.
5. Sláðu inn notandanafn og aðgangsorð sem er notuð til að skrá inn í netbanka og velja síðan **Næst** hnapp.  
6. Bankastreymisþjónusta undirbýr að tengja fyrsta netbankareikning á tilgreindum banka í nýja bankareikninginn í Dynamics NAV.

    **Athuga skal að**: Ef þú ert með fleiri en einn netbankareikning í bankanum, verður að stofna fleiri bankareikning í Dynamics NAV fyrir þessa aukalegu netbankareikninga. Sjá skref 8 til 10.

    Þegar vinnslunni er lokið á árangursríkan hátt, birtist bankaheiti í á **Mínar Reikninga** svæðinu í á **Tengt** flipanum. Númerið í svigunum gefur til kynna hversu margar netbankareikningar voru tengd við.
7. Velja hnappinn **Í lagi**.

    Ef aðeins einn netbankareikningur er tengist, opnast **Bankareikningsspjald** gluggann fyrir opnast nýr bankareikningur,  forútfylltur með nafni netbankareiknings. Í þessu tilfelli er tenging bankareiknings lokið. Allt sem er eftir er að setja upp bankareikninginn. Frekari upplýsingar sjá [hvernig skal: setja upp bankareikninga](bank-how-setup-bank-accounts.md)

    Ef fleiri en eina netbankareikninga voru tengd, opnast **Stofnun tengla fyrir bankareikning** glugginn og sýnir skrár yfir aukalega netbankareikninga sem eru ekki tengdir í bankareikninga í Dynamics NAV enn. Í því tilviki, fylgið næsta skrefi.  
8. Í á **Stofnun tengla fyrir bankareikning** glugganum, velja línuna fyrir netbankareikning, og velja síðan **tengja í Nýr Bankareikningur** aðgerð.

    opnast **Bankareikningsspjald** gluggann fyrir opnast nýr bankareikningur,  forútfylltur með nafni netbankareiknings.

    Ef bankareikningur er til í Dynamics NAV sem á að tengja annan netbankareikning við, skal fylgt næsta skref.  
9. Í á **Stofnun tengla fyrir bankareikning** glugganum, velja línuna fyrir netbankareikning, og velja síðan **tengja í fyrirliggjandi Bankareikningur** aðgerð.
10. Í glugganum **Listi yfir bankareikninga** er valið bankareikningur sem á að tengja í og smellt á **Í lagi**.

## <a name="to-link-a-bank-account-to-an-online-bank-account"></a>Til að tengja bankareikning í netbankareikning
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **bankareikning** og velja síðan viðkomandi tengil.
2. velja línuna fyrir bankareikning sem er ekki tengdur við netbankareikningur, og velja síðan **tengja í netbankareikning** aðgerð. **Stofnun tengla fyrir netbankareikning** glugginn opnast með heiti bankans sem var forútfylltur í svæðinu **Tengja reikning**
3. Veljið nafn banka. **Skrá inn** svæðinu opnast.
4. Sláðu inn notandanafn og aðgangsorð sem er notuð til að skrá inn í netbanka og velja síðan **Næst** hnapp.

    Bankastreymisþjónusta undirbýr að tengja bankareikning í Dynamics NAV við viðkomandi netbankareikning.

    Þegar vinnslunni er lokið á árangursríkan hátt, birtist bankaheiti í á **Mínar Reikninga** svæðinu í á **Tengt** flipanum. Ef bankinn er með fleiri en einn bankareikning, aðeins bankareikningurinn sem þú valdir í skrefi 2 er tengdur.
5. Velja hnappinn **Í lagi**.

Í glugganum **Bankareikningayfirlit** er valinn  **tengt** gátreiturinn .

## <a name="to-unlink-a-bank-account"></a>Að Aftengja bankareikningi
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **bankareikning** og velja síðan viðkomandi tengil.  
2. Velja línuna fyrir tengdar bankareikning sem á að aftengja frá sínum tengda netbankareikningi, og velja síðan **aftengja frá netbankareikning** aðgerð.

**Athuga skal að**: Ef þú velur **Já** í staðfestingarglugganum, er tengillinn í netbankareikninginn fjarlægður, og innskráningarupplýsingar eru þurrkaðar út. Til að tengja bankareikning við netbankareikning aftur verðurðu að skrá þig inn í bankann aftur. Nánari upplýsingar er að finna í “Til að tengja bankareikning í netbankareikning“ hlutanum.

## <a name="to-update-bank-account-linking"></a>Uppfæra tengla bankareikninga
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **bankareikning** og velja síðan viðkomandi tengil.
2. Valinn er viðeigandi bankareikningur og síðan valið **uppfæra tengla bankareiknings** aðgerðina.

Ef vandamál eru til staðar fyrir tengdu bankareikninga í glugganum **Bankareikningayfirlit** opnast **Stofnun tengla fyrir bankareikninga** og tilgreinir hvaða bankareikningar hafa verið vandamál. Vandamál má besta leyst með því að aftengja netbankareikninginn og síðan endurstofna tengilinn. Nánari upplýsingar er að finna í “Til að tengja bankareikning í netbankareikning“ hlutanum.

## <a name="to-enable-automatic-import-of-bank-statements"></a>Til að virkja sjálfvirkan innflutning bankayfirlits
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **bankareikning** og velja síðan viðkomandi tengil.
2. Veldu línuna fyrir tengdu bankareikningur og síðan valið **uppsetning sjálfvirks innflutnings bankayfirlits** aðgerð.
3. Í glugganum **uppsetning sjálfvirks innflutnings bankayfirlits** glugga í á **Fjöldi daga innifalið** reitnum, er tilgreint hversu langt aftur í tíma á að fá nýjar bankafærslur fyrir.

    **Athuga skal að**: mælt er með því að setja þetta gildi 7 daga eða fleiri.
4. Veldu **virkjað** gátreitinn.  
Á hverri klukkustund, verður nýi **Greiðsluafstemmingarbók** glugginn fylltur út með öllum nýjum greiðslum sem eru gerðar í netbankareikningi

**Athugaðu**: Færslur fyrir greiðslur sem þegar hafa verið bókaðar sem jöfnuð og/eða stemmt af í **Greiðsluafstemmingarbók** glugganum verða ekki fluttar inn.

## <a name="see-also"></a>Sjá einnig  
[Uppsetning bankaþjónustu](bank-setup-banking.md)  
[Stjórna bankareikningum](bank-manage-bank-accounts.md)  
[Jafna greiðslur sjálfkrafa og afstemma bankareikninga](receivables-apply-payments-auto-reconcile-bank-accounts.md)  
[Sérstilling Dynamics NAV með viðbótum ](ui-extensions.md)
