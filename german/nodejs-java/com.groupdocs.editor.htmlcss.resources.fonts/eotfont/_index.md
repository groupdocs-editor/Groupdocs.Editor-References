---
title: "EotFont"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt eine Schriftart im EOT Embedded OpenType-Format dar"
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

Stellt eine Schriftart im EOT‑Format (Embedded OpenType) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | Erstellt eine neue EotFont-Klasse aus Inhalt, dargestellt als base64-codiert |
String, und mit angegebenem Namen
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | Erstellt eine neue EotFont-Klasse aus Inhalt, dargestellt als Bytestrom, und |
mit angegebenem Namen
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | EOT-Headergröße (in Bytes), die für die Validierung erforderlich ist |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Prüft, ob der angegebene Strom eine gültige EOT-Schriftart ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Prüft, ob die angegebene base64-codierte Zeichenkette eine gültige EOT-Schriftart ist |
|
|  | [getType()](#getType--) | Gibt FontType.Eot zurück |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


Erstellt eine neue EotFont-Klasse aus Inhalt, dargestellt als base64-codiert
String, und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name der EOT-Schriftart. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64-codierte Zeichenkette. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein EOT-Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


Erstellt eine neue EotFont-Klasse aus Inhalt, dargestellt als Bytestrom, und
mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name der EOT-Schriftart. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | Binärinhalt | java.io.InputStream | Inhalt als Bytestrom. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird dieser Strom ebenfalls freigegeben. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


EOT-Headergröße (in Bytes), die für die Validierung erforderlich ist


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Prüft, ob der angegebene Strom eine gültige EOT-Schriftart ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | java.io.InputStream | Bytestrom, der vermutlich eine EOT-Ressource enthält |
|

**Returns:**
boolean - Wahr, wenn der angegebene Strom eine gültige EOT-Schriftart enthält, sonst falsch

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Prüft, ob die angegebene base64-codierte Zeichenkette eine gültige EOT-Schriftart ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt der vermutlich EOT-Schriftart in Form eines base64-codierten Strings |
|

**Returns:**
boolean - Wahr, wenn die angegebene Zeichenkette eine gültige EOT-Schriftart enthält, sonst falsch

### getType() {#getType--}
```
public FontType getType()
```


Gibt FontType.Eot zurück


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
