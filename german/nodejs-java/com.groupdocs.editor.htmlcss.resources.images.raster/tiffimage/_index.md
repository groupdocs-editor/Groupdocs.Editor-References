---
title: "TiffImage"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt ein Bild im TIFF Tagged Image File Format dar, zusammen mit seinen Metadaten und zusätzlichen Methoden"
type: docs
weight: 16
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

Stellt ein Bild im TIFF (Tagged Image File Format) Format dar, zusammen mit seinem
Metadaten und zusätzlichen Methoden


*** ** * ** ***

Siehe https://en.wikipedia.org/wiki/TIFF für Details. In sehr seltenen Fällen ist TIFF in WordProcessing-Dokumenten vorhanden.

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | Erstellt eine neue TiffImage-Instanz aus dem Inhalt, dargestellt als |
Base64‑kodierten String und mit angegebenem Namen
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | Erstellt eine neue GifImage‑Instanz aus dem Inhalt, dargestellt als Byte‑Stream, |
und mit angegebenem Namen
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Überprüft, ob der angegebene Stream ein gültiges TIFF-Bild ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Überprüft, ob die angegebene base64-codierte Zeichenkette ein gültiges TIFF-Bild ist |
|
|  | [getType()](#getType--) | Gibt ImageType.Tiff zurück |
|
|  | [getFramesCount()](#getFramesCount--) | Gibt die Anzahl der Frames (Bilder) in diesem TIFF-Bild zurück. |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


Erstellt eine neue TiffImage-Instanz aus dem Inhalt, dargestellt als
Base64‑kodierten String und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des TIFF-Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64-codierte Zeichenkette. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein TIFF-Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
```


Erstellt eine neue GifImage‑Instanz aus dem Inhalt, dargestellt als Byte‑Stream,
und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des GIF‑Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | Binärinhalt | java.io.InputStream | Inhalt als Bytestrom. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird dieser Strom ebenfalls freigegeben. |
|

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |
| Binärinhalt | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Überprüft, ob der angegebene Stream ein gültiges TIFF-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | java.io.InputStream | Byte-Stream, der vermutlich ein TIFF-Bild enthält |
|

**Returns:**
boolean - True, wenn der angegebene Stream ein gültiges TIFF-Bild enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Überprüft, ob die angegebene base64-codierte Zeichenkette ein gültiges TIFF-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt des vermutlich TIFF-Bildes in Form einer base64-codierten Zeichenkette |
|

**Returns:**
boolean - True, wenn die angegebene Zeichenkette ein gültiges TIFF-Bild enthält, sonst false

### getType() {#getType--}
```
public ImageType getType()
```


Gibt ImageType.Tiff zurück


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


Gibt die Anzahl der Frames (Bilder) in diesem TIFF-Bild zurück. Darf nicht
kleiner als 1 sein.


**Returns:**
int -
