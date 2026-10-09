---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Font‑Einbettungsoptionen bestimmen, welche Schriftressourcen in das Ausgabedokument für die Textverarbeitung eingebettet werden sollen."
type: docs
weight: 17
url: /de/nodejs-java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Font‑Einbettungsoptionen bestimmen, welche Schriftressourcen eingebettet werden sollen in
das Ausgabedokument für die Textverarbeitung


*** ** * ** ***

Schriftart-Einbettungsoptionen werden beim Speichern des Dokuments angewendet (vom Zwischendokument EditableDocument in das Ausgabe‑WordProcessing‑Format), diese Aufzählung ist als Eigenschaft in den WordProcessingSaveOptions enthalten, von wo aus sie verwendet werden sollte.

<br />


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | Betten Sie keine Schriftartressource ein, weder aus dem EditableDocument noch aus dem |
System.
|
|  | [EmbedAll](#EmbedAll) | Analysieren Sie den Dokumentinhalt des Eingabe‑EditableDocument und finden Sie alle verwendeten Schriftarten. |
und betten Sie sie in das Ausgabe‑WordProcessing‑Dokument ein.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Entspricht [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), schließt jedoch diese Schriftarten aus, |
die vom Betriebssystem als Systemschriftarten behandelt werden
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


Betten Sie keine Schriftartressource ein, weder aus dem EditableDocument noch aus dem
System. Standardwert.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Analysieren Sie den Dokumentinhalt des Eingabe‑EditableDocument und finden Sie alle verwendeten Schriftarten.
und betten Sie sie in das Ausgabe‑WordProcessing‑Dokument ein. Zunächst
GroupDocs.Editor übernimmt Schriftarten aus den Schriftressourcen innerhalb des EditableDocument.
Sind sie unzureichend oder fehlen sie, übernimmt GroupDocs.Editor Schriftarten
vom Betriebssystem.


*** ** * ** ***

Zunächst analysiert GroupDocs.Editor den Inhalt des EditableDocument und erstellt eine Liste aller verwendeten Schriftarten. Anschließend werden diese Schriftarten in den Schriftressourcen des EditableDocument gesucht. Enthält das EditableDocument Schriftressourcen, die nicht im Dokumentinhalt verwendet werden, werden diese Ressourcen ignoriert. Gibt es Schriftarten, die im Dokumentinhalt verwendet werden, aber keine entsprechenden Schriftressourcen im EditableDocument besitzen, versucht GroupDocs.Editor sie im Betriebssystem zu finden. Diese Option ähnelt der Option "Embed fonts in the file", bei der alle Unteroptionen in Microsoft Word 2007 und höher deaktiviert sind.

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Entspricht [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), schließt jedoch diese Schriftarten aus,
die vom Betriebssystem als Systemschriftarten behandelt werden


*** ** * ** ***

MS Windows verfügt über ein Konzept von Systemschriftarten, die die grundlegendsten und von Windows selbst am häufigsten verwendeten Schriftarten sind. Bei Verwendung dieser Option verhält sich GroupDocs.Editor wie im Fall von [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), prüft jedoch abschließend die erhaltenen Schriftarten und schließt diejenigen aus, die vom Betriebssystem als Systemschriftarten behandelt werden. Diese Option ähnelt den Optionen "Embed fonts in the file" + "Do not embed common system fonts" in Microsoft Word 2007 und höher.

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
