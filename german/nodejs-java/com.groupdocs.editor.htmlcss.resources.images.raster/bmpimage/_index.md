---
title: "BmpImage"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt ein Bild im BMP BitMap Picture-Format mit seinen Metadaten und zusätzlichen Methoden dar"
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

Stellt ein Bild im BMP (BitMap Picture)-Format dar mit seinen Metadaten und
zusätzliche Methoden

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | Erstellt eine neue BmpImage-Instanz aus dem Inhalt, dargestellt als base64-kodiert |
String, und mit angegebenem Namen
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | Erstellt eine neue BmpImage-Instanz aus dem Inhalt, dargestellt als Byte-Stream, |
und mit angegebenem Namen
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Überprüft, ob der angegebene Stream ein gültiges BMP‑Bild ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Überprüft, ob die angegebene base64‑codierte Zeichenkette ein gültiges BMP‑Bild ist |
|
|  | [getType()](#getType--) | Gibt ImageType.Bmp zurück |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


Erstellt eine neue BmpImage-Instanz aus dem Inhalt, dargestellt als base64-kodiert
String, und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des BMP‑Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64‑codierte Zeichenkette. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein BMP‑Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


Erstellt eine neue BmpImage-Instanz aus dem Inhalt, dargestellt als Byte-Stream,
und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des BMP‑Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | Binärinhalt | java.io.InputStream | Inhalt als Bytestrom. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird dieser Strom ebenfalls freigegeben. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Überprüft, ob der angegebene Stream ein gültiges BMP‑Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | java.io.InputStream | Byte‑Stream, der vermutlich ein BMP‑Bild enthält |
|

**Returns:**
boolescher Wert – True, wenn der angegebene Stream ein gültiges BMP‑Bild enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Überprüft, ob die angegebene base64‑codierte Zeichenkette ein gültiges BMP‑Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt des vermutlich BMP‑Bildes in Form einer base64‑codierten Zeichenkette |
|

**Returns:**
boolescher Wert – True, wenn die angegebene Zeichenkette ein gültiges BMP‑Bild enthält, sonst false

### getType() {#getType--}
```
public ImageType getType()
```


Gibt ImageType.Bmp zurück


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
