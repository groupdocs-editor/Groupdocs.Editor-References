---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von Markdown-Dokumenten"
type: docs
weight: 24
url: /de/nodejs-java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von Markdown-Dokumenten

<br />

*** ** * ** ***

Die Klasse MarkdownSaveOptions muss vom Benutzer verwendet werden, wenn eine Instanz der Klasse EditableDocument vorhanden ist, die bearbeitete Dokumentinhalte enthält, und es erforderlich ist, diese Inhalte in ein neues Dokument im Markdown-Format zu speichern.

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, was die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigt. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, was die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigt. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow gibt an, wie Inhalte in Tabellen ausgerichtet werden sollen, wenn sie in das Markdown-Format exportiert werden. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow gibt an, wie Inhalte in Tabellen ausgerichtet werden sollen, wenn sie in das Markdown-Format exportiert werden. |
|
|  | [getImagesFolder()](#getImagesFolder--) | Gibt den physischen Ordner an, in dem Bilder beim Export eines Dokuments nach |
dem Markdown-Format gespeichert werden.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | Gibt den physischen Ordner an, in dem Bilder beim Export eines Dokuments nach |
dem Markdown-Format gespeichert werden.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | Gibt an, ob Bilder im Base64-Format in die Ausgabedatei gespeichert werden. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | Gibt an, ob Bilder im Base64-Format in die Ausgabedatei gespeichert werden. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, was die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigt.
Setzt man diese Option auf
true
kann den Speicherverbrauch beim Erzeugen großer Dokumente erheblich reduzieren, jedoch zulasten einer langsameren Speicherzeit.
Standard ist
false
(Speicheroptimierung ist deaktiviert, um eine bessere Leistung zu erzielen).


**Returns:**
boolesch
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, was die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigt.
Setzt man diese Option auf
true
kann den Speicherverbrauch beim Erzeugen großer Dokumente erheblich reduzieren, jedoch zulasten einer langsameren Speicherzeit.
Standard ist
false
(Speicheroptimierung ist deaktiviert, um eine bessere Leistung zu erzielen).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow gibt an, wie Inhalte in Tabellen ausgerichtet werden sollen, wenn sie in das Markdown-Format exportiert werden.
Der Standardwert ist [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Wert: Die Tabelleninhaltsausrichtung


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow gibt an, wie Inhalte in Tabellen ausgerichtet werden sollen, wenn sie in das Markdown-Format exportiert werden.
Der Standardwert ist [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Wert: Die Tabelleninhaltsausrichtung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Gibt den physischen Ordner an, in dem Bilder beim Export eines Dokuments nach
das Markdown-Format. Standard ist null.

<br />

*** ** * ** ***

Wenn weder das ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) noch das ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) vom Benutzer angegeben werden, versucht der GroupDocs.Editor, das ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) selbst zu bestimmen und wendet es bei Erfolg an.

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Gibt den physischen Ordner an, in dem Bilder beim Export eines Dokuments nach
das Markdown-Format. Standard ist null.

<br />

*** ** * ** ***

Wenn weder das ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) noch das ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) vom Benutzer angegeben werden, versucht der GroupDocs.Editor, das ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) selbst zu bestimmen und wendet es bei Erfolg an.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


Gibt an, ob Bilder im Base64-Format in die Ausgabedatei gespeichert werden. Standard ist
false
.

<br />

*** ** * ** ***

Wenn diese Eigenschaft auf true gesetzt ist, werden Bilddaten direkt in die Bildelemente ![](../) exportiert und separate Dateien werden nicht erstellt. Diese Eigenschaft hat, wenn sie auf true gesetzt ist, eine höhere Priorität als die MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String))-Eigenschaft.

<br />



**Returns:**
boolesch
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


Gibt an, ob Bilder im Base64-Format in die Ausgabedatei gespeichert werden. Standard ist
false
.

<br />

*** ** * ** ***

Wenn diese Eigenschaft auf true gesetzt ist, werden Bilddaten direkt in die Bildelemente ![](../) exportiert und separate Dateien werden nicht erstellt. Diese Eigenschaft hat, wenn sie auf true gesetzt ist, eine höhere Priorität als die MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String))-Eigenschaft.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

