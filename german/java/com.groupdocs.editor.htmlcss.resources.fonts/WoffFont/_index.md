---
title: "WoffFont"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt ein Font im WOFF Web Open Font Format dar"
type: docs
weight: 17
url: /de/java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class WoffFont extends FontResourceBase
```

Stellt eine Schriftart im WOFF-Format (Web Open Font Format) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WoffFont(String name, String contentInBase64)](#WoffFont-java.lang.String-java.lang.String-) | Erstellt eine neue WoffFont‑Klasse aus Inhalt, dargestellt als Base64‑kodiert |
String und mit angegebenem Namen
|
|  | [WoffFont(String name, InputStream binaryContent)](#WoffFont-java.lang.String-java.io.InputStream-) | Erstellt eine neue WoffFont‑Klasse aus Inhalt, dargestellt als Byte‑Stream, und |
mit angegebenem Namen
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | WOFF-Headergröße (in Bytes), die für die Validierung erforderlich ist |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Überprüft, ob der angegebene Stream ein gültiges WOFF‑Font ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Überprüft, ob die angegebene Base64‑kodierte Zeichenkette ein gültiges WOFF‑Font ist |
|
|  | [getType()](#getType--) | Gibt FontType.Woff zurück |
|
### WoffFont(String name, String contentInBase64) {#WoffFont-java.lang.String-java.lang.String-}
```
public WoffFont(String name, String contentInBase64)
```


Erstellt eine neue WoffFont‑Klasse aus Inhalt, dargestellt als Base64‑kodiert
String und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des WOFF‑Fonts. Darf nicht null, leer oder nur aus Leerzeichen bestehen. |
|
|  | contentInBase64 | java.lang.String | Inhalt als Base64‑kodierte Zeichenkette. Darf nicht null, leer oder nur aus Leerzeichen bestehen. Wenn es kein WOFF‑Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### WoffFont(String name, InputStream binaryContent) {#WoffFont-java.lang.String-java.io.InputStream-}
```
public WoffFont(String name, InputStream binaryContent)
```


Erstellt eine neue WoffFont‑Klasse aus Inhalt, dargestellt als Byte‑Stream, und
mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des WOFF‑Fonts. Darf nicht null, leer oder nur aus Leerzeichen bestehen. |
|
|  | binaryContent | java.io.InputStream | Inhalt als Byte‑Stream. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und durchsuchbar sein. Wird diese Instanz freigegeben, wird auch dieser Stream freigegeben. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF-Headergröße (in Bytes), die für die Validierung erforderlich ist


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Überprüft, ob der angegebene Stream ein gültiges WOFF‑Font ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑Stream, der vermutlich eine WOFF‑Ressource enthält |
|

**Returns:**
boolesch – True, wenn der angegebene Stream ein gültiges WOFF‑Font enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Überprüft, ob die angegebene Base64‑kodierte Zeichenkette ein gültiges WOFF‑Font ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt des vermutlich WOFF‑Fonts in Form einer Base64‑kodierten Zeichenkette |
|

**Returns:**
boolesch – True, wenn die angegebene Zeichenkette ein gültiges WOFF‑Font enthält, sonst false

### getType() {#getType--}
```
public FontType getType()
```


Gibt FontType.Woff zurück


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
