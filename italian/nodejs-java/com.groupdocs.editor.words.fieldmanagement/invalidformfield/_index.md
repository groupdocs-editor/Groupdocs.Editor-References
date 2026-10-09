---
title: "InvalidFormField"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta l'aggiornamento dei nomi di campo del modulo non validi durante l'operazione FormFieldManager.FixInvalidFormFieldNames."
type: docs
weight: 18
url: /it/nodejs-java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Rappresenta l'aggiornamento dei nomi di campo modulo non validi durante il
FormFieldManager.FixInvalidFormFieldNames
operazione.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Inizializza una nuova istanza della classe [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) con il nome specificato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getName()](#getName--) | Ottiene il nome originale del campo modulo che non può essere modificato al di fuori del |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | Ottiene o imposta il nuovo nome per il campo modulo dopo la correzione. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | Ottiene o imposta il nuovo nome per il campo modulo dopo la correzione. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Inizializza una nuova istanza della classe [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) con il nome specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Il nome originale del campo modulo. |
|

### getName() {#getName--}
```
public final String getName()
```


Ottiene il nome originale del campo modulo che non può essere modificato al di fuori del
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Ottiene o imposta il nuovo nome per il campo modulo dopo la correzione.
Questo nome rimuove identificatori univoci duplicati con altri campi modulo e imposta un nome di segnalibro univoco.

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


Ottiene o imposta il nuovo nome per il campo modulo dopo la correzione.
Questo nome rimuove identificatori univoci duplicati con altri campi modulo e imposta un nome di segnalibro univoco.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

