---
title: "WordProcessingProtectionType"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt alle verfügbaren Schutztypen des WordProcessing-Dokuments dar"
type: docs
weight: 47
url: /de/nodejs-java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

Stellt alle verfügbaren Schutztypen des WordProcessing-Dokuments dar

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [NoProtection](#NoProtection) | Das Dokument ist nicht geschützt. |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | Benutzer kann nur Revisionsmarken zum Dokument hinzufügen |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | Benutzer kann nur Kommentare im Dokument ändern |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | Benutzer kann nur Daten in die Formularfelder im Dokument eingeben |
|
|  | [ReadOnly](#ReadOnly) | Keine Änderungen am Dokument erlaubt |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


Das Dokument ist nicht geschützt. Standardwert.


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


Benutzer kann nur Revisionsmarken zum Dokument hinzufügen


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


Benutzer kann nur Kommentare im Dokument ändern


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


Benutzer kann nur Daten in die Formularfelder im Dokument eingeben


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Keine Änderungen am Dokument erlaubt


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
