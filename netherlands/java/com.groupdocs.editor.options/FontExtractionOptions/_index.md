---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Opties voor het extraheren van lettertypen bepalen welke lettertypen moeten worden geëxtraheerd en van waar"
type: docs
weight: 18
url: /nl/java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Opties voor het extraheren van lettertypen bepalen welke lettertypen moeten worden geëxtraheerd en van
waar

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [NotExtract](#NotExtract) | Extraheert geen enkele lettertypebron, noch uit het document, noch uit de |
systeem.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | Extraheert alle lettertypebronnen die in de invoer-Word zijn ingebed |
document, ongeacht wat ze zijn: aangepast of systeem.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Extraheert alleen die ingebedde lettertypebronnen die aangepast zijn (niet |
systeem)
|
|  | [ExtractAll](#ExtractAll) | Probeert alle lettertypen te extraheren die worden gebruikt in de invoer-WordProcessing |
document, inclusief systeemlettertypen.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


Extraheert geen enkele lettertypebron, noch uit het document, noch uit de
systeem. Standaardwaarde.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


Extraheert alle lettertypebronnen die in de invoer-Word zijn ingebed
document, ongeacht wat ze zijn: aangepast of systeem.


*** ** * ** ***

Converter vindt en extraheert alle 100% lettertypebronnen die in het invoer‑WordProcessing‑document zijn ingebed, maar bepaalt niet of ze systeem‑ of aangepast zijn; het raakt Windows Registry of systeem‑mappen helemaal niet aan.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


Extraheert alleen die ingebedde lettertypebronnen die aangepast zijn (niet
systeem)


*** ** * ** ***

Converter vindt en extraheert alle ingebedde lettertypebronnen en probeert vervolgens te bepalen welke van deze lettertypen systeem zijn en welke niet. Om dit te bereiken, probeert de converter een lijst van alle systeemlettertypen te verkrijgen via Windows Registry en systeem‑mappen, en vergelijkt deze lijst vervolgens met de set van ingebedde lettertypen. Als resultaat wordt alleen het deel van die ingebedde lettertypen teruggegeven dat niet in het systeem is gevonden.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


Probeert alle lettertypen te extraheren die worden gebruikt in de invoer-WordProcessing
document, inclusief systeemlettertypen.


*** ** * ** ***

Converter analyseert een invoer‑WordProcessing‑document en vindt alle lettertypen die daarin worden gebruikt. Als al deze lettertypen in het invoerdocument zijn ingebed, extraheert en retourneert de converter ze. Anders, als een verzameling ingebedde lettertypen niet alle gebruikte lettertypen in het document dekt, of leeg is, probeert de converter deze lettertypebronnen uit het systeem te halen via Windows Registry en systeem‑mappen.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
