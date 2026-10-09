---
title: "SpreadsheetSaveOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour la génération et l'enregistrement de documents Spreadsheet compatibles Excel"
type: docs
weight: 37
url: /fr/nodejs-java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Permet de spécifier des options personnalisées pour la génération et l'enregistrement de Spreadsheet
(compatible Excel) documents

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Ce constructeur sans paramètres crée une nouvelle instance de SpreadsheetSaveOptions avec le format de sortie XLSX (peut ensuite être modifié via |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) propriété)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Crée une nouvelle instance de SpreadsheetSaveOptions avec le mandat spécifié |
format de sortie Spreadsheet, tandis que tous les autres paramètres sont par défaut
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permet de spécifier, modifier, obtenir ou supprimer un mot de passe, qui sera |
utilisé pour encoder le document Spreadsheet généré, si ce format de document
prend en charge la protection par mot de passe.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permet de spécifier, modifier, obtenir ou supprimer un mot de passe, qui sera |
utilisé pour encoder le document Spreadsheet généré, si ce format de document
prend en charge la protection par mot de passe.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | Permet d'insérer la feuille de calcul éditée dans une copie d'une feuille de calcul existante |
au lieu de créer une nouvelle feuille de calcul à une seule feuille (par défaut
comportement).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Permet d'insérer la feuille de calcul éditée dans une copie d'une feuille de calcul existante |
au lieu de créer une nouvelle feuille de calcul à une seule feuille (par défaut
comportement).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Drapeau booléen, qui spécifie si la feuille de calcul éditée doit remplacer le |
feuille de calcul existante dans la feuille de calcul originale à la position spécifiée par
le

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propriété, ou elle doit être injectée entre la feuille de calcul existante et
la précédente, sans remplacer son contenu.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Drapeau booléen, qui spécifie si la feuille de calcul éditée doit remplacer le |
feuille de calcul existante dans la feuille de calcul originale à la position spécifiée par
le

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propriété, ou elle doit être injectée entre la feuille de calcul existante et
la précédente, sans remplacer son contenu.
|
|  | [getOutputFormat()](#getOutputFormat--) | Permet de spécifier un format Spreadsheet, qui sera utilisé pour enregistrer le |
document
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Permet de spécifier un format Spreadsheet, qui sera utilisé pour enregistrer le |
document
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | Permet d'activer une protection de feuille de calcul pour le Spreadsheet de sortie |
document.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Permet d'activer une protection de feuille de calcul pour le Spreadsheet de sortie |
document.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | Permet de spécifier un tableau contenant des numéros de feuilles de calcul indexés à partir de 1 qui doivent être supprimés du spreadsheet lors de son enregistrement, dans le cas où la feuille de calcul modifiée est insérée dans un spreadsheet existant. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | Permet de spécifier un tableau contenant des numéros de feuilles de calcul indexés à partir de 1 qui doivent être supprimés du spreadsheet lors de son enregistrement, dans le cas où la feuille de calcul modifiée est insérée dans un spreadsheet existant. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Ce constructeur sans paramètres crée une nouvelle instance de SpreadsheetSaveOptions avec le format de sortie XLSX (peut ensuite être modifié via
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) propriété)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Crée une nouvelle instance de SpreadsheetSaveOptions avec le mandat spécifié
format de sortie Spreadsheet, tandis que tous les autres paramètres sont par défaut


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Format de sortie obligatoire, dans lequel le document Spreadsheet doit être enregistré |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permet de spécifier, modifier, obtenir ou supprimer un mot de passe, qui sera
utilisé pour encoder le document Spreadsheet généré, si ce format de document
prend en charge la protection par mot de passe. Spécifiez NULL ou une chaîne vide pour supprimer
(nettoyage) le mot de passe.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permet de spécifier, modifier, obtenir ou supprimer un mot de passe, qui sera
utilisé pour encoder le document Spreadsheet généré, si ce format de document
prend en charge la protection par mot de passe. Spécifiez NULL ou une chaîne vide pour supprimer
(nettoyage) le mot de passe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


Permet d'insérer la feuille de calcul éditée dans une copie d'une feuille de calcul existante
au lieu de créer une nouvelle feuille de calcul à une seule feuille (par défaut
comportement). WorksheetNumber est un numéro de feuille de calcul indexé à partir de 1 dans le
spreadsheet, chargé dans la classe Editor. S'il est 0 (valeur par défaut), le
nouveau spreadsheet sera créé avec une seule feuille de calcul modifiée. S'il est
supérieur ou inférieur à zéro, et qu'il existe un spreadsheet valide, chargé dans
la classe Editor, la feuille de calcul modifiée, qui est représentée par l'entrée
instance EditableDocument, sera insérée dans ce spreadsheet.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


Permet d'insérer la feuille de calcul éditée dans une copie d'une feuille de calcul existante
au lieu de créer une nouvelle feuille de calcul à une seule feuille (par défaut
comportement). WorksheetNumber est un numéro de feuille de calcul indexé à partir de 1 dans le
spreadsheet, chargé dans la classe Editor. S'il est 0 (valeur par défaut), le
nouveau spreadsheet sera créé avec une seule feuille de calcul modifiée. S'il est
supérieur ou inférieur à zéro, et qu'il existe un spreadsheet valide, chargé dans
la classe Editor, la feuille de calcul modifiée, qui est représentée par l'entrée
instance EditableDocument, sera insérée dans ce spreadsheet.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


