---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von XPS XML Paper Specifications-Dokumenten"
type: docs
weight: 54
url: /de/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von XPS (XML Paper Specifications) Dokumenten.

<br />

*** ** * ** ***

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout-, Erscheinungs- und Druckinformationen eines Dokuments.

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | Verantwortlich für das Einbetten von Schriftressourcen in das resultierende XPS-Dokument, die im Originaldokument verwendet werden. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, die die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigen. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, die die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigen. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Verantwortlich für das Einbetten von Schriftressourcen in das resultierende XPS-Dokument, die im Originaldokument verwendet werden.
Standardmäßig bettet es keine Schriftarten ein (NotEmbed).


**Returns:**
Byte
### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, die die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigen.
Wenn diese Option auf true gesetzt wird, kann der Speicherverbrauch beim Erzeugen großer Dokumente erheblich reduziert werden, allerdings auf Kosten einer langsameren Speicherzeit.
Standardwert ist false (Speicheroptimierung ist deaktiviert, um eine bessere Leistung zu erzielen).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, die die Leistung zum Preis einer verringerten Speichernutzung beeinträchtigen.
Wenn diese Option auf true gesetzt wird, kann der Speicherverbrauch beim Erzeugen großer Dokumente erheblich reduziert werden, allerdings auf Kosten einer langsameren Speicherzeit.
Standardwert ist false (Speicheroptimierung ist deaktiviert, um eine bessere Leistung zu erzielen).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

