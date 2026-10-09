---
title: "PresentationSaveOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti Presentation compatibili con PowerPoint"
type: docs
weight: 34
url: /it/nodejs-java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Consente di specificare opzioni personalizzate per la generazione e il salvataggio di Presentation
(compatibili con PowerPoint) documenti

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Questo costruttore senza parametri crea una nuova istanza di PresentationSaveOptions con formato di output PPTX (può essere modificato successivamente tramite |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Crea una nuova istanza di PresentationSaveOptions con specificato |
formato di output Presentation obbligatorio, mentre tutti gli altri parametri sono
predefinito
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPassword()](#getPassword--) | Consente di specificare, modificare e ottenere la password, che sarà utilizzata per |
codificando il documento Presentation risultante.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Consente di specificare, modificare e ottenere la password, che sarà utilizzata per codificare il documento Presentation risultante. |
|
|  | [getSlideNumber()](#getSlideNumber--) | Consente di inserire la diapositiva modificata nella presentazione esistente invece di creare una nuova presentazione a diapositiva singola (comportamento predefinito). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Consente di inserire la diapositiva modificata nella presentazione esistente invece di creare una nuova presentazione a diapositiva singola (comportamento predefinito). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Flag booleano, che specifica se la diapositiva modificata deve sostituire la diapositiva esistente nella presentazione originale nella posizione specificata da |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) property, oppure dovrebbe essere inserita tra la diapositiva esistente e quella precedente, senza sostituirne il contenuto.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Flag booleano, che specifica se la diapositiva modificata deve sostituire la diapositiva esistente nella presentazione originale nella posizione specificata da |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) property, oppure dovrebbe essere inserita tra la diapositiva esistente e quella precedente, senza sostituirne il contenuto.
|
|  | [getOutputFormat()](#getOutputFormat--) | Consente di specificare un formato Presentation, che sarà utilizzato per salvare il documento |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Consente di specificare un formato Presentation, che sarà utilizzato per salvare il documento |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Consente di specificare un array con numeri diapositive basati su 1 che devono essere eliminati dalla presentazione durante il salvataggio, nel caso in cui la diapositiva modificata venga inserita nella presentazione esistente. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Consente di specificare un array con numeri diapositive basati su 1 che devono essere eliminati dalla presentazione durante il salvataggio, nel caso in cui la diapositiva modificata venga inserita nella presentazione esistente. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Questo costruttore senza parametri crea una nuova istanza di PresentationSaveOptions con formato di output PPTX (può essere modificato successivamente tramite
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Crea una nuova istanza di PresentationSaveOptions con specificato
formato di output Presentation obbligatorio, mentre tutti gli altri parametri sono
predefinito


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Formato di output obbligatorio, nel quale il documento Presentation deve essere salvato |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Consente di specificare, modificare e ottenere la password, che sarà utilizzata per
codificando il documento Presentation risultante. Per impostazione predefinita è NULL -
la password non verrà impostata. Impostare su NULL o stringa vuota per rimuovere
la password, se era stata impostata in precedenza.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Consente di specificare, modificare e ottenere la password, che sarà utilizzata per codificare il documento Presentation risultante.
Per impostazione predefinita è NULL - la password non verrà impostata. Impostala su NULL o su una stringa vuota per rimuovere la password, se era stata impostata in precedenza.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Consente di inserire la diapositiva modificata nella presentazione esistente invece di creare una nuova presentazione a diapositiva singola (comportamento predefinito).
Il numero della diapositiva è un numero basato su 1 di una diapositiva nella presentazione, caricata nella classe Editor. Se è 0 (valore predefinito), la nuova presentazione verrà creata con una singola diapositiva modificata. Se è maggiore o minore di zero, e c'è una presentazione valida, caricata nella classe Editor, la diapositiva modificata, memorizzata all'interno dell'istanza input EditableDocument, verrà inserita in questa presentazione.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Consente di inserire la diapositiva modificata nella presentazione esistente invece di creare una nuova presentazione a diapositiva singola (comportamento predefinito).
Il numero della diapositiva è un numero basato su 1 di una diapositiva nella presentazione, caricata nella classe Editor. Se è 0 (valore predefinito), la nuova presentazione verrà creata con una singola diapositiva modificata. Se è maggiore o minore di zero, e c'è una presentazione valida, caricata nella classe Editor, la diapositiva modificata, memorizzata all'interno dell'istanza input EditableDocument, verrà inserita in questa presentazione.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


Flag booleano, che specifica se la diapositiva modificata deve sostituire la diapositiva esistente nella presentazione originale nella posizione specificata da
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) property, oppure dovrebbe essere inserita tra la diapositiva esistente e quella precedente, senza sostituirne il contenuto.
Per impostazione predefinita è false — la diapositiva esistente verrà sostituita. Questa proprietà è ignorata, se il valore di
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) la proprietà è impostata a '0'.

<br />

*** ** * ** ***

Per impostazione predefinita la diapositiva viene sostituita. Questo significa che se la presentazione fornita ha 5 diapositive, e SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, allora la quarta diapositiva sarà sostituita con la nuova diapositiva modificata, mentre il numero totale di diapositive nella presentazione (5) rimarrà invariato. Tuttavia, se il valore di questa proprietà è impostato a *true*, la nuova diapositiva modificata verrà inserita come quarta diapositiva, e tutte le diapositive successive saranno spostate verso la fine: la vecchia quarta diapositiva diventa quinta, e la quinta diventa sesta, e il numero totale di diapositive nella presentazione sarà incrementato di uno e sarà pari a 6.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Flag booleano, che specifica se la diapositiva modificata deve sostituire la diapositiva esistente nella presentazione originale nella posizione specificata da
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) property, oppure dovrebbe essere inserita tra la diapositiva esistente e quella precedente, senza sostituirne il contenuto.
Per impostazione predefinita è false — la diapositiva esistente verrà sostituita. Questa proprietà è ignorata, se il valore di
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) la proprietà è impostata a '0'.

