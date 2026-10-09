---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern der MHTML‑MIME‑Kapselung aggregierter HTML‑Dokumente."
type: docs
weight: 26
url: /de/nodejs-java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern der MHTML (MIME-Kapselung aggregierter HTML-Dokumente)-Dokumente

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | Gibt an, ob CID‑ (Content‑ID‑) URLs verwendet werden sollen, um Ressourcen (Bilder, Schriftarten, CSS) in MHTML‑Dokumenten zu referenzieren. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | Gibt an, ob CID‑ (Content‑ID‑) URLs verwendet werden sollen, um Ressourcen (Bilder, Schriftarten, CSS) in MHTML‑Dokumenten zu referenzieren. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Gibt an, ob integrierte und benutzerdefinierte Dokumenteigenschaften nach MHTML exportiert werden sollen. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Gibt an, ob integrierte und benutzerdefinierte Dokumenteigenschaften nach MHTML exportiert werden sollen. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | Gibt an, ob Sprachinformationen nach MHTML exportiert werden sollen. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Gibt an, ob Sprachinformationen nach MHTML exportiert werden sollen. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


Gibt an, ob CID‑ (Content‑ID‑) URLs verwendet werden sollen, um Ressourcen (Bilder, Schriftarten, CSS) in MHTML‑Dokumenten zu referenzieren. Standardwert ist
false
.

<br />

*** ** * ** ***


Standardmäßig werden Ressourcen in MHTML‑Dokumenten über den Dateinamen referenziert (z. b. "image.png"), der mit den "Content-Location"‑Headern von MIME‑Teilen abgeglichen wird. Diese Option ermöglicht eine alternative Methode, bei der Verweise auf Ressourcendateien als CID‑ (Content‑ID‑) URLs geschrieben werden (z. b. "cid:image.png") und mit den "Content-ID"‑Headern abgeglichen werden.


Theoretisch sollte es keinen Unterschied zwischen den beiden Referenzierungsmethoden geben und beide sollten in jedem Browser oder E‑Mail‑Programm einwandfrei funktionieren. In der Praxis jedoch scheitern einige Programme beim Abrufen von Ressourcen über den Dateinamen. Wenn Ihr Browser oder E‑Mail‑Programm das Laden von in einem MHTML‑Dokument enthaltenen Ressourcen verweigert (zeigt keine Bilder an oder lädt keine CSS‑Stile), versuchen Sie, das Dokument mit CID‑URLs zu exportieren.

<br />



**Returns:**
boolesch
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


Gibt an, ob CID‑ (Content‑ID‑) URLs verwendet werden sollen, um Ressourcen (Bilder, Schriftarten, CSS) in MHTML‑Dokumenten zu referenzieren. Standardwert ist
false
.

<br />

*** ** * ** ***


Standardmäßig werden Ressourcen in MHTML‑Dokumenten über den Dateinamen referenziert (z. b. "image.png"), der mit den "Content-Location"‑Headern von MIME‑Teilen abgeglichen wird. Diese Option ermöglicht eine alternative Methode, bei der Verweise auf Ressourcendateien als CID‑ (Content‑ID‑) URLs geschrieben werden (z. b. "cid:image.png") und mit den "Content-ID"‑Headern abgeglichen werden.


Theoretisch sollte es keinen Unterschied zwischen den beiden Referenzierungsmethoden geben und beide sollten in jedem Browser oder E‑Mail‑Programm einwandfrei funktionieren. In der Praxis jedoch scheitern einige Programme beim Abrufen von Ressourcen über den Dateinamen. Wenn Ihr Browser oder E‑Mail‑Programm das Laden von in einem MHTML‑Dokument enthaltenen Ressourcen verweigert (zeigt keine Bilder an oder lädt keine CSS‑Stile), versuchen Sie, das Dokument mit CID‑URLs zu exportieren.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Gibt an, ob integrierte und benutzerdefinierte Dokumenteigenschaften nach MHTML exportiert werden sollen. Standardwert ist
false
.


**Returns:**
boolesch
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Gibt an, ob integrierte und benutzerdefinierte Dokumenteigenschaften nach MHTML exportiert werden sollen. Standardwert ist
false
.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


Gibt an, ob Sprachinformationen nach MHTML exportiert werden sollen. Standardwert ist
false
.

<br />

*** ** * ** ***

Wenn diese Eigenschaft auf true gesetzt ist, gibt der GroupDocs.Editor das HTML‑Attribut lang an den Dokumentelementen aus, die die Sprache angeben. Dies kann erforderlich sein, um sprachbezogene Semantik zu erhalten.

<br />



**Returns:**
boolesch
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Gibt an, ob Sprachinformationen nach MHTML exportiert werden sollen. Standardwert ist
false
.

<br />

*** ** * ** ***

Wenn diese Eigenschaft auf true gesetzt ist, gibt der GroupDocs.Editor das HTML‑Attribut lang an den Dokumentelementen aus, die die Sprache angeben. Dies kann erforderlich sein, um sprachbezogene Semantik zu erhalten.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

