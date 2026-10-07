---
title: "InvalidFormField"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "FormFieldManager.FixInvalidFormFieldNames işlemi sırasında geçersiz form alanı adlarının güncellenmesini temsil eder."
type: docs
weight: 18
url: /tr/java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Geçersiz form alanı adlarının güncellenmesini temsil eder
FormFieldManager.FixInvalidFormFieldNames
işlem.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Belirtilen ad ile [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getName()](#getName--) | Dışarıda değiştirilemeyen form alanının orijinal adını alır |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | Onarım sonrası form alanı için yeni adı alır veya ayarlar. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | Onarım sonrası form alanı için yeni adı alır veya ayarlar. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Belirtilen ad ile [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | Form alanının orijinal adı. |
|

### getName() {#getName--}
```
public final String getName()
```


Dışarıda değiştirilemeyen form alanının orijinal adını alır
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Onarım sonrası form alanı için yeni adı alır veya ayarlar.
Bu ad, diğer form alanlarıyla yinelenen benzersiz tanımlayıcıları kaldırır ve benzersiz bir yer imi adı ayarlar.

<br />

*** ** * ** ***

```
 FixedName = String.format("%s_fixed", name); // as default value.
 
```

<br />



**Returns:**
java.lang.String
### setFixedName(String value) {#setFixedName-java.lang.String-}
```
public final void setFixedName(String value)
```


Onarım sonrası form alanı için yeni adı alır veya ayarlar.
Bu ad, diğer form alanlarıyla yinelenen benzersiz tanımlayıcıları kaldırır ve benzersiz bir yer imi adı ayarlar.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

