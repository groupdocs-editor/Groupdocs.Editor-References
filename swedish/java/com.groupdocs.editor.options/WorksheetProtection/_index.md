---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Inkapslar skyddsinställningar för kalkylblad som möjliggör att skydda ett kalkylblad i utdata‑Spreadsheet‑dokumentet från ändring av angiven typ med ett angivet lösenord."
type: docs
weight: 49
url: /sv/java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

Inkapslar skyddsinställningar för kalkylblad, som möjliggör att skydda ett kalkylblad
i utdata‑Spreadsheet‑dokumentet från ändring av angiven typ med ett
angivet lösenord.


*** ** * ** ***

De flesta Spreadsheet‑format som XLSX tillåter att skydda ett kalkylblad från redigering med lösenord. Denna klass möjliggör att aktivera sådant skydd och ange dess alternativ.

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | Skapar ny instans med standardparametrar. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | Skapar ny instans med angiven typ av kalkylblads-skydd och |
lösenord
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Tillåter att ange en typ av kalkylblads-skydd. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Tillåter att ange en typ av kalkylblads-skydd. |
|
|  | [getPassword()](#getPassword--) | Lösenord, som används för att skydda ett kalkylblad. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Lösenord, som används för att skydda ett kalkylblad. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


Skapar en ny instans med standardparametrar. Om den inte ändras och skickas
till SpreadsheetSaveOptions kommer inget kalkylblads-skydd att tillämpas


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


Skapar ny instans med angiven typ av kalkylblads-skydd och
lösenord


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | protectionType | int | Typ av kalkylblads-skydd |
|
|  | lösenord | java.lang.String | Lösenord, som låser skyddet |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Tillåter att ange en typ av kalkylblads-skydd. Standard är 'None' -
skyddet tillämpas inte.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Tillåter att ange en typ av kalkylblads-skydd. Standard är 'None' -
skyddet tillämpas inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Lösenord, som används för att skydda ett kalkylblad. Om NULL eller tom
sträng, kommer skyddet inte att tillämpas.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Lösenord, som används för att skydda ett kalkylblad. Om NULL eller tom
sträng, kommer skyddet inte att tillämpas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

