---
title: "TtcFont"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt eine Schriftart im TTC TrueType Collection‑Format dar"
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

Stellt eine Schriftart im TTC‑Format (TrueType Collection) dar.


Mehr erfahren: https://docs.fileformat.com/font/ttc/

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | Erstellt eine neue TtcFont‑Klasse aus Inhalt, dargestellt als base64‑kodiert |
String, und mit angegebenem Namen
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | Erstellt eine neue TtcFont‑Klasse aus Inhalt, dargestellt als Bytestream, und |
mit angegebenem Namen
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTC‑Headergröße (in Bytes), die für die Validierung erforderlich ist |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Prüft, ob der angegebene Stream ein gültiger TTC‑Font ist |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Überprüft, ob die angegebene base64-codierte Zeichenkette ein gültiger TTC‑Font ist |
|
|  | [getType()](#getType--) | Gibt FontType.Ttc zurück |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | TTC‑Header‑Version, kann "1" oder "2" sein |
|
|  | [getFontsNumber()](#getFontsNumber--) | Anzahl der Fonts in diesem TTC |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | Gibt an, ob dieses TTC eine DSIG‑Tabelle hat. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


Erstellt eine neue TtcFont‑Klasse aus Inhalt, dargestellt als base64‑kodiert
String, und mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des TTC‑Fonts. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | contentInBase64 | java.lang.String | Inhalt als base64‑codierte Zeichenkette. Darf nicht null, leer oder nur Leerzeichen sein. Wenn es kein TTC‑Inhalt ist, wird eine Ausnahme ausgelöst. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


Erstellt eine neue TtcFont‑Klasse aus Inhalt, dargestellt als Bytestream, und
mit angegebenem Namen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des TTC‑Fonts. Darf nicht null, leer oder nur Leerzeichen sein. |
|
|  | Binärinhalt | java.io.InputStream | Inhalt als Bytestrom. Das Lesen beginnt an der ursprünglichen Position. Darf nicht null sein. Sollte lesbar und suchbar sein. Wenn diese Instanz freigegeben wird, wird dieser Strom ebenfalls freigegeben. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTC‑Headergröße (in Bytes), die für die Validierung erforderlich ist


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Prüft, ob der angegebene Stream ein gültiger TTC‑Font ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Binärinhalt | java.io.InputStream | Byte‑Stream, der vermutlich eine TTC‑Ressource enthält |
|

**Returns:**
boolescher Wert – true, wenn der angegebene Stream einen gültigen TTC‑Font enthält, sonst false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Überprüft, ob die angegebene base64-codierte Zeichenkette ein gültiger TTC‑Font ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhalt des vermutlich TTC‑Fonts in Form einer base64‑codierten Zeichenkette |
|

**Returns:**
boolescher Wert – true, wenn die angegebene Zeichenkette einen gültigen TTC‑Font enthält, sonst false

### getType() {#getType--}
```
public FontType getType()
```


Gibt FontType.Ttc zurück


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


TTC‑Header‑Version, kann "1" oder "2" sein


**Returns:**
Byte
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


Anzahl der Fonts in diesem TTC


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


Gibt an, ob dieses TTC eine DSIG‑Tabelle hat. DSIG‑Tabelle kann vorhanden sein
nur wenn das TTC eine Header‑Version 2.0 hat.


**Returns:**
boolesch
