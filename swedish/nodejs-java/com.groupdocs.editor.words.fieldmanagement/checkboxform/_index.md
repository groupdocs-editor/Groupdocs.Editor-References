---
title: "CheckBoxForm"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar ett formulärfält som visar en kryssruta."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.editor.words.fieldmanagement/checkboxform/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class CheckBoxForm implements IFormField
```

Representerar ett formulärfält som visar en kryssruta.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [CheckBoxForm(String stylesheet, String name)](#CheckBoxForm-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen [CheckBoxForm](../../com.groupdocs.editor.words.fieldmanagement/checkboxform) med den angivna stilmallen och namnet. |
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
|  | [getType()](#getType--) | Hämtar typen av formulärfältet, som alltid är FormFieldType.CheckBox för denna klass. |
|
|  | [getLocaleId()](#getLocaleId--) | Hämtar eller anger kultur‑ID för formulärfältet, som representerar kultur‑ eller regionala inställningar som är associerade med formulärfältet. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Hämtar eller anger kultur‑ID för formulärfältet, som representerar kultur‑ eller regionala inställningar som är associerade med formulärfältet. |
|
|  | [getStatusText()](#getStatusText--) | Hämtar eller anger statustexten som är associerad med formulärfältet, källan till texten som visas i statusfältet när ett formulärfält har fokus. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Hämtar eller anger statustexten som är associerad med formulärfältet, källan till texten som visas i statusfältet när ett formulärfält har fokus. |
|
|  | [getHelpText()](#getHelpText--) | Hämtar eller anger hjälptexten som är associerad med formulärfältet, källan till den text som visas i ett meddelandefönster när ett formulärfält har fokus och användaren trycker på F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Hämtar eller anger hjälptexten som är associerad med formulärfältet, källan till den text som visas i ett meddelandefönster när ett formulärfält har fokus och användaren trycker på F1. |
|
|  | [getValue()](#getValue--) | Hämtar eller anger värdet för formulärfältet, vilket representerar kryssrutans tillstånd. |
|
|  | [setValue(boolean value)](#setValue-boolean-) | Hämtar eller anger värdet för formulärfältet, vilket representerar kryssrutans tillstånd. |
|
### CheckBoxForm(String stylesheet, String name) {#CheckBoxForm-java.lang.String-java.lang.String-}
```
public CheckBoxForm(String stylesheet, String name)
```


Initierar en ny instans av klassen [CheckBoxForm](../../com.groupdocs.editor.words.fieldmanagement/checkboxform) med den angivna stilmallen och namnet.


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


Hämtar typen av formulärfältet, som alltid är FormFieldType.CheckBox för denna klass.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Hämtar eller anger kultur‑ID för formulärfältet, som representerar kultur‑ eller regionala inställningar som är associerade med formulärfältet.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  checkBoxField.LocaleId = new CultureInfo("en-US").LCID;
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


Hämtar eller anger kultur‑ID för formulärfältet, som representerar kultur‑ eller regionala inställningar som är associerade med formulärfältet.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  checkBoxField.LocaleId = new CultureInfo("en-US").LCID;
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

Om den är inställd på  false , kommer statustexten inte att tillämpas.

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

Om den är inställd på  false , kommer statustexten inte att tillämpas.

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

Om den är inställd på  false , kommer hjälptexten inte att tillämpas.

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

Om den är inställd på  false , kommer hjälptexten inte att tillämpas.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final boolean getValue()
```


Hämtar eller anger värdet för formulärfältet, vilket representerar kryssrutans tillstånd.


**Returns:**
boolean
### setValue(boolean value) {#setValue-boolean-}
```
public final void setValue(boolean value)
```


Hämtar eller anger värdet för formulärfältet, vilket representerar kryssrutans tillstånd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

