---
title: "MarkdownImageLoadingAction"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Definisce la modalità di caricamento delle immagini durante l'apertura per la modifica del file in formato Markdown"
type: docs
weight: 23
url: /it/nodejs-java/com.groupdocs.editor.options/markdownimageloadingaction/
---
**Inheritance:**
java.lang.Object
```
public final class MarkdownImageLoadingAction
```

Definisce la modalità di caricamento delle immagini durante l'apertura per la modifica del file in formato Markdown

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Default](#Default) | GroupDocs.Editor caricherà questa risorsa come al solito |
|
|  | [Skip](#Skip) | GroupDocs.Editor salterà il caricamento di questa immagine |
|
|  | [UserProvided](#UserProvided) | GroupDocs.Editor utilizzerà l'array di byte fornito dall'utente in |
M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])
come dati immagine
|
### Default {#Default}
```
public static final int Default
```


GroupDocs.Editor caricherà questa risorsa come al solito


### Skip {#Skip}
```
public static final int Skip
```


GroupDocs.Editor salterà il caricamento di questa immagine


### UserProvided {#UserProvided}
```
public static final int UserProvided
```


GroupDocs.Editor utilizzerà l'array di byte fornito dall'utente in
M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])
come dati immagine


