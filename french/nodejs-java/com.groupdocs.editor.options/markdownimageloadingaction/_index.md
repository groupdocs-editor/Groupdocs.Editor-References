---
title: "MarkdownImageLoadingAction"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Définit le mode de chargement des images lors de l'ouverture du fichier pour l'édition au format Markdown"
type: docs
weight: 23
url: /fr/nodejs-java/com.groupdocs.editor.options/markdownimageloadingaction/
---
**Inheritance:**
java.lang.Object
```
public final class MarkdownImageLoadingAction
```

Définit le mode de chargement des images lors de l'ouverture du fichier pour l'édition au format Markdown

## Champs

| Champ | Description |
| --- | --- |
|  | [Default](#Default) | GroupDocs.Editor chargera cette ressource comme d'habitude |
|
|  | [Skip](#Skip) | GroupDocs.Editor ignorera le chargement de cette image |
|
|  | [UserProvided](#UserProvided) | GroupDocs.Editor utilisera le tableau d'octets fourni par l'utilisateur dans |
M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])
comme données d'image
|
### Default {#Default}
```
public static final int Default
```


GroupDocs.Editor chargera cette ressource comme d'habitude


### Skip {#Skip}
```
public static final int Skip
```


GroupDocs.Editor ignorera le chargement de cette image


### UserProvided {#UserProvided}
```
public static final int UserProvided
```


GroupDocs.Editor utilisera le tableau d'octets fourni par l'utilisateur dans
M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])
comme données d'image


