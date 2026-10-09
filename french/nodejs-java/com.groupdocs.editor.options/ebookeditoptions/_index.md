---
title: "EbookEditOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier et d'ajuster des options personnalisées pour l'édition de documents de type e-book dans tous les formats pris en charge ePub, MOBI et AZW3."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Permet de spécifier et d'ajuster des options personnalisées pour l'édition de documents de livre numérique dans tous les formats pris en charge : ePub, MOBI et AZW3.

<br />

*** ** * ** ***

Formats de livre électronique pris en charge :

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Publication électronique)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Format Kindle 8t)

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | Initialise une nouvelle instance de la classe [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), où toutes les options sont définies à leurs valeurs par défaut |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Initialise une nouvelle instance de la classe [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) avec le mode de pagination spécifié |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Permet d'activer ou de désactiver la pagination dans le document HTML résultant. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Permet d'activer ou de désactiver la pagination dans le document HTML résultant. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Spécifie si les informations de langue sont exportées dans le balisage HTML sous forme d'attributs HTML 'lang'. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Spécifie si les informations de langue sont exportées dans le balisage HTML sous forme d'attributs HTML 'lang'. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


Initialise une nouvelle instance de la classe [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), où toutes les options sont définies à leurs valeurs par défaut


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


Initialise une nouvelle instance de la classe [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) avec le mode de pagination spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | enablePagination | booléen | Active ( true ) ou désactive ( false ) la pagination du contenu du e-book dans le document HTML résultant. Par défaut, elle est désactivée ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Permet d'activer ou de désactiver la pagination dans le document HTML résultant. Par défaut, elle est désactivée (
false
).

<br />

*** ** * ** ***

En essence, la plupart des formats de livre numérique sont des formats à flux comme Office Open XML, où le contenu est continu et est découpé en chapitres mais pas en pages. Cependant, ils contiennent certaines informations spécifiques aux pages telles que les numéros de page, les notes de bas de page, les en-têtes/pieds de page, etc. Certains lecteurs de livres numériques découpent le contenu en pages, tandis que d'autres (en particulier sur mobile) \\u2014 ne le font pas. Cette option permet de contrôler la façon dont le contenu du livre numérique doit être représenté en HTML/CSS lors de l'édition \\u2014 en mode flottant ( false ) ou paginé ( true ).

<br />



**Returns:**
booléen
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Permet d'activer ou de désactiver la pagination dans le document HTML résultant. Par défaut, elle est désactivée (
false
).

<br />

*** ** * ** ***

En essence, la plupart des formats de livre numérique sont des formats à flux comme Office Open XML, où le contenu est continu et est découpé en chapitres mais pas en pages. Cependant, ils contiennent certaines informations spécifiques aux pages telles que les numéros de page, les notes de bas de page, les en-têtes/pieds de page, etc. Certains lecteurs de livres numériques découpent le contenu en pages, tandis que d'autres (en particulier sur mobile) \\u2014 ne le font pas. Cette option permet de contrôler la façon dont le contenu du livre numérique doit être représenté en HTML/CSS lors de l'édition \\u2014 en mode flottant ( false ) ou paginé ( true ).

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Spécifie si les informations de langue sont exportées dans le balisage HTML sous forme d'attributs HTML 'lang'.
Cette option peut être utile pour la conversion aller-retour des documents multilingues. Par défaut, elle est désactivée (
false
).


**Returns:**
booléen
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Spécifie si les informations de langue sont exportées dans le balisage HTML sous forme d'attributs HTML 'lang'.
Cette option peut être utile pour la conversion aller-retour des documents multilingues. Par défaut, elle est désactivée (
false
).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

