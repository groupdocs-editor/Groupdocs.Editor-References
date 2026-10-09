---
title: "WordProcessingProtectionType"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "WordProcessing belgesinin tüm mevcut koruma türlerini temsil eder."
type: docs
weight: 47
url: /tr/nodejs-java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

WordProcessing belgesinin tüm mevcut koruma türlerini temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [NoProtection](#NoProtection) | Belge korumalı değil. |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | Kullanıcı yalnızca belgeye revizyon işaretleri ekleyebilir |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | Kullanıcı yalnızca belgede yorumları değiştirebilir |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | Kullanıcı yalnızca belgede form alanlarına veri girebilir |
|
|  | [ReadOnly](#ReadOnly) | Belgeye hiçbir değişiklik yapılamaz |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


Belge korumalı değil. Varsayılan değer.


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


Kullanıcı yalnızca belgeye revizyon işaretleri ekleyebilir


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


Kullanıcı yalnızca belgede yorumları değiştirebilir


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


Kullanıcı yalnızca belgede form alanlarına veri girebilir


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Belgeye hiçbir değişiklik yapılamaz


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
