---
title: "CurrentTimeFormField"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt ein Formularfeld dar, das die aktuelle Uhrzeit anzeigt."
type: docs
weight: 12
url: /de/java/com.groupdocs.editor.words.fieldmanagement/currenttimeformfield/
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
|  | [getStylesheet()](#getStylesheet--) | Ermittelt das auf das Formularfeld angewendete Stylesheet. |
|
|  | [getReadonly()](#getReadonly--) | Ermittelt oder legt einen Wert fest, der angibt, ob das Formularfeld schreibgeschützt ist. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | Ermittelt oder legt einen Wert fest, der angibt, ob das Formularfeld schreibgeschützt ist. |
|
|  | [getName()](#getName--) | Ermittelt den Namen des Formularfelds. |
|
|  | [getType()](#getType--) | Ermittelt den Typ des Formularfelds, der für diese Klasse stets FormFieldType.CurrentTime ist. |
|
|  | [getLocaleId()](#getLocaleId--) | Ermittelt oder legt die Locale-ID des Formularfelds fest, die die Kultur- oder Regionseinstellungen des Formularfelds repräsentiert. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Ermittelt oder legt die Locale-ID des Formularfelds fest, die die Kultur- oder Regionseinstellungen des Formularfelds repräsentiert. |
|
|  | [getStatusText()](#getStatusText--) | Ermittelt oder legt den Status‑Text des Formularfelds fest, die Quelle des Textes, der in der Statusleiste angezeigt wird, wenn ein Formularfeld den Fokus hat.. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Ermittelt oder legt den Status‑Text des Formularfelds fest, die Quelle des Textes, der in der Statusleiste angezeigt wird, wenn ein Formularfeld den Fokus hat.. |
|
|  | [getHelpText()](#getHelpText--) | Ermittelt oder legt den Hilfetext des Formularfelds fest, die Quelle des Textes, der in einer Meldungsbox angezeigt wird, wenn ein Formularfeld den Fokus hat und der Benutzer F1 drückt. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Ermittelt oder legt den Hilfetext des Formularfelds fest, die Quelle des Textes, der in einer Meldungsbox angezeigt wird, wenn ein Formularfeld den Fokus hat und der Benutzer F1 drückt. |
|
|  | [getValue()](#getValue--) | Ermittelt oder legt den Wert des Formularfelds fest, der die aktuelle Zeit darstellt. |
|
|  | [setValue(Date value)](#setValue-java.util.Date-) | Ermittelt oder legt den Wert des Formularfelds fest, der die aktuelle Zeit darstellt. |
|
### CurrentTimeFormField(String stylesheet, String name) {#CurrentTimeFormField-java.lang.String-java.lang.String-}
```
public CurrentTimeFormField(String stylesheet, String name)
```


Initialisiert eine neue Instanz der [CurrentTimeFormField](../../com.groupdocs.editor.words.fieldmanagement/currenttimeformfield)-Klasse mit dem angegebenen Stylesheet und Namen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Stylesheet | java.lang.String | Das auf das Formularfeld anzuwendende Stylesheet. |
|
|  | Name | java.lang.String | Der Name des Formularfelds. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Ermittelt das auf das Formularfeld angewendete Stylesheet.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Ermittelt oder legt einen Wert fest, der angibt, ob das Formularfeld schreibgeschützt ist.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Ermittelt oder legt einen Wert fest, der angibt, ob das Formularfeld schreibgeschützt ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


Ermittelt den Namen des Formularfelds.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Ermittelt den Typ des Formularfelds, der für diese Klasse stets FormFieldType.CurrentTime ist.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Ermittelt oder legt die Locale-ID des Formularfelds fest, die die Kultur- oder Regionseinstellungen des Formularfelds repräsentiert.

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


Ermittelt oder legt die Locale-ID des Formularfelds fest, die die Kultur- oder Regionseinstellungen des Formularfelds repräsentiert.

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


Ermittelt oder legt den Status‑Text des Formularfelds fest, die Quelle des Textes, der in der Statusleiste angezeigt wird, wenn ein Formularfeld den Fokus hat..

<br />

*** ** * ** ***

Wenn auf  false  gesetzt, wird der Status‑Text nicht angewendet.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Ermittelt oder legt den Status‑Text des Formularfelds fest, die Quelle des Textes, der in der Statusleiste angezeigt wird, wenn ein Formularfeld den Fokus hat..

<br />

*** ** * ** ***

Wenn auf  false  gesetzt, wird der Status‑Text nicht angewendet.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Ermittelt oder legt den Hilfetext des Formularfelds fest, die Quelle des Textes, der in einer Meldungsbox angezeigt wird, wenn ein Formularfeld den Fokus hat und der Benutzer F1 drückt.

<br />

*** ** * ** ***

Wenn auf  false  gesetzt, wird der Hilfetext nicht angewendet.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Ermittelt oder legt den Hilfetext des Formularfelds fest, die Quelle des Textes, der in einer Meldungsbox angezeigt wird, wenn ein Formularfeld den Fokus hat und der Benutzer F1 drückt.

<br />

*** ** * ** ***

Wenn auf  false  gesetzt, wird der Hilfetext nicht angewendet.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final Date getValue()
```


Ermittelt oder legt den Wert des Formularfelds fest, der die aktuelle Zeit darstellt.


**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public final void setValue(Date value)
```


Ermittelt oder legt den Wert des Formularfelds fest, der die aktuelle Zeit darstellt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

