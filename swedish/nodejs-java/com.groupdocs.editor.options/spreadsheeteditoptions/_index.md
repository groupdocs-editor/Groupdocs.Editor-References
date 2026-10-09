---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade Spreadsheet Excel-kompatibla format"
type: docs
weight: 35
url: /sv/nodejs-java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade
Kalkylbladsformat (Excel-kompatibla)

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Tillåter att ange det nollbaserade indexet för kalkylbladet (flik) i indata |
Kalkylbladsdokument som ska konverteras till HTML (se
anmärkningar).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Tillåter att ange det nollbaserade indexet för kalkylbladet (flik) i indata |
Kalkylbladsdokument som ska konverteras till HTML (se
anmärkningar).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Tillåter att utesluta dolda kalkylblad i indata-kalkylbladsdokumentet, så |
de kommer att ignoreras helt.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Tillåter att utesluta dolda kalkylblad i indata-kalkylbladsdokumentet, så |
de kommer att ignoreras helt.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | När den är aktiverad kommer de tomma intilliggande horisontella cellerna från indata-kalkylbladsdokumentet att |
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


Tillåter att ange det nollbaserade indexet för kalkylbladet (flik) i indata
Kalkylbladsdokument som ska konverteras till HTML (se
anmärkningar).


*** ** * ** ***

De flesta kalkylbladsdokument stödjer konceptet flikar, d.v.s. de kan ha flera flikar. Å andra sidan stöder HTML-formatet inte en sådan struktur. På grund av detta kan GroupDocs.Editor konvertera till HTML endast en specifik flik i indata-dokumentet, och detta alternativ gör det möjligt att ange den. Flikindex är nollbaserat, negativa värden är förbjudna. Om det angivna indexet överstiger antalet flikar kastas ett undantag. Om indata-kalkylbladsdokumentet bara innehåller en flik ignoreras detta alternativ. Standardvärdet är 0 (första fliken).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Tillåter att ange det nollbaserade indexet för kalkylbladet (flik) i indata
Kalkylbladsdokument som ska konverteras till HTML (se
anmärkningar).


*** ** * ** ***

De flesta kalkylbladsdokument stödjer konceptet flikar, d.v.s. de kan ha flera flikar. Å andra sidan stöder HTML-formatet inte en sådan struktur. På grund av detta kan GroupDocs.Editor konvertera till HTML endast en specifik flik i indata-dokumentet, och detta alternativ gör det möjligt att ange den. Flikindex är nollbaserat, negativa värden är förbjudna. Om det angivna indexet överstiger antalet flikar kastas ett undantag. Om indata-kalkylbladsdokumentet bara innehåller en flik ignoreras detta alternativ. Standardvärdet är 0 (första fliken).

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Tillåter att utesluta dolda kalkylblad i indata-kalkylbladsdokumentet, så
de kommer att ignoreras helt. Standard är falskt - dolda kalkylblad är
tillgängliga och behandlas som vanligt.


*** ** * ** ***

Flera binära kalkylbladsformat (som XLSX) stödjer konceptet dolda kalkylblad (flikar). Dokument av sådant format, om det har mer än ett kalkylblad, kan innehålla ytterligare dolda kalkylblad. Som standard är sådana dolda kalkylblad tillgängliga för bearbetning, men med detta alternativ kan de ignoreras, som om de dolda kalkylbladen var frånvarande och inte existerade. När detta alternativ är aktiverat kan du inte välja ett dolt kalkylblad med egenskapen ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Tillåter att utesluta dolda kalkylblad i indata-kalkylbladsdokumentet, så
de kommer att ignoreras helt. Standard är falskt - dolda kalkylblad är
tillgängliga och behandlas som vanligt.


*** ** * ** ***

Flera binära kalkylbladsformat (som XLSX) stödjer konceptet dolda kalkylblad (flikar). Dokument av sådant format, om det har mer än ett kalkylblad, kan innehålla ytterligare dolda kalkylblad. Som standard är sådana dolda kalkylblad tillgängliga för bearbetning, men med detta alternativ kan de ignoreras, som om de dolda kalkylbladen var frånvarande och inte existerade. När detta alternativ är aktiverat kan du inte välja ett dolt kalkylblad med egenskapen ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


När den är aktiverad kommer de tomma intilliggande horisontella cellerna från indata-kalkylbladsdokumentet att
representeras i ett redigerbart HTML-dokument som sammanslagna till en enda cell med motsvarande
colspan-attribut. Som standard är den inaktiverad (false).


Som standard konverterar GroupDocs.Editor en tabell från indata-kalkylbladsdokumentet till utdata
HTML-dokument genom att bevara varje cell. Dock kan kalkylbladsdokumenten vara gles \\u2014 de
kan innehålla enorma mängder \"empty areas\", där många celler är tomma. Detta alternativ, när
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
standard är aktiverad (true).


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