Drapeau booléen, qui spécifie si la feuille de calcul éditée doit remplacer le
feuille de calcul existante dans la feuille de calcul originale à la position spécifiée par
le

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propriété, ou elle doit être injectée entre la feuille de calcul existante et
la précédente, sans remplacer son contenu. Par défaut, c'est false \u2014
la feuille de calcul existante sera remplacée. Cette propriété est ignorée, si la valeur
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
de la propriété est définie à '0'.


*** ** * ** ***

Par défaut, la feuille de calcul est remplacée. Cela signifie que si le spreadsheet fourni possède 5 feuilles de calcul, et que WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, alors la 4e feuille sera remplacée par la nouvelle feuille de calcul modifiée, tandis que le nombre total de feuilles dans le spreadsheet (5) restera inchangé. Cependant, si la valeur de cette propriété est définie à  *true* , la nouvelle feuille de calcul modifiée sera injectée en tant que 4e feuille, et toutes les feuilles suivantes seront décalées vers la fin : la feuille \"old\" 4e devient 5e, et la 5e devient 6e, et le nombre total de feuilles dans le spreadsheet sera incrémenté de un pour atteindre 6.

<br />



**Returns:**
booléen -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Drapeau booléen, qui spécifie si la feuille de calcul éditée doit remplacer le
feuille de calcul existante dans la feuille de calcul originale à la position spécifiée par
le

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propriété, ou elle doit être injectée entre la feuille de calcul existante et
la précédente, sans remplacer son contenu. Par défaut, c'est false \u2014
la feuille de calcul existante sera remplacée. Cette propriété est ignorée, si la valeur
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
de la propriété est définie à '0'.


*** ** * ** ***

Par défaut, la feuille de calcul est remplacée. Cela signifie que si le spreadsheet fourni possède 5 feuilles de calcul, et que WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, alors la 4e feuille sera remplacée par la nouvelle feuille de calcul modifiée, tandis que le nombre total de feuilles dans le spreadsheet (5) restera inchangé. Cependant, si la valeur de cette propriété est définie à  *true* , la nouvelle feuille de calcul modifiée sera injectée en tant que 4e feuille, et toutes les feuilles suivantes seront décalées vers la fin : la feuille \"old\" 4e devient 5e, et la 5e devient 6e, et le nombre total de feuilles dans le spreadsheet sera incrémenté de un pour atteindre 6.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Permet de spécifier un format Spreadsheet, qui sera utilisé pour enregistrer le
document


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Permet de spécifier un format Spreadsheet, qui sera utilisé pour enregistrer le
document


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Permet d'activer une protection de feuille de calcul pour le Spreadsheet de sortie
document. Par défaut, c'est NULL - la protection n'est pas appliquée. Tous les formats ne
prennent en charge une protection de feuille de calcul.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Permet d'activer une protection de feuille de calcul pour le Spreadsheet de sortie
document. Par défaut, c'est NULL - la protection n'est pas appliquée. Tous les formats ne
prennent en charge une protection de feuille de calcul.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


Permet de spécifier un tableau contenant des numéros de feuilles de calcul indexés à partir de 1 qui doivent être supprimés du spreadsheet lors de son enregistrement, dans le cas où la feuille de calcul modifiée est insérée dans un spreadsheet existant. Lorsque la feuille de calcul modifiée est enregistrée non pas comme un nouveau spreadsheet à feuille unique (comportement par défaut), mais plutôt dans un spreadsheet existant (en utilisant #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int)), il est également possible de supprimer certaines feuilles particulières de ce spreadsheet en spécifiant leurs numéros dans ce tableau. Par défaut, ce tableau est  null  \u2014 aucune feuille ne sera supprimée. Cependant, lorsque ce tableau est non null et non vide, et qu'il contient au moins un numéro de feuille valide, après la génération du document spreadsheet de sortie avec le contenu de la feuille modifiée, les feuilles dont les numéros sont spécifiés seront supprimées du spreadsheet juste avant d'écrire son contenu dans le flux de sortie ou le fichier. Les numéros de feuilles dans ce tableau sont indexés à partir de 1, pas à partir de 0. Les numéros invalides (inférieurs à 1 ou supérieurs au nombre total de feuilles) seront ignorés.


**Returns:**
int[] - Tableau de numéros de feuilles de calcul indexés à 1 à supprimer, ou  null  si rien ne doit être supprimé.

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


Permet de spécifier un tableau contenant les numéros de feuilles de calcul indexés à 1 qui doivent être supprimés du classeur lors de son enregistrement, dans le cas où la feuille modifiée est insérée dans un classeur existant. Les numéros de feuilles dans ce tableau sont indexés à 1. Les numéros invalides seront ignorés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int[] | Tableau de numéros de feuilles de calcul indexés à 1 à supprimer (peut être  null  ou vide). |
|

