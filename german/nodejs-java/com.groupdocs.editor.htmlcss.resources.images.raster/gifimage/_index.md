---
title: "GifImage"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt ein Bild im GIF Graphics Interchange Format dar, zusammen mit seinen Metadaten und zusätzlichen Methoden"
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

Stellt ein Bild im GIF (Graphics Interchange Format) Format dar, zusammen mit seinem
Metadaten und zusätzlichen Methoden

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | Erstellt eine neue GifImage‑Instanz aus dem Inhalt, dargestellt als base64‑kodiert |
String, und mit angegebenem Namen
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | Erstellt eine neue GifImage‑Instanz aus dem Inhalt, dargestellt als Byte‑Stream, |
und mit angegebenem Namen
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Prüft, ob der angegebene Stream ein gültiges GIF‑Bild ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Prüft, ob der angegebene base64‑kodierte String ein gültiges GIF‑Bild ist |
|
|  | [getType()](#getType--) | Gibt ImageType.Gif zurück |
|
|  | [getVersion()](#getVersion--) | Gibt die interne Version dieses GIF‑Bildes zurück (Version wird extrahiert aus |
Header)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


Erstellt eine neue GifImage‑Instanz aus dem Inhalt, dargestellt als base64‑kodiert
String, und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des GIF‑Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64‑kodierter String. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein GIF‑Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
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

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Prüft, ob der angegebene Stream ein gültiges GIF‑Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | java.io.InputStream | Byte‑Stream, der vermutlich ein GIF‑Bild enthält |
|

**Returns:**
boolean - True, wenn der angegebene Stream ein gültiges GIF‑Bild enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Prüft, ob der angegebene base64‑kodierte String ein gültiges GIF‑Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt des vermutlich GIF‑Bildes in Form eines base64‑kodierten Strings |
|

**Returns:**
boolean - True, wenn der angegebene String ein gültiges GIF‑Bild enthält, sonst false

### getType() {#getType--}
```
public ImageType getType()
```


Gibt ImageType.Gif zurück


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Gibt die interne Version dieses GIF‑Bildes zurück (Version wird extrahiert aus
Header)


**Returns:**
java.lang.String
