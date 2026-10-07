---
title: "DateFormField"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar ett formulärfält som visar ett datum."
type: docs
weight: 13
url: /sv/java/com.groupdocs.editor.words.fieldmanagement/dateformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class DateFormField implements IFormField
```

Representerar ett formulärfält som visar ett datum.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [DateFormField(String stylesheet, String name)](#DateFormField-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen [DateFormField](../../com.groupdocs.editor.words.fieldmanagement/dateformfield) med den angivna stilmallen och namnet. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | Hämtar den stilmall som tillämpas på formulärfältet. |
|
|  | [getReadonly()](#getReadonly--) | Hämtar eller anger ett värde som indikerar om formulärfältet är skrivskyddat. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | Hämtar eller anger ett värde som indikerar om formulärfältet är skrivskyddat. |
|
|  | [getName()](#getName--) | Hämtar namnet på formulärfältet. |
|
|  | [getType()](#getType--) | Hämtar typen av formulärfältet, som alltid är FormFieldType.Date för denna klass. |
|
|  | [getLocaleId()](#getLocaleId--) | Hämtar eller anger kultur‑ID för formulärfältet, som representerar den kultur eller de regionala inställningar som är kopplade till formulärfältet. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Hämtar eller anger kultur‑ID för formulärfältet, som representerar den kultur eller de regionala inställningar som är kopplade till formulärfältet. |
|
|  | [getStatusText()](#getStatusText--) | Hämtar eller anger statustexten som är associerad med formulärfältet, källan till texten som visas i statusfältet när ett formulärfält har fokus. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Hämtar eller anger statustexten som är associerad med formulärfältet, källan till texten som visas i statusfältet när ett formulärfält har fokus. |
|
|  | [getHelpText()](#getHelpText--) | Hämtar eller anger hjälptexten som är associerad med formulärfältet, källan till den text som visas i ett meddelandefönster när ett formulärfält har fokus och användaren trycker på F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Hämtar eller anger hjälptexten som är associerad med formulärfältet, källan till den text som visas i ett meddelandefönster när ett formulärfält har fokus och användaren trycker på F1. |
|
|  | [getValue()](#getValue--) | Hämtar eller anger värdet på formulärfältet, vilket representerar ett datum. |
|
|  | [setValue(Date value)](#setValue-java.util.Date-) | Hämtar eller anger värdet på formulärfältet, vilket representerar ett datum. |
|
### DateFormField(String stylesheet, String name) {#DateFormField-java.lang.String-java.lang.String-}
```
public DateFormField(String stylesheet, String name)
```


Initierar en ny instans av klassen [DateFormField](../../com.groupdocs.editor.words.fieldmanagement/dateformfield) med den angivna stilmallen och namnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stilmall | java.lang.String | Stilmallen som ska tillämpas på formulärfältet. |
|
|  | namn | java.lang.String | Namnet på formulärfältet. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Hämtar den stilmall som tillämpas på formulärfältet.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Hämtar eller anger ett värde som indikerar om formulärfältet är skrivskyddat.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Hämtar eller anger ett värde som indikerar om formulärfältet är skrivskyddat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på formulärfältet.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Hämtar typen av formulärfältet, som alltid är FormFieldType.Date för denna klass.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Hämtar eller anger kultur‑ID för formulärfältet, som representerar den kultur eller de regionala inställningar som är kopplade till formulärfältet.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  dateField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

Egenskapen LocaleId specificerar en lokalidentifierare (LCID) som motsvarar en viss kultur eller region.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


Hämtar eller anger kultur‑ID för formulärfältet, som representerar den kultur eller de regionala inställningar som är kopplade till formulärfältet.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  dateField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

Egenskapen LocaleId specificerar en lokalidentifierare (LCID) som motsvarar en viss kultur eller region.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Hämtar eller anger statustexten som är associerad med formulärfältet, källan till texten som visas i statusfältet när ett formulärfält har fokus.

<br />

*** ** * ** ***

Om den är inställd på false kommer statustexten inte att tillämpas.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Hämtar eller anger statustexten som är associerad med formulärfältet, källan till texten som visas i statusfältet när ett formulärfält har fokus.

<br />

*** ** * ** ***

Om den är inställd på false kommer statustexten inte att tillämpas.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Hämtar eller anger hjälptexten som är associerad med formulärfältet, källan till den text som visas i ett meddelandefönster när ett formulärfält har fokus och användaren trycker på F1.

<br />

*** ** * ** ***

Om den är inställd på false kommer hjälptexten inte att tillämpas.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Hämtar eller anger hjälptexten som är associerad med formulärfältet, källan till den text som visas i ett meddelandefönster när ett formulärfält har fokus och användaren trycker på F1.

<br />

*** ** * ** ***

Om den är inställd på false kommer hjälptexten inte att tillämpas.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final Date getValue()
```


Hämtar eller anger värdet på formulärfältet, vilket representerar ett datum.


**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public final void setValue(Date value)
```


Hämtar eller anger värdet på formulärfältet, vilket representerar ett datum.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

