---
title: "InvalidFormField"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente la mise à jour des noms de champs de formulaire invalides pendant l'opération FormFieldManager.FixInvalidFormFieldNames."
type: docs
weight: 18
url: /fr/java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Représente la mise à jour des noms de champs de formulaire invalides pendant le
FormFieldManager.FixInvalidFormFieldNames
opération.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Initialise une nouvelle instance de la classe [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) avec le nom spécifié. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Obtient le nom original du champ de formulaire qui ne peut pas être modifié à l'extérieur |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | Obtient ou définit le nouveau nom du champ de formulaire après la réparation. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | Obtient ou définit le nouveau nom du champ de formulaire après la réparation. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Initialise une nouvelle instance de la classe [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) avec le nom spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Le nom original du champ de formulaire. |
|

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom original du champ de formulaire qui ne peut pas être modifié à l'extérieur
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Obtient ou définit le nouveau nom du champ de formulaire après la réparation.
Ce nom supprime les identifiants uniques en double avec d'autres champs de formulaire et définit un nom de signet unique.

<br />

*** ** * ** ***

```
 FixedName = String.format("%s_fixed", name); // as default value.
 
```

<br />



**Returns:**
java.lang.String
### setFixedName(String value) {#setFixedName-java.lang.String-}
```
public final void setFixedName(String value)
```


Obtient ou définit le nouveau nom du champ de formulaire après la réparation.
Ce nom supprime les identifiants uniques en double avec d'autres champs de formulaire et définit un nom de signet unique.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

