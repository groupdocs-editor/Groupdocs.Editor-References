---
title: "TextType"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt einen unterstützbaren Textressourcentyp dar"
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

Stellt einen unterstützbaren Textressourcentyp dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextType()](#TextType--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Spezialwert, der undefinierten, unbekannten oder nicht unterstützten Text kennzeichnet |
resource
|
|  | [getCss()](#getCss--) | CSS-Typ der Textressource |
|
|  | [getXml()](#getXml--) | XML-Typ der Textressource |
|
|  | [getFormalName()](#getFormalName--) | Gibt einen formellen Namen dieses Textressourcentyps zurück |
|
|  | [getFileExtension()](#getFileExtension--) | Dateierweiterung (ohne führendes Punktzeichen) eines bestimmten Textes |
resource
|
|  | [getMimeCode()](#getMimeCode--) | MIME-Code eines bestimmten Textressourcentyps |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Bestimmt, ob diese Instanz mit dem angegebenen \"TextType\" gleich ist |
Instanz
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Instanz mit dem angegebenen nicht gecasteten Objekt gleich ist, |
die vermutlich eine andere \"TextType\"-Instanz ist
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Definiert, ob zwei bestimmte \"TextType\"-Instanzen gleich sind |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Definiert, ob zwei bestimmte \"TextType\"-Instanzen ungleich sind |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hash-Code zurück, der eine konstante Zahl für diesen spezifischen Wert ist |
Typ
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Gibt den TextType-Wert zurück, der dem Dateierweiterungswert entspricht, der aus dem angegebenen Dateinamen mit Erweiterung oder reiner Erweiterung extrahiert wird |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


Spezialwert, der undefinierten, unbekannten oder nicht unterstützten Text kennzeichnet
resource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


CSS-Typ der Textressource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


XML-Typ der Textressource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Gibt einen formellen Namen dieses Textressourcentyps zurück


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Dateierweiterung (ohne führendes Punktzeichen) eines bestimmten Textes
resource


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME-Code eines bestimmten Textressourcentyps


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


Bestimmt, ob diese Instanz mit dem angegebenen \"TextType\" gleich ist
Instanz


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Andere TextType-Instanz, die bei der Gleichheitsprüfung mit dieser verglichen werden soll |
|

**Returns:**
boolean - Gibt true zurück, wenn gleich, oder false, wenn ungleich

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Instanz mit dem angegebenen nicht gecasteten Objekt gleich ist,
die vermutlich eine andere \"TextType\"-Instanz ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere TextType-Instanz, die in ein Objekt verpackt wird |
|

**Returns:**
boolean - Gibt true zurück, wenn gleich, oder false, wenn ungleich

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


Definiert, ob zwei bestimmte \"TextType\"-Instanzen gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Erste TextType-Instanz |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Zweite TextType-Instanz |
|

**Returns:**
boolean - Gibt true zurück, wenn gleich, oder false, wenn ungleich

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


Definiert, ob zwei bestimmte \"TextType\"-Instanzen ungleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Erste TextType-Instanz |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Zweite TextType-Instanz |
|

**Returns:**
boolean - Gibt true zurück, wenn ungleich, oder false, wenn gleich

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hash-Code zurück, der eine konstante Zahl für diesen spezifischen Wert ist
Typ


**Returns:**
int - Vorzeichenbehaftete 4-Byte-Ganzzahl. Gibt 0 zurück, wenn diese Instanz den Standardwert hat.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


Gibt den TextType-Wert zurück, der dem Dateierweiterungswert entspricht, der aus dem angegebenen Dateinamen mit Erweiterung oder reiner Erweiterung extrahiert wird


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateiname | java.lang.String | Dateiname mit Erweiterung, kann relativer oder absoluter Pfad sein, oder die reine Erweiterung selbst |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

