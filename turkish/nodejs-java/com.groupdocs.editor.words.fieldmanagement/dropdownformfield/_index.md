---
title: "DropDownFormField"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Açılır listeyi gösteren bir form alanını temsil eder."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.editor.words.fieldmanagement/dropdownformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class DropDownFormField implements IFormField
```

Açılır listeyi gösteren bir form alanını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DropDownFormField(String stylesheet, String name)](#DropDownFormField-java.lang.String-java.lang.String-) | Belirtilen stil sayfası ve ad ile [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) sınıfının yeni bir örneğini başlatır. |
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
|  | [getSelectedIndex()](#getSelectedIndex--) | Açılır listede seçilen öğenin indeksini alır veya ayarlar. |
|
|  | [setSelectedIndex(int value)](#setSelectedIndex-int-) | Açılır listede seçilen öğenin indeksini alır veya ayarlar. |
|
|  | [getType()](#getType--) | Form alanının türünü alır; bu sınıf için her zaman FormFieldType.DropDown olur. |
|
|  | [getLocaleId()](#getLocaleId--) | Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini (locale ID) alır veya ayarlar. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Form alanıyla ilişkili kültür veya bölgesel ayarları temsil eden yerel kimliğini (locale ID) alır veya ayarlar. |
|
|  | [getStatusText()](#getStatusText--) | Form alanıyla ilişkili durum metnini alır veya ayarlar; bu metin, bir form alanı odaklandığında durum çubuğunda gösterilen metnin kaynağıdır. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Form alanıyla ilişkili durum metnini alır veya ayarlar; bu metin, bir form alanı odaklandığında durum çubuğunda gösterilen metnin kaynağıdır. |
|
|  | [getHelpText()](#getHelpText--) | Form alanının odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilen metnin kaynağı olan yardım metnini alır veya ayarlar. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Form alanının odaklandığında ve kullanıcı F1 tuşuna bastığında mesaj kutusunda gösterilen metnin kaynağı olan yardım metnini alır veya ayarlar. |
|
|  | [getValue()](#getValue--) | Form alanının değerini alır veya ayarlar; bu değer açılır listedeki seçeneklerin listesini temsil eder. |
|
|  | [setValue(List<String> value)](#setValue-java.util.List-java.lang.String--) | Form alanının değerini alır veya ayarlar; bu değer açılır listedeki seçeneklerin listesini temsil eder. |
|
### DropDownFormField(String stylesheet, String name) {#DropDownFormField-java.lang.String-java.lang.String-}
```
public DropDownFormField(String stylesheet, String name)
```


Belirtilen stil sayfası ve ad ile [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) sınıfının yeni bir örneğini başlatır.


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
### getSelectedIndex() {#getSelectedIndex--}
```
public final int getSelectedIndex()
```


Açılır listede seçilen öğenin indeksini alır veya ayarlar.


**Returns:**
int
### setSelectedIndex(int value) {#setSelectedIndex-int-}
```
public final void setSelectedIndex(int value)
```


Açılır listede seçilen öğenin indeksini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getType() {#getType--}
```
public final int getType()
```


Form alanının türünü alır; bu sınıf için her zaman FormFieldType.DropDown olur.


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
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
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
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
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

false olarak ayarlanırsa, durum metni uygulanmaz.

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
public final List<String> getValue()
```


Form alanının değerini alır veya ayarlar; bu değer açılır listedeki seçeneklerin listesini temsil eder.


**Returns:**
java.util.List<java.lang.String>
### setValue(List<String> value) {#setValue-java.util.List-java.lang.String--}
```
public final void setValue(List<String> value)
```


Form alanının değerini alır veya ayarlar; bu değer açılır listedeki seçeneklerin listesini temsil eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<java.lang.String> |  |

