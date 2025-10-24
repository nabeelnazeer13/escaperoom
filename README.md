# escaperoom
Submission for A2 HTML CSS

## Språk som används

* HTML
* CSS
* Preprocessor - SASS med SCSS-syntax

## Verktyg

* Code Editor - VSCODE
* Operativsystem - MACOS 26
* Webbläsare - Firefox, Perplexity Comet
* Molnlagring - Google Drive
* Git - Lokalt och Github
* Publicering - Github-pages
* Forskning - Föreläsningar, MDN, W3, Sass, Perplexity

## Arbetsmetod

1. Skapade HTML för både mobil och dator.
2. Skapade styling-css för mobilversionen (v1 basic)
3. Skapade styling-css för skrivbord (v1)
4. Omarbetad styling på båda skärmarna för att finslipa webbplatsen och matcha figma-filen (v2)

### Tid spenderad
~25–30 timmar

Jag arbetade först med HTML-koden och försökte använda BEM-naming. Jag såg till att använda så semantiskt korrekt HTML som möjligt – det betyder att jag använde header, nav, sektioner och artiklar istället för vanliga divs. Bilderna är under IMG-elementet och har alt med text ifall bilden inte laddas.

Jag skapade först HTML-versionen med alla element som krävs i både desktop- och mobilversionen, sedan arbetade jag med SASS för att utforma dokumentet och började med mobil-först-metoden. Jag bestämde mig för att använda scss och css eftersom jag kände att jag förstod för lite om css för att kunna använda andra ramverk som Bootstrap eller Tailwind. Scss gav mig flexibiliteten att använda css samtidigt som jag lade till vissa förbättringar som nestning och mediaqueries under ett och samma ställe. Jag strukturerade koden med hjälp av variabler för att säkerställa att färgerna är desamma och för att minska tiden och skrivtiden varje gång.

Jag använde GRID layouter för de flesta och arbetade med olika antal rader och kolumner för att få plats med innehållet som önskat. Det finns också vissa ställen där jag använde flexbox för att hålla det enkelt och på vissa ställen är det block, särskilt i mobil där många objekt ligger precis under varandra.

Med hjälp av mediaqueries bestämde jag mig för att ha en brytpunkt vid 900px för att jämna ut förändringarna mellan 1280px-skärm och 480px-mobilformatet (hämtat från Figma) så att det inte ändras plötsligt förrän det är väldigt stort.

De utmanande delarna var
1. Knappar framför bilden - II använde position - absolut och relativ för att placera knapparna framför bilden i huvudsektionen.
2. Överflöd av alla challenges som visas i mobilen - Jag gick med en mycket enkel men förmodligen fel lösning genom att ställa in en minsta bredd för varje panel så att den inte är lika responsiv mellan en dator och en mobil och det visas som ett överflöd i mobilversionen.

Mycket av det jag gjorde var nytt och jag var tvungen att ständigt googla eller be AI om hjälp med att lösa problem. Det jag är mest nöjd med är att jag lär mig mer om layout och känner mig bekväm med det. Jag tyckte också om att använda scss och css.

Jag använde terminalen för att initiera och ansluta remote origin men har sedan dess använt VSCODEs inbyggda funktioner för att commit, pull, merge och push. Jag laddade ner bilder från Figma och laddade upp dem till Google Drive och använde URL:en därifrån i min html. Jag använde Live Server-extension för konstant övervakning och feedback. Jag använde Firefox och Comet som webbläsare och deras respektive inspektörer för att förstå vad jag gjorde fel och även för att kontrollera om det arbete jag gjorde var korrekt.

