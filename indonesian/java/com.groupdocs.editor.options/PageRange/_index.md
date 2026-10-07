---
title: "PageRange"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengkapsulkan satu rentang halaman yang dapat memiliki batas terbuka atau tertutup."
type: docs
weight: 27
url: /id/java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Mengkapsulkan satu rentang halaman, yang dapat memiliki batas terbuka atau tertutup. Secara default adalah "sepenuhnya terbuka" - mencakup semua halaman yang ada. Penomoran halaman dimulai dari 1, bukan dari 0.

<br />

*** ** * ** ***

Struct tidak dapat diubah, yang mengenkapsulasi rentang halaman, yang tidak terkait dengan dokumen tertentu, dan dapat mewakili rentang halaman untuk dokumen apa pun.

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [AllPages](#AllPages) | Mewakili semua halaman yang ada dalam sebuah dokumen. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | Nomor halaman mulai inklusif, dari mana rentang halaman ini dimulai. |
|
|  | [getEndNumber()](#getEndNumber--) | Nomor halaman akhir eksklusif, sampai mana rentang halaman ini berlanjut dan pada mana berhenti secara eksklusif. |
|
|  | [getCount()](#getCount--) | Jumlah halaman dalam rentang. |
|
|  | [isDefault()](#isDefault--) | Menunjukkan apakah instance ini mewakili rentang halaman default "sepenuhnya terbuka", yaitu. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Mendeteksi apakah instance PageRange ini sama dengan yang ditentukan |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | Membuat rentang halaman, yang dimulai dari halaman pertama dan memiliki jumlah halaman yang ditentukan |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Membuat rentang halaman, yang dimulai dari nomor halaman yang ditentukan dan berlanjut hingga akhir dokumen |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Membuat rentang halaman, yang dimulai dari nomor halaman yang ditentukan dan memiliki jumlah halaman yang ditentukan, atau jumlah halaman tak terbatas (hingga akhir) |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Membuat rentang halaman, yang dimulai dari nomor halaman yang ditentukan (inklusif) dan berlanjut sampai nomor halaman yang ditentukan (eksklusif) |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


Mewakili semua halaman yang ada dalam dokumen. Nilai default.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


Nomor halaman mulai inklusif, dari mana rentang halaman ini dimulai. Jika 1 - rentang halaman dimulai dari halaman pertama dokumen


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Nomor halaman akhir eksklusif, sampai mana rentang halaman ini berlanjut dan pada mana berhenti secara eksklusif. Jika 0 - rentang halaman menyebar hingga akhir dokumen


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Jumlah halaman dalam rentang. Jika 0 - rentang halaman menyebar hingga akhir dokumen tanpa mempedulikan berapa banyak halaman yang ada


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Menunjukkan apakah instance ini mewakili rentang halaman default "sepenuhnya terbuka", yaitu mencakup semua halaman dalam dokumen


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


Mendeteksi apakah instance PageRange ini sama dengan yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Instance PageRange lain untuk memeriksa kesetaraan |
|

**Returns:**
boolean - true berarti sama; false jika tidak sama

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


Membuat rentang halaman, yang dimulai dari halaman pertama dan memiliki jumlah halaman yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageCount | int | Jumlah halaman, harus lebih besar secara ketat dari nol |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


Membuat rentang halaman, yang dimulai dari nomor halaman yang ditentukan dan berlanjut hingga akhir dokumen


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | startPageNumber | int | Nomor halaman, dari mana rentang halaman dimulai, secara inklusif. Nomor halaman berbasis 1, jadi harus lebih besar secara ketat dari nol |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Membuat rentang halaman, yang dimulai dari nomor halaman yang ditentukan dan memiliki jumlah halaman yang ditentukan, atau jumlah halaman tak terbatas (hingga akhir)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | startPageNumber | int | Nomor halaman, dari mana rentang halaman dimulai, secara inklusif. Nomor halaman berbasis 1, jadi harus lebih besar secara ketat dari nol |
|
|  | pageCount | int | Jumlah halaman, harus lebih besar secara ketat dari nol. Jika nol - ini berarti semua halaman hingga akhir dokumen |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Membuat rentang halaman, yang dimulai dari nomor halaman yang ditentukan (inklusif) dan berlanjut sampai nomor halaman yang ditentukan (eksklusif)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | startPageNumber | int | Nomor halaman, dari mana rentang halaman dimulai, secara inklusif. Nomor halaman berbasis 1, jadi harus lebih besar secara ketat dari nol |
|
|  | endPageNumber | int | Nomor halaman, sampai mana rentang halaman berlanjut, secara eksklusif. Nomor halaman berbasis 1, jadi harus lebih besar secara ketat dari nol, dan juga harus lebih besar secara ketat dari startPageNumber |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
