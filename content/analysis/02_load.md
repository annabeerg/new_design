---
Title: Laddningstid
Description: En analys av laddningstid på hemsidor. 
---

Laddningstid på hemsidor.
=======================

Rapporten fokuserar på att analysera laddningstid på tre utvalda webbplatser. Denna rapport riktar sig för laddningstid för mobil och dator. I denna rapport har tre klädfretag riktad mot herr mode valts ut. 

Urval
-----------------------

För att få ett mer slumpmässigt val av webbplatser användes sökordet "herrkläder" i Googles söktjänst. Dem tre översta hemsidor valdes som utgångspunkt för denna analys. Undantag för riktad marknadsföring kan ha påverkat denna rapport då det minimerar antagligheten för ett slumpmässigt val. Därav kan undantag ske vid varje sökning av rapportens sökord.

Val av webbplats är beroende av sökordet "herrkläder". Urvalet av hemsida blev därav inriktad mot samma målgrupp; kläder för herrar. Dem tre webbplatserna i toppen av sökordet; Stayhard, Dressman och CareofCarl. Dessa står sorterade efter ordning vid sökning.

Metod
-----------------------

Verktygen som har använts till denna rapport är vertyget PageSpeed Insight, ett vertyg på internet för att mäta laddningstid på specifika hemsidor. För att sammanställa data har Microsoft Ecxell använts. Dessa vertyg har använts för att kunna samla och sammanställa och jämföra data för de utvalda webbplatserna. Detta excell arket är sammanställt i denna rapport under Resultat, för att sedan analyseras i Analys.

Resultat
-----------------------
Microsoft Excell data från de tre hemsidorna.
<iframe width="800" height="540" frameborder="0" scrolling="no" src="https://studentbth-my.sharepoint.com/personal/anbj21_student_bth_se/_layouts/15/Doc.aspx?sourcedoc={8e0f8b1b-42b9-4804-be34-4690f289f392}&action=embedview&wdAllowInteractivity=False&wdHideGridlines=True&wdHideHeaders=True&wdDownloadButton=True&wdInConfigurator=True"></iframe>

Det kan förekomma avvikande variation av prestandapoäng och metriska värden. Bland annat kan ändring av reklam ske, routing för internettrafik och vilken enhet som testen har gjort genom kan även påverka datan. Därav är denna rapport för att minimera avvikande resultat gjorts på samma dator för alla mätningsverktyg. Testen har genomförs flertalet gånger, minst tre gången för att uppmärksamma avvikande resultat. De tre testen på vardera hemsidorna, avvek inget resultat marginellt mot de övriga. Men avvikelser bör tas till hänsyn i sammanställda resultatet. 

###Stayhard
<table>
    <a href="https://www.stayhard.se/">
        <img alt="Stayhard hemsida screenshot" src="http://localhost:8080/dbwebb-kurser/design/me/portfolio/assets/img/stayhard.png" style="width:100%; height:70%;" >
    </a>  
</table>
Enligt PageSpeed Insight får hemsidan resultatet inte godkänt vid test av viktiga webbvärden. Varken i kategori mobil eller dator. Detta beskriver en vägledning för kvalitetssignaler som är avgörande för att leverera en bra upplevelse för användaren på hemsidan. PageSpeed Insight rekommenderar sidan att omedelbart reducera JavaScript som inte används samt reducera CSS som inte används för att göra tidsbesparing på laddningstid. Verktyget påpekar även att bilder bör användas med rätt storlek. PageSpeed Insight beskriver, "Minska mobildataförbrukningen och förbättra inläsningstiden genom att skicka bilder i rätt storlek.". Detta påpekar verktyget bör åtgärdas på en gång för att göra en tidsbesparing på hemsidan. Diagnotiska förbättringar beskrivs bland annat som att minska påverkan från tredjepartkod. Kod från tretton tredjeparter uppmärksammas. Verktyget rekommenderar att låta denna kod läsas in efter att sidans huvudinnehåll har lästs in. Undvik document.write() påpekas även. Detta menar verktyget fördröjer användare med långsam anslutning med tiotalssekunder med script som infogas dynamiskt. PageSpeed Insight menar även att dem bör minska körtiden för JavaScript. Dem rekommenderar även arr begränsa antaler förfrågningar, se punkten Requests under kategorin Inspektera Mozilla. 

###Dressman
<table>
    <a href="https://dressmann.com/sv/">
        <img alt="Dressman hemsida screenshot" src="http://localhost:8080/dbwebb-kurser/design/me/portfolio/assets/img/dressman.png" style="width:100%; height:70%;" >
    </a>  
