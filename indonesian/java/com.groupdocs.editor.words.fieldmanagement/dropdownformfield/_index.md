---
title: "DropDownFormField"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili bidang formulir yang menampilkan daftar drop-down."
type: docs
weight: 14
url: /id/java/com.groupdocs.editor.words.fieldmanagement/dropdownformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class DropDownFormField implements IFormField
```

Mewakili bidang formulir yang menampilkan daftar drop-down.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DropDownFormField(String stylesheet, String name)](#DropDownFormField-java.lang.String-java.lang.String-) | Menginisialisasi instance baru dari kelas [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) dengan stylesheet dan nama yang ditentukan. |
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
|  | [getSelectedIndex()](#getSelectedIndex--) | Mendapatkan atau mengatur indeks item yang dipilih dalam daftar drop-down. |
|
|  | [setSelectedIndex(int value)](#setSelectedIndex-int-) | Mendapatkan atau mengatur indeks item yang dipilih dalam daftar drop-down. |
|
|  | [getType()](#getType--) | Mendapatkan tipe bidang formulir, yang selalu FormFieldType.DropDown untuk kelas ini. |
|
|  | [getLocaleId()](#getLocaleId--) | Mendapatkan atau mengatur ID lokal field formulir, yang mewakili budaya atau pengaturan regional yang terkait dengan field formulir. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Mendapatkan atau mengatur ID lokal field formulir, yang mewakili budaya atau pengaturan regional yang terkait dengan field formulir. |
|
|  | [getStatusText()](#getStatusText--) | Mendapatkan atau mengatur teks status yang terkait dengan bidang formulir, sumber teks yang ditampilkan di bilah status ketika bidang formulir memiliki fokus. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Mendapatkan atau mengatur teks status yang terkait dengan bidang formulir, sumber teks yang ditampilkan di bilah status ketika bidang formulir memiliki fokus. |
|
|  | [getHelpText()](#getHelpText--) | Mendapatkan atau mengatur teks bantuan yang terkait dengan field formulir, sumber teks yang ditampilkan dalam kotak pesan ketika field formulir memiliki fokus dan pengguna menekan F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Mendapatkan atau mengatur teks bantuan yang terkait dengan field formulir, sumber teks yang ditampilkan dalam kotak pesan ketika field formulir memiliki fokus dan pengguna menekan F1. |
|
|  | [getValue()](#getValue--) | Mendapatkan atau mengatur nilai bidang formulir, yang mewakili daftar opsi dalam daftar drop-down. |
|
|  | [setValue(List<String> value)](#setValue-java.util.List-java.lang.String--) | Mendapatkan atau mengatur nilai bidang formulir, yang mewakili daftar opsi dalam daftar drop-down. |
|
### DropDownFormField(String stylesheet, String name) {#DropDownFormField-java.lang.String-java.lang.String-}
```
public DropDownFormField(String stylesheet, String name)
```


Menginisialisasi instance baru dari kelas [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) dengan stylesheet dan nama yang ditentukan.


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
### getSelectedIndex() {#getSelectedIndex--}
```
public final int getSelectedIndex()
```


Mendapatkan atau mengatur indeks item yang dipilih dalam daftar drop-down.


**Returns:**
int
### setSelectedIndex(int value) {#setSelectedIndex-int-}
```
public final void setSelectedIndex(int value)
```


Mendapatkan atau mengatur indeks item yang dipilih dalam daftar drop-down.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getType() {#getType--}
```
public final int getType()
```


Mendapatkan tipe bidang formulir, yang selalu FormFieldType.DropDown untuk kelas ini.


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
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
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
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
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


Mendapatkan atau mengatur teks status yang terkait dengan bidang formulir, sumber teks yang ditampilkan di bilah status ketika bidang formulir memiliki fokus.

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


Mendapatkan atau mengatur teks status yang terkait dengan bidang formulir, sumber teks yang ditampilkan di bilah status ketika bidang formulir memiliki fokus.

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


Mendapatkan atau mengatur teks bantuan yang terkait dengan field formulir, sumber teks yang ditampilkan dalam kotak pesan ketika field formulir memiliki fokus dan pengguna menekan F1.

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


Mendapatkan atau mengatur teks bantuan yang terkait dengan field formulir, sumber teks yang ditampilkan dalam kotak pesan ketika field formulir memiliki fokus dan pengguna menekan F1.

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
public final List<String> getValue()
```


Mendapatkan atau mengatur nilai bidang formulir, yang mewakili daftar opsi dalam daftar drop-down.


**Returns:**
java.util.List<java.lang.String>
### setValue(List<String> value) {#setValue-java.util.List-java.lang.String--}
```
public final void setValue(List<String> value)
```


Mendapatkan atau mengatur nilai bidang formulir, yang mewakili daftar opsi dalam daftar drop-down.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<java.lang.String> |  |

