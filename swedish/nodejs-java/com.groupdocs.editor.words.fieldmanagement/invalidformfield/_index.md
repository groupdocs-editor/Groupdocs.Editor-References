---
title: "InvalidFormField"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar uppdateringen av ogiltiga formulärfältsnamn under FormFieldManager.FixInvalidFormFieldNames‑operationen."
type: docs
weight: 18
url: /sv/nodejs-java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Representerar uppdateringen av ogiltiga formulärfältsnamn under
FormFieldManager.FixInvalidFormFieldNames
operationen.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Initierar en ny instans av klassen [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) med det angivna namnet. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Hämtar det ursprungliga namnet på formulärfältet som inte kan ändras utanför |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | Hämtar eller anger det nya namnet på formulärfältet efter reparation. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | Hämtar eller anger det nya namnet på formulärfältet efter reparation. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Initierar en ny instans av klassen [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) med det angivna namnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Det ursprungliga namnet på formulärfältet. |
|

### getName() {#getName--}
```
public final String getName()
```


Hämtar det ursprungliga namnet på formulärfältet som inte kan ändras utanför
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Hämtar eller anger det nya namnet på formulärfältet efter reparation.
Detta namn tar bort dubbletter av unika identifierare med andra formulärfält och sätter ett unikt bokmärkesnamn.

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


Hämtar eller anger det nya namnet på formulärfältet efter reparation.
Detta namn tar bort dubbletter av unika identifierare med andra formulärfält och sätter ett unikt bokmärkesnamn.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

