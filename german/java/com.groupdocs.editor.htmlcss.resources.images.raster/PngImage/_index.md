---
title: "PngImage"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt ein Bild im PNG Portable Network Graphics-Format mit seinen Metadaten und zusätzlichen Methoden dar"
type: docs
weight: 14
url: /de/java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

Stellt ein Bild im PNG (Portable Network Graphics)-Format mit seinen
Metadaten und zusätzlichen Methoden

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | Erstellt eine neue PngImage-Instanz aus dem Inhalt, dargestellt als base64-codiert |
String und mit angegebenem Namen
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | Erstellt eine neue PngImage-Instanz aus dem Inhalt, dargestellt als Byte-Stream, |
und mit angegebenem Namen
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Überprüft, ob der angegebene Stream ein gültiges PNG-Bild ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Überprüft, ob der angegebene base64-codierte String ein gültiges PNG-Bild ist |
|
|  | [getType()](#getType--) | Gibt ImageType.Png zurück |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


Erstellt eine neue PngImage-Instanz aus dem Inhalt, dargestellt als base64-codiert
String und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des PNG-Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64-codierter String. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein PNG-Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


Erstellt eine neue PngImage-Instanz aus dem Inhalt, dargestellt als Byte-Stream,
und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des PNG-Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | binaryContent | java.io.InputStream | Inhalt als Byte-Stream. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird auch dieser Stream freigegeben. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Überprüft, ob der angegebene Stream ein gültiges PNG-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte-Stream, der vermutlich ein PNG-Bild enthält |
|

**Returns:**
boolean - True, wenn der angegebene Stream ein gültiges PNG-Bild enthält, false andernfalls

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Überprüft, ob der angegebene base64-codierte String ein gültiges PNG-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt des vermutlich PNG-Bildes in Form eines base64-codierten Strings |
|

**Returns:**
boolean - True, wenn der angegebene String ein gültiges PNG-Bild enthält, false andernfalls

### getType() {#getType--}
```
public ImageType getType()
```


Gibt ImageType.Png zurück


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
