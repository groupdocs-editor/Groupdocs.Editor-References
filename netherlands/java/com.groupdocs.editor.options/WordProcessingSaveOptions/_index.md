---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties op te geven voor het genereren en opslaan van WordProcessing‑conforme documenten nadat ze bewerkt zijn"
type: docs
weight: 48
url: /nl/java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Staat toe aangepaste opties op te geven voor het genereren en opslaan
WordProcessing‑conforme documenten nadat ze bewerkt zijn


*** ** * ** ***

WordProcessingSaveOptions wordt toegepast in situaties waarin er een instantie van de EditableDocument‑klasse bestaat, die bewerkte documentinhoud bevat, en waarbij deze inhoud moet worden opgeslagen in een nieuw document van WordProcessing‑formaat.

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Deze parameterloze constructor maakt een nieuwe instantie van WordProcessingSaveOptions aan met DOCX-uitvoerformaat (kan vervolgens worden aangepast via |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) eigenschap)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Maakt een nieuw exemplaar van WordProcessingSaveOptions met gespecificeerd |
verplichte WordProcessing-uitvoerindeling, terwijl alle andere parameters zijn
standaard
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Staat toe om paginering in of uit te schakelen die zal worden gebruikt voor het opslaan van de |
document.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Staat toe om paginering in of uit te schakelen die zal worden gebruikt voor het opslaan van de |
document.
|
|  | [getPassword()](#getPassword--) | Staat toe om een wachtwoord op te geven, te wijzigen, te verkrijgen of te verwijderen, die zal worden |
gebruikt om het gegenereerde WordProcessing-document te coderen.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Staat toe om een wachtwoord op te geven, te wijzigen, te verkrijgen of te verwijderen, die zal worden |
gebruikt om het gegenereerde WordProcessing-document te coderen.
|
|  | [getOutputFormat()](#getOutputFormat--) | Staat toe om een WordProcessing-indeling op te geven, die zal worden gebruikt voor het opslaan |
het document
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Staat toe om een WordProcessing-indeling op te geven, die zal worden gebruikt voor het opslaan |
het document
|
|  | [getLocale()](#getLocale--) | Staat toe om de standaardlocale (taal) voor de WordProcessing |
document, die zal worden toegepast tijdens de creatie ervan.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | Staat toe om de standaardlocale (taal) voor de WordProcessing |
document, die zal worden toegepast tijdens de creatie ervan.
|
|  | [getLocaleBi()](#getLocaleBi--) | Staat toe om de locale (taal) voor het WordProcessing-document te overschrijven |
voor de RTL (right-to-left) tekst, die zal worden toegepast tijdens zijn
creatie.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | Staat toe om de locale (taal) voor het WordProcessing-document te overschrijven |
voor de RTL (right-to-left) tekst, die zal worden toegepast tijdens zijn
creatie.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | Staat toe om de locale (taal) voor het WordProcessing-document te overschrijven |
voor de Oost-Aziatische tekst, die zal worden toegepast tijdens de creatie ervan.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | Staat toe om de locale (taal) voor het WordProcessing-document te overschrijven |
voor de Oost-Aziatische tekst, die zal worden toegepast tijdens de creatie ervan.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Schakelt geheugenoptimalisatiemechanismen in tijdens de documentgeneratie vanuit |
HTML, wat de prestaties vermindert als prijs voor het verlagen van het geheugengebruik.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Schakelt geheugenoptimalisatiemechanismen in tijdens de documentgeneratie vanuit |
HTML, wat de prestaties vermindert als prijs voor het verlagen van het geheugengebruik.
|
|  | [getProtection()](#getProtection--) | Staat toe om de documentbeschermingsopties te beheren en toe te passen voor de |
WordProcessing-document van elk formaat, die document
bescherming.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Staat toe om de documentbeschermingsopties te beheren en toe te passen voor de |
WordProcessing-document van elk formaat, die document
bescherming.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Verantwoordelijk voor het insluiten van lettertypebronnen in de uitvoer‑WordProcessing |
document.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Verantwoordelijk voor het insluiten van lettertypebronnen in de uitvoer‑WordProcessing |
document.
|
|  | [deepClone()](#deepClone--) | Maakt en retourneert een volledige kopie van deze instantie van |
WordProcessingSaveOptions-klasse
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Deze parameterloze constructor maakt een nieuwe instantie van WordProcessingSaveOptions aan met DOCX-uitvoerformaat (kan vervolgens worden aangepast via
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) eigenschap)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Maakt een nieuw exemplaar van WordProcessingSaveOptions met gespecificeerd
verplichte WordProcessing-uitvoerindeling, terwijl alle andere parameters zijn
standaard


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | Verplicht uitvoerformaat, waarin het WordProcessing-document moet worden opgeslagen |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Staat toe om paginering in of uit te schakelen die zal worden gebruikt voor het opslaan van de
document. Als het oorspronkelijke document werd geopend en bewerkt in paginering
modus, moet deze optie ook worden ingeschakeld. Standaard is uitgeschakeld.


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Staat toe om paginering in of uit te schakelen die zal worden gebruikt voor het opslaan van de
document. Als het oorspronkelijke document werd geopend en bewerkt in paginering
modus, moet deze optie ook worden ingeschakeld. Standaard is uitgeschakeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Staat toe om een wachtwoord op te geven, te wijzigen, te verkrijgen of te verwijderen, die zal worden
gebruikt om het gegenereerde WordProcessing-document te coderen. Geef NULL of
een lege tekenreeks op voor het verwijderen (reinigen) van het wachtwoord.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Staat toe om een wachtwoord op te geven, te wijzigen, te verkrijgen of te verwijderen, die zal worden
gebruikt om het gegenereerde WordProcessing-document te coderen. Geef NULL of
een lege tekenreeks op voor het verwijderen (reinigen) van het wachtwoord.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Staat toe om een WordProcessing-indeling op te geven, die zal worden gebruikt voor het opslaan
het document


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Staat toe om een WordProcessing-indeling op te geven, die zal worden gebruikt voor het opslaan
het document


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


Staat toe om de standaardlocale (taal) voor de WordProcessing
document, dat zal worden toegepast tijdens de creatie. Wanneer niet
gespecificeerd (standaardwaarde), zal MS Word (of een ander programma) detecteren (of
kiezen) de documenttaalinstelling volgens de eigen instellingen of andere
factoren.


*** ** * ** ***

Deze optie past de opgegeven locale geforceerd toe op de volledige tekst in het document. Gebruik deze niet als het document verschillende tekstgedeelten bevat die in verschillende talen zijn geschreven.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


Staat toe om de standaardlocale (taal) voor de WordProcessing
document, dat zal worden toegepast tijdens de creatie. Wanneer niet
gespecificeerd (standaardwaarde), zal MS Word (of een ander programma) detecteren (of
kiezen) de documenttaalinstelling volgens de eigen instellingen of andere
factoren.

*** ** * ** ***


Deze optie past de opgegeven locale geforceerd toe op de volledige tekst in
het document. Gebruik deze niet als het document verschillende delen van
tekst bevat, die in verschillende talen zijn geschreven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


Staat toe om de locale (taal) voor het WordProcessing-document te overschrijven
voor de RTL (right-to-left) tekst, die zal worden toegepast tijdens zijn
creatie. Wanneer niet gespecificeerd (standaardwaarde), zal MS Word (of andere
programma) de document-RTL-locale detecteren (of kiezen) volgens de eigen
instellingen of andere factoren.

*** ** * ** ***


Deze optie past de opgegeven locale geforceerd toe op de volledige RTL-tekst
in het document. Gebruik deze niet als het document verschillende delen van
tekst bevat, die in verschillende talen zijn geschreven.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


Staat toe om de locale (taal) voor het WordProcessing-document te overschrijven
voor de RTL (right-to-left) tekst, die zal worden toegepast tijdens zijn
creatie. Wanneer niet gespecificeerd (standaardwaarde), zal MS Word (of andere
programma) de document-RTL-locale detecteren (of kiezen) volgens de eigen
instellingen of andere factoren.

*** ** * ** ***


Deze optie past de opgegeven locale geforceerd toe op de volledige RTL-tekst
in het document. Gebruik deze niet als het document verschillende delen van
tekst bevat, die in verschillende talen zijn geschreven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


Staat toe om de locale (taal) voor het WordProcessing-document te overschrijven
voor de Oost-Aziatische tekst, die zal worden toegepast tijdens de creatie. Wanneer
niet gespecificeerd is (standaardwaarde), zal MS Word (of een ander programma) detecteren
(of kiezen) de document Oost-Aziatische locale volgens de eigen instellingen
of andere factoren.

*** ** * ** ***


Deze optie past de opgegeven locale geforceerd toe op de volledige
Oost-Aziatische tekst in het document. Gebruik het niet, als het document bevat
verschillende delen van tekst, die op verschillende
talen.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


Staat toe om de locale (taal) voor het WordProcessing-document te overschrijven
voor de Oost-Aziatische tekst, die zal worden toegepast tijdens de creatie. Wanneer
niet gespecificeerd is (standaardwaarde), zal MS Word (of een ander programma) detecteren
(of kiezen) de document Oost-Aziatische locale volgens de eigen instellingen
of andere factoren.

*** ** * ** ***


Deze optie past de opgegeven locale geforceerd toe op de volledige
Oost-Aziatische tekst in het document. Gebruik het niet, als het document bevat
verschillende delen van tekst, die op verschillende
talen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Schakelt geheugenoptimalisatiemechanismen in tijdens de documentgeneratie vanuit
HTML, wat de prestaties vermindert als prijs voor het verlagen van het geheugengebruik.
Het instellen van deze optie op true kan het geheugenverbruik aanzienlijk verminderen
bij het genereren van grote documenten ten koste van een tragere opslagtijd.
Standaard is false (geheugenoptimalisatie is uitgeschakeld ten gunste van betere
prestaties).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Schakelt geheugenoptimalisatiemechanismen in tijdens de documentgeneratie vanuit
HTML, wat de prestaties vermindert als prijs voor het verlagen van het geheugengebruik.
Het instellen van deze optie op true kan het geheugenverbruik aanzienlijk verminderen
bij het genereren van grote documenten ten koste van een tragere opslagtijd.
Standaard is false (geheugenoptimalisatie is uitgeschakeld ten gunste van betere
prestaties).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Staat toe om de documentbeschermingsopties te beheren en toe te passen voor de
WordProcessing-document van elk formaat, die document
bescherming. Standaard is NULL - documentbescherming wordt niet gebruikt.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Staat toe om de documentbeschermingsopties te beheren en toe te passen voor de
WordProcessing-document van elk formaat, die document
bescherming. Standaard is NULL - documentbescherming wordt niet gebruikt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Verantwoordelijk voor het insluiten van lettertypebronnen in de uitvoer‑WordProcessing
document. Standaard worden er geen lettertypen ingebed (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Verantwoordelijk voor het insluiten van lettertypebronnen in de uitvoer‑WordProcessing
document. Standaard worden er geen lettertypen ingebed (NotEmbed).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


Maakt en retourneert een volledige kopie van deze instantie van
WordProcessingSaveOptions-klasse


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

