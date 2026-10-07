---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara Spreadsheet Excel-kompatibla dokument"
type: docs
weight: 37
url: /sv/java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Tillåter att ange anpassade alternativ för att generera och spara Spreadsheet
(Excel-kompatibla) dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Denna parameterlösa konstruktor skapar en ny instans av SpreadsheetSaveOptions med XLSX-utdataformat (kan sedan ändras via |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) egenskap)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Skapar en ny instans av SpreadsheetSaveOptions med angivet obligatoriskt |
Spreadsheet-utdataformat, medan alla andra parametrar är standard
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPassword()](#getPassword--) | Tillåter att ange, ändra, hämta eller ta bort ett lösenord, vilket kommer att |
används för att koda det genererade Spreadsheet-dokumentet, om detta dokumentformat
stöder lösenordsskydd.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Tillåter att ange, ändra, hämta eller ta bort ett lösenord, vilket kommer att |
används för att koda det genererade Spreadsheet-dokumentet, om detta dokumentformat
stöder lösenordsskydd.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | Tillåter att infoga redigerat kalkylblad i en kopia av befintligt kalkylblad |
istället för att skapa ett nytt kalkylblad med ett enda blad (standard
beteende).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Tillåter att infoga redigerat kalkylblad i en kopia av befintligt kalkylblad |
istället för att skapa ett nytt kalkylblad med ett enda blad (standard
beteende).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Boolesk flagga som anger om redigerat kalkylblad ska ersätta |
befintligt kalkylblad i original‑kalkylbladet på den position som anges av
den

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
egenskap, eller så ska den injiceras mellan befintligt kalkylblad och
föregående, utan att ersätta dess innehåll.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Boolesk flagga som anger om redigerat kalkylblad ska ersätta |
befintligt kalkylblad i original‑kalkylbladet på den position som anges av
den

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
egenskap, eller så ska den injiceras mellan befintligt kalkylblad och
föregående, utan att ersätta dess innehåll.
|
|  | [getOutputFormat()](#getOutputFormat--) | Tillåter att ange ett kalkylbladsformat som kommer att användas för att spara |
dokument
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Tillåter att ange ett kalkylbladsformat som kommer att användas för att spara |
dokument
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | Tillåter att aktivera ett arbetsblads-skydd för det resulterande kalkylbladet |
dokumentet.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Tillåter att aktivera ett arbetsblads-skydd för det resulterande kalkylbladet |
dokumentet.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | Tillåter att ange en array med 1‑baserade nummer på arbetsblad som ska tas bort från kalkylbladet vid sparning, om det redigerade arbetsbladet infogas i ett befintligt kalkylblad. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | Tillåter att ange en array med 1‑baserade nummer på arbetsblad som ska tas bort från kalkylbladet vid sparning, om det redigerade arbetsbladet infogas i ett befintligt kalkylblad. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Denna parameterlösa konstruktor skapar en ny instans av SpreadsheetSaveOptions med XLSX-utdataformat (kan sedan ändras via
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) egenskap)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Skapar en ny instans av SpreadsheetSaveOptions med angivet obligatoriskt
Spreadsheet-utdataformat, medan alla andra parametrar är standard


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Obligatoriskt utdataformat som kalkylbladsdokumentet ska sparas i |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Tillåter att ange, ändra, hämta eller ta bort ett lösenord, vilket kommer att
används för att koda det genererade Spreadsheet-dokumentet, om detta dokumentformat
stödjer lösenordsskydd. Ange NULL eller en tom sträng för att ta bort
(rengör) lösenordet.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Tillåter att ange, ändra, hämta eller ta bort ett lösenord, vilket kommer att
används för att koda det genererade Spreadsheet-dokumentet, om detta dokumentformat
stödjer lösenordsskydd. Ange NULL eller en tom sträng för att ta bort
(rengör) lösenordet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


Tillåter att infoga redigerat kalkylblad i en kopia av befintligt kalkylblad
istället för att skapa ett nytt kalkylblad med ett enda blad (standard
beteende). WorksheetNumber är ett 1‑baserat nummer på ett arbetsblad i
kalkylbladet, laddat i Editor‑klassen. Om det är 0 (standardvärde),
kommer ett nytt kalkylblad att skapas med ett enda redigerat arbetsblad. Om det är
större eller mindre än noll, och det finns ett giltigt kalkylblad, laddat i
Editor‑klassen, det redigerade arbetsbladet, som representeras av indata
EditableDocument‑instansen, kommer att infogas i detta kalkylblad.


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


Tillåter att infoga redigerat kalkylblad i en kopia av befintligt kalkylblad
istället för att skapa ett nytt kalkylblad med ett enda blad (standard
beteende). WorksheetNumber är ett 1‑baserat nummer på ett arbetsblad i
kalkylbladet, laddat i Editor‑klassen. Om det är 0 (standardvärde),
kommer ett nytt kalkylblad att skapas med ett enda redigerat arbetsblad. Om det är
större eller mindre än noll, och det finns ett giltigt kalkylblad, laddat i
Editor‑klassen, det redigerade arbetsbladet, som representeras av indata
EditableDocument‑instansen, kommer att infogas i detta kalkylblad.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


Boolesk flagga som anger om redigerat kalkylblad ska ersätta
befintligt kalkylblad i original‑kalkylbladet på den position som anges av
den

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
egenskap, eller så ska den injiceras mellan befintligt kalkylblad och
föregående, utan att ersätta dess innehåll. Standard är falskt \u2014
befintligt arbetsblad kommer att ersättas. Denna egenskap ignoreras om värdet
på

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
egenskapen är satt till '0'.


*** ** * ** ***

Som standard ersätts arbetsbladet. Det innebär att om det givna kalkylbladet har 5 arbetsblad och WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, så kommer det fjärde arbetsbladet att ersättas med det nya redigerade arbetsbladet, medan det totala antalet arbetsblad i kalkylbladet (5) förblir oförändrat. Om värdet på denna egenskap däremot sätts till  *true* , kommer det nya redigerade arbetsbladet att injiceras som det fjärde arbetsbladet, och alla efterföljande arbetsblad kommer att flyttas till slutet: \"old\" fjärde arbetsbladet blir femte, och femte blir sjätte, och det totala antalet arbetsblad i kalkylbladet ökas med ett och blir 6.

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Boolesk flagga som anger om redigerat kalkylblad ska ersätta
befintligt kalkylblad i original‑kalkylbladet på den position som anges av
den

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
egenskap, eller så ska den injiceras mellan befintligt kalkylblad och
föregående, utan att ersätta dess innehåll. Standard är falskt \u2014
befintligt arbetsblad kommer att ersättas. Denna egenskap ignoreras om värdet
på

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
egenskapen är satt till '0'.


*** ** * ** ***

Som standard ersätts arbetsbladet. Det innebär att om det givna kalkylbladet har 5 arbetsblad och WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, så kommer det fjärde arbetsbladet att ersättas med det nya redigerade arbetsbladet, medan det totala antalet arbetsblad i kalkylbladet (5) förblir oförändrat. Om värdet på denna egenskap däremot sätts till  *true* , kommer det nya redigerade arbetsbladet att injiceras som det fjärde arbetsbladet, och alla efterföljande arbetsblad kommer att flyttas till slutet: \"old\" fjärde arbetsbladet blir femte, och femte blir sjätte, och det totala antalet arbetsblad i kalkylbladet ökas med ett och blir 6.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Tillåter att ange ett kalkylbladsformat som kommer att användas för att spara
dokument


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Tillåter att ange ett kalkylbladsformat som kommer att användas för att spara
dokument


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Tillåter att aktivera ett arbetsblads-skydd för det resulterande kalkylbladet
dokument. Standard är NULL – skydd tillämpas inte. Inte alla format
stödjer ett arbetsblads-skydd.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Tillåter att aktivera ett arbetsblads-skydd för det resulterande kalkylbladet
dokument. Standard är NULL – skydd tillämpas inte. Inte alla format
stödjer ett arbetsblads-skydd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


Tillåter att ange en array med 1‑baserade nummer på arbetsblad som ska tas bort från kalkylbladet vid sparning, om det redigerade arbetsbladet infogas i ett befintligt kalkylblad. När det redigerade arbetsbladet sparas inte som ett nytt kalkylblad med ett enda arbetsblad (standardbeteende), utan istället sparas i ett befintligt kalkylblad (med hjälp av #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int)), är det också möjligt att ta bort vissa specifika arbetsblad från detta kalkylblad genom att ange deras nummer i denna array. Som standard är denna array  null  \u2014 inga arbetsblad kommer att tas bort. Om arrayen däremot är icke‑null och inte tom, och den innehåller minst ett giltigt arbetsbladsnummer, kommer arbetsbladen med angivna nummer att tas bort från kalkylbladet precis innan dess innehåll skrivs till utströmmen eller filen. Arbetsbladsnummer i denna array är 1‑baserade, inte 0‑baserade. Ogiltiga nummer (mindre än 1 eller större än det totala antalet arbetsblad) ignoreras.


**Returns:**
int[] – Array med 1‑baserade arbetsbladsnummer att ta bort, eller  null  om inget ska tas bort.

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


Tillåter att ange en array med 1‑baserade nummer på kalkylblad som ska tas bort från kalkylarket vid sparande, om det redigerade kalkylbladet infogas i ett befintligt kalkylark. Kalkylbladsnummer i denna array är 1‑baserade. Ogiltiga nummer ignoreras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int[] | Array med 1‑baserade kalkylbladsnummer att ta bort (kan vara null eller tom). |
|

