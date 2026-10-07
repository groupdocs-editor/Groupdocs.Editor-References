---
title: "DropDownFormField"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta un campo modulo che visualizza un elenco a discesa."
type: docs
weight: 14
url: /it/java/com.groupdocs.editor.words.fieldmanagement/dropdownformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class DropDownFormField implements IFormField
```

Rappresenta un campo modulo che visualizza un elenco a discesa.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DropDownFormField(String stylesheet, String name)](#DropDownFormField-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) con il foglio di stile e il nome specificati. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | Ottiene il foglio di stile applicato al campo modulo. |
|
|  | [getReadonly()](#getReadonly--) | Ottiene o imposta un valore che indica se il campo modulo è di sola lettura. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | Ottiene o imposta un valore che indica se il campo modulo è di sola lettura. |
|
|  | [getName()](#getName--) | Ottiene il nome del campo modulo. |
|
|  | [getSelectedIndex()](#getSelectedIndex--) | Ottiene o imposta l'indice dell'elemento selezionato nella lista a discesa. |
|
|  | [setSelectedIndex(int value)](#setSelectedIndex-int-) | Ottiene o imposta l'indice dell'elemento selezionato nella lista a discesa. |
|
|  | [getType()](#getType--) | Restituisce il tipo del campo modulo, che è sempre FormFieldType.DropDown per questa classe. |
|
|  | [getLocaleId()](#getLocaleId--) | Ottiene o imposta l'ID locale del campo modulo, che rappresenta la cultura o le impostazioni regionali associate al campo modulo. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Ottiene o imposta l'ID locale del campo modulo, che rappresenta la cultura o le impostazioni regionali associate al campo modulo. |
|
|  | [getStatusText()](#getStatusText--) | Ottiene o imposta il testo di stato associato al campo modulo, la fonte del testo visualizzato nella barra di stato quando un campo modulo ha il focus. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Ottiene o imposta il testo di stato associato al campo modulo, la fonte del testo visualizzato nella barra di stato quando un campo modulo ha il focus. |
|
|  | [getHelpText()](#getHelpText--) | Ottiene o imposta il testo di aiuto associato al campo modulo, la fonte del testo visualizzato in una finestra di messaggio quando un campo modulo ha il focus e l'utente preme F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Ottiene o imposta il testo di aiuto associato al campo modulo, la fonte del testo visualizzato in una finestra di messaggio quando un campo modulo ha il focus e l'utente preme F1. |
|
|  | [getValue()](#getValue--) | Ottiene o imposta il valore del campo modulo, che rappresenta l'elenco delle opzioni nella lista a discesa. |
|
|  | [setValue(List<String> value)](#setValue-java.util.List-java.lang.String--) | Ottiene o imposta il valore del campo modulo, che rappresenta l'elenco delle opzioni nella lista a discesa. |
|
### DropDownFormField(String stylesheet, String name) {#DropDownFormField-java.lang.String-java.lang.String-}
```
public DropDownFormField(String stylesheet, String name)
```


Inizializza una nuova istanza della classe [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) con il foglio di stile e il nome specificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | foglio di stile | java.lang.String | Il foglio di stile da applicare al campo modulo. |
|
|  | nome | java.lang.String | Il nome del campo modulo. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Ottiene il foglio di stile applicato al campo modulo.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Ottiene o imposta un valore che indica se il campo modulo è di sola lettura.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Ottiene o imposta un valore che indica se il campo modulo è di sola lettura.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


Ottiene il nome del campo modulo.


**Returns:**
java.lang.String
### getSelectedIndex() {#getSelectedIndex--}
```
public final int getSelectedIndex()
```


Ottiene o imposta l'indice dell'elemento selezionato nella lista a discesa.


**Returns:**
int
### setSelectedIndex(int value) {#setSelectedIndex-int-}
```
public final void setSelectedIndex(int value)
```


Ottiene o imposta l'indice dell'elemento selezionato nella lista a discesa.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getType() {#getType--}
```
public final int getType()
```


Restituisce il tipo del campo modulo, che è sempre FormFieldType.DropDown per questa classe.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Ottiene o imposta l'ID locale del campo modulo, che rappresenta la cultura o le impostazioni regionali associate al campo modulo.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

La proprietà LocaleId specifica un identificatore locale (LCID) che corrisponde a una determinata cultura o regione.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


Ottiene o imposta l'ID locale del campo modulo, che rappresenta la cultura o le impostazioni regionali associate al campo modulo.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

La proprietà LocaleId specifica un identificatore locale (LCID) che corrisponde a una determinata cultura o regione.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Ottiene o imposta il testo di stato associato al campo modulo, la fonte del testo visualizzato nella barra di stato quando un campo modulo ha il focus.

<br />

*** ** * ** ***

Se impostato su false, il testo di stato non verrà applicato.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Ottiene o imposta il testo di stato associato al campo modulo, la fonte del testo visualizzato nella barra di stato quando un campo modulo ha il focus.

<br />

*** ** * ** ***

Se impostato su false, il testo di stato non verrà applicato.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Ottiene o imposta il testo di aiuto associato al campo modulo, la fonte del testo visualizzato in una finestra di messaggio quando un campo modulo ha il focus e l'utente preme F1.

<br />

*** ** * ** ***

Se impostato su false, il testo di aiuto non verrà applicato.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Ottiene o imposta il testo di aiuto associato al campo modulo, la fonte del testo visualizzato in una finestra di messaggio quando un campo modulo ha il focus e l'utente preme F1.

<br />

*** ** * ** ***

Se impostato su false, il testo di aiuto non verrà applicato.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final List<String> getValue()
```


Ottiene o imposta il valore del campo modulo, che rappresenta l'elenco delle opzioni nella lista a discesa.


**Returns:**
java.util.List<java.lang.String>
### setValue(List<String> value) {#setValue-java.util.List-java.lang.String--}
```
public final void setValue(List<String> value)
```


Ottiene o imposta il valore del campo modulo, che rappresenta l'elenco delle opzioni nella lista a discesa.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<java.lang.String> |  |

