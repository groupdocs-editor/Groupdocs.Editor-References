---
title: "TtfFont"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt eine Schrift im TTF TrueType Font‑Format dar"
type: docs
weight: 15
url: /de/java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

Stellt eine Schriftart im TTF-Format (TrueType Font) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | Erstellt eine neue TtfFont‑Klasse aus Inhalt, dargestellt als base64‑kodiert |
String und mit angegebenem Namen
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | Erstellt eine neue TtfFont‑Klasse aus Inhalt, dargestellt als Byte‑Stream, und |
mit angegebenem Namen
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTF-Headergröße (in Bytes), die für die Validierung erforderlich ist |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Überprüft, ob der angegebene Stream ein gültiges TTF‑Font ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Überprüft, ob die angegebene Base64‑kodierte Zeichenkette ein gültiges TTF‑Font ist |
|
|  | [getType()](#getType--) | Gibt FontType.Ttf zurück |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


Erstellt eine neue TtfFont‑Klasse aus Inhalt, dargestellt als base64‑kodiert
String und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des TTF‑Fonts. Darf nicht null, leer oder nur aus Leerzeichen bestehen. |
|
|  | contentInBase64 | java.lang.String | Inhalt als Base64‑kodierte Zeichenkette. Darf nicht null, leer oder nur aus Leerzeichen bestehen. Wenn es kein TTF‑Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


Erstellt eine neue TtfFont‑Klasse aus Inhalt, dargestellt als Byte‑Stream, und
mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des TTF‑Fonts. Darf nicht null, leer oder nur aus Leerzeichen bestehen. |
|
|  | binaryContent | java.io.InputStream | Inhalt als Byte-Stream. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird auch dieser Stream freigegeben. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTF-Headergröße (in Bytes), die für die Validierung erforderlich ist


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Überprüft, ob der angegebene Stream ein gültiges TTF‑Font ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑Stream, der vermutlich eine TTF‑Ressource enthält |
|

**Returns:**
boolesch – True, wenn der angegebene Stream ein gültiges TTF‑Font enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Überprüft, ob die angegebene Base64‑kodierte Zeichenkette ein gültiges TTF‑Font ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt des vermutlich TTF‑Fonts in Form einer Base64‑kodierten Zeichenkette |
|

**Returns:**
boolesch – True, wenn die angegebene Zeichenkette ein gültiges TTF‑Font enthält, sonst false

### getType() {#getType--}
```
public FontType getType()
```


Gibt FontType.Ttf zurück


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
