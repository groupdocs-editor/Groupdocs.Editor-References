---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Enthält Optionen zum Laden von WordProcessing‑Word‑kompatiblen Dokumenten wie DOCX, RTF, ODT usw."
type: docs
weight: 45
url: /de/nodejs-java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

Enthält Optionen zum Laden von WordProcessing (Word‑kompatiblen) Dokumenten wie
DOC(X), RTF, ODT usw. in die Editor‑Klasse

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPassword()](#getPassword--) | Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für |
Öffnen eines WordProcessing‑Dokuments, falls es verschlüsselt ist.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für |
Öffnen eines WordProcessing‑Dokuments, falls es verschlüsselt ist.
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für
Öffnen eines WordProcessing‑Dokuments, falls es verschlüsselt ist. Auf NULL oder leer setzen
Zeichenkette, um das Passwort nicht zu verwenden (Standardwert).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für
Öffnen eines WordProcessing‑Dokuments, falls es verschlüsselt ist. Auf NULL oder leer setzen
Zeichenkette, um das Passwort nicht zu verwenden (Standardwert).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

