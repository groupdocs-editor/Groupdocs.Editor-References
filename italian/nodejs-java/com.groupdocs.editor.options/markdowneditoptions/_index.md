---
title: "MarkdownEditOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare opzioni personalizzate per la modifica di documenti in formato Markdown."
type: docs
weight: 21
url: /it/nodejs-java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Consente di specificare opzioni personalizzate per la modifica di documenti in formato Markdown.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | Crea e restituisce una nuova istanza della classe MarkdownEditOptions, |
dove tutte le opzioni sono impostate ai valori predefiniti
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Consente di controllare come vengono salvate le immagini durante la conversione del documento Markdown |
in Html.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Consente di controllare come vengono salvate le immagini durante la conversione del documento Markdown |
in Html.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


Crea e restituisce una nuova istanza della classe MarkdownEditOptions,
dove tutte le opzioni sono impostate ai valori predefiniti


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Consente di controllare come vengono salvate le immagini durante la conversione del documento Markdown
in Html.
Valore: il callback di salvataggio dell'immagine.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Consente di controllare come vengono salvate le immagini durante la conversione del documento Markdown
in Html.
Valore: il callback di salvataggio dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

