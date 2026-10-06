---
title: "FontType"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt einen unterstützbaren Schriftarttyp dar."
type: docs
weight: 12
url: /de/java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

Stellt einen unterstützbaren Schriftarttyp dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontType()](#FontType--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Spezialwert, der undefinierte, unbekannte oder nicht unterstützte Schriftart kennzeichnet |
Ressource
|
|  | [getWoff()](#getWoff--) | Stellt einen WOFF (Web Open Font Format)-Schrifttyp dar |
|
|  | [getWoff2()](#getWoff2--) | Stellt einen WOFF2 (Web Open Font Format Version 2)-Schrifttyp dar |
|
|  | [getTtf()](#getTtf--) | Stellt einen TTF (TrueType Font)-Schrifttyp dar |
|
|  | [getOtf()](#getOtf--) | Stellt einen OTF (OpenType Font)-Schrifttyp dar |
|
|  | [getTtc()](#getTtc--) | Stellt eine TrueType Collection (TTC)-Schrift dar |
|
|  | [getEot()](#getEot--) | Stellt einen EOT (Embedded OpenType)-Schrifttyp dar |
|
|  | [getCssName()](#getCssName--) | Gibt den CSS-kompatiblen Namen dieses Schrifttyps zurück, der in dem |
|
|  | [getFormalName()](#getFormalName--) | Gibt einen formellen Namen dieses Schrifttyps zurück |
|
|  | [getFileExtension()](#getFileExtension--) | Dateierweiterung (ohne Punktzeichen) für diesen Schrifttyp |
|
|  | [getFontFormat()](#getFontFormat--) | Schriftformat für das @font-face-Format |
|
|  | [getMimeCode()](#getMimeCode--) | MIME-Code eines bestimmten Schrifttyps |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Gibt den FontType-Wert zurück, der dem angegebenen CSS-kompatiblen |
Namen des Schrifttyps
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Gibt den FontType-Wert zurück, der der Dateierweiterung entspricht, die |
aus dem angegebenen Dateinamen extrahiert wird
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Gibt den FontType-Wert zurück, der dem angegebenen MIME-Code entspricht |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Gibt den ersten Schrifttyp aus dem angegebenen Satz zurück, der nicht "Undefined" ist |
Wert, oder andernfalls der Schrifttyp "Undefined" (wenn alle Elemente
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Bestimmt, ob diese Instanz gleich dem angegebenen "FontType" ist |
Instanz
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Instanz mit dem angegebenen nicht gecasteten Objekt gleich ist, |
die vermutlich eine andere "FontType"-Instanz ist
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Prüft, ob zwei "FontType"-Werte gleich sind |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Prüft, ob zwei "FontType"-Werte ungleich sind |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hash-Code zurück, der eine konstante Zahl für diesen spezifischen Wert darstellt |
Typ
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


Spezialwert, der undefinierte, unbekannte oder nicht unterstützte Schriftart kennzeichnet
Ressource


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


Stellt einen WOFF (Web Open Font Format)-Schrifttyp dar


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


Stellt einen WOFF2 (Web Open Font Format Version 2)-Schrifttyp dar


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


Stellt einen TTF (TrueType Font)-Schrifttyp dar


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


Stellt einen OTF (OpenType Font)-Schrifttyp dar


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


Stellt eine TrueType Collection (TTC)-Schrift dar


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


Stellt einen EOT (Embedded OpenType)-Schrifttyp dar


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Gibt den CSS-kompatiblen Namen dieses Schrifttyps zurück, der in dem


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Gibt einen formellen Namen dieses Schrifttyps zurück


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Dateierweiterung (ohne Punktzeichen) für diesen Schrifttyp


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Schriftformat für das @font-face-Format


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME-Code eines bestimmten Schrifttyps


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


Gibt den FontType-Wert zurück, der dem angegebenen CSS-kompatiblen
Namen des Schrifttyps


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | CSS-kompatibler Name des Schrifttyps |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Gibt den FontType-Wert zurück, der der Dateierweiterung entspricht, die
aus dem angegebenen Dateinamen extrahiert wird


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateiname | java.lang.String | Dateiname mit Erweiterung, kann ein vollständiger Name sein |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


Gibt den FontType-Wert zurück, der dem angegebenen MIME-Code entspricht


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | mimeCode | java.lang.String | MIME-Code |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


Gibt den ersten Schrifttyp aus dem angegebenen Satz zurück, der nicht "Undefined" ist
Wert, oder andernfalls der Schrifttyp "Undefined" (wenn alle Elemente
"Undefined")


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Ein oder mehrere FontType-Werte, NULL oder eine leere Sammlung sind nicht erlaubt |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


Bestimmt, ob diese Instanz gleich dem angegebenen "FontType" ist
Instanz


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Andere FontType-Instanz zum Vergleich mit dieser |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Instanz mit dem angegebenen nicht gecasteten Objekt gleich ist,
die vermutlich eine andere "FontType"-Instanz ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere Instanz, vermutlich vom FontType-Struct, die zu System.Object boxed wurde |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


Prüft, ob zwei "FontType"-Werte gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Erste FontType zum Prüfen |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Zweite FontType zum Prüfen |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


Prüft, ob zwei "FontType"-Werte ungleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Erste FontType zum Prüfen |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Zweite FontType zum Prüfen |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hash-Code zurück, der eine konstante Zahl für diesen spezifischen Wert darstellt
Typ


**Returns:**
int - 4-Byte vorzeichenbehaftete Ganzzahl, 0 für undefinierten Wert

