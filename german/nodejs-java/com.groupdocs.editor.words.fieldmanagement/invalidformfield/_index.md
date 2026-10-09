---
title: "InvalidFormField"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt die Aktualisierung ungültiger Formularfeldnamen während des FormFieldManager.FixInvalidFormFieldNames-Vorgangs dar."
type: docs
weight: 18
url: /de/nodejs-java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Stellt die Aktualisierung ungültiger Formularfeldnamen während des
FormFieldManager.FixInvalidFormFieldNames
Vorgang.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Initialisiert eine neue Instanz der [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) Klasse mit dem angegebenen Namen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Liest den ursprünglichen Namen des Formularfelds, der außerhalb nicht geändert werden kann |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | Liest oder setzt den neuen Namen des Formularfelds nach der Reparatur. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | Liest oder setzt den neuen Namen des Formularfelds nach der Reparatur. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Initialisiert eine neue Instanz der [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) Klasse mit dem angegebenen Namen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Der ursprüngliche Name des Formularfelds. |
|

### getName() {#getName--}
```
public final String getName()
```


Liest den ursprünglichen Namen des Formularfelds, der außerhalb nicht geändert werden kann
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Liest oder setzt den neuen Namen des Formularfelds nach der Reparatur.
Dieser Name entfernt doppelte eindeutige Bezeichner mit anderen Formularfeldern und legt einen eindeutigen Lesezeichen-Namen fest.

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


Liest oder setzt den neuen Namen des Formularfelds nach der Reparatur.
Dieser Name entfernt doppelte eindeutige Bezeichner mit anderen Formularfeldern und legt einen eindeutigen Lesezeichen-Namen fest.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

