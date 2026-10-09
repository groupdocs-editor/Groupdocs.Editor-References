---
title: "MetaImageBase"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Abstrakte Basisklasse für WMF- und EMF-Bildformate."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

Abstrakte Basisklasse für WMF- und EMF-Bildformate.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Gemeinsamer Konstruktor, der das Erzeugen einer WMF‑ oder EMF‑Instanz aus vorbereitet |
Base64‑kodierter String
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Gemeinsamer Konstruktor, der das Erzeugen einer WMF‑ oder EMF‑Instanz aus vorbereitet |
Byte‑Stream
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Bestimmt, ob der angegebene Byte‑Stream ein gültiges WMF‑Bild enthält |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Bestimmt, ob der angegebene String ein gültiges WMF‑Bild enthält, das |
mit Base64 kodiert
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Bestimmt, ob der angegebene Byte‑Stream ein gültiges EMF‑Bild enthält |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Bestimmt, ob der angegebene String ein gültiges EMF‑Bild enthält, das |
mit Base64 kodiert
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Der implementierende Typ sollte ein aktuelles Vektor‑Meta‑Bild in das |
Vektor‑SVG‑Format in den angegebenen Byte‑Stream speichern
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Gemeinsamer Konstruktor, der das Erzeugen einer WMF‑ oder EMF‑Instanz aus vorbereitet
Base64‑kodierter String


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Erforderlicher Name |
|
|  | contentInBase64 | java.lang.String | Inhalt als Base64‑String. Sollte nicht NULL oder leer sein. |
|
|  | isWmf | boolesch | true für WMF, false für EMF |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Gemeinsamer Konstruktor, der das Erzeugen einer WMF‑ oder EMF‑Instanz aus vorbereitet
Byte‑Stream


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Erforderlicher Name |
|
|  | Binärinhalt | java.io.InputStream | Inhalt als Byte‑Stream. Sollte gültig sein. |
|
|  | isWmf | boolesch | true für WMF, false für EMF |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


Bestimmt, ob der angegebene Byte‑Stream ein gültiges WMF‑Bild enthält


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | java.io.InputStream | Eingabe‑Byte‑Stream. Sollte gültig sein. |
|

**Returns:**
boolescher Wert – Gibt 'true' zurück, wenn gültig, und 'false', wenn ungültig

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


Bestimmt, ob der angegebene String ein gültiges WMF‑Bild enthält, das
mit Base64 kodiert


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String, von dem angenommen wird, dass er ein Base64‑kodiertes WMF‑Bild enthält |
|

**Returns:**
boolescher Wert – Gibt 'true' zurück, wenn gültig, und 'false', wenn ungültig

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


Bestimmt, ob der angegebene Byte‑Stream ein gültiges EMF‑Bild enthält


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | java.io.InputStream | Eingabe‑Byte‑Stream. Sollte gültig sein. |
|

**Returns:**
boolescher Wert – Gibt 'true' zurück, wenn gültig, und 'false', wenn ungültig

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


Bestimmt, ob der angegebene String ein gültiges EMF‑Bild enthält, das
mit Base64 kodiert


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String, von dem angenommen wird, dass er ein Base64‑kodiertes EMF‑Bild enthält |
|

**Returns:**
boolescher Wert – Gibt 'true' zurück, wenn gültig, und 'false', wenn ungültig

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


Der implementierende Typ sollte ein aktuelles Vektor‑Meta‑Bild in das
Vektor‑SVG‑Format in den angegebenen Byte‑Stream speichern


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Byte‑Stream, in den die SVG‑Version dieses Vektor‑Meta‑Bildes gespeichert wird. Sollte nicht NULL sein und Schreiben unterstützen. |
|

