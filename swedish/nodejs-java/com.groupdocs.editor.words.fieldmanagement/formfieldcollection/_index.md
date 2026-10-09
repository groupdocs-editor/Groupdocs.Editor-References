---
title: "FormFieldCollection"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar en samling av formulärfält."
type: docs
weight: 15
url: /sv/nodejs-java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

Representerar en samling av formulärfält.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | Initierar en ny instans av klassen [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | Infogar ett formulärfält i samlingen. |
|
|  | [get(String name)](#get-java.lang.String-) | Hämtar formulärfältet med det angivna namnet. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | Hämtar formulärfältet med det angivna namnet och typen. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


Initierar en ny instans av klassen [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection).


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


Returnerar en enumerator som itererar genom samlingen.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - En enumerator som kan användas för att iterera genom samlingen.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


Infogar ett formulärfält i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | Formulärfältet att infoga. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


Hämtar formulärfältet med det angivna namnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på formulärfältet. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


Hämtar formulärfältet med det angivna namnet och typen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på formulärfältet. |


T
: Typen av formulärfältet.
|
| typ | java.lang.Class<T> |  |

**Returns:**
T - Formulärfältet med det angivna namnet och typen, om det hittas; annars standardvärdet för typen.

