---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von PDF Portable Document Format-Dokumenten"
type: docs
weight: 31
url: /de/nodejs-java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von PDF (Portable
Document Format) Dokumente

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPassword()](#getPassword--) | Passwort, das auf das erzeugte PDF-Dokument als Benutzerpasswort angewendet wird und zum Öffnen erforderlich ist. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Passwort, das auf das erzeugte PDF-Dokument als Benutzerpasswort angewendet wird und zum Öffnen erforderlich ist. |
|
|  | [getCompliance()](#getCompliance--) | Gibt das Konformitätsniveau der PDF-Standards für Ausgabedokumente an. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | Gibt das Konformitätsniveau der PDF-Standards für Ausgabedokumente an. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Verantwortlich für das Einbetten von Schriftressourcen in das resultierende PDF-Dokument, die im Originaldokument verwendet werden. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Verantwortlich für das Einbetten von Schriftressourcen in das resultierende PDF-Dokument, die im Originaldokument verwendet werden. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, was die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigt. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, was die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigt. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Passwort, das auf das erzeugte PDF-Dokument als Benutzerpasswort angewendet wird und zum Öffnen erforderlich ist.
Wenn NULL oder leer, wird kein Passwort auf das Dokument angewendet. Andernfalls wird das Dokument mit RC4 (Schlüssellänge von 128 Bit) verschlüsselt.
Standardmäßig ist NULL \u2014 Passwort wird nicht angewendet.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Passwort, das auf das erzeugte PDF-Dokument als Benutzerpasswort angewendet wird und zum Öffnen erforderlich ist.
Wenn NULL oder leer, wird kein Passwort auf das Dokument angewendet. Andernfalls wird das Dokument mit RC4 (Schlüssellänge von 128 Bit) verschlüsselt.
Standardmäßig ist NULL \u2014 Passwort wird nicht angewendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Gibt das Konformitätsniveau der PDF-Standards für Ausgabedokumente an. Standard ist PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Gibt das Konformitätsniveau der PDF-Standards für Ausgabedokumente an. Standard ist PdfCompliance.Pdf17.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Verantwortlich für das Einbetten von Schriftressourcen in das resultierende PDF-Dokument, die im Originaldokument verwendet werden. Standardmäßig werden keine Schriften eingebettet (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Verantwortlich für das Einbetten von Schriftressourcen in das resultierende PDF-Dokument, die im Originaldokument verwendet werden. Standardmäßig werden keine Schriften eingebettet (NotEmbed).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, was die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigt.
Das Setzen dieser Option auf true kann den Speicherverbrauch beim Erzeugen großer Dokumente erheblich senken, jedoch zulasten einer langsameren Speicherzeit.
Standard ist false (Speicheroptimierung ist zum Zweck einer besseren Leistung deaktiviert).


**Returns:**
boolesch
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, was die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigt.
Das Setzen dieser Option auf true kann den Speicherverbrauch beim Erzeugen großer Dokumente erheblich senken, jedoch zulasten einer langsameren Speicherzeit.
Standard ist false (Speicheroptimierung ist zum Zweck einer besseren Leistung deaktiviert).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

