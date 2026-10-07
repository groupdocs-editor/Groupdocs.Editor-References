---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe om aangepaste opties op te geven voor het bewerken van documenten van alle ondersteunde WordProcessing Words-conforme formaten zoals DOCX, RTF, ODT enz."
type: docs
weight: 44
url: /nl/java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Staat toe om aangepaste opties op te geven voor het bewerken van alle ondersteunde documenten
WordProcessing (Words-conforme) formaten zoals DOC(X), RTF, ODT enz.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | Maakt een nieuw exemplaar van WordProcessingEditOptions aan en retourneert dit |
klasse, waarbij alle opties zijn ingesteld op hun standaardwaarden
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | Maakt een nieuw exemplaar van WordProcessingEditOptions aan en retourneert dit |
klasse met gespecificeerde paginering en standaard alle andere opties
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Staat toe om paginering in het resulterende HTML-document in of uit te schakelen. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Staat toe om paginering in het resulterende HTML-document in of uit te schakelen. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Specificeert of taalinformatie wordt geëxporteerd naar de HTML-markup in |
een vorm van 'lang' HTML-attributen.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Specificeert of taalinformatie wordt geëxporteerd naar de HTML-markup in |
een vorm van 'lang' HTML-attributen.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Haalt of stelt een waarde in die aangeeft of alleen lettertypebronnen die |
worden gebruikt in de tekstuele inhoud van het document.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Haalt of stelt een waarde in die aangeeft of alleen lettertypebronnen die |
worden gebruikt in de tekstuele inhoud van het document.
|
|  | [getFontExtraction()](#getFontExtraction--) | Verantwoordelijk voor het extraheren van lettertypebronnen die worden gebruikt in de invoer |
WordProcessing-document.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Verantwoordelijk voor het extraheren van lettertypebronnen die worden gebruikt in de invoer |
WordProcessing-document.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | Staat toe om een klassenaam op te geven die wordt geplaatst in het 'class'-attribuut |
attribuut in elk HTML-element dat een bepaald veld in de invoer vertegenwoordigt
WordProcessing-document.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Staat toe om een klassenaam op te geven die wordt geplaatst in het 'class'-attribuut |
attribuut in elk HTML-element dat een bepaald veld in de invoer vertegenwoordigt
WordProcessing-document.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Bepaalt waar de stijl- en opmaakgegevens van het invoer-WordProcessing-document worden opgeslagen: in een extern stylesheet ( |
false
) of als inline stijlen in de HTML-markup (
true
, ).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Bepaalt waar de stijl- en opmaakgegevens van het invoer-WordProcessing-document worden opgeslagen: in een extern stylesheet ( |
false
) of als inline stijlen in de HTML-markup (
true
, ).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


Maakt een nieuw exemplaar van WordProcessingEditOptions aan en retourneert dit
klasse, waarbij alle opties zijn ingesteld op hun standaardwaarden


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


Maakt een nieuw exemplaar van WordProcessingEditOptions aan en retourneert dit
klasse met gespecificeerde paginering en standaard alle andere opties


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | enablePagination | boolean | Pagineringvlag, die HTML-uitvoer inschakelt, aangepast voor paginamodus |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Staat toe om paginering in het resulterende HTML-document in of uit te schakelen. Door
standaard is uitgeschakeld (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Staat toe om paginering in het resulterende HTML-document in of uit te schakelen. Door
standaard is uitgeschakeld (false).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Specificeert of taalinformatie wordt geëxporteerd naar de HTML-markup in
een vorm van 'lang' HTML-attributen. Deze optie kan nuttig zijn voor roundtrip
conversie van de meertalige documenten. Standaard is deze uitgeschakeld
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Specificeert of taalinformatie wordt geëxporteerd naar de HTML-markup in
een vorm van 'lang' HTML-attributen. Deze optie kan nuttig zijn voor roundtrip
conversie van de meertalige documenten. Standaard is deze uitgeschakeld
(false).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Haalt of stelt een waarde in die aangeeft of alleen lettertypebronnen die
worden gebruikt in de tekstuele inhoud van het document.
Waarde:  true  als het nodig is om alleen die lettertypebronnen te extraheren die worden gebruikt in de tekstinhoud van het document; anders,  false . Standaardwaarde is  false .


*** ** * ** ***

Niet alle lettertypen die in het WordProcessing-document worden gebruikt, worden 100 % direct gebruikt (toegepast op tekst). Er kan een situatie ontstaan waarin een lettertype in het document wordt gerefereerd en zelfs kan worden ingesloten, maar niet op enige tekst wordt toegepast. Bijvoorbeeld, een lettertype kan aan een stijl gekoppeld zijn, maar die stijl wordt op geen enkel deel van de tekst toegepast. Deze optie bepaalt hoe dergelijke gevallen worden verwerkt.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Haalt of stelt een waarde in die aangeeft of alleen lettertypebronnen die
worden gebruikt in de tekstuele inhoud van het document.
Waarde:  true  als het nodig is om alleen die lettertypebronnen te extraheren die worden gebruikt in de tekstinhoud van het document; anders,  false . Standaardwaarde is  false .


*** ** * ** ***

Niet alle lettertypen die in het WordProcessing-document worden gebruikt, worden 100 % direct gebruikt (toegepast op tekst). Er kan een situatie ontstaan waarin een lettertype in het document wordt gerefereerd en zelfs kan worden ingesloten, maar niet op enige tekst wordt toegepast. Bijvoorbeeld, een lettertype kan aan een stijl gekoppeld zijn, maar die stijl wordt op geen enkel deel van de tekst toegepast. Deze optie bepaalt hoe dergelijke gevallen worden verwerkt.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Verantwoordelijk voor het extraheren van lettertypebronnen die worden gebruikt in de invoer
WordProcessing-document. Standaard worden er geen lettertypen geëxtraheerd
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Verantwoordelijk voor het extraheren van lettertypebronnen die worden gebruikt in de invoer
WordProcessing-document. Standaard worden er geen lettertypen geëxtraheerd
(NotExtract).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Staat toe om een klassenaam op te geven die wordt geplaatst in het 'class'-attribuut
attribuut in elk HTML-element dat een bepaald veld in de invoer vertegenwoordigt
WordProcessing document. Standaard is NULL - 'class' attributen zijn niet
toegepast.


*** ** * ** ***

Bijna alle formaten uit de WordProcessing-formaatfamilie bevatten velden \\\\u2014 specifieke documententiteiten die het mogelijk maken invoergegevens van gebruikers te verkrijgen. Er is een grote verscheidenheid aan velden: tekstvakken, selectievakjes, keuzelijsten, vervolgkeuzelijsten, knoppen, datum/tijdkiezers, enz. Al deze worden vertaald naar de meest geschikte HTML-structuren en -elementen, met behoud van de ingevoerde gebruikersgegevens, indien deze aanwezig zijn in het invoerdocument. In specifieke use-cases is het alleen nodig om ingevoerde gegevens aan de client‑kant te verzamelen in plaats van de volledige documentinhoud te bewerken. Voor zo’n geval moet men invoerbesturingselementen op een bepaalde manier identificeren om ze met hun gegevens aan de client‑kant op te halen. Deze eigenschap maakt het mogelijk een klassenaam op te geven die wordt toegepast op elk invoerbesturingselement in de HTML-markup, zodat clientcode over de HTML‑documentstructuur kan traverseren en gegevens kan verzamelen.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Staat toe om een klassenaam op te geven die wordt geplaatst in het 'class'-attribuut
attribuut in elk HTML-element dat een bepaald veld in de invoer vertegenwoordigt
WordProcessing document. Standaard is NULL - 'class' attributen zijn niet
toegepast.


*** ** * ** ***

Bijna alle formaten uit de WordProcessing-formaatfamilie bevatten velden \\\\u2014 specifieke documententiteiten die het mogelijk maken invoergegevens van gebruikers te verkrijgen. Er is een grote verscheidenheid aan velden: tekstvakken, selectievakjes, keuzelijsten, vervolgkeuzelijsten, knoppen, datum/tijdkiezers, enz. Al deze worden vertaald naar de meest geschikte HTML-structuren en -elementen, met behoud van de ingevoerde gebruikersgegevens, indien deze aanwezig zijn in het invoerdocument. In specifieke use-cases is het alleen nodig om ingevoerde gegevens aan de client‑kant te verzamelen in plaats van de volledige documentinhoud te bewerken. Voor zo’n geval moet men invoerbesturingselementen op een bepaalde manier identificeren om ze met hun gegevens aan de client‑kant op te halen. Deze eigenschap maakt het mogelijk een klassenaam op te geven die wordt toegepast op elk invoerbesturingselement in de HTML-markup, zodat clientcode over de HTML‑documentstructuur kan traverseren en gegevens kan verzamelen.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


Bepaalt waar de stijl- en opmaakgegevens van het invoer-WordProcessing-document worden opgeslagen: in een extern stylesheet (
false
) of als inline stijlen in de HTML-markup (
true
). Standaard worden externe stijlen gebruikt (
false
, ).


**Returns:**
boolean
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


Bepaalt waar de stijl- en opmaakgegevens van het invoer-WordProcessing-document worden opgeslagen: in een extern stylesheet (
false
) of als inline stijlen in de HTML-markup (
true
). Standaard worden externe stijlen gebruikt (
false
, ).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

