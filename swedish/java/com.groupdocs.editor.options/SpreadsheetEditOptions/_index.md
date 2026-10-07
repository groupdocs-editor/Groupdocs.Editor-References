---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade kalkylbladsformat som är Excel-kompatibla"
type: docs
weight: 35
url: /sv/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade
Kalkylblad (Excel-kompatibla) format

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Tillåter att ange det nollbaserade indexet för kalkylbladet (fliken) i indata |
Kalkylbladsdokument som ska konverteras till HTML (se
anmärkningar).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Tillåter att ange det nollbaserade indexet för kalkylbladet (fliken) i indata |
Kalkylbladsdokument som ska konverteras till HTML (se
anmärkningar).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Tillåter att utesluta dolda arbetsblad i inmatningskalkylbladsdokumentet, så |
de kommer att ignoreras helt.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Tillåter att utesluta dolda arbetsblad i inmatningskalkylbladsdokumentet, så |
de kommer att ignoreras helt.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | När den är aktiverad kommer de tomma intilliggande horisontella cellerna från inmatningskalkylbladsdokumentet att |
representeras i ett redigerbart HTML-dokument som sammanslagna till en enda cell med motsvarande
colspan-attribut.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | När den är aktiverad innehåller HTML-tabellen i det genererade HTML-dokumentet en tom dold rad längst ner med |
nollhöjd och tomma celler, där endast bredd är angiven.
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


Tillåter att ange det nollbaserade indexet för kalkylbladet (fliken) i indata
Kalkylbladsdokument som ska konverteras till HTML (se
anmärkningar).


*** ** * ** ***

De flesta kalkylbladsdokument stödjer ett flikkoncept, dvs. de kan ha flera flikar. Å andra sidan stöder HTML-formatet inte en sådan struktur. På grund av detta kan GroupDocs.Editor konvertera till HTML endast en specifik flik i inmatningsdokumentet, och detta alternativ låter dig ange den. Flikindex är nollbaserat, negativa värden är förbjudna. Om det angivna indexet överstiger antalet flikar kastas ett undantag. Om inmatningskalkylbladsdokumentet bara har en flik ignoreras detta alternativ. Standardvärdet är 0 (första fliken).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Tillåter att ange det nollbaserade indexet för kalkylbladet (fliken) i indata
Kalkylbladsdokument som ska konverteras till HTML (se
anmärkningar).


*** ** * ** ***

De flesta kalkylbladsdokument stödjer ett flikkoncept, dvs. de kan ha flera flikar. Å andra sidan stöder HTML-formatet inte en sådan struktur. På grund av detta kan GroupDocs.Editor konvertera till HTML endast en specifik flik i inmatningsdokumentet, och detta alternativ låter dig ange den. Flikindex är nollbaserat, negativa värden är förbjudna. Om det angivna indexet överstiger antalet flikar kastas ett undantag. Om inmatningskalkylbladsdokumentet bara har en flik ignoreras detta alternativ. Standardvärdet är 0 (första fliken).

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Tillåter att utesluta dolda arbetsblad i inmatningskalkylbladsdokumentet, så
de kommer att ignoreras helt. Standard är falskt – dolda arbetsblad är
tillgängliga och behandlas som vanligt.


*** ** * ** ***

Flera binära kalkylbladsformat (som XLSX) stödjer konceptet med dolda arbetsblad (flikar). Dokument av sådant format, om det har mer än ett arbetsblad, kan innehålla ytterligare dolda arbetsblad. Som standard är sådana dolda arbetsblad tillgängliga för bearbetning, men med detta alternativ kan de ignoreras, som om de dolda arbetsbladen saknas och inte existerar. När detta alternativ är aktiverat kan du inte välja ett dolt arbetsblad med egenskapen ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Tillåter att utesluta dolda arbetsblad i inmatningskalkylbladsdokumentet, så
de kommer att ignoreras helt. Standard är falskt – dolda arbetsblad är
tillgängliga och behandlas som vanligt.


*** ** * ** ***

Flera binära kalkylbladsformat (som XLSX) stödjer konceptet med dolda arbetsblad (flikar). Dokument av sådant format, om det har mer än ett arbetsblad, kan innehålla ytterligare dolda arbetsblad. Som standard är sådana dolda arbetsblad tillgängliga för bearbetning, men med detta alternativ kan de ignoreras, som om de dolda arbetsbladen saknas och inte existerar. När detta alternativ är aktiverat kan du inte välja ett dolt arbetsblad med egenskapen ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


När den är aktiverad kommer de tomma intilliggande horisontella cellerna från inmatningskalkylbladsdokumentet att
representeras i ett redigerbart HTML-dokument som sammanslagna till en enda cell med motsvarande
colspan-attribut. Som standard är den inaktiverad (falskt).


Som standard konverterar GroupDocs.Editor en tabell från inmatningskalkylbladsdokumentet till
HTML-dokumentet genom att bevara varje cell. Dock kan kalkylbladsdokumenten vara glesa \u2014 de
kan innehålla en enorm mängd "empty areas", där många celler är tomma. Detta alternativ, när
aktiverat, slår samman sådana tomma celler till en med colspan-attribut i TD-elementet,
och kan därmed avsevärt minska storleken på den genererade HTML-markupen.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


När den är aktiverad innehåller HTML-tabellen i det genererade HTML-dokumentet en tom dold rad längst ner med
nollhöjd och tomma celler, där endast bredd är angiven. Denna rad med tomma celler innehåller
exakta breddvärden för varje kolumn och förbättrar bakåtkonvertering från HTML till kalkylblad. Genom
standard är aktiverad (sant).


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

