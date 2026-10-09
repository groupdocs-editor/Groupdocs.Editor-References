---
title: "Woff2Font"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt eine Schriftart im WOFF2 Web Open Font Format dar"
type: docs
weight: 16
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

Stellt eine Schriftart im WOFF2‑Format (Web Open Font Format) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | Erstellt neue Woff2Font-Klasse aus Inhalt, dargestellt als base64-codiert |
String, und mit angegebenem Namen
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | Erstellt neue Woff2Font-Klasse aus Inhalt, dargestellt als Bytestrom, und |
mit angegebenem Namen
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | WOFF2-Headergröße (in Bytes), die für die Validierung erforderlich ist |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Prüft, ob der angegebene Stream eine gültige WOFF2-Schriftart ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Prüft, ob die angegebene base64-codierte Zeichenkette eine gültige WOFF2-Schriftart ist |
|
|  | [getType()](#getType--) | Gibt FontType.Woff2 zurück |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


Erstellt neue Woff2Font-Klasse aus Inhalt, dargestellt als base64-codiert
String, und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name der WOFF2-Schriftart. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64-codierte Zeichenkette. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein WOFF2-Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


Erstellt neue Woff2Font-Klasse aus Inhalt, dargestellt als Bytestrom, und
mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name der WOFF2-Schriftart. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | Binärinhalt | java.io.InputStream | Inhalt als Byte-Stream. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz entsorgt wird, wird auch dieser Stream entsorgt. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF2-Headergröße (in Bytes), die für die Validierung erforderlich ist


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Prüft, ob der angegebene Stream eine gültige WOFF2-Schriftart ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | java.io.InputStream | Bytestrom, der vermutlich eine WOFF2-Ressource enthält |
|

**Returns:**
boolescher Wert – True, wenn der angegebene Stream eine gültige WOFF2-Schriftart enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Prüft, ob die angegebene base64-codierte Zeichenkette eine gültige WOFF2-Schriftart ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt der vermutlich WOFF2-Schriftart in Form einer base64-codierten Zeichenkette |
|

**Returns:**
boolescher Wert – True, wenn die angegebene Zeichenkette eine gültige WOFF2-Schriftart enthält, sonst false

### getType() {#getType--}
```
public FontType getType()
```


Gibt FontType.Woff2 zurück


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
