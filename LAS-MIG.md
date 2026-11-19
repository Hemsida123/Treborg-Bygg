# Treborg Bygg – premium redesign

Färdig lokal webbplatsleverans, skapad 19 november 2026. Ingen publicering eller kontakt med företaget har gjorts.

## Öppna webbplatsen

Öppna **index.html** i en modern webbläsare. All formgivning, alla bilder och alla vyer ingår i filen. Den kan flyttas och öppnas utan mappen assets och fungerar även utan internet. E-post, telefon och externa länkar kräver lämplig app eller uppkoppling.

**redigerbar.html** är samma webbplats med externa bildfiler och är enklare att redigera. Behåll mappen **assets** bredvid den filen.

En lokal förhandsvisningsadress fungerar bara på datorn där förhandsvisningen är igång. Den är inte en offentlig publicering. Den nedladdade fristående index.html behöver ingen lokal server.

## Innehåll och formgivning

18 vyer: startsida, tjänsteöversikt, åtta tjänstesidor, referensgalleri, The Edge, Om oss, arbetsprocess, vanliga frågor, kontakt, offert och integritet. Adresserna fungerar direkt i filen, exempelvis `index.html#/tjanster/renovering`.

Stor fotografisk hero över hela sidbredden och minst hela första skärmhöjden. På korta skärmar får sektionen växa så att text och kontroller får plats. Tre manuella bildval växlar mellan pool, kök och The Edge. Transparent navigation över huvudbilden, solid bakgrund längre ned och på undersidor. Originallogotypens form är bevarad och visas utan bakgrundsruta. Över huvudbilden och i mörkt tema visas den i vitt för kontrast; på ljusa ytor används originalets röda/grå färger.

Responsiv layout, ljust och mörkt färgtema, mobilmeny, klickbara telefon- och mejllänkar, filtrerbart bildgalleri med tangentbordsstöd och ett offertflöde i tre delar. Sidfoten innehåller **Designed by Ekom**, länkat till https://ekom.se.

## Formulären

Kontakt och offert **förbereder ett mejl**, utan att skicka det. Besökaren granskar och skickar själv i sin e-postapp. Det finns också nedladdning av underlag som textfil. Bilder och ritningar bifogas manuellt i mejlet.

Mottagaren är originalets **info@treborgbygg.se**. Namn och e-post är obligatoriska; telefon och företagsnamn är valfria. Offerten kräver dessutom tjänst, ort och projektbeskrivning. Ingen automatisk mottagning, svarstid eller leveransbekräftelse utlovas.

Uppgifterna finns endast i minnet i den öppna fliken och töms vid omladdning eller stängning. Ingen server, databas, spårning eller kakhantering behövs. Automatiskt inskick kräver en separat konfigurerad och testad mottagartjänst.

## Källor och företagsuppgifter

Företagsnamn, telefon, e-post, kontorsadress, tjänster, arbetsområde, grundande 2017 och referenser är kontrollerade mot originalwebbplatsen. Org.nr **559104-7831** och företagsidentitet stöds även av extern registerinformation. Östergatan 62 presenteras som kontor enligt webbplatsen; registeradressen skiljer sig och har inte blandats in som besöksadress. Inga öppettider eller teamprofiler har hittats på originalet och sådana har inte lagts till.

Fakta, källor och verifieringsgränser finns i **KALLOR.md** och **foretagsuppgifter.json**. Kontrollera uppgifterna med företaget före offentlig publicering.

## Bilder och referenser

Originallogotyp och bildmaterial är hämtade från Treborgs befintliga webbplats. Bilderna har bara beskurits, skalats och komprimerats, utan generativa ändringar. **bildkallor.json** anger originaladresser, mått, transformationer och kontrollsummor.

Referensgalleriet innehåller nio unika bilder: sju bildposter från originalets referenssida och två ytterligare kontorsbilder från startsidans The Edge-galleri. Antalet bilder är inte ett påstående om antal separata uppdrag. Originalets benämningar och synliga motiv används utan påhittade beställare, orter, projektår, budgetar eller resultat.

The Edge presenteras som **medverkan i kontorsbyggnation i Hyllie på uppdrag av Peab**, enligt företagets presentation. Inget påstående om totalentreprenörsroll eller formellt kundgodkännande har lagts till. Medverkan vid den nya domstolen i Malmö nämns enbart i text, eftersom ingen bild har identifierats som det projektet.

Originalets AI-genererade rivningsbilder, Getty-bild och andra osäkra illustrationer används inte i det dokumentära galleriet. Inga påhittade recensioner, certifieringar, garantier eller precisa svarstidslöften har lagts till.

## Publicering och adresser

Filerna fungerar på vanlig statisk webbhosting. Mapparna för originalets huvudsidor (`tjanster`, `renovering`, `rivning`, `malning`, `taklaggning`, `referenser`, `omoss`, `contact`) innehåller vidarekopplingar till motsvarande vy.

Vyerna har egna sidtitlar, men är inte separata serverrenderade SEO-sidor. En framtida fullständig SEO-migrering bör ge tjänsterna egna sökbara adresser och anpassa metadata, omdirigeringar och strukturerade företagsuppgifter. Moderna webbläsare behövs för AVIF-bilder och den inbyggda bildvisaren.

## Kontrollerad leverans

Alla 18 vyer har kontrollerats vid fem bredder, 320–1440 pixlar, med ytterligare 36 rutkontroller efter den sista ändringen. Inga trasiga bilder, dubbla huvudrubriker eller horisontella överflöden hittades. Huvudsektionen är också granskad i sju stående och liggande skärmformat upp till 1920 × 1080.

Mobilmeny, bildval, gallerifilter, bildvisarens piltangenter/Escape/fokus, formulärens felmeddelanden, offertsammanställning, textnedladdning, FAQ och färgteman har provats i appens webbläsare. Mejlets mottagare och kodning har kontrollerats isolerat utan att skicka ett meddelande. Den fristående filens avsaknad av externa bild-, stil- och skriptberoenden är kontrollerad; appen tillåter inte ett separat prov via file-adress.

Lighthouse för den lokala fristående filen: tillgänglighet 100, bästa praxis 100, SEO 100, prestanda 67 med simulerad långsam mobiluppkoppling. Filen är cirka 934 kB med alla bilder inbakade, vilket påverkar den simulerade första laddningen. Den redigerbara versionen separerar bilderna. Ett framtida webbhotell bör använda komprimering och cachelagring. Lighthouse ersätter inte manuell tillgänglighetsgranskning eller den SEO-migrering som beskrivs ovan.
