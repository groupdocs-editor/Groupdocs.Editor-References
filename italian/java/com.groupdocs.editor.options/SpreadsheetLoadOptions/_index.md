---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Contiene le opzioni per caricare documenti binari Spreadsheet Cells compatibili con Excel, come XLSX, ODS, ecc."
type: docs
weight: 36
url: /it/java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

Contiene le opzioni per caricare Spreadsheet binario (Cells, compatibile con Excel)
documenti come XLS(X), ODS, ecc. nella classe Editor

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Costruttore predefinito senza parametri - tutti i parametri hanno valori predefiniti |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPassword()](#getPassword--) | Consente di specificare, modificare e ottenere la password, che verrà utilizzata per |
apertura del documento Spreadsheet, se è codificato.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Consente di specificare, modificare e ottenere la password, che verrà utilizzata per |
apertura del documento Spreadsheet, se è codificato.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Abilita meccanismi di ottimizzazione della memoria durante l'elaborazione del documento di input, |
che possono degradare le prestazioni in alcuni casi speciali, ma dall'altro
riduce manualmente l'utilizzo della memoria.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Abilita meccanismi di ottimizzazione della memoria durante l'elaborazione del documento di input, |
che possono degradare le prestazioni in alcuni casi speciali, ma dall'altro
riduce manualmente l'utilizzo della memoria.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Costruttore predefinito senza parametri - tutti i parametri hanno valori predefiniti


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Consente di specificare, modificare e ottenere la password, che verrà utilizzata per
apertura del documento Spreadsheet, se è codificato. Impostare a NULL o vuoto
stringa per non utilizzare la password (valore predefinito).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Consente di specificare, modificare e ottenere la password, che verrà utilizzata per
apertura del documento Spreadsheet, se è codificato. Impostare a NULL o vuoto
stringa per non utilizzare la password (valore predefinito).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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

