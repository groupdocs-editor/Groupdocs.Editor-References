---
title: "MarkdownEditOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour l'édition de documents au format Markdown."
type: docs
weight: 21
url: /fr/nodejs-java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Permet de spécifier des options personnalisées pour l'édition de documents au format Markdown.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | Crée et renvoie une nouvelle instance de la classe MarkdownEditOptions, |
où toutes les options sont définies à leurs valeurs par défaut
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Permet de contrôler comment les images sont enregistrées lors de la conversion d'un document Markdown |
en HTML.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Permet de contrôler comment les images sont enregistrées lors de la conversion d'un document Markdown |
en HTML.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


Crée et renvoie une nouvelle instance de la classe MarkdownEditOptions,
où toutes les options sont définies à leurs valeurs par défaut


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Permet de contrôler comment les images sont enregistrées lors de la conversion d'un document Markdown
en HTML.
Valeur : le rappel d'enregistrement d'image.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Permet de contrôler comment les images sont enregistrées lors de la conversion d'un document Markdown
en HTML.
Valeur : le rappel d'enregistrement d'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

