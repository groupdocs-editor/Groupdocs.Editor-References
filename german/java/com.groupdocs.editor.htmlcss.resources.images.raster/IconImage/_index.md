---
title: "IconImage"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt ein Bild im ICON-Format mit seinen Metadaten und zusätzlichen Methoden dar."
type: docs
weight: 12
url: /de/java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

Stellt ein Bild im ICON-Format mit seinen Metadaten und zusätzlichen Methoden dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Erstellt eine neue IconImage-Instanz aus dem Inhalt, dargestellt als |
Base64-codierter Zeichenkette und mit angegebenem Namen
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Erstellt eine neue IconImage-Instanz aus dem Inhalt, dargestellt als Bytestrom, |
und mit angegebenem Namen
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Überprüft, ob der angegebene Stream ein gültiges ICON-Bild ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Überprüft, ob die angegebene Base64-codierte Zeichenkette ein gültiges ICON-Bild ist |
|
|  | [getType()](#getType--) | Gibt ImageType.Icon zurück |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Gibt die Anzahl der Bilder zurück, die in dieser ICON-Datei vorhanden sind |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Erstellt eine neue IconImage-Instanz aus dem Inhalt, dargestellt als
Base64-codierter Zeichenkette und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des ICON-Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als Base64-codierte Zeichenkette. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein ICON-Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Erstellt eine neue IconImage-Instanz aus dem Inhalt, dargestellt als Bytestrom,
und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des ICON-Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | binaryContent | java.io.InputStream | Inhalt als Byte-Stream. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird auch dieser Stream freigegeben. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Überprüft, ob der angegebene Stream ein gültiges ICON-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Bytestrom, der vermutlich ein ICON-Bild enthält |
|

**Returns:**
boolean - True, wenn der angegebene Stream ein gültiges ICON-Bild enthält, false andernfalls

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Überprüft, ob die angegebene Base64-codierte Zeichenkette ein gültiges ICON-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt des vermutlich ICON-Bildes in Form einer Base64-codierten Zeichenkette |
|

**Returns:**
boolean - True, wenn die angegebene Zeichenkette ein gültiges ICON-Bild enthält, false andernfalls

### getType() {#getType--}
```
public ImageType getType()
```


Gibt ImageType.Icon zurück


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


Gibt die Anzahl der Bilder zurück, die in dieser ICON-Datei vorhanden sind


**Returns:**
int
