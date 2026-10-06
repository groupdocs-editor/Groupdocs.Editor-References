---
title: "MarkdownSaveOptions"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Permet de spécifier des options personnalisées pour générer et enregistrer des documents Markdown"
type: docs
weight: 24
url: /fr/java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Permet de spécifier des options personnalisées pour générer et enregistrer des documents Markdown

<br />

*** ** * ** ***

La classe MarkdownSaveOptions doit être appliquée par l'utilisateur lorsqu'il existe une instance de la classe EditableDocument, qui contient le contenu d'un document modifié, et qu'il est nécessaire d'enregistrer ce contenu dans un nouveau document au format Markdown.

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Active les mécanismes d’optimisation de la mémoire lors de la génération du document à partir de HTML, ce qui dégrade les performances en contrepartie d’une réduction de l’utilisation de la mémoire. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Active les mécanismes d’optimisation de la mémoire lors de la génération du document à partir de HTML, ce qui dégrade les performances en contrepartie d’une réduction de l’utilisation de la mémoire. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow spécifie comment aligner le contenu dans les tableaux lors de l'exportation au format Markdown. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow spécifie comment aligner le contenu dans les tableaux lors de l'exportation au format Markdown. |
|
|  | [getImagesFolder()](#getImagesFolder--) | Spécifie le dossier physique où les images sont enregistrées lors de l'exportation d'un document vers |
le format Markdown.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | Spécifie le dossier physique où les images sont enregistrées lors de l'exportation d'un document vers |
le format Markdown.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | Spécifie si les images sont enregistrées au format Base64 dans le fichier de sortie. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | Spécifie si les images sont enregistrées au format Base64 dans le fichier de sortie. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Active les mécanismes d’optimisation de la mémoire lors de la génération du document à partir de HTML, ce qui dégrade les performances en contrepartie d’une réduction de l’utilisation de la mémoire.
Définir cette option à
true
peut réduire considérablement la consommation de mémoire lors de la génération de gros documents au prix d'un temps d'enregistrement plus lent.
Par défaut, c'est
false
(l'optimisation de la mémoire est désactivée afin d'améliorer les performances).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Active les mécanismes d’optimisation de la mémoire lors de la génération du document à partir de HTML, ce qui dégrade les performances en contrepartie d’une réduction de l’utilisation de la mémoire.
Définir cette option à
true
peut réduire considérablement la consommation de mémoire lors de la génération de gros documents au prix d'un temps d'enregistrement plus lent.
Par défaut, c'est
false
(l'optimisation de la mémoire est désactivée afin d'améliorer les performances).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow spécifie comment aligner le contenu dans les tableaux lors de l'exportation au format Markdown.
La valeur par défaut est [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Valeur : l'alignement du contenu du tableau


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow spécifie comment aligner le contenu dans les tableaux lors de l'exportation au format Markdown.
La valeur par défaut est [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Valeur : l'alignement du contenu du tableau


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Spécifie le dossier physique où les images sont enregistrées lors de l'exportation d'un document vers
le format Markdown. Par défaut, null.

<br />

*** ** * ** ***

Si ni le ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) ni ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) ne sont spécifiés par l'utilisateur, alors GroupDocs.Editor tentera de déterminer le ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) lui‑même et l'appliquera en cas de succès

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Spécifie le dossier physique où les images sont enregistrées lors de l'exportation d'un document vers
le format Markdown. Par défaut, null.

<br />

*** ** * ** ***

Si ni le ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) ni ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) ne sont spécifiés par l'utilisateur, alors GroupDocs.Editor tentera de déterminer le ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) lui‑même et l'appliquera en cas de succès

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


Spécifie si les images sont enregistrées au format Base64 dans le fichier de sortie. La valeur par défaut est
false
.

<br />

*** ** * ** ***

Lorsque cette propriété est définie sur  true , les données d'images sont exportées directement dans les éléments image ![](../) et aucun fichier séparé n'est créé. Cette propriété, si elle est définie sur  true , a la priorité supérieure à la propriété MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


Spécifie si les images sont enregistrées au format Base64 dans le fichier de sortie. La valeur par défaut est
false
.

<br />

*** ** * ** ***

Lorsque cette propriété est définie sur  true , les données d'images sont exportées directement dans les éléments image ![](../) et aucun fichier séparé n'est créé. Cette propriété, si elle est définie sur  true , a la priorité supérieure à la propriété MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

