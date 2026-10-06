---
title: "WordProcessingProtection"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Encapsule les options de protection du document WordProcessing qui est généré à partir de HTML"
type: docs
weight: 46
url: /fr/java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

Encapsule les options de protection du document WordProcessing,
qui est généré à partir de HTML

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | Constructeur sans paramètres - tous les paramètres ont des valeurs par défaut |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | Permet de définir tous les paramètres lors de l'instanciation de la classe |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Permet de définir un type de protection du document. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Permet de définir un type de protection du document. |
|
|  | [getPassword()](#getPassword--) | Le mot de passe pour protéger le document. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Le mot de passe pour protéger le document. |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


Constructeur sans paramètres - tous les paramètres ont des valeurs par défaut


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


Permet de définir tous les paramètres lors de l'instanciation de la classe


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | protectionType | int | Définir le type de protection du document |
|
|  | mot de passe | java.lang.String | Définir le mot de passe de protection |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Permet de définir un type de protection du document. Par défaut, il est réglé sur ne pas
protéger le document du tout.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Permet de définir un type de protection du document. Par défaut, il est réglé sur ne pas
protéger le document du tout.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Le mot de passe pour protéger le document. Si null ou chaîne vide - le
protection ne sera pas appliquée au document.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Le mot de passe pour protéger le document. Si null ou chaîne vide - le
protection ne sera pas appliquée au document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
