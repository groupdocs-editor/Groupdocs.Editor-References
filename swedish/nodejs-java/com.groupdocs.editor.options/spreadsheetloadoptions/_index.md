---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Innehåller alternativ för att läsa in binära Spreadsheet Cells Excel‑kompatibla dokument som XLSX, ODS osv."
type: docs
weight: 36
url: /sv/nodejs-java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

Innehåller alternativ för att läsa in binära Spreadsheet (Cells, Excel‑kompatibel).
dokument som XLS(X), ODS osv. i Editor‑klassen.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Standardkonstruktor utan parametrar – alla parametrar har standardvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPassword()](#getPassword--) | Tillåter att ange, ändra och hämta lösenordet som kommer att användas för |
öppnar Spreadsheet‑dokumentet, om det är kodat.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Tillåter att ange, ändra och hämta lösenordet som kommer att användas för |
öppnar Spreadsheet‑dokumentet, om det är kodat.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiverar minnesoptimeringsmekanismer under bearbetning av inmatningsdokument, |
vilket kan försämra prestanda i vissa speciella fall, men å andra
sidan minskar minnesanvändningen.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiverar minnesoptimeringsmekanismer under bearbetning av inmatningsdokument, |
vilket kan försämra prestanda i vissa speciella fall, men å andra
sidan minskar minnesanvändningen.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Standardkonstruktor utan parametrar – alla parametrar har standardvärden.


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Tillåter att ange, ändra och hämta lösenordet som kommer att användas för
öppnar Spreadsheet‑dokumentet, om det är kodat. Sätt till NULL eller tomt.
sträng för att inte använda lösenordet (standardvärde).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Tillåter att ange, ändra och hämta lösenordet som kommer att användas för
öppnar Spreadsheet‑dokumentet, om det är kodat. Sätt till NULL eller tomt.
sträng för att inte använda lösenordet (standardvärde).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiverar minnesoptimeringsmekanismer under bearbetning av inmatningsdokument,
vilket kan försämra prestanda i vissa speciella fall, men å andra
sidan minskar minnesanvändningen. Användbart vid bearbetning av stora dokument och
vid ett OutOfMemoryException. Standard är falskt (minnesoptimering är
inaktiverad för att uppnå bättre prestanda).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiverar minnesoptimeringsmekanismer under bearbetning av inmatningsdokument,
vilket kan försämra prestanda i vissa speciella fall, men å andra
sidan minskar minnesanvändningen. Användbart vid bearbetning av stora dokument och
vid ett OutOfMemoryException. Standard är falskt (minnesoptimering är
inaktiverad för att uppnå bättre prestanda).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

