---
Title: Colors
Description: Page about color analysis
---

<div class="main-text">
    <span class="underline"><h1>Load</h1></span>
    <div class="text">
        <p>Laddnings Uppgiften handlar om att analysera laddningstiden för tre olika webbsidor och komma fram till en slutsats över vilken sida av urvalen som fördröjer sig minst med att ladda sina requests.</p>
    </div>
    <h1>Urval</h1>
    <div class="text">
        <p>Hemsidorna jag valt att undersöka är hemsidor av artister. Jag valde att undersöka artisters egna hemsidor dedikerade till att marknadsföra deras musik osv eftersom de med stor sannolikhet använder sig av en del videos och bilder. Videos och bilder är en stor anledning till varför många sidor har. Sidorna är som följer: beyonce.com, torikellymusic.com, kaceymusgraves.com</p>
    </div>
    <h1>Metod</h1>
    <div class="text">
        <p>För att samla in datan som verkställs i undersökningen så använde jag mig utav två verktyg. Det första verktyget jag använder mig är Googles PageSpeed insights som är ett verktyg utformad för att hjälpa webbplatser med prestandaoptimering genom att webbplatsen undergår ett par tester, såsom accessibility, performance etc. Därpå använder jag mig även av googles dev tools för att ta reda på laddningstiden för sidan och hur många resurser som laddas in.</p>
    </div>
    <h1>Resultat</h1>
    <div class="wrapper-result">
    <iframe class="data-show" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSOudrZeHuyezC-QjH8E0J8W0hF8u6vorOm9K_vPZGieh2mrzMHObawMOyQVcSv3UjIfKtwMm0PMKvK/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
        <div class="result-container">
            <div class="result-title">
                <h4>Tori Kelly</h4>
            </div>
            <img class="result-img" src="../assets/img/tori.png">
            <div class="result-fonts">
                <p>Tori Kellys sida hade relativt snabb laddningstid när sidan laddas med cache inaktiverat, men för nya användare som inte har besökt sidan tidigare så hade Tori Kellys hemsida en laddningstid på cirka 6 sekunder vilket inte är optimalt. Laddningstiden borde ligga mellan 0-4 sekunder för bra conversion rates. Dessutom tar det väldigt länge för hemsidan att få sin first contentful paint, vilket kan vara något som får besökaren att klicka bort sig från sidan eftersom det tar alltför lång tid. Dessutom har hemsidan en massa render blocking resources som gör det långsammare för hemsidan att skicka över sitt content. Hemsidan använder heller inte lazy loading för exempelvis bilder på mobila enheter vilket ökar till dröjningen hos uppladdningen av content för användaren.</p>
            </div>
        </div>
        <div class="result-container2">
            <div class="result-title">
                <h4 style="margin-top: 30px;">Kacey Musgraves</h4>
            </div>
            <img class="result-img" src="../assets/img/kacey.png">
            <div class="result-fonts">
                <p>Kacey Musgraves sida hade en ganska seg laddningstid i jämförelse med de övriga sidorna i urvalet, både med cache aktiverat och inaktiverat. Detta är inte optimalt speciellt för conversion rates. First contentful paint för mobila enheter är väldigt hög i antal sekunder vilket inte är bra, dessutom så använder hemsidan av många bilder som inte är av WebP eller AVIF format vilket gör så att det dröjer ytterligare med nedladdningen av content och data. För desktop ligger dock first contentful paint på gränsen till för dålig vilket är en förbättring i jämförelse med tidigare hemsidan.</p>
            </div>
        </div>
        <div class="result-container2">
            <div class="result-title">
                <h4 style="margin-top: 30px;">Beyonce</h4>
            </div>
            <img class="result-img" src="../assets/img/bey.png">
            <div class="result-fonts">
                <p>Beyonces sida av alla sidor var snabbast både med cache aktiverat och oaktiverat när det kom till laddningstid. Sidan hade dessutom snabbast first contentful paint för både mobila enheter och desktop enheter. Dessutom använder sig hemsidan av lazy load vilket förbättrar användarupplevelsen då användaren inte behöver vänta tills allt har hämtats och laddats ner. De flesta faktorer som leder till hög laddningstid för hemsidan är bilder och oanvänd JavaScript. För mobila enheter har hemsidan sämre performance i jämförelse med desktop, mestadels ligger nog hos bilderna, som inte är lämpligt nerskalade.</p>
            </div>
        </div>
    </div>
    <h1>Analys</h1>
    <div class="text">
        <p>Sidorna som valts i undersökningen verkar alla ha någorlunda lika laddningstid både med cache inaktiverat och aktiverat, förutom Beyonces sida som har en markant förbättring i laddningstid i jämförelse med övriga sidor. Dock så säger PageSpeed Insights att alla dessa sidor är sämre på mobila enheter i jämförelse med Desktop enheter. För det mesta ligger bekymret hos bilderna. Beyonces sida verkar vara den enda sidan som använder sig av lazy load vilket hade behövts i resterande sidor eftersom de använder sig av flera bilder. Dessutom hade sidorna behövt tänka över vilka bilder de använder och se om de kan lägga tid andra storlekar av bilder som hämtas beroende på storleken av webbläsaren. Optimeringen av JavaScript för alla sidor hade även underlättat nedladdningen av content för användaren vilket hade förbättrar laddningstiden för de valda sidorna.<br><br>
        Sammanfattningsvis går det att konstatera att av alla sidor i urvalet var Beyonces den bästa både för mobila enheter och desktop enheter. De resterande sidor fungerade inte lika bra och kräver förbättrníngar för att maximera användarupplevelsen.</p>
    </div>
    <h1>Referenser</h1>
    <div class="text">
        <ul class="reference-list">
            <li><a src="https://beyonce.com/">https://beyonce.com/</a></li>
            <li><a src="http://www.torikellymusic.com/#/">http://www.torikellymusic.com/#/</a></li>
            <li><a src="https://www.kaceymusgraves.com/">https://www.kaceymusgraves.com/</a></li>
        </ul>
    </div>
    <h1>Övrigt</h1>
    <div class="text">
    <p>Författare: Endri Haziri</p>
    </div>
    </div>
    
</div>