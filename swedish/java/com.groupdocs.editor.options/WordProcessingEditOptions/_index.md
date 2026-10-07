---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade WordProcessing Words‑kompatibla format som DOCX, RTF, ODT etc."
type: docs
weight: 44
url: /sv/java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade
WordProcessing (Words‑kompatibla) format som DOC(X), RTF, ODT etc.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | Skapar och returnerar en ny instans av WordProcessingEditOptions |
klass, där alla alternativ är satta till sina standardvärden
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | Skapar och returnerar en ny instans av WordProcessingEditOptions |
klass med specificerad paginering och standard för alla andra alternativ
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Anger om språkinformation exporteras till HTML‑markup i |
en form av 'lang'-HTML‑attribut.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Anger om språkinformation exporteras till HTML‑markup i |
en form av 'lang'-HTML‑attribut.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Hämtar eller anger ett värde som indikerar om endast teckensnittresurser som |
används i dokumentets textinnehåll.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Hämtar eller anger ett värde som indikerar om endast teckensnittresurser som |
används i dokumentets textinnehåll.
|
|  | [getFontExtraction()](#getFontExtraction--) | Ansvarig för att extrahera teckensnittresurser som används i den inkommande |
WordProcessing‑dokumentet.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Ansvarig för att extrahera teckensnittresurser som används i den inkommande |
WordProcessing‑dokumentet.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | Tillåter att ange ett klassnamn som kommer att placeras i 'class' |
attribut i varje HTML‑element som representerar ett fält i den inkommande
WordProcessing‑dokumentet.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Tillåter att ange ett klassnamn som kommer att placeras i 'class' |
attribut i varje HTML‑element som representerar ett fält i den inkommande
WordProcessing‑dokumentet.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Styr var styling‑ och formateringsdata för det inkommande WordProcessing‑dokumentet lagras: i extern stilmall ( |
false
) eller som inline‑stilar i HTML‑markup (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Styr var styling‑ och formateringsdata för det inkommande WordProcessing‑dokumentet lagras: i extern stilmall ( |
false
) eller som inline‑stilar i HTML‑markup (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


Skapar och returnerar en ny instans av WordProcessingEditOptions
klass, där alla alternativ är satta till sina standardvärden


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


Skapar och returnerar en ny instans av WordProcessingEditOptions
klass med specificerad paginering och standard för alla andra alternativ


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | enablePagination | boolean | Pagineringflagga som möjliggör HTML‑utdata, anpassad för paginerat läge |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. Genom
standard är inaktiverad (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. Genom
standard är inaktiverad (false).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Anger om språkinformation exporteras till HTML‑markup i
en form av 'lang'-HTML‑attribut. Detta alternativ kan vara användbart för round‑trip
konvertering av flerspråkiga dokument. Som standard är den inaktiverad
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Anger om språkinformation exporteras till HTML‑markup i
en form av 'lang'-HTML‑attribut. Detta alternativ kan vara användbart för round‑trip
konvertering av flerspråkiga dokument. Som standard är den inaktiverad
(false).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Hämtar eller anger ett värde som indikerar om endast teckensnittresurser som
används i dokumentets textinnehåll.
Värde:  true  om det krävs att endast extrahera de teckensnittresurser som används i dokumentets textinnehåll; annars  false . Standardvärdet är  false .


*** ** * ** ***

Inte alla teckensnitt som används i WordProcessing-dokumentet används 100 % direkt (tillämpas på någon text). Det kan finnas en situation där teckensnittet refereras i dokumentet och till och med kan vara inbäddat, men inte tillämpas på någon textdel. Till exempel kan ett teckensnitt vara kopplat till en stil, men den stilen tillämpas inte på någon del av texten. Detta alternativ styr hur sådana fall hanteras.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Hämtar eller anger ett värde som indikerar om endast teckensnittresurser som
används i dokumentets textinnehåll.
Värde:  true  om det krävs att endast extrahera de teckensnittresurser som används i dokumentets textinnehåll; annars  false . Standardvärdet är  false .


*** ** * ** ***

Inte alla teckensnitt som används i WordProcessing-dokumentet används 100 % direkt (tillämpas på någon text). Det kan finnas en situation där teckensnittet refereras i dokumentet och till och med kan vara inbäddat, men inte tillämpas på någon textdel. Till exempel kan ett teckensnitt vara kopplat till en stil, men den stilen tillämpas inte på någon del av texten. Detta alternativ styr hur sådana fall hanteras.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Ansvarig för att extrahera teckensnittresurser som används i den inkommande
WordProcessing-dokument. Som standard extraheras inga teckensnitt.
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Ansvarig för att extrahera teckensnittresurser som används i den inkommande
WordProcessing-dokument. Som standard extraheras inga teckensnitt.
(NotExtract).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Tillåter att ange ett klassnamn som kommer att placeras i 'class'
attribut i varje HTML‑element som representerar ett fält i den inkommande
WordProcessing-dokument. Som standard är NULL – 'class'-attribut är inte
tillämpade.


*** ** * ** ***

Nästan alla format från WordProcessing-formatfamiljen innehåller fält \\\\u2014 specifika dokumentenheter som möjliggör att hämta indata från användare. Det finns en mängd olika fält: textrutor, kryssrutor, kombinationsrutor, rullgardinslistor, knappar, datum-/tidväljare osv. Alla dessa översätts till de mest lämpliga HTML‑strukturerna och -elementen, med bevarande av den inmatade användardatan om den finns i inmatningsdokumentet. I specifika användningsfall krävs det bara att samla in den inmatade datan på klientsidan istället för att redigera hela dokumentinnehållet. För ett sådant fall krävs det att identifiera inmatningskontroller på något sätt för att hämta dem med deras data på klientsidan. Denna egenskap tillåter att ange ett klassnamn som kommer att tillämpas på varje inmatningskontroll i HTML‑markup, så att klientkoden kan traversera HTML‑dokumentstrukturen och samla data.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Tillåter att ange ett klassnamn som kommer att placeras i 'class'
attribut i varje HTML‑element som representerar ett fält i den inkommande
WordProcessing-dokument. Som standard är NULL – 'class'-attribut är inte
tillämpade.


*** ** * ** ***

Nästan alla format från WordProcessing-formatfamiljen innehåller fält \\\\u2014 specifika dokumentenheter som möjliggör att hämta indata från användare. Det finns en mängd olika fält: textrutor, kryssrutor, kombinationsrutor, rullgardinslistor, knappar, datum-/tidväljare osv. Alla dessa översätts till de mest lämpliga HTML‑strukturerna och -elementen, med bevarande av den inmatade användardatan om den finns i inmatningsdokumentet. I specifika användningsfall krävs det bara att samla in den inmatade datan på klientsidan istället för att redigera hela dokumentinnehållet. För ett sådant fall krävs det att identifiera inmatningskontroller på något sätt för att hämta dem med deras data på klientsidan. Denna egenskap tillåter att ange ett klassnamn som kommer att tillämpas på varje inmatningskontroll i HTML‑markup, så att klientkoden kan traversera HTML‑dokumentstrukturen och samla data.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


Styr var styling‑ och formateringsdata för det inkommande WordProcessing‑dokumentet lagras: i extern stilmall (
false
) eller som inline‑stilar i HTML‑markup (
true
). Som standard används externa stilar (
false
).


**Returns:**
boolean
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


Styr var styling‑ och formateringsdata för det inkommande WordProcessing‑dokumentet lagras: i extern stilmall (
false
) eller som inline‑stilar i HTML‑markup (
true
). Som standard används externa stilar (
false
).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

