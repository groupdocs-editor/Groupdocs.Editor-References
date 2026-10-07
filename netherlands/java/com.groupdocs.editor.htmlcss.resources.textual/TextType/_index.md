---
title: "TextType"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één ondersteund tekstueel resource-type voor"
type: docs
weight: 12
url: /nl/java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

Stelt één ondersteund tekstueel resource-type voor

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextType()](#TextType--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Speciale waarde, die ongedefinieerde, onbekende of niet-ondersteunde tekst markeert |
bron
|
|  | [getCss()](#getCss--) | CSS-type van de tekstresource |
|
|  | [getXml()](#getXml--) | XML-type van de tekstresource |
|
|  | [getFormalName()](#getFormalName--) | Retourneert een formele naam van dit type tekstresource |
|
|  | [getFileExtension()](#getFileExtension--) | Bestandsextensie (zonder voorafgaande punt) van een specifieke tekst |
bron
|
|  | [getMimeCode()](#getMimeCode--) | MIME-code van een specifiek type tekstresource |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Bepaalt of deze instantie gelijk is aan de opgegeven "TextType" |
instantie
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object, |
die vermoedelijk een andere "TextType"-instantie is
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Definieert of twee specifieke "TextType"-instanties gelijk zijn |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Definieert of twee specifieke "TextType"-instanties niet gelijk zijn |
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode, die een constant getal is voor deze specifieke waarde |
type
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Retourneert een TextType-waarde, die gelijk is aan de bestandsnaamextensie, die is afgeleid van de opgegeven bestandsnaam met extensie of zuivere extensie |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


Speciale waarde, die ongedefinieerde, onbekende of niet-ondersteunde tekst markeert
bron


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


CSS-type van de tekstresource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


XML-type van de tekstresource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Retourneert een formele naam van dit type tekstresource


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Bestandsextensie (zonder voorafgaande punt) van een specifieke tekst
bron


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME-code van een specifiek type tekstresource


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


Bepaalt of deze instantie gelijk is aan de opgegeven "TextType"
instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Andere TextType-instantie, die moet worden vergeleken met deze op gelijkheid |
|

**Returns:**
boolean - Retourneert true als ze gelijk zijn of false als ze ongelijk zijn

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object,
die vermoedelijk een andere "TextType"-instantie is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere TextType-instantie, die is verpakt naar object |
|

**Returns:**
boolean - Retourneert true als ze gelijk zijn of false als ze ongelijk zijn

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


Definieert of twee specifieke "TextType"-instanties gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Eerste TextType-instantie |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Tweede TextType-instantie |
|

**Returns:**
boolean - Retourneert true als ze gelijk zijn of false als ze ongelijk zijn

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


Definieert of twee specifieke "TextType"-instanties niet gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Eerste TextType-instantie |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Tweede TextType-instantie |
|

**Returns:**
boolean - Retourneert true als ze ongelijk zijn of false als ze gelijk zijn

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode, die een constant getal is voor deze specifieke waarde
type


**Returns:**
int - Ondertekend 4-byte geheel getal. Retourneert 0 als deze instantie de standaardwaarde heeft.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


Retourneert een TextType-waarde, die gelijk is aan de bestandsnaamextensie, die is afgeleid van de opgegeven bestandsnaam met extensie of zuivere extensie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bestandsnaam | java.lang.String | Bestandsnaam met extensie, kan een relatief of absoluut pad zijn, of alleen de extensie zelf |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

