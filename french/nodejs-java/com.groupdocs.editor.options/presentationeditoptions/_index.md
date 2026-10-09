---
title: "PresentationEditOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour l'édition de documents de tous les formats de présentation compatibles PowerPoint pris en charge"
type: docs
weight: 32
url: /fr/nodejs-java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Permet de spécifier des options personnalisées pour l’édition de documents de tous les formats pris en charge
Formats de présentation (compatibles PowerPoint)

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | Permet de spécifier les numéros de diapositives qui doivent être ouverts pour l'édition |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Permet de spécifier les numéros de diapositives qui doivent être ouverts pour l'édition |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Spécifie si les diapositives masquées doivent être incluses ou non. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Spécifie si les diapositives masquées doivent être incluses ou non. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Permet de spécifier les numéros de diapositives qui doivent être ouverts pour l'édition


*** ** * ** ***

Le numéro de diapositive est un indice basé sur zéro d'une diapositive, qui permet de spécifier et de sélectionner une diapositive particulière d'une présentation à éditer. Si la valeur est inférieure à 0, la première diapositive sera sélectionnée (identique à SlideNumber = 0). Si elle est supérieure au nombre total de diapositives de la présentation, la dernière diapositive sera sélectionnée. Si la présentation d'entrée ne contient qu'une seule diapositive, cette option sera ignorée et cette diapositive unique sera éditée. Si vous essayez d'ouvrir pour édition une diapositive masquée alors que l'option ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) est définie sur 'false', une exception sera levée.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Permet de spécifier les numéros de diapositives qui doivent être ouverts pour l'édition


*** ** * ** ***

Le numéro de diapositive est un indice basé sur zéro d'une diapositive, qui permet de spécifier et de sélectionner une diapositive particulière d'une présentation à éditer. Si la valeur est inférieure à 0, la première diapositive sera sélectionnée (identique à SlideNumber = 0). Si elle est supérieure au nombre total de diapositives de la présentation, la dernière diapositive sera sélectionnée. Si la présentation d'entrée ne contient qu'une seule diapositive, cette option sera ignorée et cette diapositive unique sera éditée. Si vous essayez d'ouvrir pour édition une diapositive masquée alors que l'option ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) est définie sur 'false', une exception sera levée.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Spécifie si les diapositives masquées doivent être incluses ou non. La valeur par défaut est
false - les diapositives masquées ne sont pas affichées et une exception sera levée lors de
tentative d'édition.


**Returns:**
booléen
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Spécifie si les diapositives masquées doivent être incluses ou non. La valeur par défaut est
false - les diapositives masquées ne sont pas affichées et une exception sera levée lors de
tentative d'édition.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

