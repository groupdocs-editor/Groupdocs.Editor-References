---
title: "TextFormField"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Metin girişi kabul eden bir form alanını temsil eder."
type: docs
weight: 20
url: /tr/java/com.groupdocs.editor.words.fieldmanagement/textformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class TextFormField implements IFormField
```

Metin girişi kabul eden bir form alanını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TextFormField(String stylesheet, String name)](#TextFormField-java.lang.String-java.lang.String-) | Belirtilen stil sayfası ve ad ile yeni bir [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) sınıf örneği başlatır. |
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
|  | [getType()](#getType--) | Bu sınıf için form alanının tipini alır; bu her zaman FormFieldType.Text olur. |
|
|  | [getLocaleId()](#getLocaleId--) | Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini alır veya ayarlar. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini alır veya ayarlar. |
|
|  | [getStatusText()](#getStatusText--) | Form alanı ile ilişkili durum metnini alır veya ayarlar, |
Form alanı odaklandığında durum çubuğunda gösterilen metnin kaynağı.
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Form alanı ile ilişkili durum metnini alır veya ayarlar, |
Form alanı odaklandığında durum çubuğunda gösterilen metnin kaynağı.
|
|  | [getHelpText()](#getHelpText--) | Form alanı ile ilişkili yardım metnini alır veya ayarlar, |
Form alanı odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilen metnin kaynağı.
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Form alanı ile ilişkili yardım metnini alır veya ayarlar, |
Form alanı odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilen metnin kaynağı.
|
|  | [getValue()](#getValue--) | Form alanının değerini alır veya ayarlar; bu değer metin girişini temsil eder. |
|
|  | [setValue(String value)](#setValue-java.lang.String-) | Form alanının değerini alır veya ayarlar; bu değer metin girişini temsil eder. |
|
|  | [getMaxLength()](#getMaxLength--) | Form alanı için girişin maksimum uzunluğunu alır veya ayarlar. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | Form alanı için girişin maksimum uzunluğunu alır veya ayarlar. |
|
### TextFormField(String stylesheet, String name) {#TextFormField-java.lang.String-java.lang.String-}
```
public TextFormField(String stylesheet, String name)
```


Belirtilen stil sayfası ve ad ile yeni bir [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) sınıf örneği başlatır.


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


Bu sınıf için form alanının tipini alır; bu her zaman FormFieldType.Text olur.


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
>  textField.LocaleId = new CultureInfo("en-US").LCID;
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
>  textField.LocaleId = new CultureInfo("en-US").LCID;
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


Form alanı ile ilişkili durum metnini alır veya ayarlar,
Form alanı odaklandığında durum çubuğunda gösterilen metnin kaynağı.

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


Form alanı ile ilişkili durum metnini alır veya ayarlar,
Form alanı odaklandığında durum çubuğunda gösterilen metnin kaynağı.

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


Form alanı ile ilişkili yardım metnini alır veya ayarlar,
Form alanı odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilen metnin kaynağı.

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


Form alanı ile ilişkili yardım metnini alır veya ayarlar,
Form alanı odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilen metnin kaynağı.

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
public final String getValue()
```


Form alanının değerini alır veya ayarlar; bu değer metin girişini temsil eder.


**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Form alanının değerini alır veya ayarlar; bu değer metin girişini temsil eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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

