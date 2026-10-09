---
title: "WordProcessingProtection"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Incapsula le opzioni di protezione del documento WordProcessing che è generato da HTML"
type: docs
weight: 46
url: /it/nodejs-java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

Incapsula le opzioni di protezione del documento WordProcessing,
che è generato da HTML

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | Costruttore senza parametri - tutti i parametri hanno valori predefiniti |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | Consente di impostare tutti i parametri durante l'istanziazione della classe |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Consente di impostare un tipo di protezione del documento. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Consente di impostare un tipo di protezione del documento. |
|
|  | [getPassword()](#getPassword--) | La password per proteggere il documento. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | La password per proteggere il documento. |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


Costruttore senza parametri - tutti i parametri hanno valori predefiniti


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


Consente di impostare tutti i parametri durante l'istanziazione della classe


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | protectionType | int | Imposta il tipo di protezione del documento |
|
|  | password | java.lang.String | Imposta la password di protezione |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Consente di impostare un tipo di protezione del documento. Per impostazione predefinita è impostato su non
proteggere il documento affatto.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Consente di impostare un tipo di protezione del documento. Per impostazione predefinita è impostato su non
proteggere il documento affatto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


La password con cui proteggere il documento. Se null o stringa vuota - la
protezione non verrà applicata al documento.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


La password con cui proteggere il documento. Se null o stringa vuota - la
protezione non verrà applicata al documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
