---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Opzioni per il caricamento di documenti Spreadsheet basati su testo CSV, basati su tabulazione ecc. che utilizzano un separatore delimitatore"
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Opzioni per il caricamento di documenti Spreadsheet basati su testo (CSV, basati su tabulazione ecc.),
che utilizzano un separatore (delimitatore)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Crea un'istanza della classe di opzioni per testo delimitato con obbligatorio |
separatore (delimitatore)
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Consente di specificare un separatore di stringa (delimitatore) per basati su testo |
documenti Spreadsheet
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Consente di specificare un separatore di stringa (delimitatore) per basati su testo |
documenti Spreadsheet
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Ottiene o imposta un valore che indica se la stringa nei documenti basati su testo |
viene convertita in dati data.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Ottiene o imposta un valore che indica se la stringa nei documenti basati su testo |
viene convertita in dati data.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Ottiene o imposta un valore che indica se la stringa nei documenti basati su testo |
viene convertita in dati numerici.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Ottiene o imposta un valore che indica se la stringa nei documenti basati su testo |
viene convertita in dati numerici.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Definisce se i delimitatori consecutivi devono essere trattati come uno solo. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Definisce se i delimitatori consecutivi devono essere trattati come uno solo. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Abilita meccanismi di ottimizzazione della memoria durante l'elaborazione del documento di input, |
che possono degradare le prestazioni in alcuni casi speciali, ma dall'altro
riduce manualmente l'utilizzo della memoria.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Abilita meccanismi di ottimizzazione della memoria durante l'elaborazione del documento di input, |
che possono degradare le prestazioni in alcuni casi speciali, ma dall'altro
riduce manualmente l'utilizzo della memoria.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Crea un'istanza della classe di opzioni per testo delimitato con obbligatorio
separatore (delimitatore)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | separatore | java.lang.String | Separatore obbligatorio (delimitatore), che non può essere NULL o vuoto |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Consente di specificare un separatore di stringa (delimitatore) per basati su testo
documenti Spreadsheet


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Consente di specificare un separatore di stringa (delimitatore) per basati su testo
documenti Spreadsheet


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Ottiene o imposta un valore che indica se la stringa nei documenti basati su testo
Il documento viene convertito in dati di tipo data. Il valore predefinito è false.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Ottiene o imposta un valore che indica se la stringa nei documenti basati su testo
Il documento viene convertito in dati di tipo data. Il valore predefinito è false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Ottiene o imposta un valore che indica se la stringa nei documenti basati su testo
Il documento viene convertito in dati numerici. Il valore predefinito è false.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Ottiene o imposta un valore che indica se la stringa nei documenti basati su testo
Il documento viene convertito in dati numerici. Il valore predefinito è false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Definisce se i delimitatori consecutivi devono essere trattati come uno. Per
Il valore predefinito è false.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Definisce se i delimitatori consecutivi devono essere trattati come uno. Per
Il valore predefinito è false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Abilita meccanismi di ottimizzazione della memoria durante l'elaborazione del documento di input,
che possono degradare le prestazioni in alcuni casi speciali, ma dall'altro
riduce manualmente l'utilizzo della memoria. Utile durante l'elaborazione di documenti enormi e
di fronte a OutOfMemoryException. Il valore predefinito è false (l'ottimizzazione della memoria è
disabilitata per garantire migliori prestazioni).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Abilita meccanismi di ottimizzazione della memoria durante l'elaborazione del documento di input,
che possono degradare le prestazioni in alcuni casi speciali, ma dall'altro
riduce manualmente l'utilizzo della memoria. Utile durante l'elaborazione di documenti enormi e
di fronte a OutOfMemoryException. Il valore predefinito è false (l'ottimizzazione della memoria è
disabilitata per garantire migliori prestazioni).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

