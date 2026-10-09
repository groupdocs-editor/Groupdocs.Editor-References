---
title: "JpegImage"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt ein Bild im JPEG Joint Photographic Experts Group-Format mit seinen Metadaten und zusätzlichen Methoden dar"
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Stellt ein Bild im JPEG (Joint Photographic Experts Group)-Format dar mit
seine Metadaten und zusätzliche Methoden

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | Erstellt eine neue JpegImage-Instanz aus dem Inhalt, dargestellt als |
Base64‑kodierten String und mit angegebenem Namen
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | Erstellt eine neue JpegImage-Instanz aus dem Inhalt, dargestellt als Byte-Stream, |
und mit angegebenem Namen
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Prüft, ob der angegebene Stream ein gültiges JPEG-Bild ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Prüft, ob die angegebene base64-kodierte Zeichenkette ein gültiges JPEG-Bild ist |
|
|  | [getType()](#getType--) | Gibt ImageType.Jpeg zurück |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


Erstellt eine neue JpegImage-Instanz aus dem Inhalt, dargestellt als
Base64‑kodierten String und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des JPEG-Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64-kodierter String. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein JPEG-Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


Erstellt eine neue JpegImage-Instanz aus dem Inhalt, dargestellt als Byte-Stream,
und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des JPEG-Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | Binärinhalt | java.io.InputStream | Inhalt als Bytestrom. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird dieser Strom ebenfalls freigegeben. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Prüft, ob der angegebene Stream ein gültiges JPEG-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | java.io.InputStream | Byte-Stream, der vermutlich ein JPEG-Bild enthält |
|

**Returns:**
boolescher Wert - True, wenn der angegebene Stream ein gültiges JPEG-Bild enthält, false sonst

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Prüft, ob die angegebene base64-kodierte Zeichenkette ein gültiges JPEG-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt des vermutlich JPEG-Bildes in Form eines base64-kodierten Strings |
|

**Returns:**
boolescher Wert - True, wenn die angegebene Zeichenkette ein gültiges JPEG-Bild enthält, false sonst

### getType() {#getType--}
```
public ImageType getType()
```


Gibt ImageType.Jpeg zurück


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
