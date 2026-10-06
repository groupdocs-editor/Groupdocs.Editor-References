---
title: "PdfLoadOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Enthält Optionen zum Laden von PDF‑Dokumenten in die Editor‑Klasse."
type: docs
weight: 30
url: /de/java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

Enthält Optionen zum Laden von PDF‑Dokumenten in die Editor‑Klasse.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPassword()](#getPassword--) | Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das zum Öffnen eines PDF‑Dokuments verwendet wird, falls es verschlüsselt ist. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das zum Öffnen eines PDF‑Dokuments verwendet wird, falls es verschlüsselt ist. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das zum Öffnen eines PDF‑Dokuments verwendet wird, falls es verschlüsselt ist.
Auf NULL oder leere Zeichenfolge setzen, um das Passwort nicht zu verwenden (Standardwert).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das zum Öffnen eines PDF‑Dokuments verwendet wird, falls es verschlüsselt ist.
Auf NULL oder leere Zeichenfolge setzen, um das Passwort nicht zu verwenden (Standardwert).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

