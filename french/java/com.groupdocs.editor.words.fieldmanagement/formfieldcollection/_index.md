---
title: "FormFieldCollection"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente une collection de champs de formulaire."
type: docs
weight: 15
url: /fr/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

Représente une collection de champs de formulaire.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | Initialise une nouvelle instance de la classe [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | Insère un champ de formulaire dans la collection. |
|
|  | [get(String name)](#get-java.lang.String-) | Obtient le champ de formulaire avec le nom spécifié. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | Obtient le champ de formulaire avec le nom et le type spécifiés. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


Initialise une nouvelle instance de la classe [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection).


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


Renvoie un énumérateur qui parcourt la collection.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - Un énumérateur qui peut être utilisé pour parcourir la collection.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


Insère un champ de formulaire dans la collection.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | Le champ de formulaire à insérer. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


Obtient le champ de formulaire avec le nom spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Le nom du champ de formulaire. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


Obtient le champ de formulaire avec le nom et le type spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | name | java.lang.String | Le nom du champ de formulaire. |


T
: Le type du champ de formulaire.
|
| type | java.lang.Class<T> |  |

**Returns:**
T - Le champ de formulaire avec le nom et le type spécifiés, s'il est trouvé ; sinon, la valeur par défaut pour le type.

