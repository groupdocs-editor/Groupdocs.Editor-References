---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för att läsa in dokument i alla stödjade Presentation-format som PPTX, PPTM, PPSX etc."
type: docs
weight: 33
url: /sv/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Tillåter att ange anpassade alternativ för att läsa in dokument i alla stödjade
Presentation-format som PPT(X), PPTM, PPS(X) etc.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPassword()](#getPassword--) | Tillåter att ange, ändra och hämta lösenordet, som kommer att användas för |
öppning av Presentation-dokumentet, om det är kodad.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Tillåter att ange, ändra och hämta lösenordet, som kommer att användas för |
öppning av Presentation-dokumentet, om det är kodad.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Tillåter att ange, ändra och hämta lösenordet, som kommer att användas för
öppning av Presentation-dokumentet, om det är kodad. Sätt till NULL eller tom
sträng för att ta bort lösenordet.


*** ** * ** ***

Som standard har denna egenskap värdet NULL \\u2014 lösenordet är inte angivet. Om inmatnings-Presentation-dokumentet är lösenordsskyddat, är lösenordet obligatoriskt och ett undantag kommer att kastas om lösenordet inte specificeras eller är ogiltigt. Om inmatnings-Presentation-dokumentet INTE är lösenordsskyddat, men ett lösenord är angivet, kommer det att ignoreras.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Tillåter att ange, ändra och hämta lösenordet, som kommer att användas för
öppning av Presentation-dokumentet, om det är kodad. Sätt till NULL eller tom
sträng för att ta bort lösenordet.


*** ** * ** ***

Som standard har denna egenskap värdet NULL \\u2014 lösenordet är inte angivet. Om inmatnings-Presentation-dokumentet är lösenordsskyddat, är lösenordet obligatoriskt och ett undantag kommer att kastas om lösenordet inte specificeras eller är ogiltigt. Om inmatnings-Presentation-dokumentet INTE är lösenordsskyddat, men ett lösenord är angivet, kommer det att ignoreras.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

