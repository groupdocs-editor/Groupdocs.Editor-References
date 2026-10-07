---
title: "WordProcessingProtectionType"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta tutti i tipi di protezione disponibili del documento WordProcessing"
type: docs
weight: 47
url: /it/java/com.groupdocs.editor.options/wordprocessingprotectiontype/
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
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | L'utente può solo aggiungere segni di revisione al documento |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | L'utente può solo modificare i commenti nel documento |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | L'utente può solo inserire dati nei campi del modulo nel documento |
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


L'utente può solo aggiungere segni di revisione al documento


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


L'utente può solo modificare i commenti nel documento


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


L'utente può solo inserire dati nei campi del modulo nel documento


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
