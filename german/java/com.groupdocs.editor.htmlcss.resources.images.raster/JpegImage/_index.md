---
title: "JpegImage"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt ein Bild im JPEG Joint Photographic Experts Group-Format mit seinen Metadaten und zusätzlichen Methoden dar"
type: docs
weight: 13
url: /de/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Stellt ein Bild im JPEG (Joint Photographic Experts Group)-Format mit
seinen Metadaten und zusätzlichen Methoden

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | Erstellt eine neue JpegImage-Instanz aus dem Inhalt, dargestellt als |
Base64-codierter Zeichenkette und mit angegebenem Namen
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | Erstellt eine neue JpegImage-Instanz aus dem Inhalt, dargestellt als Byte-Stream, |
und mit angegebenem Namen
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Überprüft, ob der angegebene Stream ein gültiges JPEG-Bild ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Überprüft, ob die angegebene base64-codierte Zeichenkette ein gültiges JPEG-Bild ist |
|
|  | [getType()](#getType--) | Gibt ImageType.Jpeg zurück |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


Erstellt eine neue JpegImage-Instanz aus dem Inhalt, dargestellt als
Base64-codierter Zeichenkette und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des JPEG-Bildes. Darf nicht null, leer oder nur aus Leerzeichen bestehen. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64-codierter String. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein JPEG-Inhalt ist, wird eine Ausnahme ausgelöst. |
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
|  | Name | java.lang.String | Name des JPEG-Bildes. Darf nicht null, leer oder nur aus Leerzeichen bestehen. |
|
|  | binaryContent | java.io.InputStream | Inhalt als Byte-Stream. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird auch dieser Stream freigegeben. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Überprüft, ob der angegebene Stream ein gültiges JPEG-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑Stream, der vermutlich ein JPEG‑Bild enthält |
|

**Returns:**
boolean - True, wenn der angegebene Stream ein gültiges JPEG‑Bild enthält, sonst False

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Überprüft, ob die angegebene base64-codierte Zeichenkette ein gültiges JPEG-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt des vermutlich JPEG‑Bildes in Form eines base64-codierten Strings |
|

**Returns:**
boolean - True, wenn der angegebene String ein gültiges JPEG‑Bild enthält, sonst False

### getType() {#getType--}
```
public ImageType getType()
```


Gibt ImageType.Jpeg zurück


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
