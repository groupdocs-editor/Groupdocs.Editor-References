---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Innehåller alternativ för att läsa in WordProcessing Word-kompatibla dokument som DOCX, RTF, ODT etc."
type: docs
weight: 45
url: /sv/nodejs-java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

Innehåller alternativ för att läsa in WordProcessing (Word-kompatibla) dokument som
DOC(X), RTF, ODT etc. till Editor-klass

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPassword()](#getPassword--) | Tillåter att ange, ändra och hämta lösenordet som kommer att användas för |
öppning av WordProcessing-dokument, om det är kodat.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Tillåter att ange, ändra och hämta lösenordet som kommer att användas för |
öppning av WordProcessing-dokument, om det är kodat.
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Tillåter att ange, ändra och hämta lösenordet som kommer att användas för
öppning av WordProcessing-dokument, om det är kodat. Sätt till NULL eller tom
sträng för att inte använda lösenordet (standardvärde).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Tillåter att ange, ändra och hämta lösenordet som kommer att användas för
öppning av WordProcessing-dokument, om det är kodat. Sätt till NULL eller tom
sträng för att inte använda lösenordet (standardvärde).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

