---
title: "FormFieldCollection"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل مجموعة من حقول النماذج."
type: docs
weight: 15
url: /ar/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

يمثل مجموعة من حقول النماذج.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | ينشئ مثيلاً جديدًا من الفئة [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [iterator()](#iterator--) | يعيد مُعدِّداً يتنقل عبر المجموعة. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | يدرج حقل نموذج في المجموعة. |
|
|  | [get(String name)](#get-java.lang.String-) | يحصل على حقل النموذج بالاسم المحدد. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | يحصل على حقل النموذج بالاسم والنوع المحددين. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


ينشئ مثيلاً جديدًا من الفئة [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection).


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


يعيد مُعدِّداً يتنقل عبر المجموعة.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - مُعدِّداً يمكن استخدامه للتنقل عبر المجموعة.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


يدرج حقل نموذج في المجموعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | حقل النموذج المراد إدراجه. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


يحصل على حقل النموذج بالاسم المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم حقل النموذج. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


يحصل على حقل النموذج بالاسم والنوع المحددين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم حقل النموذج. |


T
: نوع حقل النموذج.
|
| نوع | java.lang.Class<T> |  |

**Returns:**
T - حقل النموذج بالاسم والنوع المحددين، إذا تم العثور عليه؛ وإلا، القيمة الافتراضية للنوع.

