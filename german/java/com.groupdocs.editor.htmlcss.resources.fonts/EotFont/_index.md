---
title: "EotFont"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt eine Schriftart im EOT Embedded OpenType-Format dar"
type: docs
weight: 10
url: /de/java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

Stellt eine Schriftart im EOT-Format (Embedded OpenType) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | Erstellt eine neue EotFont-Klasse aus dem Inhalt, dargestellt als base64-kodiert |
String und mit angegebenem Namen
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | Erstellt eine neue EotFont-Klasse aus dem Inhalt, dargestellt als Bytestrom, und |
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
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Überprüft, ob der angegebene Stream eine gültige EOT-Schriftart ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Überprüft, ob die angegebene base64-kodierte Zeichenkette eine gültige EOT-Schriftart ist |
|
|  | [getType()](#getType--) | Gibt FontType.Eot zurück |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


Erstellt eine neue EotFont-Klasse aus dem Inhalt, dargestellt als base64-kodiert
String und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name der EOT-Schriftart. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64-kodierte Zeichenkette. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein EOT-Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


Erstellt eine neue EotFont-Klasse aus dem Inhalt, dargestellt als Bytestrom, und
mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name der EOT-Schriftart. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | binaryContent | java.io.InputStream | Inhalt als Byte-Stream. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird auch dieser Stream freigegeben. |
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


Überprüft, ob der angegebene Stream eine gültige EOT-Schriftart ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Bytestrom, der vermutlich eine EOT-Ressource enthält |
|

**Returns:**
boolesch – True, wenn der angegebene Stream eine gültige EOT-Schriftart enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Überprüft, ob die angegebene base64-kodierte Zeichenkette eine gültige EOT-Schriftart ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt der vermutlich EOT-Schriftart in Form einer base64-kodierten Zeichenkette |
|

**Returns:**
boolesch – True, wenn die angegebene Zeichenkette eine gültige EOT-Schriftart enthält, sonst false

### getType() {#getType--}
```
public FontType getType()
```


Gibt FontType.Eot zurück


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
