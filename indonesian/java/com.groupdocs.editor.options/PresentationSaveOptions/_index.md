---
title: "PresentationSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengizinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen Presentation yang kompatibel dengan PowerPoint"
type: docs
weight: 34
url: /id/java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Mengizinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan Presentation
(dokumen yang kompatibel dengan PowerPoint)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Konstruktor tanpa parameter ini membuat instance baru dari PresentationSaveOptions dengan format keluaran PPTX (dapat diubah kemudian melalui |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) properti)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Membuat instance baru dari PresentationSaveOptions dengan |
format keluaran Presentation yang wajib, sementara semua parameter lain adalah
bawaan
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPassword()](#getPassword--) | Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk |
menyandikan dokumen Presentation hasil.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mengizinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk menyandikan dokumen Presentation hasil. |
|
|  | [getSlideNumber()](#getSlideNumber--) | Mengizinkan untuk menyisipkan slide yang diedit ke dalam presentasi yang ada alih-alih membuat presentasi satu slide baru (perilaku default). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Mengizinkan untuk menyisipkan slide yang diedit ke dalam presentasi yang ada alih-alih membuat presentasi satu slide baru (perilaku default). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Bendera boolean, yang menentukan apakah slide yang diedit harus menggantikan slide yang ada dalam presentasi asli pada posisi, yang ditentukan oleh |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) properti, atau harus disisipkan antara slide yang ada dan slide sebelumnya, tanpa mengganti isinya.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Bendera boolean, yang menentukan apakah slide yang diedit harus menggantikan slide yang ada dalam presentasi asli pada posisi, yang ditentukan oleh |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) properti, atau harus disisipkan antara slide yang ada dan slide sebelumnya, tanpa mengganti isinya.
|
|  | [getOutputFormat()](#getOutputFormat--) | Mengizinkan untuk menentukan format Presentation, yang akan digunakan untuk menyimpan dokumen |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Mengizinkan untuk menentukan format Presentation, yang akan digunakan untuk menyimpan dokumen |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Mengizinkan untuk menentukan array dengan nomor slide berbasis 1 yang harus dihapus dari presentasi selama penyimpanan, jika slide yang diedit disisipkan ke dalam presentasi yang ada. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Mengizinkan untuk menentukan array dengan nomor slide berbasis 1 yang harus dihapus dari presentasi selama penyimpanan, jika slide yang diedit disisipkan ke dalam presentasi yang ada. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Konstruktor tanpa parameter ini membuat instance baru dari PresentationSaveOptions dengan format keluaran PPTX (dapat diubah kemudian melalui
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) properti)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Membuat instance baru dari PresentationSaveOptions dengan
format keluaran Presentation yang wajib, sementara semua parameter lain adalah
bawaan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Format keluaran wajib, di mana dokumen Presentation harus disimpan |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk
menyandikan dokumen Presentation hasil. Secara default adalah NULL -
kata sandi tidak akan diatur. Atur ke NULL atau string kosong untuk menghapusnya
kata sandi, jika sebelumnya telah diatur.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mengizinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk menyandikan dokumen Presentation hasil.
Secara default adalah NULL - kata sandi tidak akan diatur. Atur ke NULL atau string kosong untuk menghapus kata sandi, jika sebelumnya telah diatur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Mengizinkan untuk menyisipkan slide yang diedit ke dalam presentasi yang ada alih-alih membuat presentasi satu slide baru (perilaku default).
Nomor slide adalah nomor berbasis 1 untuk sebuah slide dalam presentasi, yang dimuat dalam kelas Editor. Jika nilainya 0 (nilai default), presentasi baru akan dibuat dengan satu slide yang diedit. Jika nilainya lebih besar atau lebih kecil dari nol, dan ada presentasi yang valid, yang dimuat dalam kelas Editor, slide yang diedit, yang disimpan di dalam instance EditableDocument input, akan disisipkan ke dalam presentasi ini.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Mengizinkan untuk menyisipkan slide yang diedit ke dalam presentasi yang ada alih-alih membuat presentasi satu slide baru (perilaku default).
Nomor slide adalah nomor berbasis 1 untuk sebuah slide dalam presentasi, yang dimuat dalam kelas Editor. Jika nilainya 0 (nilai default), presentasi baru akan dibuat dengan satu slide yang diedit. Jika nilainya lebih besar atau lebih kecil dari nol, dan ada presentasi yang valid, yang dimuat dalam kelas Editor, slide yang diedit, yang disimpan di dalam instance EditableDocument input, akan disisipkan ke dalam presentasi ini.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


Bendera boolean, yang menentukan apakah slide yang diedit harus menggantikan slide yang ada dalam presentasi asli pada posisi, yang ditentukan oleh
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) properti, atau harus disisipkan antara slide yang ada dan slide sebelumnya, tanpa mengganti isinya.
Secara default adalah false \\u2014 slide yang ada akan diganti. Properti ini diabaikan, jika nilai dari
SlideNumber
properti (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) diatur ke '0'.

