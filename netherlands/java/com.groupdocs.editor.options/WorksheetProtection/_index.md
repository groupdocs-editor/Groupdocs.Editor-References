---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Omsluit opties voor werkbladbeveiliging die het mogelijk maken een werkblad in het uitvoer‑Spreadsheet‑document te beschermen tegen wijziging van een gespecificeerd type met een opgegeven wachtwoord."
type: docs
weight: 49
url: /nl/java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

Omsluit opties voor werkbladbeveiliging, die het mogelijk maken een werkblad te beschermen
in het uitvoer‑Spreadsheet‑document tegen wijziging van een gespecificeerd type met een
opgegeven wachtwoord.


*** ** * ** ***

De meeste Spreadsheet‑formaten zoals XLSX staan toe een werkblad te beveiligen tegen bewerken met een wachtwoord. Deze klasse maakt het mogelijk die beveiliging in te schakelen en de opties te specificeren.

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | Maakt een nieuw exemplaar aan met standaardparameters. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | Maakt een nieuw exemplaar aan met een gespecificeerd type werkbladbeveiliging en |
password
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Staat toe een type werkbladbeveiliging op te geven. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Staat toe een type werkbladbeveiliging op te geven. |
|
|  | [getPassword()](#getPassword--) | Wachtwoord, dat wordt gebruikt om een werkblad te beveiligen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Wachtwoord, dat wordt gebruikt om een werkblad te beveiligen. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


Maakt een nieuw exemplaar aan met standaardparameters. Indien niet gewijzigd en doorgegeven
aan SpreadsheetSaveOptions, wordt er geen werkbladbeveiliging toegepast


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


Maakt een nieuw exemplaar aan met een gespecificeerd type werkbladbeveiliging en
password


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | protectionType | int | Type werkbladbeveiliging |
|
|  | password | java.lang.String | Wachtwoord, dat de beveiliging vergrendelt |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Staat toe een type werkbladbeveiliging op te geven. Standaard is 'None' -
beveiliging wordt niet toegepast.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Staat toe een type werkbladbeveiliging op te geven. Standaard is 'None' -
beveiliging wordt niet toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Wachtwoord, dat wordt gebruikt om een werkblad te beveiligen. Als NULL of leeg
tekenreeks, wordt de beveiliging niet toegepast.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Wachtwoord, dat wordt gebruikt om een werkblad te beveiligen. Als NULL of leeg
tekenreeks, wordt de beveiliging niet toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

