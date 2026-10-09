---
title: "CurrentTimeFormField"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt ein Formularfeld dar, das die aktuelle Uhrzeit anzeigt."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.editor.words.fieldmanagement/currenttimeformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class CurrentTimeFormField implements IFormField
```

Stellt ein Formularfeld dar, das die aktuelle Uhrzeit anzeigt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [CurrentTimeFormField(String stylesheet, String name)](#CurrentTimeFormField-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der [CurrentTimeFormField](../../com.groupdocs.editor.words.fieldmanagement/currenttimeformfield)-Klasse mit dem angegebenen Stylesheet und Namen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | Ruft das auf das Formularfeld angewendete Stylesheet ab. |
|
|  | [getReadonly()](#getReadonly--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Formularfeld schreibgeschützt ist. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Formularfeld schreibgeschützt ist. |
|
|  | [getName()](#getName--) | Ruft den Namen des Formularfelds ab. |
|
|  | [getType()](#getType--) | Ruft den Typ des Formularfelds ab, der für diese Klasse immer FormFieldType.CurrentTime ist. |
|
|  | [getLocaleId()](#getLocaleId--) | Ruft die Gebietsschema‑ID des Formularfelds ab oder legt sie fest, die die Kultur‑ oder Regionseinstellungen des Formularfelds darstellt. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Ruft die Gebietsschema‑ID des Formularfelds ab oder legt sie fest, die die Kultur‑ oder Regionseinstellungen des Formularfelds darstellt. |
|
|  | [getStatusText()](#getStatusText--) | Ruft den Status‑Text des Formularfelds ab oder legt ihn fest, die Quelle des Textes, der in der Statusleiste angezeigt wird, wenn ein Formularfeld den Fokus hat. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Ruft den Status‑Text des Formularfelds ab oder legt ihn fest, die Quelle des Textes, der in der Statusleiste angezeigt wird, wenn ein Formularfeld den Fokus hat. |
|
|  | [getHelpText()](#getHelpText--) | Ruft den Hilfetext des Formularfelds ab oder legt ihn fest, die Quelle des Textes, der in einer Meldungsbox angezeigt wird, wenn ein Formularfeld den Fokus hat und der Benutzer F1 drückt. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Ruft den Hilfetext des Formularfelds ab oder legt ihn fest, die Quelle des Textes, der in einer Meldungsbox angezeigt wird, wenn ein Formularfeld den Fokus hat und der Benutzer F1 drückt. |
|
|  | [getValue()](#getValue--) | Ruft den Wert des Formularfelds ab oder legt ihn fest, der die aktuelle Uhrzeit darstellt. |
|
|  | [setValue(Date value)](#setValue-java.util.Date-) | Ruft den Wert des Formularfelds ab oder legt ihn fest, der die aktuelle Uhrzeit darstellt. |
|
### CurrentTimeFormField(String stylesheet, String name) {#CurrentTimeFormField-java.lang.String-java.lang.String-}
```
public CurrentTimeFormField(String stylesheet, String name)
```


Initialisiert eine neue Instanz der [CurrentTimeFormField](../../com.groupdocs.editor.words.fieldmanagement/currenttimeformfield)-Klasse mit dem angegebenen Stylesheet und Namen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Stylesheet | java.lang.String | Das Stylesheet, das auf das Formularfeld angewendet werden soll. |
|
|  | Name | java.lang.String | Der Name des Formularfelds. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Ruft das auf das Formularfeld angewendete Stylesheet ab.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Formularfeld schreibgeschützt ist.


**Returns:**
boolesch
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Formularfeld schreibgeschützt ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getName() {#getName--}
```
public final String getName()
```


Ruft den Namen des Formularfelds ab.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Ruft den Typ des Formularfelds ab, der für diese Klasse immer FormFieldType.CurrentTime ist.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Ruft die Gebietsschema‑ID des Formularfelds ab oder legt sie fest, die die Kultur‑ oder Regionseinstellungen des Formularfelds darstellt.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

Die LocaleId‑Eigenschaft gibt einen Gebietsschema‑Bezeichner (LCID) an, der einer bestimmten Kultur oder Region entspricht.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


Ruft die Gebietsschema‑ID des Formularfelds ab oder legt sie fest, die die Kultur‑ oder Regionseinstellungen des Formularfelds darstellt.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

Die LocaleId‑Eigenschaft gibt einen Gebietsschema‑Bezeichner (LCID) an, der einer bestimmten Kultur oder Region entspricht.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Ruft den Status‑Text des Formularfelds ab oder legt ihn fest, die Quelle des Textes, der in der Statusleiste angezeigt wird, wenn ein Formularfeld den Fokus hat.

<br />

*** ** * ** ***

Wenn auf false gesetzt, wird der Status‑Text nicht angewendet.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Ruft den Status‑Text des Formularfelds ab oder legt ihn fest, die Quelle des Textes, der in der Statusleiste angezeigt wird, wenn ein Formularfeld den Fokus hat.

<br />

*** ** * ** ***

Wenn auf false gesetzt, wird der Status‑Text nicht angewendet.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Ruft den Hilfetext des Formularfelds ab oder legt ihn fest, die Quelle des Textes, der in einer Meldungsbox angezeigt wird, wenn ein Formularfeld den Fokus hat und der Benutzer F1 drückt.

<br />

*** ** * ** ***

Wenn auf false gesetzt, wird der Hilfetext nicht angewendet.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Ruft den Hilfetext des Formularfelds ab oder legt ihn fest, die Quelle des Textes, der in einer Meldungsbox angezeigt wird, wenn ein Formularfeld den Fokus hat und der Benutzer F1 drückt.

<br />

*** ** * ** ***

Wenn auf false gesetzt, wird der Hilfetext nicht angewendet.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final Date getValue()
```


Ruft den Wert des Formularfelds ab oder legt ihn fest, der die aktuelle Uhrzeit darstellt.


**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public final void setValue(Date value)
```


Ruft den Wert des Formularfelds ab oder legt ihn fest, der die aktuelle Uhrzeit darstellt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

