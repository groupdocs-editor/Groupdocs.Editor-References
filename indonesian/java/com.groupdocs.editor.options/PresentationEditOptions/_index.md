---
title: "PresentationEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk mengedit dokumen dalam semua format Presentasi yang didukung dan kompatibel dengan PowerPoint"
type: docs
weight: 32
url: /id/java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Memungkinkan menentukan opsi khusus untuk mengedit semua dokumen yang didukung
Format Presentasi (kompatibel dengan PowerPoint)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | Memungkinkan untuk menentukan nomor slide yang harus dibuka untuk diedit |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Memungkinkan untuk menentukan nomor slide yang harus dibuka untuk diedit |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Menentukan apakah slide tersembunyi harus disertakan atau tidak. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Menentukan apakah slide tersembunyi harus disertakan atau tidak. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Memungkinkan untuk menentukan nomor slide yang harus dibuka untuk diedit


*** ** * ** ***

Nomor slide adalah indeks berbasis nol dari sebuah slide, yang memungkinkan untuk menentukan dan memilih satu slide tertentu dari presentasi untuk diedit. Jika kurang dari 0, slide pertama akan dipilih (sama dengan SlideNumber = 0). Jika lebih besar dari jumlah semua slide dalam presentasi, slide terakhir akan dipilih. Jika presentasi input hanya berisi satu slide, opsi ini akan diabaikan, dan slide tunggal tersebut akan diedit. Jika mencoba membuka slide tersembunyi untuk diedit, sementara opsi ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) disetel ke 'false', pengecualian akan dilempar.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Memungkinkan untuk menentukan nomor slide yang harus dibuka untuk diedit


*** ** * ** ***

Nomor slide adalah indeks berbasis nol dari sebuah slide, yang memungkinkan untuk menentukan dan memilih satu slide tertentu dari presentasi untuk diedit. Jika kurang dari 0, slide pertama akan dipilih (sama dengan SlideNumber = 0). Jika lebih besar dari jumlah semua slide dalam presentasi, slide terakhir akan dipilih. Jika presentasi input hanya berisi satu slide, opsi ini akan diabaikan, dan slide tunggal tersebut akan diedit. Jika mencoba membuka slide tersembunyi untuk diedit, sementara opsi ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) disetel ke 'false', pengecualian akan dilempar.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Menentukan apakah slide tersembunyi harus disertakan atau tidak. Defaultnya adalah
false - slide tersembunyi tidak ditampilkan dan pengecualian akan dilempar saat
mencoba mengeditnya.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Menentukan apakah slide tersembunyi harus disertakan atau tidak. Defaultnya adalah
false - slide tersembunyi tidak ditampilkan dan pengecualian akan dilempar saat
mencoba mengeditnya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

