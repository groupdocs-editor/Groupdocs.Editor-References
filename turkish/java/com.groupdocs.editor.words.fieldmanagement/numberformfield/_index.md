---
title: "NumberFormField"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Sayısal giriş kabul eden bir form alanını temsil eder."
type: docs
weight: 19
url: /tr/java/com.groupdocs.editor.words.fieldmanagement/numberformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class NumberFormField implements IFormField
```

Sayısal giriş kabul eden bir form alanını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [NumberFormField(String stylesheet, String name)](#NumberFormField-java.lang.String-java.lang.String-) | Belirtilen stil sayfası ve ad ile [NumberFormField](../../com.groupdocs.editor.words.fieldmanagement/numberformfield) sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | Form alanına uygulanan stil sayfasını alır. |
|
|  | [getReadonly()](#getReadonly--) | Form alanının yalnızca okunur olup olmadığını gösteren değeri alır veya ayarlar. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | Form alanının yalnızca okunur olup olmadığını gösteren değeri alır veya ayarlar. |
|
|  | [getName()](#getName--) | Form alanının adını alır. |
|
|  | [getType()](#getType--) | Bu sınıf için form alanının tipini alır; bu tip her zaman FormFieldType.Number olur. |
|
|  | [getLocaleId()](#getLocaleId--) | Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini alır veya ayarlar. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini alır veya ayarlar. |
|
|  | [getStatusText()](#getStatusText--) | Form alanıyla ilişkili durum metnini alır veya ayarlar; bu metin, bir form alanı odaklandığında durum çubuğunda gösterilen metnin kaynağıdır. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Form alanıyla ilişkili durum metnini alır veya ayarlar; bu metin, bir form alanı odaklandığında durum çubuğunda gösterilen metnin kaynağıdır. |
|
|  | [getHelpText()](#getHelpText--) | Form alanıyla ilişkili yardım metnini alır veya ayarlar; bu metin, form alanı odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilir. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Form alanıyla ilişkili yardım metnini alır veya ayarlar; bu metin, form alanı odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilir. |
|
|  | [getValue()](#getValue--) | Form alanının değerini alır veya ayarlar; bu değer bir sayıyı temsil eder. |
|
|  | [setValue(float value)](#setValue-float-) | Form alanının değerini alır veya ayarlar; bu değer bir sayıyı temsil eder. |
|
|  | [getMaxLength()](#getMaxLength--) | Form alanı için girişin maksimum uzunluğunu alır veya ayarlar. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | Form alanı için girişin maksimum uzunluğunu alır veya ayarlar. |
|
### NumberFormField(String stylesheet, String name) {#NumberFormField-java.lang.String-java.lang.String-}
```
public NumberFormField(String stylesheet, String name)
```


Belirtilen stil sayfası ve ad ile [NumberFormField](../../com.groupdocs.editor.words.fieldmanagement/numberformfield) sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stil sayfası | java.lang.String | Form alanına uygulanacak stil sayfası. |
|
|  | ad | java.lang.String | Form alanının adı. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Form alanına uygulanan stil sayfasını alır.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Form alanının yalnızca okunur olup olmadığını gösteren değeri alır veya ayarlar.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Form alanının yalnızca okunur olup olmadığını gösteren değeri alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


Form alanının adını alır.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Bu sınıf için form alanının tipini alır; bu tip her zaman FormFieldType.Number olur.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini alır veya ayarlar.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  numberField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

LocaleId özelliği, belirli bir kültür veya bölgeye karşılık gelen bir yerel tanımlayıcıyı (LCID) belirtir.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini alır veya ayarlar.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  numberField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

LocaleId özelliği, belirli bir kültür veya bölgeye karşılık gelen bir yerel tanımlayıcıyı (LCID) belirtir.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Form alanıyla ilişkili durum metnini alır veya ayarlar; bu metin, bir form alanı odaklandığında durum çubuğunda gösterilen metnin kaynağıdır.

<br />

*** ** * ** ***

false olarak ayarlanırsa, durum metni uygulanmayacaktır.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Form alanıyla ilişkili durum metnini alır veya ayarlar; bu metin, bir form alanı odaklandığında durum çubuğunda gösterilen metnin kaynağıdır.

<br />

*** ** * ** ***

false olarak ayarlanırsa, durum metni uygulanmayacaktır.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Form alanıyla ilişkili yardım metnini alır veya ayarlar; bu metin, form alanı odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilir.

<br />

*** ** * ** ***

false olarak ayarlanırsa, yardım metni uygulanmayacaktır.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Form alanıyla ilişkili yardım metnini alır veya ayarlar; bu metin, form alanı odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilir.

<br />

*** ** * ** ***

false olarak ayarlanırsa, yardım metni uygulanmayacaktır.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final float getValue()
```


Form alanının değerini alır veya ayarlar; bu değer bir sayıyı temsil eder.


**Returns:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```


Form alanının değerini alır veya ayarlar; bu değer bir sayıyı temsil eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


Form alanı için girişin maksimum uzunluğunu alır veya ayarlar.


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


Form alanı için girişin maksimum uzunluğunu alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

