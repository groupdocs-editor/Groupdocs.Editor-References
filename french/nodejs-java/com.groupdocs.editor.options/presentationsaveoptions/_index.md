---
title: "PresentationSaveOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour la génération et l'enregistrement de documents Presentation compatibles PowerPoint"
type: docs
weight: 34
url: /fr/nodejs-java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Permet de spécifier des options personnalisées pour la génération et l'enregistrement de Presentation
(documents compatibles PowerPoint)

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Ce constructeur sans paramètres crée une nouvelle instance de PresentationSaveOptions avec le format de sortie PPTX (pouvant ensuite être modifié via |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) propriété)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Crée une nouvelle instance de PresentationSaveOptions avec le |
format de sortie Presentation obligatoire, tandis que tous les autres paramètres sont
par défaut
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permet de spécifier, modifier et obtenir le mot de passe, qui sera utilisé pour |
encodant le document Presentation résultant.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour l'encodage du document Presentation résultant. |
|
|  | [getSlideNumber()](#getSlideNumber--) | Permet d'insérer une diapositive modifiée dans une présentation existante au lieu de créer une nouvelle présentation à diapositive unique (comportement par défaut). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Permet d'insérer une diapositive modifiée dans une présentation existante au lieu de créer une nouvelle présentation à diapositive unique (comportement par défaut). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Indicateur booléen qui spécifie si la diapositive modifiée doit remplacer la diapositive existante dans la présentation originale à la position indiquée par le |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) propriété, ou elle doit être insérée entre la diapositive existante et la précédente, sans remplacer son contenu.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Indicateur booléen qui spécifie si la diapositive modifiée doit remplacer la diapositive existante dans la présentation originale à la position indiquée par le |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) propriété, ou elle doit être insérée entre la diapositive existante et la précédente, sans remplacer son contenu.
|
|  | [getOutputFormat()](#getOutputFormat--) | Permet de spécifier un format Presentation qui sera utilisé pour enregistrer le document |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Permet de spécifier un format Presentation qui sera utilisé pour enregistrer le document |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Permet de spécifier un tableau contenant les numéros de diapositives (à partir de 1) qui doivent être supprimés de la présentation lors de son enregistrement, dans le cas où la diapositive modifiée est insérée dans une présentation existante. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Permet de spécifier un tableau contenant les numéros de diapositives (à partir de 1) qui doivent être supprimés de la présentation lors de son enregistrement, dans le cas où la diapositive modifiée est insérée dans une présentation existante. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Ce constructeur sans paramètres crée une nouvelle instance de PresentationSaveOptions avec le format de sortie PPTX (pouvant ensuite être modifié via
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) propriété)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Crée une nouvelle instance de PresentationSaveOptions avec le
format de sortie Presentation obligatoire, tandis que tous les autres paramètres sont
par défaut


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Format de sortie obligatoire dans lequel le document Presentation doit être enregistré |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permet de spécifier, modifier et obtenir le mot de passe, qui sera utilisé pour
encodage du document Presentation résultant. Par défaut, il est NULL -
le mot de passe ne sera pas défini. Définissez-le sur NULL ou une chaîne vide afin de supprimer
le mot de passe, s'il avait été défini précédemment.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour l'encodage du document Presentation résultant.
Par défaut, c'est NULL - le mot de passe ne sera pas défini. Réglez sur NULL ou une chaîne vide afin de supprimer le mot de passe, s'il avait été défini précédemment.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Permet d'insérer une diapositive modifiée dans une présentation existante au lieu de créer une nouvelle présentation à diapositive unique (comportement par défaut).
Le numéro de diapositive est un nombre indexé à partir de 1 d'une diapositive dans la présentation, chargée dans la classe Editor. S'il vaut 0 (valeur par défaut), la nouvelle présentation sera créée avec une seule diapositive modifiée. S'il est supérieur ou inférieur à zéro, et qu'il existe une présentation valide chargée dans la classe Editor, la diapositive modifiée, stockée dans l'instance d'EditableDocument d'entrée, sera insérée dans cette présentation.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Permet d'insérer une diapositive modifiée dans une présentation existante au lieu de créer une nouvelle présentation à diapositive unique (comportement par défaut).
Le numéro de diapositive est un nombre indexé à partir de 1 d'une diapositive dans la présentation, chargée dans la classe Editor. S'il vaut 0 (valeur par défaut), la nouvelle présentation sera créée avec une seule diapositive modifiée. S'il est supérieur ou inférieur à zéro, et qu'il existe une présentation valide chargée dans la classe Editor, la diapositive modifiée, stockée dans l'instance d'EditableDocument d'entrée, sera insérée dans cette présentation.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