</table>
Enligt PageSpeed Insight får hemsidan resultatet godkänt vid test av viktiga webbvärden. Både i kategori mobil och dator. Dem påpekar att hemsidan bör ta bort resurser som blockerar redneringen. Lösning på detta är att infoga nödvändig JS-/CSS-kod direkt på sidan och skjut upp inläsningen av JS-kod/formatmallar som är mindre viktiga. Sedan att reducera både CSS och JavaScript som inte används. Dem påpekar även att skjuta upp inläsningen av bilder som inte visas på skärmen efter att alla viktiga resurser genom lat inläsning. Detta kommer att göra att interaktiva tillståndet kommer att minska. Dessa fyra punkter rekomenderar PageSpeed Insight att hemsidan bör åtgärda på en gång för tidsbesparing på laddningstiden. Sedan påpekas även den diagnostiska ändringarna som skulle förbättra laddningstiden. Genom att minska påverkar från tredjepartskod. Fyra tredjeparter uppmärksammas. Passiva lyssnare används inte för att förbättra rullningsprestanda. Alla bilder har inte width och height. PageSpeed Insight påpekar även att hemsidan har ett onödigt stort DOM-träd. PageSpeet Insight belyser "En stor DOM leder till att minnesförbrukning ökar, formatberäkningarna förlängs och att kostsamma flödesuppdateringar för layouten produceras.". Minska körtiden för JavaScript. 

###CareofCarl
<table>
    <a href="https://www.careofcarl.se/">
        <img alt="CarofCarl hemsida screenshot" src="http://localhost:8080/dbwebb-kurser/design/me/portfolio/assets/img/carl.png" style="width:100%; height:70%;" >
    </a>  
</table>
Enligt PageSpeed Insight får hemsidan resultatet inte godkänt vid test av viktiga webbvärden. Varken i kategori mobil eller dator. PageSpeed Insight rekommenderar sidan att omedelbart reducera JavaScript som inte används samt reducera CSS som inte används för att göra tidsbesparing på laddningstid. Diagnotiska värden beskriver bland annat minska nätverksbelastningen som hemsidan har för användaren. Se punkten Media under verktyget Inspektera Mozilla. CareofCarl är det enda av de tre hemsidorna som använder Media filer. 16,90 MB av totala se punkten All, 19.95 MB och efter att ha rullat ner till sidans bott 22,19MB. Det motsvarar 84% av startsida och 76% efter nedrullning av den totala överföringen av filer till besökaren. PageSpeed Insight påpekar just dessa filer under kategorin Media att detta har ett starkt samband med lång inläsningstid. Passiva lyssnare används inte för att förbättra rullningsprestanda. Alla bildelement har inte width och height, arton element uppmärksammas. PageSpeed Insight påpekar även att hemsidan har ett onödigt stort DOM-träd.

Analys
-----------------------
Data från verktyget Inspektera använder CareofCarl betydligt mer överföringar än Stayhard och Dressman som båda har en betydande lägre storlek på öveföringar. Dem tre hemsidorna har en undefärlig ökning på 2 MB från sidans start till sidans bott. Men CareofCarl har en betydanade större grundstorlek på överföringar. Se punkt All. Som nämnt tidigare i resultat, rubrik CareofCarl, är CareofCarl det enda företaget som använder sig av Media genom video på startsidan. 16,90 MB av totalen är Mediafiler. Av hemsidans total består 76% av alla överföringar Mediafiler. Detta gör att datan är betydande större hos företaget än hos Stayhard eller Dressman. Däremot är Stayhard det företag som använder störst överföring av bilder, se punkt Images. Detta är ingen avsevärd marginell skillnad. Dressman är det företaget med mest förfrågningar, se punkt Requests medan stayhard är den med minst.

Genom att belysa PageSpeed Insight prestandapoäng och metriska data och dess rekommendationer kan fler likheter finnas mellan dem tre hemsidorna. Dressman är dock det enda föetaget enligt PageSpeeds långsiktiga mätverk som är godkänt, medans dem andra två blev underkända. Dock finns det flera likheter mellan dem tre hemsidorna som dem kan göra för att förbättra sin laddningstid. Alla tre hemsidorna rekommenderas att reducera både JavaScript och CSS för att förbättra hemsidorna. Både CareofCarl och Stayhard bör minska körtiden för JavaScript. PageSpeed Insight menar att alla tre företagen bör se över sina bilder. Dressman och CareofCarl har inte alla bilder width och height. Medan Stayhard bör använda rätt storlek på sina bilder. Både Stayhard och Dressman bör minska påverkan från tredjepartskoder. Stayhard belysts ha tio tredjeparter mer än Dressman.

Slutligen bör det belysas skillnader på alla tre hemsidor att laddningstiden på dator är betydligt bättre än på mobil. Detta gäller alla tre sidor. 
Men som slutsats anses Dressman som Stayhard som vinnare i laddningstid. Dressman tätt bakom och CareofCarl som sämst. 


Referenser
-----------------------
Google Developers (2021). PageSpeed Insight [Verktyg online]. https://pagespeed.web.dev/  [2021-12-02] 

Mozilla Firefox (2019). Inspektera [Tillägg till webbläsare]. [2021-12-02] 

Webbplatser: <br>
CareOfCarl (2021). CareofCarl. https://www.careofcarl.se/ [2021-12-02] 

Dressman (2021). Dressman. https://dressmann.com/sv/ [2021-12-02] 

Stayhard (2021). Stayhard. https://www.stayhard.se/ [2021-12-02] 


Övrigt
-----------------------

Anna Berg 2021