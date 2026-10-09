---
title: "TextEditOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour le chargement de documents texte brut TXT"
type: docs
weight: 39
url: /fr/nodejs-java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Permet de spécifier des options personnalisées pour le chargement de documents texte brut (TXT).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Encodage des caractères du document texte, qui sera appliqué à son |
ouverture
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Encodage des caractères du document texte, qui sera appliqué à son |
ouverture
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Permet de spécifier comment les éléments de listes numérotées sont reconnus lorsque le document est |
importé depuis un format texte brut.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Permet de spécifier comment les éléments de listes numérotées sont reconnus lorsque le document est |
importé depuis un format texte brut.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | Obtient ou définit l'option préférée de gestion des espaces en début. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Obtient ou définit l'option préférée de gestion des espaces en début. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | Obtient ou définit l'option préférée de gestion des espaces en fin. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Obtient ou définit l'option préférée de gestion des espaces en fin. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Permet d'activer ou de désactiver la pagination dans le document HTML résultant. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Permet d'activer ou de désactiver la pagination dans le document HTML résultant. |
|
|  | [getDirection()](#getDirection--) | Permet de spécifier la direction du flux de texte dans le texte brut d'entrée |
document.
|
|  | [setDirection(int value)](#setDirection-int-) | Permet de spécifier la direction du flux de texte dans le texte brut d'entrée |
document.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Encodage des caractères du document texte, qui sera appliqué à son
ouverture


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Encodage des caractères du document texte, qui sera appliqué à son
ouverture


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Permet de spécifier comment les éléments de listes numérotées sont reconnus lorsque le document est
importé depuis un format texte brut. La valeur par défaut est vraie.


*** ** * ** ***

Si cette option est définie sur false, l'algorithme de reconnaissance des listes détecte les paragraphes de listes lorsque les numéros de liste se terminent par un point, une parenthèse droite ou des symboles de puces (tels que "\\u2022", "*", "-" ou "o"). Si cette option est définie sur true, les espaces sont également utilisés comme délimiteurs de numéros de liste : l'algorithme de reconnaissance des listes pour la numérotation de style arabe (1., 1.1.2.) utilise à la fois les espaces et le point (".") comme symboles.

<br />



**Returns:**
booléen
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Permet de spécifier comment les éléments de listes numérotées sont reconnus lorsque le document est
importé depuis un format texte brut. La valeur par défaut est vraie.


*** ** * ** ***

Si cette option est définie sur false, l'algorithme de reconnaissance des listes détecte les paragraphes de listes lorsque les numéros de liste se terminent par un point, une parenthèse droite ou des symboles de puces (tels que "\\u2022", "*", "-" ou "o"). Si cette option est définie sur true, les espaces sont également utilisés comme délimiteurs de numéros de liste : l'algorithme de reconnaissance des listes pour la numérotation de style arabe (1., 1.1.2.) utilise à la fois les espaces et le point (".") comme symboles.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Obtient ou définit l'option préférée de gestion des espaces en début. Par défaut
convertit les espaces en début en retrait à gauche.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Obtient ou définit l'option préférée de gestion des espaces en début. Par défaut
convertit les espaces en début en retrait à gauche.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Obtient ou définit l'option préférée de gestion des espaces en fin. Par défaut
supprime tous les espaces de fin.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Obtient ou définit l'option préférée de gestion des espaces en fin. Par défaut
supprime tous les espaces de fin.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Permet de spécifier la direction du flux de texte dans le texte brut d'entrée
document. Par défaut, il est de gauche à droite.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Permet de spécifier la direction du flux de texte dans le texte brut d'entrée
document. Par défaut, il est de gauche à droite.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

