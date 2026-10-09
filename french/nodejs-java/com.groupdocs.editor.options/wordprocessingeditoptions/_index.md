---
title: "WordProcessingEditOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour l’édition de documents de tous les formats WordProcessing compatibles Words pris en charge, tels que DOCX, RTF, ODT, etc."
type: docs
weight: 44
url: /fr/nodejs-java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Permet de spécifier des options personnalisées pour l’édition de documents de tous les formats pris en charge
Formats WordProcessing (compatibles Words) comme DOC(X), RTF, ODT, etc.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | Crée et renvoie une nouvelle instance de WordProcessingEditOptions |
classe où toutes les options sont définies à leurs valeurs par défaut
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | Crée et renvoie une nouvelle instance de WordProcessingEditOptions |
classe avec pagination spécifiée et toutes les autres options par défaut
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Permet d'activer ou de désactiver la pagination dans le document HTML résultant. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Permet d'activer ou de désactiver la pagination dans le document HTML résultant. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Spécifie si les informations de langue sont exportées dans le balisage HTML en |
une forme d’attributs HTML 'lang'.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Spécifie si les informations de langue sont exportées dans le balisage HTML en |
une forme d’attributs HTML 'lang'.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Obtient ou définit une valeur indiquant s’il faut extraire uniquement les ressources de police qui |
sont utilisées dans le contenu textuel du document.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Obtient ou définit une valeur indiquant s’il faut extraire uniquement les ressources de police qui |
sont utilisées dans le contenu textuel du document.
|
|  | [getFontExtraction()](#getFontExtraction--) | Responsable de l’extraction des ressources de police, qui sont utilisées en entrée |
Document WordProcessing.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Responsable de l’extraction des ressources de police, qui sont utilisées en entrée |
Document WordProcessing.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | Permet de spécifier un nom de classe, qui sera placé dans l'attribut 'class' |
attributs dans chaque élément HTML, qui représente un champ dans l'entrée
Document WordProcessing.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Permet de spécifier un nom de classe, qui sera placé dans l'attribut 'class' |
attributs dans chaque élément HTML, qui représente un champ dans l'entrée
Document WordProcessing.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Contrôle où stocker les données de style et de mise en forme du document WordProcessing d'entrée : dans une feuille de style externe ( |
false
) ou comme styles en ligne dans le balisage HTML (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Contrôle où stocker les données de style et de mise en forme du document WordProcessing d'entrée : dans une feuille de style externe ( |
false
) ou comme styles en ligne dans le balisage HTML (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


Crée et renvoie une nouvelle instance de WordProcessingEditOptions
classe où toutes les options sont définies à leurs valeurs par défaut


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


Crée et renvoie une nouvelle instance de WordProcessingEditOptions
classe avec pagination spécifiée et toutes les autres options par défaut


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | enablePagination | booléen | Indicateur de pagination, qui active la sortie HTML, adaptée au mode paginé |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Permet d'activer ou de désactiver la pagination dans le document HTML résultant. Par
Par défaut, elle est désactivée (false).


**Returns:**
booléen
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Permet d'activer ou de désactiver la pagination dans le document HTML résultant. Par
Par défaut, elle est désactivée (false).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Spécifie si les informations de langue sont exportées dans le balisage HTML en
une forme d'attributs HTML 'lang'. Cette option peut être utile pour le round‑trip
conversion des documents multilingues. Par défaut, elle est désactivée
(false).


**Returns:**
booléen
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Spécifie si les informations de langue sont exportées dans le balisage HTML en
une forme d'attributs HTML 'lang'. Cette option peut être utile pour le round‑trip
conversion des documents multilingues. Par défaut, elle est désactivée
(false).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Obtient ou définit une valeur indiquant s’il faut extraire uniquement les ressources de police qui
sont utilisées dans le contenu textuel du document.
Valeur :  true  si vous devez extraire uniquement les ressources de police utilisées dans le contenu texte du document ; sinon,  false . La valeur par défaut est  false .


*** ** * ** ***

Tous les polices utilisées dans le document WordProcessing ne sont pas 100 % utilisées directement (appliquées à du texte). Il peut arriver qu’une police soit référencée dans le document et même incorporée, mais qu’elle ne soit appliquée à aucun texte. Par exemple, une police peut être attachée à un style, mais ce style n’est appliqué à aucune partie du texte. Cette option contrôle la façon de traiter de tels cas.

<br />



**Returns:**
booléen
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Obtient ou définit une valeur indiquant s’il faut extraire uniquement les ressources de police qui
sont utilisées dans le contenu textuel du document.
Valeur :  true  si vous devez extraire uniquement les ressources de police utilisées dans le contenu texte du document ; sinon,  false . La valeur par défaut est  false .


*** ** * ** ***

Tous les polices utilisées dans le document WordProcessing ne sont pas 100 % utilisées directement (appliquées à du texte). Il peut arriver qu’une police soit référencée dans le document et même incorporée, mais qu’elle ne soit appliquée à aucun texte. Par exemple, une police peut être attachée à un style, mais ce style n’est appliqué à aucune partie du texte. Cette option contrôle la façon de traiter de tels cas.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Responsable de l’extraction des ressources de police, qui sont utilisées en entrée
Document WordProcessing. Par défaut, aucune police n'est extraite
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Responsable de l’extraction des ressources de police, qui sont utilisées en entrée
Document WordProcessing. Par défaut, aucune police n'est extraite
(NotExtract).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Permet de spécifier un nom de classe, qui sera placé dans l'attribut 'class'
attributs dans chaque élément HTML, qui représente un champ dans l'entrée
Document WordProcessing. Par défaut, il est NULL - les attributs 'class' ne sont pas
appliqués.


*** ** * ** ***

Presque tous les formats de la famille de formats WordProcessing contiennent des champs \\u2014 des entités document spécifiques, qui permettent d’obtenir des données d’entrée auprès des utilisateurs. Il existe une grande variété de champs : zones de texte, cases à cocher, listes déroulantes, listes à choix multiples, boutons, sélecteurs de date/heure, etc. Tous sont traduits en structures et éléments HTML les plus appropriés, tout en préservant les données saisies par l’utilisateur, si elles sont présentes dans le document d’entrée. Dans certains cas d’utilisation, il suffit de récupérer les données saisies côté client au lieu de modifier tout le contenu du document. Pour ce cas, il faut identifier les contrôles d’entrée d’une manière ou d’une autre afin de les récupérer avec leurs données côté client. Cette propriété permet de spécifier un nom de classe qui sera appliqué à chaque contrôle d’entrée dans le balisage HTML, afin que le code client puisse parcourir la structure du document HTML et collecter les données.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Permet de spécifier un nom de classe, qui sera placé dans l'attribut 'class'
attributs dans chaque élément HTML, qui représente un champ dans l'entrée
Document WordProcessing. Par défaut, il est NULL - les attributs 'class' ne sont pas
appliqués.


*** ** * ** ***

Presque tous les formats de la famille de formats WordProcessing contiennent des champs \\u2014 des entités document spécifiques, qui permettent d’obtenir des données d’entrée auprès des utilisateurs. Il existe une grande variété de champs : zones de texte, cases à cocher, listes déroulantes, listes à choix multiples, boutons, sélecteurs de date/heure, etc. Tous sont traduits en structures et éléments HTML les plus appropriés, tout en préservant les données saisies par l’utilisateur, si elles sont présentes dans le document d’entrée. Dans certains cas d’utilisation, il suffit de récupérer les données saisies côté client au lieu de modifier tout le contenu du document. Pour ce cas, il faut identifier les contrôles d’entrée d’une manière ou d’une autre afin de les récupérer avec leurs données côté client. Cette propriété permet de spécifier un nom de classe qui sera appliqué à chaque contrôle d’entrée dans le balisage HTML, afin que le code client puisse parcourir la structure du document HTML et collecter les données.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


Contrôle où stocker les données de style et de mise en forme du document WordProcessing d'entrée : dans une feuille de style externe (
false
) ou comme styles en ligne dans le balisage HTML (
true
). Par défaut, les styles externes sont utilisés (
false
).


**Returns:**
booléen
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


Contrôle où stocker les données de style et de mise en forme du document WordProcessing d'entrée : dans une feuille de style externe (
false
) ou comme styles en ligne dans le balisage HTML (
true
). Par défaut, les styles externes sont utilisés (
false
).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