<br />

*** ** * ** ***

Secara default slide diganti. Ini berarti bahwa jika presentasi yang diberikan memiliki 5 slide, dan SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, maka slide ke‑4 akan diganti dengan slide yang baru diedit, sementara jumlah total slide dalam presentasi (5) tetap tidak berubah. Namun, jika nilai properti ini diatur ke *true*, slide yang baru diedit akan disisipkan sebagai slide ke‑4, dan semua slide berikutnya akan digeser ke akhir: slide \"old\" ke‑4 menjadi ke‑5, dan ke‑5 menjadi ke‑6, dan jumlah total slide dalam presentasi akan bertambah satu menjadi 6.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Bendera boolean, yang menentukan apakah slide yang diedit harus menggantikan slide yang ada dalam presentasi asli pada posisi, yang ditentukan oleh
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) properti, atau harus disisipkan antara slide yang ada dan slide sebelumnya, tanpa mengganti isinya.
Secara default adalah false \\u2014 slide yang ada akan diganti. Properti ini diabaikan, jika nilai dari
SlideNumber
properti (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) diatur ke '0'.

<br />

*** ** * ** ***

Secara default slide diganti. Ini berarti bahwa jika presentasi yang diberikan memiliki 5 slide, dan SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, maka slide ke‑4 akan diganti dengan slide yang baru diedit, sementara jumlah total slide dalam presentasi (5) tetap tidak berubah. Namun, jika nilai properti ini diatur ke *true*, slide yang baru diedit akan disisipkan sebagai slide ke‑4, dan semua slide berikutnya akan digeser ke akhir: slide \"old\" ke‑4 menjadi ke‑5, dan ke‑5 menjadi ke‑6, dan jumlah total slide dalam presentasi akan bertambah satu menjadi 6.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Mengizinkan untuk menentukan format Presentation, yang akan digunakan untuk menyimpan dokumen

<br />

*** ** * ** ***

Format output biasanya diatur dalam konstruktor kelas ini, karena bersifat wajib. Properti ini memungkinkan untuk memperoleh atau mengubah format output nanti, ketika instance kelas [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) sudah dibuat.

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


Mengizinkan untuk menentukan format Presentation, yang akan digunakan untuk menyimpan dokumen

<br />

*** ** * ** ***

Format output biasanya diatur dalam konstruktor kelas ini, karena bersifat wajib. Properti ini memungkinkan untuk memperoleh atau mengubah format output nanti, ketika instance kelas [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) sudah dibuat.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


Mengizinkan untuk menentukan array dengan nomor slide berbasis 1 yang harus dihapus dari presentasi selama proses penyimpanan, dalam kasus ketika slide yang diedit disisipkan ke dalam presentasi yang ada. Ketika slide yang diedit disimpan bukan sebagai presentasi satu‑slide baru (perilaku default), melainkan disimpan ke dalam presentasi yang ada (menggunakan #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int)), juga memungkinkan menghapus beberapa slide tertentu dari presentasi ini dengan menentukan nomor mereka dalam array ini. Secara default array ini adalah null \\u2014 tidak ada slide yang akan dihapus. Namun, ketika array ini tidak null dan tidak kosong, serta berisi setidaknya satu nomor slide yang valid, setelah dokumen Presentation output dihasilkan dengan konten slide yang diedit, slide dengan nomor yang ditentukan akan dihapus dari presentasi tepat sebelum menulis isinya ke aliran output atau file. Nomor slide dalam array ini berbasis 1, bukan berbasis 0. Nomor yang tidak valid (kurang dari 1 atau lebih besar dari total jumlah slide) akan diabaikan.


**Returns:**
int[] - Array nomor slide berbasis 1 untuk dihapus, atau null jika tidak ada yang harus dihapus.

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Mengizinkan untuk menentukan array dengan nomor slide berbasis 1 yang harus dihapus dari presentasi selama penyimpanan, dalam kasus ketika slide yang diedit disisipkan ke dalam presentasi yang ada. Nomor slide dalam array ini berbasis 1. Nomor yang tidak valid akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int[] | Array nomor slide berbasis 1 untuk dihapus (bisa null atau kosong). |
|

