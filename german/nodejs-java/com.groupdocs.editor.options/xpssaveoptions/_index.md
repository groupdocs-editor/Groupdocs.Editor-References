---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen für die Erstellung und das Speichern von XPS XML Paper Specification-Dokumenten"
type: docs
weight: 54
url: /de/nodejs-java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von XPS (XML Paper Specifications) Dokumenten

<br />

*** ** * ** ***

Eine XPS-Datei stellt Seitenlayout‑Dateien dar, die auf von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF‑Dateiformat ähnlich, verwendet jedoch XML für Layout-, Erscheinungs‑ und Druckinformationen eines Dokuments.

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | Verantwortlich für das Einbetten von Schriftartressourcen in das resultierende XPS-Dokument, die im Originaldokument verwendet werden. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, was die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigt. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, was die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigt. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Verantwortlich für das Einbetten von Schriftartressourcen in das resultierende XPS-Dokument, die im Originaldokument verwendet werden.
Standardmäßig werden keine Schriftarten eingebettet (NotEmbed).


**Returns:**
Byte
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

