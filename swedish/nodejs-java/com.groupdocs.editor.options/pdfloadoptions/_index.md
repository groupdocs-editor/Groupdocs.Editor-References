---
title: "PdfLoadOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Innehåller alternativ för att läsa in PDF-dokument i Editor-klassen"
type: docs
weight: 30
url: /sv/nodejs-java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

Innehåller alternativ för att läsa in PDF-dokument i Editor-klassen

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPassword()](#getPassword--) | Tillåter att ange, ändra och hämta lösenordet som kommer att användas för att öppna ett PDF‑dokument, om det är krypterat. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Tillåter att ange, ändra och hämta lösenordet som kommer att användas för att öppna ett PDF‑dokument, om det är krypterat. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Tillåter att ange, ändra och hämta lösenordet som kommer att användas för att öppna ett PDF‑dokument, om det är krypterat.
Sätt till NULL eller en tom sträng för att inte använda lösenordet (standardvärde).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Tillåter att ange, ändra och hämta lösenordet som kommer att användas för att öppna ett PDF‑dokument, om det är krypterat.
Sätt till NULL eller en tom sträng för att inte använda lösenordet (standardvärde).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

