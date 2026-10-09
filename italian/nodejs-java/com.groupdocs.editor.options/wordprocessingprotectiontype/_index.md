---
title: "WordProcessingProtectionType"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta tutti i tipi di protezione disponibili del documento WordProcessing"
type: docs
weight: 47
url: /it/nodejs-java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

Rappresenta tutti i tipi di protezione disponibili del documento WordProcessing

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [NoProtection](#NoProtection) | Il documento non è protetto. |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | L'utente può aggiungere solo segni di revisione al documento |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | L'utente può modificare solo i commenti nel documento |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | L'utente può inserire dati solo nei campi modulo del documento |
|
|  | [ReadOnly](#ReadOnly) | Non sono consentite modifiche al documento |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


Il documento non è protetto. Valore predefinito.


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


L'utente può aggiungere solo segni di revisione al documento


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


L'utente può modificare solo i commenti nel documento


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


L'utente può inserire dati solo nei campi modulo del documento


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Non sono consentite modifiche al documento


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
