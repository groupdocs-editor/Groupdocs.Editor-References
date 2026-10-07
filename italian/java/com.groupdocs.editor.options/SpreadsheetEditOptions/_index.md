---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Consente di specificare opzioni personalizzate per la modifica dei documenti di tutti i formati di foglio di calcolo compatibili con Excel supportati"
type: docs
weight: 35
url: /it/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Consente di specificare opzioni personalizzate per la modifica di tutti i documenti supportati
Formati di foglio di calcolo (compatibili con Excel)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Consente di specificare l'indice basato su zero del foglio di lavoro (scheda) di input |
Documento di foglio di calcolo, che deve essere convertito in HTML (vedi
note).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Consente di specificare l'indice basato su zero del foglio di lavoro (scheda) di input |
Documento di foglio di calcolo, che deve essere convertito in HTML (vedi
note).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Consente di escludere i fogli di lavoro nascosti nel documento di foglio di calcolo di input, così |
verranno completamente ignorati.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Consente di escludere i fogli di lavoro nascosti nel documento di foglio di calcolo di input, così |
verranno completamente ignorati.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | Quando abilitato, le celle orizzontali vuote adiacenti del documento di foglio di calcolo di input saranno |
rappresentate nel documento HTML modificabile come unite in un'unica cella con il corrispondente
attributo colspan.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | Quando abilitato, la tabella HTML nel documento HTML prodotto contiene una riga nascosta vuota in fondo con |
altezza zero e celle vuote, dove è specificata solo la larghezza.
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Consente di specificare l'indice basato su zero del foglio di lavoro (scheda) di input
Documento di foglio di calcolo, che deve essere convertito in HTML (vedi
note).


*** ** * ** ***

La maggior parte dei documenti di foglio di calcolo supporta il concetto di schede, cioè possono avere più schede. D'altra parte, il formato HTML non supporta tale struttura. Per questo motivo GroupDocs.Editor può convertire in HTML solo una scheda specifica del documento di input, e questa opzione consente di specificarla. L'indice della scheda è basato su zero, i valori negativi sono proibiti. Se l'indice specificato supera il numero di tutte le schede, verrà generata un'eccezione. Se il documento di foglio di calcolo di input contiene una sola scheda, questa opzione verrà ignorata. Il valore predefinito è 0 (prima scheda).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Consente di specificare l'indice basato su zero del foglio di lavoro (scheda) di input
Documento di foglio di calcolo, che deve essere convertito in HTML (vedi
note).


*** ** * ** ***

La maggior parte dei documenti di foglio di calcolo supporta il concetto di schede, cioè possono avere più schede. D'altra parte, il formato HTML non supporta tale struttura. Per questo motivo GroupDocs.Editor può convertire in HTML solo una scheda specifica del documento di input, e questa opzione consente di specificarla. L'indice della scheda è basato su zero, i valori negativi sono proibiti. Se l'indice specificato supera il numero di tutte le schede, verrà generata un'eccezione. Se il documento di foglio di calcolo di input contiene una sola scheda, questa opzione verrà ignorata. Il valore predefinito è 0 (prima scheda).

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Consente di escludere i fogli di lavoro nascosti nel documento di foglio di calcolo di input, così
verranno completamente ignorati. Il valore predefinito è false - i fogli di lavoro nascosti sono
disponibili e processati normalmente.


*** ** * ** ***

Diversi formati binari di foglio di calcolo (come XLSX) supportano il concetto di fogli di lavoro nascosti (schede). Un documento di tale formato, se contiene più di un foglio di lavoro, può contenere fogli di lavoro nascosti aggiuntivi. Per impostazione predefinita questi fogli di lavoro nascosti sono disponibili per l'elaborazione, ma con questa opzione è possibile ignorarli, come se fossero assenti e non esistessero. Quando questa opzione è abilitata, non è possibile selezionare un foglio di lavoro nascosto con la proprietà ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Consente di escludere i fogli di lavoro nascosti nel documento di foglio di calcolo di input, così
verranno completamente ignorati. Il valore predefinito è false - i fogli di lavoro nascosti sono
disponibili e processati normalmente.


*** ** * ** ***

Diversi formati binari di foglio di calcolo (come XLSX) supportano il concetto di fogli di lavoro nascosti (schede). Un documento di tale formato, se contiene più di un foglio di lavoro, può contenere fogli di lavoro nascosti aggiuntivi. Per impostazione predefinita questi fogli di lavoro nascosti sono disponibili per l'elaborazione, ma con questa opzione è possibile ignorarli, come se fossero assenti e non esistessero. Quando questa opzione è abilitata, non è possibile selezionare un foglio di lavoro nascosto con la proprietà ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


Quando abilitato, le celle orizzontali vuote adiacenti del documento di foglio di calcolo di input saranno
rappresentate nel documento HTML modificabile come unite in un'unica cella con il corrispondente
attributo colspan. Per impostazione predefinita è disabilitato (false).


Per impostazione predefinita GroupDocs.Editor converte una tabella dal documento di foglio di calcolo di input all'output
documento HTML preservando ogni cella. Tuttavia, i documenti di foglio di calcolo possono essere sparsi \\\\u2014 essi
possono contenere una grande quantità di "empty areas", dove molte celle sono vuote. Questa opzione, quando
abilitata, unisce tali celle vuote in una sola con l'attributo colspan nell'elemento TD,
e quindi può ridurre significativamente le dimensioni del markup HTML prodotto.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


Quando abilitato, la tabella HTML nel documento HTML prodotto contiene una riga nascosta vuota in fondo con
altezza zero e celle vuote, dove è specificata solo la larghezza. Questa riga con celle vuote contiene
valori di larghezza esatti per ogni colonna e migliora la conversione inversa da HTML a Spreadsheet. Per
il valore predefinito è abilitato (true).


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

