---
title: "IconImage"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt ein Bild im ICON-Format mit seinen Metadaten und zusätzlichen Methoden dar."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
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
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Erstellt eine neue IconImage‑Instanz aus Inhalt, dargestellt als |
Base64‑kodierten String und mit angegebenem Namen
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Erstellt eine neue IconImage‑Instanz aus Inhalt, dargestellt als Byte‑Stream, |
und mit angegebenem Namen
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Überprüft, ob der angegebene Stream ein gültiges ICON‑Bild ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Überprüft, ob der angegebene Base64‑kodierte String ein gültiges ICON‑Bild ist |
|
|  | [getType()](#getType--) | Gibt ImageType.Icon zurück |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Gibt die Anzahl der Bilder zurück, die in dieser ICON‑Datei vorhanden sind |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Erstellt eine neue IconImage‑Instanz aus Inhalt, dargestellt als
Base64‑kodierten String und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des ICON‑Bildes. Darf nicht null, leer oder nur aus Leerzeichen bestehen. |
|
|  | contentInBase64 | java.lang.String | Inhalt als Base64‑kodierter String. Darf nicht null, leer oder nur aus Leerzeichen bestehen. Wenn es kein ICON‑Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Erstellt eine neue IconImage‑Instanz aus Inhalt, dargestellt als Byte‑Stream,
und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des ICON‑Bildes. Darf nicht null, leer oder nur aus Leerzeichen bestehen. |
|
|  | Binärinhalt | java.io.InputStream | Inhalt als Bytestrom. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird dieser Strom ebenfalls freigegeben. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Überprüft, ob der angegebene Stream ein gültiges ICON‑Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | java.io.InputStream | Byte-Stream, der vermutlich ein ICON‑Bild enthält |
|

**Returns:**
boolean - True, wenn der angegebene Stream ein gültiges ICON‑Bild enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Überprüft, ob der angegebene Base64‑kodierte String ein gültiges ICON‑Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt des vermutlich ICON‑Bildes in Form eines base64‑kodierten Strings |
|

**Returns:**
boolean - True, wenn der angegebene String ein gültiges ICON‑Bild enthält, sonst false

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


Gibt die Anzahl der Bilder zurück, die in dieser ICON‑Datei vorhanden sind


**Returns:**
int
