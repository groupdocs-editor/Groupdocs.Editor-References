---
title: "MarkdownImageLoadingAction"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Define el modo de carga de imágenes al abrir el archivo para editarlo en formato Markdown"
type: docs
weight: 23
url: /es/nodejs-java/com.groupdocs.editor.options/markdownimageloadingaction/
---
**Inheritance:**
java.lang.Object
```
public final class MarkdownImageLoadingAction
```

Define el modo de carga de imágenes al abrir el archivo para editarlo en formato Markdown

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Default](#Default) | GroupDocs.Editor cargará este recurso como de costumbre |
|
|  | [Skip](#Skip) | GroupDocs.Editor omitirá la carga de esta imagen |
|
|  | [UserProvided](#UserProvided) | GroupDocs.Editor usará la matriz de bytes proporcionada por el usuario en |
M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])
como datos de imagen
|
### Default {#Default}
```
public static final int Default
```


GroupDocs.Editor cargará este recurso como de costumbre


### Skip {#Skip}
```
public static final int Skip
```


GroupDocs.Editor omitirá la carga de esta imagen


### UserProvided {#UserProvided}
```
public static final int UserProvided
```


GroupDocs.Editor usará la matriz de bytes proporcionada por el usuario en
M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])
como datos de imagen


