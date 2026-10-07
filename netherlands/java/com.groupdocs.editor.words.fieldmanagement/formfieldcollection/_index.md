---
title: "FormFieldCollection"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt een verzameling formuliervelden voor."
type: docs
weight: 15
url: /nl/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

Stelt een verzameling formuliervelden voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | Initialiseert een nieuw exemplaar van de klasse [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | Voegt een formulierveld toe aan de collectie. |
|
|  | [get(String name)](#get-java.lang.String-) | Haalt het formulierveld op met de opgegeven naam. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | Haalt het formulierveld op met de opgegeven naam en type. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


Initialiseert een nieuw exemplaar van de klasse [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection).


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


Retourneert een enumerator die door de collectie iterereert.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - Een enumerator die kan worden gebruikt om door de collectie te itereren.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


Voegt een formulierveld toe aan de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | Het formulierveld om in te voegen. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


Haalt het formulierveld op met de opgegeven naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | De naam van het formulierveld. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


Haalt het formulierveld op met de opgegeven naam en type.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | De naam van het formulierveld. |


T
: Het type van het formulierveld.
|
| type | java.lang.Class<T> |  |

**Returns:**
T - Het formulierveld met de opgegeven naam en type, indien gevonden; anders de standaardwaarde voor het type.

