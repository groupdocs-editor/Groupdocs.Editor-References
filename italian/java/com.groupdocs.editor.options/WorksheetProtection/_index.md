---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Incapsula le opzioni di protezione del foglio di lavoro che consentono di proteggere un foglio di lavoro nel documento Spreadsheet di output dalla modifica di tipo specificato con una password specificata."
type: docs
weight: 49
url: /it/java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

Incapsula le opzioni di protezione del foglio di lavoro, che consentono di proteggere un foglio di lavoro
nel documento Spreadsheet di output dalla modifica di tipo specificato con una
password specificata.


*** ** * ** ***

La maggior parte dei formati Spreadsheet come XLSX consente di proteggere un foglio di lavoro dalla modifica con password. Questa classe consente di abilitare tale protezione e specificarne le opzioni.

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | Crea una nuova istanza con i parametri predefiniti. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | Crea una nuova istanza con il tipo di protezione del foglio di lavoro specificato e |
password
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Consente di specificare un tipo di protezione del foglio di lavoro. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Consente di specificare un tipo di protezione del foglio di lavoro. |
|
|  | [getPassword()](#getPassword--) | Password, che viene utilizzata per proteggere un foglio di lavoro. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Password, che viene utilizzata per proteggere un foglio di lavoro. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


Crea una nuova istanza con i parametri predefiniti. Se non modificato e passato
a SpreadsheetSaveOptions, non verrà applicata alcuna protezione del foglio di lavoro


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


Crea una nuova istanza con il tipo di protezione del foglio di lavoro specificato e
password


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | protectionType | int | Tipo di protezione del foglio di lavoro |
|
|  | password | java.lang.String | Password, che blocca la protezione |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Consente di specificare un tipo di protezione del foglio di lavoro. Per impostazione predefinita è 'None' -
la protezione non viene applicata.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Consente di specificare un tipo di protezione del foglio di lavoro. Per impostazione predefinita è 'None' -
la protezione non viene applicata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Password, che viene utilizzata per proteggere un foglio di lavoro. Se NULL o stringa vuota
la protezione non verrà applicata.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Password, che viene utilizzata per proteggere un foglio di lavoro. Se NULL o stringa vuota
la protezione non verrà applicata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

