---
title: "WordProcessingProtectionType"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل جميع أنواع الحماية المتاحة لمستند معالجة الكلمات."
type: docs
weight: 47
url: /ar/java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

يمثل جميع أنواع الحماية المتاحة لمستند معالجة الكلمات.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NoProtection](#NoProtection) | المستند غير محمي. |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | يمكن للمستخدم فقط إضافة علامات مراجعة إلى المستند |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | يمكن للمستخدم فقط تعديل التعليقات في المستند |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | يمكن للمستخدم فقط إدخال البيانات في حقول النموذج داخل المستند |
|
|  | [ReadOnly](#ReadOnly) | لا يُسمح بإجراء أي تغييرات على المستند |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


المستند غير محمي. القيمة الافتراضية.


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


يمكن للمستخدم فقط إضافة علامات مراجعة إلى المستند


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


يمكن للمستخدم فقط تعديل التعليقات في المستند


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


يمكن للمستخدم فقط إدخال البيانات في حقول النموذج داخل المستند


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


لا يُسمح بإجراء أي تغييرات على المستند


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
