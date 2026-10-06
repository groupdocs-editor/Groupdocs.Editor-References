---
title: "OtfFont"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt eine Schrift im OTF Open Type Format dar"
type: docs
weight: 13
url: /de/java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

Stellt eine Schriftart im OTF-Format (Open Type Format) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | Erstellt eine neue OtfFont-Klasse aus dem Inhalt, dargestellt als base64-kodiert |
String und mit angegebenem Namen
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | Erstellt eine neue OtfFont-Klasse aus dem Inhalt, dargestellt als Bytestrom, und |
mit angegebenem Namen
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | OTF-Headergröße (in Bytes), die für die Validierung erforderlich ist |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Prüft, ob der angegebene Stream eine gültige OTF-Schrift ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Prüft, ob der angegebene base64-kodierte String eine gültige OTF-Schrift ist |
|
|  | [getType()](#getType--) | Gibt zurück |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


Erstellt eine neue OtfFont-Klasse aus dem Inhalt, dargestellt als base64-kodiert
String und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name der OTF-Schrift. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64-kodierter String. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein OTF-Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


Erstellt eine neue OtfFont-Klasse aus dem Inhalt, dargestellt als Bytestrom, und
mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name der OTF-Schrift. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | binaryContent | java.io.InputStream | Inhalt als Byte-Stream. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird auch dieser Stream freigegeben. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


OTF-Headergröße (in Bytes), die für die Validierung erforderlich ist


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Prüft, ob der angegebene Stream eine gültige OTF-Schrift ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Bytestrom, der vermutlich eine OTF-Ressource enthält |
|

**Returns:**
boolescher Wert – True, wenn der angegebene Stream eine gültige OTF-Schrift enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Prüft, ob der angegebene base64-kodierte String eine gültige OTF-Schrift ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt der vermutlich OTF-Schrift in Form eines base64-kodierten Strings |
|

**Returns:**
boolescher Wert – True, wenn der angegebene String eine gültige OTF-Schrift enthält, sonst false

### getType() {#getType--}
```
public FontType getType()
```


Gibt zurück
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
