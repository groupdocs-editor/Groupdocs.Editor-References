---
title: "WordProcessingProtection"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Kapselt Dokumentenschutzoptionen für das WordProcessing-Dokument, das aus HTML generiert wird"
type: docs
weight: 46
url: /de/java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

Kapselt Dokumentenschutzoptionen für das WordProcessing-Dokument,
das aus HTML generiert wird

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | Parameterloser Konstruktor – alle Parameter haben Standardwerte |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | Ermöglicht das Festlegen aller Parameter während der Klasseninstanziierung |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Ermöglicht das Festlegen eines Schutztyps für das Dokument. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Ermöglicht das Festlegen eines Schutztyps für das Dokument. |
|
|  | [getPassword()](#getPassword--) | Das Passwort, mit dem das Dokument geschützt wird. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Das Passwort, mit dem das Dokument geschützt wird. |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


Parameterloser Konstruktor – alle Parameter haben Standardwerte


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


Ermöglicht das Festlegen aller Parameter während der Klasseninstanziierung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | protectionType | int | Setzen Sie den Schutztyp des Dokuments |
|
|  | Passwort | java.lang.String | Setzen Sie das Schutzpasswort |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Ermöglicht das Festlegen eines Schutztyps für das Dokument. Standardmäßig ist er auf nicht
das Dokument überhaupt zu schützen.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Ermöglicht das Festlegen eines Schutztyps für das Dokument. Standardmäßig ist er auf nicht
das Dokument überhaupt zu schützen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Das Passwort, mit dem das Dokument geschützt wird. Wenn null oder leerer String – das
Schutz wird nicht auf das Dokument angewendet.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Das Passwort, mit dem das Dokument geschützt wird. Wenn null oder leerer String – das
Schutz wird nicht auf das Dokument angewendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
