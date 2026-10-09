---
title: "SpreadsheetSaveOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti Spreadsheet conformi a Excel"
type: docs
weight: 37
url: /it/nodejs-java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Consente di specificare opzioni personalizzate per la generazione e il salvataggio di Spreadsheet
(conformi a Excel) documenti

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Questo costruttore senza parametri crea una nuova istanza di SpreadsheetSaveOptions con formato di output XLSX (può essere modificato successivamente tramite |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) proprietà)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Crea una nuova istanza di SpreadsheetSaveOptions con il formato obbligatorio specificato |
formato di output Spreadsheet, mentre tutti gli altri parametri sono predefiniti
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPassword()](#getPassword--) | Consente di specificare, modificare, ottenere o rimuovere una password, che sarà |
utilizzato per codificare il documento Spreadsheet generato, se questo formato di documento
supporta la protezione con password.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Consente di specificare, modificare, ottenere o rimuovere una password, che sarà |
utilizzato per codificare il documento Spreadsheet generato, se questo formato di documento
supporta la protezione con password.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | Consente di inserire il foglio di lavoro modificato in una copia del foglio di calcolo esistente |
invece di creare un nuovo foglio di calcolo a singolo foglio (predefinito
comportamento).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Consente di inserire il foglio di lavoro modificato in una copia del foglio di calcolo esistente |
invece di creare un nuovo foglio di calcolo a singolo foglio (predefinito
comportamento).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Flag booleano, che specifica se il foglio di lavoro modificato deve sostituire il |
foglio di lavoro esistente nel foglio di calcolo originale nella posizione, specificata da
il

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
proprietà, o dovrebbe essere inserita tra il foglio di lavoro esistente e
quello precedente, senza sostituirne il contenuto.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Flag booleano, che specifica se il foglio di lavoro modificato deve sostituire il |
foglio di lavoro esistente nel foglio di calcolo originale nella posizione, specificata da
il

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
proprietà, o dovrebbe essere inserita tra il foglio di lavoro esistente e
quello precedente, senza sostituirne il contenuto.
|
|  | [getOutputFormat()](#getOutputFormat--) | Consente di specificare un formato Spreadsheet, che verrà utilizzato per salvare il |
documento
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Consente di specificare un formato Spreadsheet, che verrà utilizzato per salvare il |
documento
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | Consente di abilitare una protezione del foglio di lavoro per lo Spreadsheet di output |
documento.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Consente di abilitare una protezione del foglio di lavoro per lo Spreadsheet di output |
documento.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | Consente di specificare un array con numeri basati su 1 dei fogli di lavoro che devono essere eliminati dallo spreadsheet durante il salvataggio, nel caso in cui il foglio di lavoro modificato sia inserito in uno spreadsheet esistente. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | Consente di specificare un array con numeri basati su 1 dei fogli di lavoro che devono essere eliminati dallo spreadsheet durante il salvataggio, nel caso in cui il foglio di lavoro modificato sia inserito in uno spreadsheet esistente. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Questo costruttore senza parametri crea una nuova istanza di SpreadsheetSaveOptions con formato di output XLSX (può essere modificato successivamente tramite
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) proprietà)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Crea una nuova istanza di SpreadsheetSaveOptions con il formato obbligatorio specificato
formato di output Spreadsheet, mentre tutti gli altri parametri sono predefiniti


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Formato di output obbligatorio, nel quale il documento Spreadsheet deve essere salvato |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Consente di specificare, modificare, ottenere o rimuovere una password, che sarà
utilizzato per codificare il documento Spreadsheet generato, se questo formato di documento
supporta la protezione con password. Specificare NULL o stringa vuota per rimuovere
(pulizia) della password.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Consente di specificare, modificare, ottenere o rimuovere una password, che sarà
utilizzato per codificare il documento Spreadsheet generato, se questo formato di documento
supporta la protezione con password. Specificare NULL o stringa vuota per rimuovere
(pulizia) della password.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


Consente di inserire il foglio di lavoro modificato in una copia del foglio di calcolo esistente
invece di creare un nuovo foglio di calcolo a singolo foglio (predefinito
comportamento). WorksheetNumber è un numero basato su 1 di un foglio di lavoro nel
spreadsheet, caricato nella classe Editor. Se è 0 (valore predefinito), il
nuovo spreadsheet verrà creato con un singolo foglio di lavoro modificato. Se è
maggiore o minore di zero, e c'è uno spreadsheet valido, caricato in
la classe Editor, il foglio di lavoro modificato, che è rappresentato dall'input
istanza di EditableDocument, verrà inserito in questo spreadsheet.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


Consente di inserire il foglio di lavoro modificato in una copia del foglio di calcolo esistente
invece di creare un nuovo foglio di calcolo a singolo foglio (predefinito
comportamento). WorksheetNumber è un numero basato su 1 di un foglio di lavoro nel
spreadsheet, caricato nella classe Editor. Se è 0 (valore predefinito), il
nuovo spreadsheet verrà creato con un singolo foglio di lavoro modificato. Se è
maggiore o minore di zero, e c'è uno spreadsheet valido, caricato in
la classe Editor, il foglio di lavoro modificato, che è rappresentato dall'input
istanza di EditableDocument, verrà inserito in questo spreadsheet.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


Flag booleano, che specifica se il foglio di lavoro modificato deve sostituire il
foglio di lavoro esistente nel foglio di calcolo originale nella posizione, specificata da
il

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
proprietà, o dovrebbe essere inserita tra il foglio di lavoro esistente e
quello precedente, senza sostituirne il contenuto. Per impostazione predefinita è false \\u2014
il foglio di lavoro esistente sarà sostituito. Questa proprietà è ignorata, se il valore
di

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
la proprietà è impostata a '0'.


*** ** * ** ***

Per impostazione predefinita il foglio di lavoro è sostituito. Ciò significa che se lo spreadsheet fornito ha 5 fogli di lavoro, e WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, allora il 4° foglio di lavoro sarà sostituito con il nuovo foglio di lavoro modificato, mentre il numero totale di fogli di lavoro nello spreadsheet (5) rimarrà invariato. Tuttavia, se il valore di questa proprietà è impostato a  *true* , il nuovo foglio di lavoro modificato sarà inserito come 4° foglio di lavoro, e tutti i fogli di lavoro successivi saranno spostati alla fine: "old" 4° diventa 5°, e il 5° diventa 6°, e il numero totale di fogli di lavoro nello spreadsheet sarà incrementato di uno e sarà pari a 6.

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Flag booleano, che specifica se il foglio di lavoro modificato deve sostituire il
foglio di lavoro esistente nel foglio di calcolo originale nella posizione, specificata da
il

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
proprietà, o dovrebbe essere inserita tra il foglio di lavoro esistente e
quello precedente, senza sostituirne il contenuto. Per impostazione predefinita è false \\u2014
il foglio di lavoro esistente sarà sostituito. Questa proprietà è ignorata, se il valore
di

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
la proprietà è impostata a '0'.


*** ** * ** ***

Per impostazione predefinita il foglio di lavoro è sostituito. Ciò significa che se lo spreadsheet fornito ha 5 fogli di lavoro, e WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, allora il 4° foglio di lavoro sarà sostituito con il nuovo foglio di lavoro modificato, mentre il numero totale di fogli di lavoro nello spreadsheet (5) rimarrà invariato. Tuttavia, se il valore di questa proprietà è impostato a  *true* , il nuovo foglio di lavoro modificato sarà inserito come 4° foglio di lavoro, e tutti i fogli di lavoro successivi saranno spostati alla fine: "old" 4° diventa 5°, e il 5° diventa 6°, e il numero totale di fogli di lavoro nello spreadsheet sarà incrementato di uno e sarà pari a 6.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Consente di specificare un formato Spreadsheet, che verrà utilizzato per salvare il
documento


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Consente di specificare un formato Spreadsheet, che verrà utilizzato per salvare il
documento


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Consente di abilitare una protezione del foglio di lavoro per lo Spreadsheet di output
documento. Per impostazione predefinita è NULL - la protezione non è applicata. Non tutti i formati
supportano una protezione del foglio di lavoro.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Consente di abilitare una protezione del foglio di lavoro per lo Spreadsheet di output
documento. Per impostazione predefinita è NULL - la protezione non è applicata. Non tutti i formati
supportano una protezione del foglio di lavoro.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


Consente di specificare un array con numeri basati su 1 dei fogli di lavoro che devono essere eliminati dallo spreadsheet durante il salvataggio, nel caso in cui il foglio di lavoro modificato sia inserito in uno spreadsheet esistente. Quando il foglio di lavoro modificato viene salvato non come un nuovo spreadsheet a foglio singolo (comportamento predefinito), ma invece viene salvato in uno spreadsheet esistente (utilizzando #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int)), è anche possibile eliminare alcuni fogli di lavoro particolari da questo spreadsheet specificando i loro numeri in questo array. Per impostazione predefinita questo array è  null  \\u2014 nessun foglio di lavoro sarà eliminato. Tuttavia, quando questo array è non-null e non vuoto, e contiene almeno un numero di foglio di lavoro valido, dopo che il documento spreadsheet di output è generato con il contenuto del foglio di lavoro modificato, i fogli di lavoro con i numeri specificati saranno eliminati dallo spreadsheet subito prima di scrivere il suo contenuto nello stream di output o nel file. I numeri dei fogli di lavoro in questo array sono basati su 1, non su 0. I numeri non validi (meno di 1 o maggiori del numero totale di fogli di lavoro) saranno ignorati.


**Returns:**
int[] - Array di numeri di foglio di lavoro basati su 1 da eliminare, o  null  se non deve essere eliminato nulla.

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


Consente di specificare un array con numeri basati su 1 dei fogli di lavoro che devono essere eliminati dal foglio di calcolo durante il salvataggio, nel caso in cui il foglio di lavoro modificato venga inserito in un foglio di calcolo esistente. I numeri dei fogli di lavoro in questo array sono basati su 1. I numeri non validi verranno ignorati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int[] | Array di numeri di foglio di lavoro basati su 1 da eliminare (può essere  null  o vuoto). |
|

