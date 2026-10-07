---
title: "FontType"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één ondersteund lettertype voor."
type: docs
weight: 12
url: /nl/java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

Stelt één ondersteund lettertype voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontType()](#FontType--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Speciale waarde, die een ongedefinieerd, onbekend of niet‑ondersteund lettertype aangeeft |
bron
|
|  | [getWoff()](#getWoff--) | Stelt een WOFF (Web Open Font Format)-lettertype voor |
|
|  | [getWoff2()](#getWoff2--) | Stelt een WOFF2 (Web Open Font Format versie 2)-lettertype voor |
|
|  | [getTtf()](#getTtf--) | Stelt een TTF (TrueType Font)-lettertype voor |
|
|  | [getOtf()](#getOtf--) | Stelt een OTF (OpenType Font)-lettertype voor |
|
|  | [getTtc()](#getTtc--) | Stelt een TrueType Collection (TTC)-lettertype voor |
|
|  | [getEot()](#getEot--) | Stelt een EOT (Embedded OpenType) lettertype voor |
|
|  | [getCssName()](#getCssName--) | Retourneert een CSS-compatibele naam van dit lettertype, die wordt gebruikt in de |
|
|  | [getFormalName()](#getFormalName--) | Retourneert een formele naam van dit lettertype |
|
|  | [getFileExtension()](#getFileExtension--) | Bestandsnaamextensie (zonder puntteken) voor dit lettertype |
|
|  | [getFontFormat()](#getFontFormat--) | Lettertypeformaat voor @font-face-indeling |
|
|  | [getMimeCode()](#getMimeCode--) | MIME-code van een specifiek lettertype |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Retourneert FontType-waarde, die gelijk is aan de opgegeven CSS-compatibele |
naam van het lettertype
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Retourneert FontType-waarde, die gelijk is aan de bestandsnaamextensie, die |
wordt gehaald uit de opgegeven bestandsnaam
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Retourneert FontType-waarde, die gelijk is aan de opgegeven MIME-code |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Retourneert het eerste lettertype uit de opgegeven set, dat geen "Undefined" is |
waarde, of anders "Undefined" lettertype (wanneer alle items
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Bepaalt of deze instantie gelijk is aan de opgegeven "FontType" |
instantie
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object, |
die vermoedelijk een andere "FontType"-instantie is
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Controleert of twee "FontType"-waarden gelijk zijn |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Controleert of twee "FontType"-waarden niet gelijk zijn |
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode, die een constant getal is voor deze specifieke waarde |
type
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


Speciale waarde, die een ongedefinieerd, onbekend of niet‑ondersteund lettertype aangeeft
bron


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


Stelt een WOFF (Web Open Font Format)-lettertype voor


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


Stelt een WOFF2 (Web Open Font Format versie 2)-lettertype voor


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


Stelt een TTF (TrueType Font)-lettertype voor


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


Stelt een OTF (OpenType Font)-lettertype voor


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


Stelt een TrueType Collection (TTC)-lettertype voor


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


Stelt een EOT (Embedded OpenType) lettertype voor


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Retourneert een CSS-compatibele naam van dit lettertype, die wordt gebruikt in de


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Retourneert een formele naam van dit lettertype


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Bestandsnaamextensie (zonder puntteken) voor dit lettertype


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Lettertypeformaat voor @font-face-indeling


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME-code van een specifiek lettertype


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


Retourneert FontType-waarde, die gelijk is aan de opgegeven CSS-compatibele
naam van het lettertype


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | CSS-compatibele naam van het lettertype |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Retourneert FontType-waarde, die gelijk is aan de bestandsnaamextensie, die
wordt gehaald uit de opgegeven bestandsnaam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bestandsnaam | java.lang.String | Bestandsnaam met extensie, kan een volledige naam zijn |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


Retourneert FontType-waarde, die gelijk is aan de opgegeven MIME-code


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | mimeCode | java.lang.String | MIME-code |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


Retourneert het eerste lettertype uit de opgegeven set, dat geen "Undefined" is
waarde, of anders "Undefined" lettertype (wanneer alle items
"Undefined")


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Een of meer FontType-waarden, NULL of een lege collectie is niet toegestaan |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


Bepaalt of deze instantie gelijk is aan de opgegeven "FontType"
instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Andere FontType-instantie om met deze te vergelijken |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object,
die vermoedelijk een andere "FontType"-instantie is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere instantie vermoedelijk van FontType-struct, die was verpakt naar System.Object |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


Controleert of twee "FontType"-waarden gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Eerste FontType om te controleren |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Tweede FontType om te controleren |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


Controleert of twee "FontType"-waarden niet gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Eerste FontType om te controleren |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Tweede FontType om te controleren |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode, die een constant getal is voor deze specifieke waarde
type


**Returns:**
int - 4-byte ondertekend geheel getal, 0 voor ongedefinieerde waarde

