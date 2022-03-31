# TopicModeling_NL
In deze repository vind je 5 notebooks waarmee je stap voor stap Topic Modeling kunt toepassen op een tekstcorpus bestaande uit txt-, pdf-, en/of docx-bestanden.
Alle tekst en uitleg in deze repository is in het Nederlands. De documentatie waar soms naar verwezen wordt, is wel hoofdzakelijk in het Engels. 

De notebooks bevatten verschillende stukken verzamelde code, die zijn voorzien van tekst en uitleg, om iemand zonder enige kennis van python in staat te stellen Topic Modeling toe te passen op een tekstcorpus. In de stukken code moet af en toe een pad naar een map waar bestanden staan (path), een pad naar een map waar bestanden heen moeten (dst_folder) of bestandsnaam worden ingevuld (filename). Waar dit het geval is, is in de betreffende regel de comment #VUL IN: aangebracht.

Elk notebook begint met een uitleg van welke python bibliotheken en andere modules geïnstalleerd moeten worden om de code in de notebooks te draaien. 

Voor een introductie op wat Topic Modeling precies is en wat je er mee kunt, verwijzen we naar het stageverslag van Gijs Aangenendt. Dit verslag volgt op een onderzoek naar de vraag of je met Topic Modeling documenten op een bruikbare wijze kunt ordenen.

## Tekst naar data
De eerste drie notebooks kunnen worden gebruikt om documenten in docx-, of pdf-formaat om te zetten in txt-bestanden en daarna naar json. Mocht je corpus alleen uit txt-bestanden bestaan, begin met notebook 3.
### 1. DOCX naar TXT
Met behulp van dit notebook kunnen docx-bestanden (word) worden omgezet in txt-bestanden. 
### 2. PDF naar TXT
Met behulp van dit notebook kunnen pdf-bestanden worden omgezet in txt-bestanden.
### 3. Corpus creëren
Met behulp van dit notebook kunnen de txt-versies van de pdf- en docx-documenten worden samengevoegd in een json-bestand. Om met Gensim aan de slag te gaan, is een json-bestand nodig bestaande uit twee lijsten, een lijst met de bestandsnamen en een lijst met de inhoud van de txt-bestanden.
### Extra: Inhoudelijke vergelijking corpus
Met behulp van dit notebook kunnen de documenten in het corpus woordelijk met elkaar vergeleken worden. Documenten die geheel of grotendeels overeenkomen, kunnen worden geïdentificeerd met behulp van een cosinusgelijkenis. Daarna kunnen deze documenten eventueel uit het corpus worden gehaald. De effecten hiervan op het eindresultaat van Topic Modeling moeten nog worden onderzocht. Met dit notebook maak je van de txt-bestanden ook een json-bestand.

## Topic Modeling
Na de documenten in je corpus omgezet te hebben in data, is het tijd om het Topic Modeling model toe te passen en de resultaten te visualiseren en te analyseren.
### 4. Topic Modeling met Gensim
Met behulp van dit notebook wordt de data uit het corpus geladen. Vervolgens gebruiken we spaCy en Gensim enige corpusbewerking en opschoning toegepast. Daarna kan Topic Modeling worden toegepast en de resultaten op verschillende manieren gevisualiseerd worden.
