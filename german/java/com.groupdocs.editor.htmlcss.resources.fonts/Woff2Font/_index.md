---
title: "Woff2Font"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt eine Schrift im WOFF2 Web Open Font Format dar"
type: docs
weight: 16
url: /de/java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

Stellt eine Schriftart im WOFF2-Format (Web Open Font Format) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | Erstellt eine neue Woff2Font‑Klasse aus Inhalt, dargestellt als base64‑kodiert |
String und mit angegebenem Namen
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | Erstellt eine neue Woff2Font‑Klasse aus Inhalt, dargestellt als Byte‑Stream, und |
mit angegebenem Namen
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | WOFF2‑Headergröße (in Bytes), die für die Validierung erforderlich ist |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Prüft, ob der angegebene Stream eine gültige WOFF2‑Schrift ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Prüft, ob der angegebene base64‑kodierte String eine gültige WOFF2‑Schrift ist |
|
|  | [getType()](#getType--) | Gibt FontType.Woff2 zurück |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


Erstellt eine neue Woff2Font‑Klasse aus Inhalt, dargestellt als base64‑kodiert
String und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name der WOFF2‑Schrift. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64‑kodierter String. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein WOFF2‑Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


Erstellt eine neue Woff2Font‑Klasse aus Inhalt, dargestellt als Byte‑Stream, und
mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name der WOFF2‑Schrift. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | binaryContent | java.io.InputStream | Inhalt als Byte‑Stream. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und durchsuchbar sein. Wird diese Instanz freigegeben, wird auch dieser Stream freigegeben. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF2‑Headergröße (in Bytes), die für die Validierung erforderlich ist


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Prüft, ob der angegebene Stream eine gültige WOFF2‑Schrift ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑Stream, der vermutlich eine WOFF2‑Ressource enthält |
|

**Returns:**
boolean – True, wenn der angegebene Stream eine gültige WOFF2‑Schrift enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Prüft, ob der angegebene base64‑kodierte String eine gültige WOFF2‑Schrift ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt der vermutlich WOFF2‑Schrift in Form eines base64‑kodierten Strings |
|

**Returns:**
boolean – True, wenn der angegebene String eine gültige WOFF2‑Schrift enthält, sonst false

### getType() {#getType--}
```
public FontType getType()
```


Gibt FontType.Woff2 zurück


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
