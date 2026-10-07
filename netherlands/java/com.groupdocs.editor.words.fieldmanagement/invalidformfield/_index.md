---
title: "InvalidFormField"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt de bijwerking van ongeldige formulierveldnamen voor tijdens de FormFieldManager.FixInvalidFormFieldNames operatie."
type: docs
weight: 18
url: /nl/java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Stelt de bijwerking van ongeldige formulierveldnamen voor tijdens de
FormFieldManager.FixInvalidFormFieldNames
bewerking.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Initialiseert een nieuw exemplaar van de [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) klasse met de opgegeven naam. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Haalt de oorspronkelijke naam van het formulierveld op die buiten |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | Haalt de nieuwe naam voor het formulierveld op of stelt deze in na reparatie. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | Haalt de nieuwe naam voor het formulierveld op of stelt deze in na reparatie. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Initialiseert een nieuw exemplaar van de [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) klasse met de opgegeven naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | De oorspronkelijke naam van het formulierveld. |
|

### getName() {#getName--}
```
public final String getName()
```


Haalt de oorspronkelijke naam van het formulierveld op die buiten
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Haalt de nieuwe naam voor het formulierveld op of stelt deze in na reparatie.
Deze naam verwijdert dubbele unieke identifiers met andere formuliervelden en stelt een unieke bladwijzernaam in.

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


Haalt de nieuwe naam voor het formulierveld op of stelt deze in na reparatie.
Deze naam verwijdert dubbele unieke identifiers met andere formuliervelden en stelt een unieke bladwijzernaam in.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

