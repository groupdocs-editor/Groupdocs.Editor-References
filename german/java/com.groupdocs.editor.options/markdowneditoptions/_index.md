---
title: "MarkdownEditOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten im Markdown‑Format."
type: docs
weight: 21
url: /de/java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten im Markdown‑Format.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | Erstellt und gibt eine neue Instanz der Klasse MarkdownEditOptions zurück, |
wobei alle Optionen auf ihre Standardwerte gesetzt sind
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Ermöglicht die Steuerung, wie Bilder beim Konvertieren eines Markdown-Dokuments gespeichert werden |
nach Html.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Ermöglicht die Steuerung, wie Bilder beim Konvertieren eines Markdown-Dokuments gespeichert werden |
nach Html.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


Erstellt und gibt eine neue Instanz der Klasse MarkdownEditOptions zurück,
wobei alle Optionen auf ihre Standardwerte gesetzt sind


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Ermöglicht die Steuerung, wie Bilder beim Konvertieren eines Markdown-Dokuments gespeichert werden
nach Html.
Wert: Der Bildspeicher-Callback.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Ermöglicht die Steuerung, wie Bilder beim Konvertieren eines Markdown-Dokuments gespeichert werden
nach Html.
Wert: Der Bildspeicher-Callback.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

