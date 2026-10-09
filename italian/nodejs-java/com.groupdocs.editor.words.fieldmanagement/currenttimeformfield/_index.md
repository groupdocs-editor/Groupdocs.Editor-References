---
title: "CurrentTimeFormField"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un campo modulo che visualizza l'ora corrente."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.editor.words.fieldmanagement/currenttimeformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class CurrentTimeFormField implements IFormField
```

Rappresenta un campo modulo che visualizza l'ora corrente.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [CurrentTimeFormField(String stylesheet, String name)](#CurrentTimeFormField-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe [CurrentTimeFormField](../../com.groupdocs.editor.words.fieldmanagement/currenttimeformfield) con il foglio di stile e il nome specificati. |
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
|  | [getType()](#getType--) | Ottiene il tipo del campo modulo, che è sempre FormFieldType.CurrentTime per questa classe. |
|
|  | [getLocaleId()](#getLocaleId--) | Ottiene o imposta l'ID locale del campo modulo, che rappresenta la cultura o le impostazioni regionali associate al campo modulo. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Ottiene o imposta l'ID locale del campo modulo, che rappresenta la cultura o le impostazioni regionali associate al campo modulo. |
|
|  | [getStatusText()](#getStatusText--) | Ottiene o imposta il testo di stato associato al campo modulo, la fonte del testo visualizzato nella barra di stato quando un campo modulo ha il focus.. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Ottiene o imposta il testo di stato associato al campo modulo, la fonte del testo visualizzato nella barra di stato quando un campo modulo ha il focus.. |
|
|  | [getHelpText()](#getHelpText--) | Ottiene o imposta il testo di aiuto associato al campo modulo, la fonte del testo visualizzato in una finestra di messaggio quando un campo modulo ha il focus e l'utente preme F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Ottiene o imposta il testo di aiuto associato al campo modulo, la fonte del testo visualizzato in una finestra di messaggio quando un campo modulo ha il focus e l'utente preme F1. |
|
|  | [getValue()](#getValue--) | Ottiene o imposta il valore del campo modulo, che rappresenta l'ora corrente. |
|
|  | [setValue(Date value)](#setValue-java.util.Date-) | Ottiene o imposta il valore del campo modulo, che rappresenta l'ora corrente. |
|
### CurrentTimeFormField(String stylesheet, String name) {#CurrentTimeFormField-java.lang.String-java.lang.String-}
```
public CurrentTimeFormField(String stylesheet, String name)
```


Inizializza una nuova istanza della classe [CurrentTimeFormField](../../com.groupdocs.editor.words.fieldmanagement/currenttimeformfield) con il foglio di stile e il nome specificati.


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
### getType() {#getType--}
```
public final int getType()
```


Ottiene il tipo del campo modulo, che è sempre FormFieldType.CurrentTime per questa classe.


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
>  currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

La proprietà LocaleId specifica un identificatore di locale (LCID) che corrisponde a una cultura o regione specifica.

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
>  currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

La proprietà LocaleId specifica un identificatore di locale (LCID) che corrisponde a una cultura o regione specifica.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Ottiene o imposta il testo di stato associato al campo modulo, la fonte del testo visualizzato nella barra di stato quando un campo modulo ha il focus..

<br />

*** ** * ** ***

Se impostato su  false , il testo di stato non verrà applicato.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Ottiene o imposta il testo di stato associato al campo modulo, la fonte del testo visualizzato nella barra di stato quando un campo modulo ha il focus..

<br />

*** ** * ** ***

Se impostato su  false , il testo di stato non verrà applicato.

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

Se impostato su  false , il testo di aiuto non verrà applicato.

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

Se impostato su  false , il testo di aiuto non verrà applicato.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final Date getValue()
```


Ottiene o imposta il valore del campo modulo, che rappresenta l'ora corrente.


**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public final void setValue(Date value)
```


Ottiene o imposta il valore del campo modulo, che rappresenta l'ora corrente.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

