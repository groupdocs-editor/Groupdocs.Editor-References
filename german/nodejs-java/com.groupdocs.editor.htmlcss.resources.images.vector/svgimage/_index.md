---
title: "SvgImage"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt ein Vektorbild im SVG (Scalable Vector Graphics)-Format mit seinen Metadaten und zusätzlichen Methoden dar"
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

Stellt ein Vektorbild im SVG (Scalable Vector Graphics)-Format mit seinen dar
Metadaten und zusätzlichen Methoden

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | Erstellt eine neue SvgImage-Instanz aus dem Inhalt, dargestellt als übliche Zeichenkette, |
und mit angegebenem Namen
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | Erstellt eine neue SvgImage-Instanz aus dem Inhalt, dargestellt als Byte-Stream, |
und mit angegebenem Namen
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | Führt eine Oberflächenprüfung durch, ob der angegebene textuelle XML-konforme Inhalt |
stellt ein SVG-Bild dar
|
|  | [getType()](#getType--) | Gibt ImageType.Svg zurück |
|
|  | [getByteContent()](#getByteContent--) | Gibt den Inhalt dieses SVG-Bildes als Binärstrom zurück |
|
|  | [getTextContent()](#getTextContent--) | Gibt den Inhalt dieses SVG-Bildes als Klartext (im XML-Format) zurück |
|
|  | [getXmlContent()](#getXmlContent--) | Gibt den Inhalt dieses SVG-Bildes in seiner ursprünglichen XML-konformen Form zurück |
textuelle Form
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Speichert dieses SVG-Bild in die Datei |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Speichert dieses Vektor‑SVG-Bild in ein Raster‑PNG-Bild |
|
|  | [dispose()](#dispose--) | Entfernt dieses Rasterbild, gibt dessen Inhalt frei und macht die meisten Methoden |
und Eigenschaften nicht funktionsfähig.
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


Erstellt eine neue SvgImage-Instanz aus dem Inhalt, dargestellt als übliche Zeichenkette,
und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des SVG-Bildes. Darf nicht null, leer oder nur aus Leerzeichen bestehen. |
|
|  | Inhalt | java.lang.String | Inhalt als übliche Zeichenkette, die einen gültigen XML‑konformen Inhalt eines SVG-Bildes enthält. Darf nicht null, leer oder nur aus Leerzeichen bestehen. Wenn es kein SVG‑Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


Erstellt eine neue SvgImage-Instanz aus dem Inhalt, dargestellt als Byte-Stream,
und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des SVG-Bildes. Darf nicht null, leer oder nur aus Leerzeichen bestehen. |
|
|  | Binärinhalt | java.io.InputStream | Inhalt als Bytestrom. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird dieser Strom ebenfalls freigegeben. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


Führt eine Oberflächenprüfung durch, ob der angegebene textuelle XML-konforme Inhalt
stellt ein SVG-Bild dar


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Inhalt | java.lang.String | XML‑Inhalt eines SVG-Bildes als einfacher Text, nicht als base64‑kodierter Inhalt |
|

**Returns:**
boolescher Wert – True, wenn die angegebene Zeichenkette auf den ersten Blick als gültiges SVG behandelt werden kann, false, wenn sie definitiv kein SVG ist

### getType() {#getType--}
```
public ImageType getType()
```


Gibt ImageType.Svg zurück


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Gibt den Inhalt dieses SVG-Bildes als Binärstrom zurück


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Gibt den Inhalt dieses SVG-Bildes als Klartext (im XML-Format) zurück


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


Gibt den Inhalt dieses SVG-Bildes in seiner ursprünglichen XML-konformen Form zurück
textuelle Form


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Speichert dieses SVG-Bild in die Datei


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | vollerPfadZurDatei | java.lang.String | Vollständiger Pfad zur Datei, die erstellt wird (falls sie nicht existiert) oder überschrieben wird (falls sie existiert) mit dem Inhalt dieses SVG-Bildes |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Speichert dieses Vektor‑SVG-Bild in ein Raster‑PNG-Bild


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Ausgabestream, in den der Inhalt des PNG-Bildes geschrieben wird. Darf nicht NULL sein und sollte beschreibbar sein. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Entfernt dieses Rasterbild, gibt dessen Inhalt frei und macht die meisten Methoden
und Eigenschaften nicht funktionsfähig.


