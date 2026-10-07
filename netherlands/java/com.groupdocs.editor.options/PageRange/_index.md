---
title: "PageRange"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Omsluit één page range die open of gesloten grenzen kan hebben."
type: docs
weight: 27
url: /nl/java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Omsluit één page range, die open of gesloten grenzen kan hebben. Standaard is \"fully open\" - het omvat alle bestaande pagina's. Paginanummering begint bij 1, niet bij 0.

<br />

*** ** * ** ***

Onveranderlijke struct, die een page range omsluit, die niet gerelateerd is aan een specifiek document, en een page range voor elk document kan vertegenwoordigen.

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [AllPages](#AllPages) | Vertegenwoordigt alle bestaande pagina's van een document. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | Inclusief startpaginanummer, vanaf waar dit page range begint. |
|
|  | [getEndNumber()](#getEndNumber--) | Exclusief eindpaginanummer, tot waar dit page range doorgaat en waarop het exclusief stopt. |
|
|  | [getCount()](#getCount--) | Aantal pagina's binnen het bereik. |
|
|  | [isDefault()](#isDefault--) | Geeft aan of deze instantie een standaard \"fully open\" page range vertegenwoordigt, d.w.z. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Detecteert of deze instantie van PageRange gelijk is aan de gespecificeerde |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | Maakt een page range die begint bij de eerste pagina en een gespecificeerd aantal pagina's heeft |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Maakt een page range die begint bij het opgegeven paginanummer en doorgaat tot het einde van het document |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Maakt een page range die begint bij het opgegeven paginanummer en een gespecificeerd aantal pagina's heeft, of een onbeperkt aantal pagina's (tot het einde) |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Maakt een page range die begint bij het opgegeven paginanummer (inclusief) en doorgaat tot het opgegeven paginanummer (exclusief) |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


Vertegenwoordigt alle bestaande pagina's van een document. Standaardwaarde.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


Inclusief startpaginanummer, vanaf waar dit page range begint. Als 1 - begint het page range bij de eerste pagina van een document


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Exclusief eindpaginanummer, tot waar dit page range doorgaat en waarop het exclusief stopt. Als 0 - strekt het page range zich uit tot het einde van het document


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Aantal pagina's binnen het bereik. Als 0 - strekt het page range zich uit tot het einde van het document, ongeacht hoeveel pagina's het bevat


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Geeft aan of deze instantie een standaard \"fully open\" page range vertegenwoordigt, d.w.z. het omvat alle pagina's van een document


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


Detecteert of deze instantie van PageRange gelijk is aan de gespecificeerde


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Andere PageRange‑instantie om op gelijkheid te controleren |
|

**Returns:**
boolean - true betekent gelijk; false betekent ongelijk

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


Maakt een page range die begint bij de eerste pagina en een gespecificeerd aantal pagina's heeft


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageCount | int | Aantal pagina's, moet strikt groter zijn dan nul |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


Maakt een page range die begint bij het opgegeven paginanummer en doorgaat tot het einde van het document


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | startPageNumber | int | Paginanummer, vanaf waar het paginabereik begint, inclusief. Paginanummers zijn 1-gebaseerd, dus moeten strikt groter zijn dan nul |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Maakt een page range die begint bij het opgegeven paginanummer en een gespecificeerd aantal pagina's heeft, of een onbeperkt aantal pagina's (tot het einde)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | startPageNumber | int | Paginanummer, vanaf waar het paginabereik begint, inclusief. Paginanummers zijn 1-gebaseerd, dus moeten strikt groter zijn dan nul |
|
|  | pageCount | int | Aantal pagina's, moet strikt groter zijn dan nul. Als nul - betekent dit alle pagina's tot het einde van een document |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Maakt een page range die begint bij het opgegeven paginanummer (inclusief) en doorgaat tot het opgegeven paginanummer (exclusief)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | startPageNumber | int | Paginanummer, vanaf waar het paginabereik begint, inclusief. Paginanummers zijn 1-gebaseerd, dus moeten strikt groter zijn dan nul |
|
|  | endPageNumber | int | Paginanummer, tot waar het paginabereik doorgaat, exclusief. Paginanummers zijn 1-gebaseerd, dus moeten strikt groter zijn dan nul, en ook strikt groter dan startPageNumber |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
