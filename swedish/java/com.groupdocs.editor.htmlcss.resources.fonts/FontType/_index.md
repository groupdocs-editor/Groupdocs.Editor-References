---
title: "FontType"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar en stödbar teckensnittstyp."
type: docs
weight: 12
url: /sv/java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

Representerar en stödbar teckensnittstyp.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontType()](#FontType--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Speciellt värde som markerar odefinierat, okänt eller ej stödt teckensnitt |
resurs
|
|  | [getWoff()](#getWoff--) | Representerar en WOFF (Web Open Font Format)-teckensnittstyp |
|
|  | [getWoff2()](#getWoff2--) | Representerar en WOFF2 (Web Open Font Format version 2)-teckensnittstyp |
|
|  | [getTtf()](#getTtf--) | Representerar en TTF (TrueType Font) typsnittstyp |
|
|  | [getOtf()](#getOtf--) | Representerar en OTF (OpenType Font) typsnittstyp |
|
|  | [getTtc()](#getTtc--) | Representerar en TrueType Collection (TTC) typsnitt |
|
|  | [getEot()](#getEot--) | Representerar en EOT (Embedded OpenType) typsnittstyp |
|
|  | [getCssName()](#getCssName--) | Returnerar ett CSS-kompatibelt namn för denna typsnittstyp, som används i |
|
|  | [getFormalName()](#getFormalName--) | Returnerar ett formellt namn för denna typsnittstyp |
|
|  | [getFileExtension()](#getFileExtension--) | Filnamnstillägg (utan punkttecken) för denna typsnittstyp |
|
|  | [getFontFormat()](#getFontFormat--) | Typsnittformat för @font-face-format |
|
|  | [getMimeCode()](#getMimeCode--) | MIME-kod för en viss typsnittstyp |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Returnerar FontType‑värde som är motsvarande den specificerade CSS-kompatibla |
namnet på typsnittstypen
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Returnerar FontType‑värde som är motsvarande filnamnstillägget, som |
extraheras från angivet filnamn
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Returnerar FontType‑värde som är motsvarande den specificerade MIME‑koden |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Returnerar den första typsnittstypen från den specificerade mängden, som inte är "Undefined" |
värde, eller "Undefined"‑typsnittstyp annars (när alla objekt är
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Bestämmer om detta objekt är lika med den specificerade "FontType" |
instans
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om detta objekt är lika med angivet okastat objekt, |
som förmodligen är en annan "FontType"‑instans
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Kontrollerar om två "FontType"‑värden är lika |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Kontrollerar om två "FontType"‑värden är olika |
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod, som är ett konstant tal för detta specifika värde |
typ
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


Speciellt värde som markerar odefinierat, okänt eller ej stödt teckensnitt
resurs


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


Representerar en WOFF (Web Open Font Format)-teckensnittstyp


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


Representerar en WOFF2 (Web Open Font Format version 2)-teckensnittstyp


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


Representerar en TTF (TrueType Font) typsnittstyp


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


Representerar en OTF (OpenType Font) typsnittstyp


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


Representerar en TrueType Collection (TTC) typsnitt


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


Representerar en EOT (Embedded OpenType) typsnittstyp


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Returnerar ett CSS-kompatibelt namn för denna typsnittstyp, som används i


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Returnerar ett formellt namn för denna typsnittstyp


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Filnamnstillägg (utan punkttecken) för denna typsnittstyp


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Typsnittformat för @font-face-format


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME-kod för en viss typsnittstyp


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


Returnerar FontType‑värde som är motsvarande den specificerade CSS-kompatibla
namnet på typsnittstypen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | CSS-kompatibelt namn för typsnittstypen |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Returnerar FontType‑värde som är motsvarande filnamnstillägget, som
extraheras från angivet filnamn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filnamn | java.lang.String | Filnamn med filändelse, kan vara ett fullständigt namn |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


Returnerar FontType‑värde som är motsvarande den specificerade MIME‑koden


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | mimeCode | java.lang.String | MIME‑kod |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


Returnerar den första typsnittstypen från den specificerade mängden, som inte är "Undefined"
värde, eller "Undefined"‑typsnittstyp annars (när alla objekt är
"Undefined")


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | En eller flera FontType‑värden, NULL eller tom samling är inte tillåtet |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


Bestämmer om detta objekt är lika med den specificerade "FontType"
instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Annan FontType‑instans att jämföra med denna |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om detta objekt är lika med angivet okastat objekt,
som förmodligen är en annan "FontType"‑instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Annat instans antagligen av FontType-struct, som var boxad till System.Object |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


Kontrollerar om två "FontType"‑värden är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Första FontType att kontrollera |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Andra FontType att kontrollera |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


Kontrollerar om två "FontType"‑värden är olika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Första FontType att kontrollera |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Andra FontType att kontrollera |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod, som är ett konstant tal för detta specifika värde
typ


**Returns:**
int - 4‑byte signerat heltal, 0 för Odefinierat värde

