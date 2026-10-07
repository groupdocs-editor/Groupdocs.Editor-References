---
title: "TextEditOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för inläsning av enkla TXT-dokument"
type: docs
weight: 39
url: /sv/java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Tillåter att ange anpassade alternativ för att läsa in vanlig text (TXT) dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Teckenkodning för textdokumentet, som kommer att tillämpas för dess |
öppning
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Teckenkodning för textdokumentet, som kommer att tillämpas för dess |
öppning
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Tillåter att ange hur numrerade listobjekt identifieras när dokumentet är |
importerat från enkelt textformat.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Tillåter att ange hur numrerade listobjekt identifieras när dokumentet är |
importerat från enkelt textformat.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | Hämtar eller anger föredraget alternativ för hantering av inledande mellanslag. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Hämtar eller anger föredraget alternativ för hantering av inledande mellanslag. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | Hämtar eller anger föredraget alternativ för hantering av avslutande mellanslag. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Hämtar eller anger föredraget alternativ för hantering av avslutande mellanslag. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. |
|
|  | [getDirection()](#getDirection--) | Tillåter att ange riktningen för textflödet i den inmatade enkla texten |
dokumentet.
|
|  | [setDirection(int value)](#setDirection-int-) | Tillåter att ange riktningen för textflödet i den inmatade enkla texten |
dokumentet.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Teckenkodning för textdokumentet, som kommer att tillämpas för dess
öppning


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Teckenkodning för textdokumentet, som kommer att tillämpas för dess
öppning


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Tillåter att ange hur numrerade listobjekt identifieras när dokumentet är
importerad från enkelt textformat. Standardvärdet är true.


*** ** * ** ***

Om detta alternativ är satt till false, upptäcker listigenkänningsalgoritmen listparagrafer när listnummer slutar med antingen punkt, högra parentes eller punkttecken (såsom "\\u2022", "\*", "-" eller "o"). Om detta alternativ är satt till true, används även blanksteg som avgränsare för listnummer: listigenkänningsalgoritmen för arabiskt stilnumrering (1., 1.1.2.) använder både blanksteg och punkt (".")-symboler.

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Tillåter att ange hur numrerade listobjekt identifieras när dokumentet är
importerad från enkelt textformat. Standardvärdet är true.


*** ** * ** ***

Om detta alternativ är satt till false, upptäcker listigenkänningsalgoritmen listparagrafer när listnummer slutar med antingen punkt, högra parentes eller punkttecken (såsom "\\u2022", "\*", "-" eller "o"). Om detta alternativ är satt till true, används även blanksteg som avgränsare för listnummer: listigenkänningsalgoritmen för arabiskt stilnumrering (1., 1.1.2.) använder både blanksteg och punkt (".")-symboler.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Hämtar eller anger föredraget alternativ för hantering av inledande mellanslag. Standard är
konverterar inledande mellanslag till vänster indrag.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Hämtar eller anger föredraget alternativ för hantering av inledande mellanslag. Standard är
konverterar inledande mellanslag till vänster indrag.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Hämtar eller anger föredragen inställning för hantering av efterföljande mellanslag. Som standard
trunkerar alla efterföljande mellanslag.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Hämtar eller anger föredragen inställning för hantering av efterföljande mellanslag. Som standard
trunkerar alla efterföljande mellanslag.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Tillåter att ange riktningen för textflödet i den inmatade enkla texten
dokument. Som standard är vänster-till-höger.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Tillåter att ange riktningen för textflödet i den inmatade enkla texten
dokument. Som standard är vänster-till-höger.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

