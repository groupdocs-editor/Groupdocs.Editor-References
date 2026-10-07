---
title: "NumberFormField"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt een formulierveld voor dat een numerieke invoer accepteert."
type: docs
weight: 19
url: /nl/java/com.groupdocs.editor.words.fieldmanagement/numberformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class NumberFormField implements IFormField
```

Stelt een formulierveld voor dat een numerieke invoer accepteert.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [NumberFormField(String stylesheet, String name)](#NumberFormField-java.lang.String-java.lang.String-) | Initialiseert een nieuw exemplaar van de [NumberFormField](../../com.groupdocs.editor.words.fieldmanagement/numberformfield) klasse met het opgegeven stylesheet en de naam. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | Haalt het stylesheet op dat op het formulierveld is toegepast. |
|
|  | [getReadonly()](#getReadonly--) | Haalt een waarde op of stelt deze in die aangeeft of het formulierveld alleen‑lezen is. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of het formulierveld alleen‑lezen is. |
|
|  | [getName()](#getName--) | Haalt de naam van het formulierveld op. |
|
|  | [getType()](#getType--) | Haalt het type van het formulierveld op, dat altijd FormFieldType.Number is voor deze klasse. |
|
|  | [getLocaleId()](#getLocaleId--) | Haalt de locale‑ID van het formulierveld op of stelt deze in, die de cultuur- of regionale instellingen van het formulierveld vertegenwoordigt. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Haalt de locale‑ID van het formulierveld op of stelt deze in, die de cultuur- of regionale instellingen van het formulierveld vertegenwoordigt. |
|
|  | [getStatusText()](#getStatusText--) | Haalt de statustekst op die aan het formulierveld is gekoppeld, de bron van de tekst die wordt weergegeven in de statusbalk wanneer een formulierveld de focus heeft, of stelt deze in. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Haalt de statustekst op die aan het formulierveld is gekoppeld, de bron van de tekst die wordt weergegeven in de statusbalk wanneer een formulierveld de focus heeft, of stelt deze in. |
|
|  | [getHelpText()](#getHelpText--) | Haalt de help‑tekst op die aan het formulierveld is gekoppeld, of stelt deze in; de bron van de tekst die wordt weergegeven in een berichtvenster wanneer een formulierveld de focus heeft en de gebruiker F1 indrukt. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Haalt de help‑tekst op die aan het formulierveld is gekoppeld, of stelt deze in; de bron van de tekst die wordt weergegeven in een berichtvenster wanneer een formulierveld de focus heeft en de gebruiker F1 indrukt. |
|
|  | [getValue()](#getValue--) | Haalt de waarde van het formulierveld op of stelt deze in, die een getal vertegenwoordigt. |
|
|  | [setValue(float value)](#setValue-float-) | Haalt de waarde van het formulierveld op of stelt deze in, die een getal vertegenwoordigt. |
|
|  | [getMaxLength()](#getMaxLength--) | Haalt de maximale lengte van de invoer voor het formulierveld op of stelt deze in. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | Haalt de maximale lengte van de invoer voor het formulierveld op of stelt deze in. |
|
### NumberFormField(String stylesheet, String name) {#NumberFormField-java.lang.String-java.lang.String-}
```
public NumberFormField(String stylesheet, String name)
```


Initialiseert een nieuw exemplaar van de [NumberFormField](../../com.groupdocs.editor.words.fieldmanagement/numberformfield) klasse met het opgegeven stylesheet en de naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stylesheet | java.lang.String | Het stylesheet dat op het formulierveld moet worden toegepast. |
|
|  | naam | java.lang.String | De naam van het formulierveld. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Haalt het stylesheet op dat op het formulierveld is toegepast.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Haalt een waarde op of stelt deze in die aangeeft of het formulierveld alleen‑lezen is.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of het formulierveld alleen‑lezen is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


Haalt de naam van het formulierveld op.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Haalt het type van het formulierveld op, dat altijd FormFieldType.Number is voor deze klasse.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Haalt de locale‑ID van het formulierveld op of stelt deze in, die de cultuur- of regionale instellingen van het formulierveld vertegenwoordigt.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  numberField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

De eigenschap LocaleId specificeert een locale-identificatie (LCID) die overeenkomt met een bepaalde cultuur of regio.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


Haalt de locale‑ID van het formulierveld op of stelt deze in, die de cultuur- of regionale instellingen van het formulierveld vertegenwoordigt.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  numberField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

De eigenschap LocaleId specificeert een locale-identificatie (LCID) die overeenkomt met een bepaalde cultuur of regio.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Haalt de statustekst op die aan het formulierveld is gekoppeld, de bron van de tekst die wordt weergegeven in de statusbalk wanneer een formulierveld de focus heeft, of stelt deze in.

<br />

*** ** * ** ***

Als ingesteld op  false , wordt de statustekst niet toegepast.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Haalt de statustekst op die aan het formulierveld is gekoppeld, de bron van de tekst die wordt weergegeven in de statusbalk wanneer een formulierveld de focus heeft, of stelt deze in.

<br />

*** ** * ** ***

Als ingesteld op  false , wordt de statustekst niet toegepast.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Haalt de help‑tekst op die aan het formulierveld is gekoppeld, of stelt deze in; de bron van de tekst die wordt weergegeven in een berichtvenster wanneer een formulierveld de focus heeft en de gebruiker F1 indrukt.

<br />

*** ** * ** ***

Als ingesteld op  false , wordt de helptekst niet toegepast.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Haalt de help‑tekst op die aan het formulierveld is gekoppeld, of stelt deze in; de bron van de tekst die wordt weergegeven in een berichtvenster wanneer een formulierveld de focus heeft en de gebruiker F1 indrukt.

<br />

*** ** * ** ***

Als ingesteld op  false , wordt de helptekst niet toegepast.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final float getValue()
```


Haalt de waarde van het formulierveld op of stelt deze in, die een getal vertegenwoordigt.


**Returns:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```


Haalt de waarde van het formulierveld op of stelt deze in, die een getal vertegenwoordigt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


Haalt de maximale lengte van de invoer voor het formulierveld op of stelt deze in.


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


Haalt de maximale lengte van de invoer voor het formulierveld op of stelt deze in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

