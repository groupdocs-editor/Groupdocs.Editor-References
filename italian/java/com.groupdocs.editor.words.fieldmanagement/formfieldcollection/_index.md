---
title: "FormFieldCollection"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta una raccolta di campi modulo."
type: docs
weight: 15
url: /it/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

Rappresenta una raccolta di campi modulo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | Inizializza una nuova istanza della classe [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | Inserisce un campo modulo nella collezione. |
|
|  | [get(String name)](#get-java.lang.String-) | Ottiene il campo modulo con il nome specificato. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | Ottiene il campo modulo con il nome e il tipo specificati. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


Inizializza una nuova istanza della classe [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection).


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - Un enumeratore che può essere usato per iterare attraverso la collezione.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


Inserisce un campo modulo nella collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | Il campo modulo da inserire. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


Ottiene il campo modulo con il nome specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Il nome del campo modulo. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


Ottiene il campo modulo con il nome e il tipo specificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Il nome del campo modulo. |


T
: Il tipo del campo modulo.
|
| tipo | java.lang.Class<T> |  |

**Returns:**
T - Il campo modulo con il nome e il tipo specificati, se trovato; altrimenti, il valore predefinito per il tipo.

