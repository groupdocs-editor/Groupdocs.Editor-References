---
title: "FixedLayoutEditOptionsBase"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Classe abstraite de base pour les options de tous les documents aux formats à mise en page fixe comme PDF et XPS"
type: docs
weight: 16
url: /fr/java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

Classe abstraite de base pour les options de tous les documents aux formats à mise en page fixe comme PDF et XPS

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | Obtient ou définit le drapeau indiquant si les images doivent être ignorées lors de la conversion du document à mise en page fixe d'entrée vers le HTML résultant. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | Obtient ou définit le drapeau indiquant si les images doivent être ignorées lors de la conversion du document à mise en page fixe d'entrée vers le HTML résultant. |
|
|  | [getPages()](#getPages--) | Permet de définir une plage de pages à traiter. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | Permet de définir une plage de pages à traiter. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Permet d'activer (true) ou de désactiver (false) la pagination dans le document HTML résultant. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Permet d'activer (true) ou de désactiver (false) la pagination dans le document HTML résultant. |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


Obtient ou définit le drapeau indiquant si les images doivent être ignorées lors de la conversion du document à mise en page fixe d'entrée vers le HTML résultant. La valeur par défaut est false — les images sont conservées.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


Obtient ou définit le drapeau indiquant si les images doivent être ignorées lors de la conversion du document à mise en page fixe d'entrée vers le HTML résultant. La valeur par défaut est false — les images sont conservées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


Permet de définir une plage de pages à traiter. Par défaut, toutes les pages d'un document à mise en page fixe sont traitées.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


Permet de définir une plage de pages à traiter. Par défaut, toutes les pages d'un document à mise en page fixe sont traitées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Permet d'activer (true) ou de désactiver (false) la pagination dans le document HTML résultant. Par défaut, elle est désactivée (false).

<br />

*** ** * ** ***

Les documents au format à mise en page fixe (PDF et XPS en particulier) sont, par essence, strictement paginés, leur contenu possède une mise en page fixe et est divisé en pages. Cependant, le HTML éditable résultant peut être présenté soit en vue sans pagination, soit en vue paginée.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Permet d'activer (true) ou de désactiver (false) la pagination dans le document HTML résultant. Par défaut, elle est désactivée (false).

<br />

*** ** * ** ***

Les documents au format à mise en page fixe (PDF et XPS en particulier) sont, par essence, strictement paginés, leur contenu possède une mise en page fixe et est divisé en pages. Cependant, le HTML éditable résultant peut être présenté soit en vue sans pagination, soit en vue paginée.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