<br />

*** ** * ** ***

Per impostazione predefinita la diapositiva viene sostituita. Questo significa che se la presentazione fornita ha 5 diapositive, e SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, allora la quarta diapositiva sarà sostituita con la nuova diapositiva modificata, mentre il numero totale di diapositive nella presentazione (5) rimarrà invariato. Tuttavia, se il valore di questa proprietà è impostato a *true*, la nuova diapositiva modificata verrà inserita come quarta diapositiva, e tutte le diapositive successive saranno spostate verso la fine: la vecchia quarta diapositiva diventa quinta, e la quinta diventa sesta, e il numero totale di diapositive nella presentazione sarà incrementato di uno e sarà pari a 6.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Consente di specificare un formato Presentation, che sarà utilizzato per salvare il documento

<br />

*** ** * ** ***

Il formato di output è solitamente impostato nel costruttore di questa classe, perché è obbligatorio. Questa proprietà consente di ottenere o modificare il formato di output in seguito, quando l'istanza della classe [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) è già stata creata.

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


Consente di specificare un formato Presentation, che sarà utilizzato per salvare il documento

<br />

*** ** * ** ***

Il formato di output è solitamente impostato nel costruttore di questa classe, perché è obbligatorio. Questa proprietà consente di ottenere o modificare il formato di output in seguito, quando l'istanza della classe [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) è già stata creata.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


Consente di specificare un array con numeri diapositive basati su 1 che devono essere eliminati dalla presentazione durante il salvataggio, nel caso in cui la diapositiva modificata venga inserita in una presentazione esistente. Quando la diapositiva modificata viene salvata non come una nuova presentazione a diapositiva singola (comportamento predefinito), ma invece viene salvata in una presentazione esistente (utilizzando #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int)), è anche possibile eliminare alcune diapositive specifiche da questa presentazione specificando i loro numeri in questo array. Per impostazione predefinita questo array è null — nessuna diapositiva verrà eliminata. Tuttavia, quando questo array è non null e non vuoto, e contiene almeno un numero di diapositiva valido, dopo che il documento Presentation di output è stato generato con il contenuto della diapositiva modificata, le diapositive con i numeri specificati saranno eliminate dalla presentazione subito prima di scrivere il suo contenuto nello stream di output o nel file. I numeri delle diapositive in questo array sono basati su 1, non su 0. I numeri non validi (meno di 1 o superiori al numero totale di diapositive) saranno ignorati.


**Returns:**
int[] - Array di numeri diapositive basati su 1 da eliminare, o null se non deve essere eliminato nulla.

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Consente di specificare un array con numeri diapositive basati su 1 che devono essere eliminati dalla presentazione durante il salvataggio, nel caso in cui la diapositiva modificata venga inserita in una presentazione esistente. I numeri delle diapositive in questo array sono basati su 1. I numeri non validi saranno ignorati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int[] | Array di numeri diapositive basati su 1 da eliminare (può essere null o vuoto). |
|

