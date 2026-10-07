---
title: "FormFieldCollection"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Form alanlarının bir koleksiyonunu temsil eder."
type: docs
weight: 15
url: /tr/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

Form alanlarının bir koleksiyonunu temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | Yeni bir [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) sınıf örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | Koleksiyona bir form alanı ekler. |
|
|  | [get(String name)](#get-java.lang.String-) | Belirtilen ada sahip form alanını alır. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | Belirtilen ada ve tipe sahip form alanını alır. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


Yeni bir [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) sınıf örneği başlatır.


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


Koleksiyon içinde yineleme yapan bir enumerator döndürür.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir enumerator.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


Koleksiyona bir form alanı ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | Eklenecek form alanı. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


Belirtilen ada sahip form alanını alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | Form alanının adı. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


Belirtilen ada ve tipe sahip form alanını alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | Form alanının adı. |


T
: Form alanının tipi.
|
| tür | java.lang.Class<T> |  |

**Returns:**
T - Belirtilen ada ve tipe sahip form alanı, bulunursa; aksi takdirde tipin varsayılan değeri.

