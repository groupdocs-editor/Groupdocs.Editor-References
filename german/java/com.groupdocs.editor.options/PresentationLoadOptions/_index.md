---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Laden von Dokumenten aller unterstützten Präsentationsformate wie PPTX, PPTM, PPSX usw."
type: docs
weight: 33
url: /de/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Laden von Dokumenten aller unterstützten
Präsentationsformate wie PPT(X), PPTM, PPS(X) usw.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPassword()](#getPassword--) | Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für |
Öffnen des Präsentationsdokuments, falls es verschlüsselt ist.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für |
Öffnen des Präsentationsdokuments, falls es verschlüsselt ist.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für
Öffnen des Präsentationsdokuments, falls es verschlüsselt ist. Setzen Sie es auf NULL oder leer
Zeichenfolge, um das Passwort zu entfernen.


*** ** * ** ***

Standardmäßig hat diese Eigenschaft den Wert NULL — Passwort ist nicht gesetzt. Wenn das Eingabe‑Präsentationsdokument passwortgeschützt ist, ist das Passwort zwingend erforderlich und es wird eine Ausnahme ausgelöst, wenn das Passwort nicht angegeben oder ungültig ist. Wenn das Eingabe‑Präsentationsdokument NICHT passwortgeschützt ist, das Passwort jedoch gesetzt wurde, wird es ignoriert.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für
Öffnen des Präsentationsdokuments, falls es verschlüsselt ist. Setzen Sie es auf NULL oder leer
Zeichenfolge, um das Passwort zu entfernen.


*** ** * ** ***

Standardmäßig hat diese Eigenschaft den Wert NULL — Passwort ist nicht gesetzt. Wenn das Eingabe‑Präsentationsdokument passwortgeschützt ist, ist das Passwort zwingend erforderlich und es wird eine Ausnahme ausgelöst, wenn das Passwort nicht angegeben oder ungültig ist. Wenn das Eingabe‑Präsentationsdokument NICHT passwortgeschützt ist, das Passwort jedoch gesetzt wurde, wird es ignoriert.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