Indicateur booléen qui spécifie si la diapositive modifiée doit remplacer la diapositive existante dans la présentation originale à la position indiquée par le
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) propriété, ou elle doit être insérée entre la diapositive existante et la précédente, sans remplacer son contenu.
Par défaut, c'est false \\u2014 la diapositive existante sera remplacée. Cette propriété est ignorée, si la valeur de
SlideNumber
la propriété (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) est définie sur '0'.

<br />

*** ** * ** ***

Par défaut, la diapositive est remplacée. Cela signifie que si la présentation donnée possède 5 diapositives, et que SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, alors la 4ᵉ diapositive sera remplacée par la nouvelle diapositive modifiée, tandis que le nombre total de diapositives dans la présentation (5) restera inchangé. Cependant, si la valeur de cette propriété est définie sur  *true* , la nouvelle diapositive modifiée sera injectée comme 4ᵉ diapositive, et toutes les diapositives suivantes seront décalées vers la fin\: \"old\" 4ᵉ diapositive devient la 5ᵉ, et la 5ᵉ devient la 6ᵉ, et le nombre total de diapositives dans la présentation sera incrémenté de un pour atteindre 6.

<br />



**Returns:**
booléen
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Indicateur booléen qui spécifie si la diapositive modifiée doit remplacer la diapositive existante dans la présentation originale à la position indiquée par le
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) propriété, ou elle doit être insérée entre la diapositive existante et la précédente, sans remplacer son contenu.
Par défaut, c'est false \\u2014 la diapositive existante sera remplacée. Cette propriété est ignorée, si la valeur de
SlideNumber
la propriété (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) est définie sur '0'.

<br />

*** ** * ** ***

Par défaut, la diapositive est remplacée. Cela signifie que si la présentation donnée possède 5 diapositives, et que SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, alors la 4ᵉ diapositive sera remplacée par la nouvelle diapositive modifiée, tandis que le nombre total de diapositives dans la présentation (5) restera inchangé. Cependant, si la valeur de cette propriété est définie sur  *true* , la nouvelle diapositive modifiée sera injectée comme 4ᵉ diapositive, et toutes les diapositives suivantes seront décalées vers la fin\: \"old\" 4ᵉ diapositive devient la 5ᵉ, et la 5ᵉ devient la 6ᵉ, et le nombre total de diapositives dans la présentation sera incrémenté de un pour atteindre 6.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Permet de spécifier un format Presentation qui sera utilisé pour enregistrer le document

<br />

*** ** * ** ***

Le format de sortie est généralement défini dans le constructeur de cette classe, car il est obligatoire. Cette propriété permet d'obtenir ou de modifier le format de sortie ultérieurement, lorsque l'instance de la classe [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) a déjà été créée.

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


Permet de spécifier un format Presentation qui sera utilisé pour enregistrer le document

<br />

*** ** * ** ***

Le format de sortie est généralement défini dans le constructeur de cette classe, car il est obligatoire. Cette propriété permet d'obtenir ou de modifier le format de sortie ultérieurement, lorsque l'instance de la classe [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) a déjà été créée.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


Permet de spécifier un tableau contenant les numéros de diapositives indexés à partir de 1 qui doivent être supprimés de la présentation lors de son enregistrement, dans le cas où la diapositive modifiée est insérée dans une présentation existante. Lorsque la diapositive modifiée n'est pas enregistrée comme une nouvelle présentation à diapositive unique (comportement par défaut), mais est enregistrée dans une présentation existante (en utilisant #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int)), il est également possible de supprimer certaines diapositives particulières de cette présentation en indiquant leurs numéros dans ce tableau. Par défaut, ce tableau est  null  \\u2014 aucune diapositive ne sera supprimée. Cependant, lorsque ce tableau est non nul et non vide, et qu'il contient au moins un numéro de diapositive valide, après la génération du document Presentation de sortie avec le contenu de la diapositive modifiée, les diapositives avec les numéros spécifiés seront supprimées de la présentation juste avant d'écrire son contenu dans le flux ou le fichier de sortie. Les numéros de diapositives dans ce tableau sont indexés à partir de 1, pas à partir de 0. Les numéros invalides (inférieurs à 1 ou supérieurs au nombre total de diapositives) seront ignorés.


**Returns:**
int[] - Tableau de numéros de diapositives indexés à partir de 1 à supprimer, ou  null  si rien ne doit être supprimé.

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Permet de spécifier un tableau contenant les numéros de diapositives indexés à partir de 1 qui doivent être supprimés de la présentation lors de son enregistrement, dans le cas où la diapositive modifiée est insérée dans une présentation existante. Les numéros de diapositives dans ce tableau sont indexés à partir de 1. Les numéros invalides seront ignorés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int[] | Tableau de numéros de diapositives indexés à partir de 1 à supprimer (peut être  null  ou vide). |
|

