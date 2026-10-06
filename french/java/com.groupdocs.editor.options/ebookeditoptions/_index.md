---
title: "EbookEditOptions"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Permet de spécifier et d'ajuster des options personnalisées pour l'édition de documents de livre électronique dans tous les formats pris en charge ePub, MOBI et AZW3."
type: docs
weight: 12
url: /fr/java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Permet de spécifier et d'ajuster des options personnalisées pour l'édition de documents E-book dans tous les formats pris en charge : ePub, MOBI et AZW3.

<br />

*** ** * ** ***

Formats de livre numérique pris en charge :

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
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Spécifie si les informations de langue sont exportées vers le balisage HTML sous forme d'attributs HTML 'lang'. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Spécifie si les informations de langue sont exportées vers le balisage HTML sous forme d'attributs HTML 'lang'. |
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
|  | enablePagination | boolean | Active ( true ) ou désactive ( false ) la pagination du contenu du livre électronique dans le document HTML résultant. Par défaut, elle est désactivée ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Permet d'activer ou de désactiver la pagination dans le document HTML résultant. Par défaut, elle est désactivée (
false
 ou sous forme de styles en ligne dans le balisage HTML (", ").

<br />

*** ** * ** ***

En essence, la plupart des formats de livre électronique sont internement un format flux comme Office Open XML, où le contenu est solide et est découpé en chapitres mais pas en pages. Cependant, il contient certaines informations spécifiques aux pages comme les numéros de page, les notes de bas de page, les en-têtes/pieds de page, etc. Certains lecteurs de livres électroniques effectuent une division du contenu en pages, tandis que d'autres (en particulier sur mobile) \\u2014 pas. Cette option permet de contrôler comment le contenu du livre électronique doit être représenté en HTML/CSS lors de l'édition \\u2014 en vue flottante ( false ) ou paginée ( true ).

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Permet d'activer ou de désactiver la pagination dans le document HTML résultant. Par défaut, elle est désactivée (
false
 ou sous forme de styles en ligne dans le balisage HTML (", ").

<br />

*** ** * ** ***

En essence, la plupart des formats de livre électronique sont internement un format flux comme Office Open XML, où le contenu est solide et est découpé en chapitres mais pas en pages. Cependant, il contient certaines informations spécifiques aux pages comme les numéros de page, les notes de bas de page, les en-têtes/pieds de page, etc. Certains lecteurs de livres électroniques effectuent une division du contenu en pages, tandis que d'autres (en particulier sur mobile) \\u2014 pas. Cette option permet de contrôler comment le contenu du livre électronique doit être représenté en HTML/CSS lors de l'édition \\u2014 en vue flottante ( false ) ou paginée ( true ).

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Spécifie si les informations de langue sont exportées vers le balisage HTML sous forme d'attributs HTML 'lang'.
Cette option peut être utile pour la conversion aller-retour des documents multilingues. Par défaut, elle est désactivée (
false
 ou sous forme de styles en ligne dans le balisage HTML (", ").


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Spécifie si les informations de langue sont exportées vers le balisage HTML sous forme d'attributs HTML 'lang'.
Cette option peut être utile pour la conversion aller-retour des documents multilingues. Par défaut, elle est désactivée (
false
 ou sous forme de styles en ligne dans le balisage HTML (", ").


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

