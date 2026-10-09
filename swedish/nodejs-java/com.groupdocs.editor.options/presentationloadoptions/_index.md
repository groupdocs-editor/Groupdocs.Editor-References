---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Tillåter att ange anpassade alternativ för att läsa in dokument i alla stödjade Presentation‑format som PPTX, PPTM, PPSX osv."
type: docs
weight: 33
url: /sv/nodejs-java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Tillåter att ange anpassade alternativ för att läsa in dokument i alla stödjade
Presentation‑format som PPT(X), PPTM, PPS(X) osv.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPassword()](#getPassword--) | Tillåter att ange, ändra och hämta lösenordet som kommer att användas för |
öppnar Presentation‑dokumentet, om det är kodat.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Tillåter att ange, ändra och hämta lösenordet som kommer att användas för |
öppnar Presentation‑dokumentet, om det är kodat.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Tillåter att ange, ändra och hämta lösenordet som kommer att användas för
öppnar Presentation‑dokumentet, om det är kodat. Sätt till NULL eller tomt.
sträng för att ta bort lösenordet.


*** ** * ** ***

Som standard har denna egenskap värdet NULL \u2014 lösenordet är inte angivet. Om inmatnings‑Presentation‑dokumentet är lösenordsskyddat är lösenordet obligatoriskt och ett undantag kommer att kastas om lösenordet inte anges eller är ogiltigt. Om inmatnings‑Presentation‑dokumentet INTE är lösenordsskyddat, men ett lösenord har angetts, kommer det att ignoreras.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Tillåter att ange, ändra och hämta lösenordet som kommer att användas för
öppnar Presentation‑dokumentet, om det är kodat. Sätt till NULL eller tomt.
sträng för att ta bort lösenordet.


*** ** * ** ***

Som standard har denna egenskap värdet NULL \u2014 lösenordet är inte angivet. Om inmatnings‑Presentation‑dokumentet är lösenordsskyddat är lösenordet obligatoriskt och ett undantag kommer att kastas om lösenordet inte anges eller är ogiltigt. Om inmatnings‑Presentation‑dokumentet INTE är lösenordsskyddat, men ett lösenord har angetts, kommer det att ignoreras.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

