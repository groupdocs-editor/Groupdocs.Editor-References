---
title: "TextEditOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe om aangepaste opties op te geven voor het laden van platte tekst TXT-documenten"
type: docs
weight: 39
url: /nl/java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Staat toe om aangepaste opties op te geven voor het laden van platte tekst (TXT) documenten

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Tekencodering van het tekstdocument, die zal worden toegepast op zijn |
openen
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Tekencodering van het tekstdocument, die zal worden toegepast op zijn |
openen
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Staat toe om op te geven hoe genummerde lijstitems worden herkend wanneer het document is |
geïmporteerd vanuit platte-tekstformaat.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Staat toe om op te geven hoe genummerde lijstitems worden herkend wanneer het document is |
geïmporteerd vanuit platte-tekstformaat.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | Haalt op of stelt de voorkeursoptie voor het afhandelen van een voorloopspatie in. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Haalt op of stelt de voorkeursoptie voor het afhandelen van een voorloopspatie in. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | Haalt op of stelt de voorkeursoptie voor het afhandelen van een naloopspatie in. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Haalt op of stelt de voorkeursoptie voor het afhandelen van een naloopspatie in. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Staat toe om paginering in het resulterende HTML-document in of uit te schakelen. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Staat toe om paginering in het resulterende HTML-document in of uit te schakelen. |
|
|  | [getDirection()](#getDirection--) | Staat toe om de richting van de tekststroom in de invoer platte tekst op te geven |
document.
|
|  | [setDirection(int value)](#setDirection-int-) | Staat toe om de richting van de tekststroom in de invoer platte tekst op te geven |
document.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Tekencodering van het tekstdocument, die zal worden toegepast op zijn
openen


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Tekencodering van het tekstdocument, die zal worden toegepast op zijn
openen


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Staat toe om op te geven hoe genummerde lijstitems worden herkend wanneer het document is
geïmporteerd vanuit platte-tekstformaat. De standaardwaarde is true.


*** ** * ** ***

Als deze optie is ingesteld op false, detecteert het lijstherkenningsalgoritme alinea's met lijsten wanneer lijstnummers eindigen op een punt, rechte haak of opsommingsteken (zoals "\\u2022", "\*", "-" of "o"). Als deze optie is ingesteld op true, worden ook spaties gebruikt als scheidingsteken voor lijstnummers: het lijstherkenningsalgoritme voor Arabische nummering (1., 1.1.2.) gebruikt zowel spaties als punt (".") symbolen.

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Staat toe om op te geven hoe genummerde lijstitems worden herkend wanneer het document is
geïmporteerd vanuit platte-tekstformaat. De standaardwaarde is true.


*** ** * ** ***

Als deze optie is ingesteld op false, detecteert het lijstherkenningsalgoritme alinea's met lijsten wanneer lijstnummers eindigen op een punt, rechte haak of opsommingsteken (zoals "\\u2022", "\*", "-" of "o"). Als deze optie is ingesteld op true, worden ook spaties gebruikt als scheidingsteken voor lijstnummers: het lijstherkenningsalgoritme voor Arabische nummering (1., 1.1.2.) gebruikt zowel spaties als punt (".") symbolen.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Haalt op of stelt de voorkeursoptie voor het afhandelen van een voorloopspatie in. Standaard
zet voorloopspaties om naar een linkerinspringing.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Haalt op of stelt de voorkeursoptie voor het afhandelen van een voorloopspatie in. Standaard
zet voorloopspaties om naar een linkerinspringing.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Haalt op of stelt de voorkeursoptie voor het afhandelen van een naloopspatie in. Standaard
knipt alle naloopspaties af.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Haalt op of stelt de voorkeursoptie voor het afhandelen van een naloopspatie in. Standaard
knipt alle naloopspaties af.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Staat toe om de richting van de tekststroom in de invoer platte tekst op te geven
document. Standaard is van links naar rechts.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Staat toe om de richting van de tekststroom in de invoer platte tekst op te geven
document. Standaard is van links naar rechts.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

