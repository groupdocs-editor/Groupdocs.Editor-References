---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara XPS XML Paper Specifications-dokument"
type: docs
weight: 54
url: /sv/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

Tillåter att ange anpassade alternativ för att generera och spara XPS (XML Paper Specifications) dokument

<br />

*** ** * ** ***

En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som ett ersättningsformat för EMF-filformatet och liknar PDF-filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | Ansvarig för att bädda in teckensnittresurser i det resulterande XPS-dokumentet, som används i originaldokumentet. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesanvändning. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesanvändning. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Ansvarig för att bädda in teckensnittresurser i det resulterande XPS-dokumentet, som används i originaldokumentet.
Som standard bäddas inga teckensnitt in (NotEmbed).


**Returns:**
byte
### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesanvändning.
Att sätta detta alternativ till true kan avsevärt minska minnesförbrukningen vid generering av stora dokument, men till priset av längre sparningstid.
Standard är false (minnesoptimering är inaktiverad för bättre prestanda).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesanvändning.
Att sätta detta alternativ till true kan avsevärt minska minnesförbrukningen vid generering av stora dokument, men till priset av längre sparningstid.
Standard är false (minnesoptimering är inaktiverad för bättre prestanda).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

