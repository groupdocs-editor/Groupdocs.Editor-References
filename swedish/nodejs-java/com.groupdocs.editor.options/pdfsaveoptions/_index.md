---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Tillåter att specificera anpassade alternativ för att generera och spara PDF Portable Document Format-dokument"
type: docs
weight: 31
url: /sv/nodejs-java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

Tillåter att specificera anpassade alternativ för att generera och spara PDF (Portable
Dokumentformat) dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPassword()](#getPassword--) | Lösenord, som kommer att tillämpas på det genererade PDF-dokumentet som användarlösenord, krävs för att öppna. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Lösenord, som kommer att tillämpas på det genererade PDF-dokumentet som användarlösenord, krävs för att öppna. |
|
|  | [getCompliance()](#getCompliance--) | Anger PDF-standardernas efterlevnadsnivå för utdata-dokument. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | Anger PDF-standardernas efterlevnadsnivå för utdata-dokument. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Ansvarig för att bädda in teckensnittresurser i det resulterande PDF-dokumentet, som används i originaldokumentet. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Ansvarig för att bädda in teckensnittresurser i det resulterande PDF-dokumentet, som används i originaldokumentet. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestanda som en kostnad för minskat minnesanvändning. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestanda som en kostnad för minskat minnesanvändning. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Lösenord, som kommer att tillämpas på det genererade PDF-dokumentet som användarlösenord, krävs för att öppna.
Om NULL eller tomt, kommer inget lösenord att tillämpas på dokumentet. Annars kommer dokumentet att krypteras med RC4 (nyckellängd 128 bit).
Som standard är NULL \u2014 lösenord tillämpas inte.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Lösenord, som kommer att tillämpas på det genererade PDF-dokumentet som användarlösenord, krävs för att öppna.
Om NULL eller tomt, kommer inget lösenord att tillämpas på dokumentet. Annars kommer dokumentet att krypteras med RC4 (nyckellängd 128 bit).
Som standard är NULL \u2014 lösenord tillämpas inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Anger PDF-standardernas efterlevnadsnivå för utdata-dokument. Standard är PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Anger PDF-standardernas efterlevnadsnivå för utdata-dokument. Standard är PdfCompliance.Pdf17.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Ansvarig för att bädda in teckensnittresurser i det resulterande PDF-dokumentet, som används i originaldokumentet. Som standard bäddar den inte in några teckensnitt (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Ansvarig för att bädda in teckensnittresurser i det resulterande PDF-dokumentet, som används i originaldokumentet. Som standard bäddar den inte in några teckensnitt (NotEmbed).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestanda som en kostnad för minskat minnesanvändning.
Att sätta detta alternativ till true kan avsevärt minska minnesförbrukningen vid generering av stora dokument, men till priset av längre sparningstid.
Standard är false (minnesoptimering är inaktiverad för bättre prestanda).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestanda som en kostnad för minskat minnesanvändning.
Att sätta detta alternativ till true kan avsevärt minska minnesförbrukningen vid generering av stora dokument, men till priset av längre sparningstid.
Standard är false (minnesoptimering är inaktiverad för bättre prestanda).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

