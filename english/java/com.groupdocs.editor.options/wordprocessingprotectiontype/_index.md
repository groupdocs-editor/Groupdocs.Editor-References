---
title: WordProcessingProtectionType
second_title: GroupDocs.Editor for Java API Reference
description:  Represents all available protection types of the WordProcessing document
type: docs
weight: 45
url: /java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

Represents all available protection types of the WordProcessing document
## Fields

| Field | Description |
| --- | --- |
| [NoProtection](#NoProtection) | The document is not protected. |
| [AllowOnlyRevisions](#AllowOnlyRevisions) | User can only add revision marks to the document |
| [AllowOnlyComments](#AllowOnlyComments) | User can only modify comments in the document |
| [AllowOnlyFormFields](#AllowOnlyFormFields) | User can only enter data in the form fields in the document |
| [ReadOnly](#ReadOnly) | No changes are allowed to the document |
## Methods

| Method | Description |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final byte NoProtection
```


The document is not protected. Default value.

### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final byte AllowOnlyRevisions
```


User can only add revision marks to the document

### AllowOnlyComments {#AllowOnlyComments}
```
public static final byte AllowOnlyComments
```


User can only modify comments in the document

### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final byte AllowOnlyFormFields
```


User can only enter data in the form fields in the document

### ReadOnly {#ReadOnly}
```
public static final byte ReadOnly
```


No changes are allowed to the document

### getAll() {#getAll--}
```
public static Map<Byte,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Byte,java.lang.String>
