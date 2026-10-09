---
title: "MarkdownEditOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Tillåter att ange anpassade alternativ för att redigera dokument i Markdown-format."
type: docs
weight: 21
url: /sv/nodejs-java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Tillåter att ange anpassade alternativ för att redigera dokument i Markdown-format.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | Skapar och returnerar en ny instans av klassen MarkdownEditOptions, |
där alla alternativ är inställda på sina standardvärden
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Tillåter att kontrollera hur bilder sparas när Markdown-dokument konverteras |
till Html.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Tillåter att kontrollera hur bilder sparas när Markdown-dokument konverteras |
till Html.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


Skapar och returnerar en ny instans av klassen MarkdownEditOptions,
där alla alternativ är inställda på sina standardvärden


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Tillåter att kontrollera hur bilder sparas när Markdown-dokument konverteras
till Html.
Värde: Bildsparningscallback.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Tillåter att kontrollera hur bilder sparas när Markdown-dokument konverteras
till Html.
Värde: Bildsparningscallback.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

