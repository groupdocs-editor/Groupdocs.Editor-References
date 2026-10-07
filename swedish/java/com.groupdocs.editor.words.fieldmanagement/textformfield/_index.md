---
title: "TextFormField"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar ett formulärfält som accepterar textinmatning."
type: docs
weight: 20
url: /sv/java/com.groupdocs.editor.words.fieldmanagement/textformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class TextFormField implements IFormField
```

Representerar ett formulärfält som accepterar textinmatning.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TextFormField(String stylesheet, String name)](#TextFormField-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) med den angivna stilmallen och namnet. |
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
|  | [getType()](#getType--) | Hämtar typen av formulärfältet, som alltid är FormFieldType.Text för denna klass. |
|
|  | [getLocaleId()](#getLocaleId--) | Hämtar eller anger kultur‑ID för formulärfältet, som representerar den kultur eller de regionala inställningar som är kopplade till formulärfältet. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Hämtar eller anger kultur‑ID för formulärfältet, som representerar den kultur eller de regionala inställningar som är kopplade till formulärfältet. |
|
|  | [getStatusText()](#getStatusText--) | Hämtar eller anger statustexten som är associerad med formulärfältet, |
källan till texten som visas i statusfältet när ett formulärfält har fokus.
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Hämtar eller anger statustexten som är associerad med formulärfältet, |
källan till texten som visas i statusfältet när ett formulärfält har fokus.
|
|  | [getHelpText()](#getHelpText--) | Hämtar eller anger hjälptexten som är associerad med formulärfältet, |
källan till texten som visas i ett meddelandefönster när ett formulärfält har fokus och användaren trycker på F1.
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Hämtar eller anger hjälptexten som är associerad med formulärfältet, |
källan till texten som visas i ett meddelandefönster när ett formulärfält har fokus och användaren trycker på F1.
|
|  | [getValue()](#getValue--) | Hämtar eller anger värdet på formulärfältet, vilket representerar textinmatningen. |
|
|  | [setValue(String value)](#setValue-java.lang.String-) | Hämtar eller anger värdet på formulärfältet, vilket representerar textinmatningen. |
|
|  | [getMaxLength()](#getMaxLength--) | Hämtar eller anger den maximala längden på inmatningen för formulärfältet. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | Hämtar eller anger den maximala längden på inmatningen för formulärfältet. |
|
### TextFormField(String stylesheet, String name) {#TextFormField-java.lang.String-java.lang.String-}
```
public TextFormField(String stylesheet, String name)
```


Initierar en ny instans av klassen [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) med den angivna stilmallen och namnet.


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


Hämtar typen av formulärfältet, som alltid är FormFieldType.Text för denna klass.


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
>  textField.LocaleId = new CultureInfo("en-US").LCID;
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
>  textField.LocaleId = new CultureInfo("en-US").LCID;
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


Hämtar eller anger statustexten som är associerad med formulärfältet,
källan till texten som visas i statusfältet när ett formulärfält har fokus.

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


Hämtar eller anger statustexten som är associerad med formulärfältet,
källan till texten som visas i statusfältet när ett formulärfält har fokus.

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


Hämtar eller anger hjälptexten som är associerad med formulärfältet,
källan till texten som visas i ett meddelandefönster när ett formulärfält har fokus och användaren trycker på F1.

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


Hämtar eller anger hjälptexten som är associerad med formulärfältet,
källan till texten som visas i ett meddelandefönster när ett formulärfält har fokus och användaren trycker på F1.

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
public final String getValue()
```


Hämtar eller anger värdet på formulärfältet, vilket representerar textinmatningen.


**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Hämtar eller anger värdet på formulärfältet, vilket representerar textinmatningen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


Hämtar eller anger den maximala längden på inmatningen för formulärfältet.


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


Hämtar eller anger den maximala längden på inmatningen för formulärfältet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

