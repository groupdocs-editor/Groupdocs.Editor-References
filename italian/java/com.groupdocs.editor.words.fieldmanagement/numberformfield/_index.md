---
title: "NumberFormField"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta un campo modulo che accetta un input numerico."
type: docs
weight: 19
url: /it/java/com.groupdocs.editor.words.fieldmanagement/numberformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class NumberFormField implements IFormField
```

Rappresenta un campo modulo che accetta un input numerico.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [NumberFormField(String stylesheet, String name)](#NumberFormField-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe [NumberFormField](../../com.groupdocs.editor.words.fieldmanagement/numberformfield) con il foglio di stile e il nome specificati. |
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
|  | [getType()](#getType--) | Ottiene il tipo del campo modulo, che è sempre FormFieldType.Number per questa classe. |
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
|  | [getValue()](#getValue--) | Ottiene o imposta il valore del campo modulo, che rappresenta un numero. |
|
|  | [setValue(float value)](#setValue-float-) | Ottiene o imposta il valore del campo modulo, che rappresenta un numero. |
|
|  | [getMaxLength()](#getMaxLength--) | Ottiene o imposta la lunghezza massima dell'input per il campo modulo. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | Ottiene o imposta la lunghezza massima dell'input per il campo modulo. |
|
### NumberFormField(String stylesheet, String name) {#NumberFormField-java.lang.String-java.lang.String-}
```
public NumberFormField(String stylesheet, String name)
```


Inizializza una nuova istanza della classe [NumberFormField](../../com.groupdocs.editor.words.fieldmanagement/numberformfield) con il foglio di stile e il nome specificati.


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


Ottiene il tipo del campo modulo, che è sempre FormFieldType.Number per questa classe.


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
>  numberField.LocaleId = new CultureInfo("en-US").LCID;
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
>  numberField.LocaleId = new CultureInfo("en-US").LCID;
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
public final float getValue()
```


Ottiene o imposta il valore del campo modulo, che rappresenta un numero.


**Returns:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```


Ottiene o imposta il valore del campo modulo, che rappresenta un numero.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


Ottiene o imposta la lunghezza massima dell'input per il campo modulo.


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


Ottiene o imposta la lunghezza massima dell'input per il campo modulo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

