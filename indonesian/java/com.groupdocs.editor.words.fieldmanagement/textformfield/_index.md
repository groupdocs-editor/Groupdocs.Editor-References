---
title: "TextFormField"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili bidang formulir yang menerima input teks."
type: docs
weight: 20
url: /id/java/com.groupdocs.editor.words.fieldmanagement/textformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class TextFormField implements IFormField
```

Mewakili bidang formulir yang menerima input teks.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TextFormField(String stylesheet, String name)](#TextFormField-java.lang.String-java.lang.String-) | Menginisialisasi instance baru dari kelas [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) dengan lembar gaya dan nama yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | Mendapatkan stylesheet yang diterapkan pada field formulir. |
|
|  | [getReadonly()](#getReadonly--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah field formulir bersifat read-only. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah field formulir bersifat read-only. |
|
|  | [getName()](#getName--) | Mendapatkan nama field formulir. |
|
|  | [getType()](#getType--) | Mendapatkan tipe bidang formulir, yang selalu FormFieldType.Text untuk kelas ini. |
|
|  | [getLocaleId()](#getLocaleId--) | Mendapatkan atau mengatur ID lokal field formulir, yang mewakili budaya atau pengaturan regional yang terkait dengan field formulir. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Mendapatkan atau mengatur ID lokal field formulir, yang mewakili budaya atau pengaturan regional yang terkait dengan field formulir. |
|
|  | [getStatusText()](#getStatusText--) | Mendapatkan atau mengatur teks status yang terkait dengan bidang formulir, |
sumber teks yang ditampilkan di bilah status ketika bidang formulir memiliki fokus.
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Mendapatkan atau mengatur teks status yang terkait dengan bidang formulir, |
sumber teks yang ditampilkan di bilah status ketika bidang formulir memiliki fokus.
|
|  | [getHelpText()](#getHelpText--) | Mendapatkan atau mengatur teks bantuan yang terkait dengan bidang formulir, |
sumber teks yang ditampilkan dalam kotak pesan ketika bidang formulir memiliki fokus dan pengguna menekan F1.
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Mendapatkan atau mengatur teks bantuan yang terkait dengan bidang formulir, |
sumber teks yang ditampilkan dalam kotak pesan ketika bidang formulir memiliki fokus dan pengguna menekan F1.
|
|  | [getValue()](#getValue--) | Mendapatkan atau mengatur nilai bidang formulir, yang mewakili masukan teks. |
|
|  | [setValue(String value)](#setValue-java.lang.String-) | Mendapatkan atau mengatur nilai bidang formulir, yang mewakili masukan teks. |
|
|  | [getMaxLength()](#getMaxLength--) | Mendapatkan atau mengatur panjang maksimum input untuk bidang formulir. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | Mendapatkan atau mengatur panjang maksimum input untuk bidang formulir. |
|
### TextFormField(String stylesheet, String name) {#TextFormField-java.lang.String-java.lang.String-}
```
public TextFormField(String stylesheet, String name)
```


Menginisialisasi instance baru dari kelas [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) dengan lembar gaya dan nama yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stylesheet | java.lang.String | Lembar gaya yang diterapkan pada bidang formulir. |
|
|  | nama | java.lang.String | Nama bidang formulir. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Mendapatkan stylesheet yang diterapkan pada field formulir.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah field formulir bersifat read-only.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah field formulir bersifat read-only.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama field formulir.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Mendapatkan tipe bidang formulir, yang selalu FormFieldType.Text untuk kelas ini.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Mendapatkan atau mengatur ID lokal field formulir, yang mewakili budaya atau pengaturan regional yang terkait dengan field formulir.

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

Properti LocaleId menentukan pengidentifikasi lokal (LCID) yang sesuai dengan budaya atau wilayah tertentu.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


Mendapatkan atau mengatur ID lokal field formulir, yang mewakili budaya atau pengaturan regional yang terkait dengan field formulir.

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

Properti LocaleId menentukan pengidentifikasi lokal (LCID) yang sesuai dengan budaya atau wilayah tertentu.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Mendapatkan atau mengatur teks status yang terkait dengan bidang formulir,
sumber teks yang ditampilkan di bilah status ketika bidang formulir memiliki fokus.

<br />

*** ** * ** ***

Jika disetel ke false, teks status tidak akan diterapkan.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Mendapatkan atau mengatur teks status yang terkait dengan bidang formulir,
sumber teks yang ditampilkan di bilah status ketika bidang formulir memiliki fokus.

<br />

*** ** * ** ***

Jika disetel ke false, teks status tidak akan diterapkan.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Mendapatkan atau mengatur teks bantuan yang terkait dengan bidang formulir,
sumber teks yang ditampilkan dalam kotak pesan ketika bidang formulir memiliki fokus dan pengguna menekan F1.

<br />

*** ** * ** ***

Jika disetel ke false, teks bantuan tidak akan diterapkan.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Mendapatkan atau mengatur teks bantuan yang terkait dengan bidang formulir,
sumber teks yang ditampilkan dalam kotak pesan ketika bidang formulir memiliki fokus dan pengguna menekan F1.

<br />

*** ** * ** ***

Jika disetel ke false, teks bantuan tidak akan diterapkan.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final String getValue()
```


Mendapatkan atau mengatur nilai bidang formulir, yang mewakili masukan teks.


**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Mendapatkan atau mengatur nilai bidang formulir, yang mewakili masukan teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


Mendapatkan atau mengatur panjang maksimum input untuk bidang formulir.


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


Mendapatkan atau mengatur panjang maksimum input untuk bidang formulir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

