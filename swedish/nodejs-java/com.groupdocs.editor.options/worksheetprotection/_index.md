---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Innesluter alternativ för arbetsblads-skydd som tillåter att skydda ett arbetsblad i det resulterande Spreadsheet-dokumentet från modifiering av angiven typ med ett angivet lösenord."
type: docs
weight: 49
url: /sv/nodejs-java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

Innesluter alternativ för arbetsblads-skydd, som tillåter att skydda ett arbetsblad
i det resulterande Spreadsheet-dokumentet från modifiering av angiven typ med en
angivet lösenord.


*** ** * ** ***

De flesta Spreadsheet-format som XLSX tillåter att skydda ett arbetsblad från redigering med lösenord. Denna klass möjliggör att aktivera sådant skydd och specificera dess alternativ.

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | Skapar en ny instans med standardparametrar. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | Skapar en ny instans med angiven typ av arbetsblads-skydd och |
lösenord
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Tillåter att specificera en typ av arbetsblads-skydd. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Tillåter att specificera en typ av arbetsblads-skydd. |
|
|  | [getPassword()](#getPassword--) | Lösenord, som används för att skydda ett arbetsblad. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Lösenord, som används för att skydda ett arbetsblad. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


Skapar en ny instans med standardparametrar. Om den inte ändras och skickas
till SpreadsheetSaveOptions, kommer inget arbetsblads-skydd att tillämpas


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


Skapar en ny instans med angiven typ av arbetsblads-skydd och
lösenord


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | protectionType | int | Typ av arbetsblads-skydd |
|
|  | lösenord | java.lang.String | Lösenord, som låser skyddet |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Tillåter att specificera en typ av arbetsblads-skydd. Standard är 'None' -
skyddet tillämpas inte.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Tillåter att specificera en typ av arbetsblads-skydd. Standard är 'None' -
skyddet tillämpas inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Lösenord, som används för att skydda ett arbetsblad. Om NULL eller tom
sträng, kommer skyddet inte att tillämpas.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Lösenord, som används för att skydda ett arbetsblad. Om NULL eller tom
sträng, kommer skyddet inte att tillämpas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

