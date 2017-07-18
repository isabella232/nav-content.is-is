---
title: "Hvernig á að búa til sérsniðið útlit"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 90136439e09deb00a9aed9344fc5f89812caef3a
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-create-a-custom-report-layout"></a>Hvernig á að búa til sérsniðið útlit
Sjálfgefið er að skýrsla hafa innbyggt skýrsluútlit, sem getur verið RDLC-skýrsluútlit, Word-skýrsluútlit eða bæði. Ekki er hægt að breyta innbyggðu útliti. Þú getur einnig búið til þitt eigið sérsniðið útlit sem gerir þér kleift að breyta útliti skýrslu þegar hún er skoðuð, prentuð eða vistuð. Hægt er að búa til mörg sérsniðin skýrsluútlit fyrir sömu skýrsluna, og skipta svo á milli útlita fyrir skýrsluna eftir þörfum.

Til að búa til sérsniðið útlit geturðu búið til afrit af öðru sérsniðið útliti, eða bætt við nýju sérsniðnu útliti, sem í flestum tilfellum er byggt á innbyggða útlitinu. Þegar þú bætir við nýju sérsniðnu útliti geturðu valið að bæta við RDLC-skýrsluútliti, Word-skýrsluútliti eða bæði. Nýja sérsniðna útlitið verður sjálfkrafa byggt á innbyggða útlitinu fyrir skýrsluna ef það er til staðar. Ef ekkert innbyggt útlit fyrir gerðina er til þá er stofnað nýtt autt útlit, sem verður að breyta og hanna frá grunni. Frekari upplýsingar um RDLC- og Word-skýrsluútlit, innbyggð útlit, sérsniðið útlit og fleira eru í [stjórna skýrsluútliti](ui-manage-report-layouts.md).  

## <a name="to-create-a-custom-layout"></a>Til að búa til sérsniðið útlit
1. Í efra hægra horni skal útlit táknið **Leita að síðu eða skýrslu**, slá inn **útlit skýrslu - val**, og velja síðan viðeigandi tengil.  
Valmyndin ** Skýrslusnið val** birtir allar skýrslur sem eru í boði í fyrirtækinu sem er tilgreint í reitnum Fyrirtæki efst í glugganum.
2. Stilltu reitinn **Fyrirtæki** á fyrirtækið sem búa á til skýrsluútliti fyrir.
3. Veldu röðina fyrir skýrsluna sem þú vilt stofna útlitið fyrir, og veldu svo **Sérsniðið útlit**.  
Glugginn **Sérsniðið skýrsluútlit** birtist og sýnir öll sérsniðin útlit sem eru í boði fyrir völdu skýrsluna.
4. Ef þú vilt búa til afrit af sérsniðnu útliti sem þegar er til velurðu sérsniðið útlitið af listanum og velur svo **Afrita**.  
Afrit af sérsniðna útlitinu birtist í glugganum **Sérsniðið skýrsluútlit** með orðunum Afrit í reitnum Lýsing.
5. Ef þú vilt bæta við nýju sérsniðnu útliti sem byggir á innbyggðu útliti skaltu gera eftirfarandi:  
    1. Velja **Nýtt**. Glugginn **Setja inn innbyggt útlit fyrir skýrslu** birtist. Reitirnir **Auðkenni** og **Heiti** eru fylltir inn sjálfkrafa.
    2. Til að bæta við sérsniðnu Word-skýrsluútliti fyrir skýrsluna skaltu velja **Setja inn Word-útlit** gátreitinn.
    3. Til að bæta við sérsniðnu RDLC-skýrsluútliti skaltu velja **Setja inn RDLC-útlit** gátreitinn.
    4. Velja hnappinn **Í lagi**.  
    Nýja sérsniðna útlitið birtist í glugganum **Sérsniðið skýrsluútlit**. Ef nýtt útlit byggir á innbyggðu útliti er það með orðin **Afrit af innbyggðu útiliti** í reitnum **Lýsing**. Ef ekkert innbyggt útlit var til staðar fyrir skýrsluna þá er nýja útlitið með orðin **Nýtt útlit** í reitnum **Lýsing**, sem táknar að sérsniðna útlitið er autt.
6. Reiturinn **Heiti fyrirtækis** er sjálfgefið auður, sem táknar að sérsniðið útlit er í boði fyrir skýrsluna í öllum fyrirtækjum. Til að gera sérsniðið útlit aðeins aðgengilegt fyrir tiltekið fyrirtæki, skal velja **Breyta** og stilla síðan reitinn **Heiti fyrirtækis** á það fyrirtæki sem þú vilt.

## <a name="see-also"></a>Sjá einnig
[Stjórna skýrsluútlit](ui-manage-report-layouts.md)  
[Hvernig á að: Breyta hvaða útlit er nú notað í skýrslu](ui-how-change-layout-currently-used-report.md)
