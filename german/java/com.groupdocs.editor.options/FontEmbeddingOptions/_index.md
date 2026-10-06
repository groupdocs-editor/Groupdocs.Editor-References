---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Font‑Embedding‑Optionen steuern, welche Schriftressourcen in das Ausgabedokument für die Textverarbeitung eingebettet werden sollen"
type: docs
weight: 17
url: /de/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Font‑Embedding‑Optionen steuern, welche Schriftressourcen eingebettet werden sollen
das Ausgabedokument für die Textverarbeitung


*** ** * ** ***

Font‑Embedding‑Optionen werden beim Speichern des Dokuments angewendet (vom Zwischendokument EditableDocument in das Ausgabedokument im WordProcessing‑Format), diese Aufzählung ist als Eigenschaft in den WordProcessingSaveOptions enthalten und sollte dort verwendet werden

<br />


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | Betten Sie keine Schriftressource ein, weder aus EditableDocument noch aus dem |
System.
|
|  | [EmbedAll](#EmbedAll) | Analysieren Sie den Dokumentinhalt des Eingabe‑EditableDocument und finden Sie alle verwendeten Schriften |
und betten Sie sie in das Ausgabedokument für die Textverarbeitung ein.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Entspricht [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), schließt jedoch diese Schriften aus, |
die vom Betriebssystem als Systemschriften behandelt werden
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


Betten Sie keine Schriftressource ein, weder aus EditableDocument noch aus dem
System. Standardwert.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Analysieren Sie den Dokumentinhalt des Eingabe‑EditableDocument und finden Sie alle verwendeten Schriften
und betten Sie sie in das Ausgabedokument für die Textverarbeitung ein. Zunächst
GroupDocs.Editor übernimmt Schriften aus den Schriftressourcen innerhalb von EditableDocument.
Wenn sie unzureichend oder nicht vorhanden sind, übernimmt GroupDocs.Editor die Schriften
vom Betriebssystem.


*** ** * ** ***

Zunächst analysiert GroupDocs.Editor den Inhalt von EditableDocument und erstellt eine Liste aller verwendeten Schriftarten. Dann werden diese Schriftarten in den Schriftartressourcen von EditableDocument gesucht. Wenn EditableDocument einige Schriftartressourcen enthält, die nicht im Dokumentinhalt verwendet werden, werden solche Ressourcen ignoriert. Wenn es Schriftarten im Dokumentinhalt gibt, für die keine entsprechenden Schriftartressourcen in EditableDocument vorhanden sind, versucht GroupDocs.Editor, sie im Betriebssystem zu finden. Diese Option entspricht der Option "Schriftarten in die Datei einbetten" mit allen Unteroptionen deaktiviert in Microsoft Word 2007 und höher.

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Entspricht [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), schließt jedoch diese Schriften aus,
die vom Betriebssystem als Systemschriften behandelt werden


*** ** * ** ***

MS Windows hat ein Konzept von Systemschriftarten, die die grundlegendsten und von Windows selbst verwendeten Schriftarten sind. Bei Verwendung dieser Option verhält sich GroupDocs.Editor wie im Fall von [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), prüft jedoch abschließend die Menge der erhaltenen Schriftarten und schließt diejenigen aus, die vom Betriebssystem als Systemschriftarten behandelt werden. Diese Option entspricht den Optionen "Schriftarten in die Datei einbetten" + "Gemeinsame Systemschriftarten nicht einbetten" in Microsoft Word 2007 und höher.

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
