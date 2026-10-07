---
title: "WordProcessingProtectionType"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar alla tillgängliga skyddstyper för WordProcessing-dokumentet"
type: docs
weight: 47
url: /sv/java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

Representerar alla tillgängliga skyddstyper för WordProcessing-dokumentet

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [NoProtection](#NoProtection) | Dokumentet är inte skyddat. |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | Användaren kan endast lägga till revisionsmarkeringar i dokumentet |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | Användaren kan endast ändra kommentarer i dokumentet |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | Användaren kan endast ange data i formulärfälten i dokumentet |
|
|  | [ReadOnly](#ReadOnly) | Inga ändringar är tillåtna i dokumentet |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


Dokumentet är inte skyddat. Standardvärde.


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


Användaren kan endast lägga till revisionsmarkeringar i dokumentet


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


Användaren kan endast ändra kommentarer i dokumentet


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


Användaren kan endast ange data i formulärfälten i dokumentet


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Inga ändringar är tillåtna i dokumentet


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
