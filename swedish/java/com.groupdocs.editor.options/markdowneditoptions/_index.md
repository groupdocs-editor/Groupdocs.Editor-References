---
title: "MarkdownEditOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för att redigera dokument i Markdown-format."
type: docs
weight: 21
url: /sv/java/com.groupdocs.editor.options/markdowneditoptions/
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
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Tillåter att styra hur bilder sparas vid konvertering av Markdown-dokument |
till HTML.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Tillåter att styra hur bilder sparas vid konvertering av Markdown-dokument |
till HTML.
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


Tillåter att styra hur bilder sparas vid konvertering av Markdown-dokument
till HTML.
Värde: Bildsparningsåteranropet.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Tillåter att styra hur bilder sparas vid konvertering av Markdown-dokument
till HTML.
Värde: Bildsparningsåteranropet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

