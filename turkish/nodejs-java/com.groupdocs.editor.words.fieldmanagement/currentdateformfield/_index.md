---
title: "CurrentDateFormField"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Geçerli tarihi gösteren bir form alanını temsil eder."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor.words.fieldmanagement/currentdateformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class CurrentDateFormField implements IFormField
```

Geçerli tarihi gösteren bir form alanını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [CurrentDateFormField(String stylesheet, String name)](#CurrentDateFormField-java.lang.String-java.lang.String-) | Belirtilen stil sayfası ve ad ile [CurrentDateFormField](../../com.groupdocs.editor.words.fieldmanagement/currentdateformfield) sınıfının yeni bir örneğini başlatır. |
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
|  | [getType()](#getType--) | Bu sınıf için form alanının tipini alır; bu her zaman FormFieldType.CurrentDate olur. |
|
|  | [getLocaleId()](#getLocaleId--) | Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini (locale ID) alır veya ayarlar. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini (locale ID) alır veya ayarlar. |
|
|  | [getStatusText()](#getStatusText--) | Form alanının odaklandığında durum çubuğunda gösterilen metnin kaynağı olan durum metnini alır veya ayarlar. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Form alanının odaklandığında durum çubuğunda gösterilen metnin kaynağı olan durum metnini alır veya ayarlar. |
|
|  | [getHelpText()](#getHelpText--) | Form alanının odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilen metnin kaynağı olan yardım metnini alır veya ayarlar. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Form alanının odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilen metnin kaynağı olan yardım metnini alır veya ayarlar. |
|
|  | [getValue()](#getValue--) | Form alanının değerini alır veya ayarlar; bu değer geçerli tarihi temsil eder. |
|
|  | [setValue(Date value)](#setValue-java.util.Date-) | Form alanının değerini alır veya ayarlar; bu değer geçerli tarihi temsil eder. |
|
### CurrentDateFormField(String stylesheet, String name) {#CurrentDateFormField-java.lang.String-java.lang.String-}
```
public CurrentDateFormField(String stylesheet, String name)
```


Belirtilen stil sayfası ve ad ile [CurrentDateFormField](../../com.groupdocs.editor.words.fieldmanagement/currentdateformfield) sınıfının yeni bir örneğini başlatır.


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


Bu sınıf için form alanının tipini alır; bu her zaman FormFieldType.CurrentDate olur.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini (locale ID) alır veya ayarlar.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
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


Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini (locale ID) alır veya ayarlar.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
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


Form alanının odaklandığında durum çubuğunda gösterilen metnin kaynağı olan durum metnini alır veya ayarlar.

<br />

*** ** * ** ***

false olarak ayarlanırsa, durum metni uygulanmaz.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Form alanının odaklandığında durum çubuğunda gösterilen metnin kaynağı olan durum metnini alır veya ayarlar.

<br />

*** ** * ** ***

false olarak ayarlanırsa, durum metni uygulanmaz.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Form alanının odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilen metnin kaynağı olan yardım metnini alır veya ayarlar.

<br />

*** ** * ** ***

false olarak ayarlanırsa, yardım metni uygulanmaz.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Form alanının odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilen metnin kaynağı olan yardım metnini alır veya ayarlar.

<br />

*** ** * ** ***

false olarak ayarlanırsa, yardım metni uygulanmaz.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final Date getValue()
```


Form alanının değerini alır veya ayarlar; bu değer geçerli tarihi temsil eder.


**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public final void setValue(Date value)
```


Form alanının değerini alır veya ayarlar; bu değer geçerli tarihi temsil eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

