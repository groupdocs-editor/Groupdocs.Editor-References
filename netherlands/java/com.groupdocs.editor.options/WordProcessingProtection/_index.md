---
title: "WordProcessingProtection"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Omsluit documentbeschermingsopties voor het WordProcessing‑document dat uit HTML wordt gegenereerd"
type: docs
weight: 46
url: /nl/java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

Omsluit documentbeschermingsopties voor het WordProcessing‑document,
dat uit HTML wordt gegenereerd

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | Constructor zonder parameters - alle parameters hebben standaardwaarden |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | Staat toe om alle parameters in te stellen tijdens het instantieren van de klasse |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Staat toe om een beschermingstype voor het document in te stellen. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Staat toe om een beschermingstype voor het document in te stellen. |
|
|  | [getPassword()](#getPassword--) | Het wachtwoord om het document mee te beveiligen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Het wachtwoord om het document mee te beveiligen. |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


Constructor zonder parameters - alle parameters hebben standaardwaarden


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


Staat toe om alle parameters in te stellen tijdens het instantieren van de klasse


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | protectionType | int | Stel het beschermingstype van het document in |
|
|  | password | java.lang.String | Stel het beveiligingswachtwoord in |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Staat toe een beschermingstype van het document in te stellen. Standaard is ingesteld op niet
het document helemaal te beveiligen.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Staat toe een beschermingstype van het document in te stellen. Standaard is ingesteld op niet
het document helemaal te beveiligen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Het wachtwoord om het document mee te beveiligen. Als null of een lege string - de
beveiliging zal niet op het document worden toegepast.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Het wachtwoord om het document mee te beveiligen. Als null of een lege string - de
beveiliging zal niet op het document worden toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
