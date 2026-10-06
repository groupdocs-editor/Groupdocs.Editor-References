---
title: "FormFieldCollection"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt eine Sammlung von Formularfeldern dar."
type: docs
weight: 15
url: /de/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

Stellt eine Sammlung von Formularfeldern dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | Initialisiert eine neue Instanz der [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection)-Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | Fügt ein Formularfeld in die Sammlung ein. |
|
|  | [get(String name)](#get-java.lang.String-) | Liefert das Formularfeld mit dem angegebenen Namen. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | Liefert das Formularfeld mit dem angegebenen Namen und Typ. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


Initialisiert eine neue Instanz der [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection)-Klasse.


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - Ein Enumerator, der verwendet werden kann, um die Sammlung zu durchlaufen.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


Fügt ein Formularfeld in die Sammlung ein.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | Das einzufügende Formularfeld. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


Liefert das Formularfeld mit dem angegebenen Namen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Der Name des Formularfelds. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


Liefert das Formularfeld mit dem angegebenen Namen und Typ.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Der Name des Formularfelds. |


T
: Der Typ des Formularfelds.
|
| Typ | java.lang.Class<T> |  |

**Returns:**
T - Das Formularfeld mit dem angegebenen Namen und Typ, falls gefunden; andernfalls der Standardwert für den Typ.

