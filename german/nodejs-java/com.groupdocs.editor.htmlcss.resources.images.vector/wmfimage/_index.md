---
title: "WmfImage"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt ein Vektorbild im WMF Windows MetaFile-Format mit seinen Metadaten und zusätzlichen Methoden dar"
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

Stellt ein Vektorbild im WMF (Windows MetaFile)-Format mit seinem
Metadaten und zusätzlichen Methoden

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | Erstellt eine neue WmfImage-Instanz aus dem Inhalt, dargestellt als base64-codiert |
String, und mit angegebenem Namen
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | Erstellt eine neue WmfImage-Instanz aus dem Inhalt, dargestellt als Bytestrom, |
und mit angegebenem Namen
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Prüft, ob der angegebene Stream ein gültiges WMF-Bild ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Prüft, ob die angegebene base64-codierte Zeichenkette ein gültiges WMF-Bild ist |
|
|  | [getType()](#getType--) | Gibt ImageType.Wmf zurück |
|
|  | [getByteContent()](#getByteContent--) | Gibt den Inhalt dieses WMF-Bildes als Binärstrom zurück |
|
|  | [getTextContent()](#getTextContent--) | Gibt den Inhalt dieses WMF-Bildes als Klartext zurück |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Speichert dieses WMF-Bild in die Datei |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Speichert dieses Vektor-WMF-Bild in ein Raster-PNG-Bild |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Speichert dieses Vektor-WMF-Bild in ein Vektor-SVG-Bild |
|
|  | [dispose()](#dispose--) | Entfernt dieses WMF-Bild, indem es dessen Inhalt freigibt und die meisten seiner |
Methoden und Eigenschaften nicht funktionsfähig macht
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


Erstellt eine neue WmfImage-Instanz aus dem Inhalt, dargestellt als base64-codiert
String, und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des WMF-Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64-codierte Zeichenkette. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein WMF-Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


Erstellt eine neue WmfImage-Instanz aus dem Inhalt, dargestellt als Bytestrom,
und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des WMF-Bildes. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | Binärinhalt | java.io.InputStream | Inhalt als Bytestrom. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird dieser Strom ebenfalls freigegeben. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Prüft, ob der angegebene Stream ein gültiges WMF-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | java.io.InputStream | Eingabe-Bytestrom. Darf nicht NULL sein und sollte Lesen und Suchen unterstützen. |
|

**Returns:**
boolescher Wert – True, wenn der angegebene Stream ein gültiges WMF-Bild enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Prüft, ob die angegebene base64-codierte Zeichenkette ein gültiges WMF-Bild ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Eingabezeichenkette, in der der Inhalt des WMF-Bildes base64-codiert gespeichert ist. Darf nicht NULL oder leer sein. |
|

**Returns:**
boolescher Wert – True, wenn die angegebene Zeichenkette ein gültiges WMF-Bild enthält, sonst false

### getType() {#getType--}
```
public ImageType getType()
```


Gibt ImageType.Wmf zurück


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Gibt den Inhalt dieses WMF-Bildes als Binärstrom zurück


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Gibt den Inhalt dieses WMF-Bildes als Klartext zurück


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Speichert dieses WMF-Bild in die Datei


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | vollerPfadZurDatei | java.lang.String | Vollständiger Pfad zur Datei, die erstellt (falls sie nicht existiert) oder überschrieben (falls sie existiert) wird mit dem Inhalt dieses WMF-Bildes |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Speichert dieses Vektor-WMF-Bild in ein Raster-PNG-Bild


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Ausgabestream, in den der Inhalt des PNG-Bildes geschrieben wird. Darf nicht NULL sein und sollte beschreibbar sein. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Speichert dieses Vektor-WMF-Bild in ein Vektor-SVG-Bild


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Ausgabestream, in den der Inhalt des SVG-Bildes geschrieben wird. Darf nicht NULL sein und sollte beschreibbar sein. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Entfernt dieses WMF-Bild, indem es dessen Inhalt freigibt und die meisten seiner
Methoden und Eigenschaften nicht funktionsfähig macht


