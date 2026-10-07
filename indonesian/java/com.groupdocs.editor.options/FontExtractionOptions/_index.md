---
title: "FontExtractionOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Opsi ekstraksi font mengontrol font mana yang harus diekstrak dan dari mana"
type: docs
weight: 18
url: /id/java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Opsi ekstraksi font mengontrol font mana yang harus diekstrak dan dari
di mana

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [NotExtract](#NotExtract) | Tidak mengekstrak sumber daya font apa pun baik dari dokumen maupun dari |
sistem.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | Mengekstrak semua sumber daya font yang tertanam dalam Word input |
dokumen, terlepas dari apa mereka: khusus atau sistem.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Mengekstrak hanya sumber daya font yang tertanam, yang bersifat khusus (tidak |
sistem)
|
|  | [ExtractAll](#ExtractAll) | Mencoba mengekstrak semua font yang digunakan dalam WordProcessing input |
dokumen, termasuk font sistem.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


Tidak mengekstrak sumber daya font apa pun baik dari dokumen maupun dari
sistem. Nilai default.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


Mengekstrak semua sumber daya font yang tertanam dalam Word input
dokumen, terlepas dari apa mereka: khusus atau sistem.


*** ** * ** ***

Converter menemukan dan mengekstrak semua sumber daya font 100%, yang tertanam dalam dokumen WordProcessing input, tetapi tidak menentukan apakah mereka sistem atau khusus; tidak menyentuh Windows Registry atau folder sistem sama sekali.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


Mengekstrak hanya sumber daya font yang tertanam, yang bersifat khusus (tidak
sistem)


*** ** * ** ***

Converter menemukan dan mengekstrak semua sumber daya font yang tertanam, kemudian mencoba menentukan font mana yang merupakan sistem, dan mana yang tidak. Untuk mencapai ini, converter berusaha memperoleh daftar semua font sistem dengan menggunakan Windows Registry dan folder sistem, kemudian membandingkan daftar ini dengan kumpulan font yang tertanam. Akibatnya, hanya subset dari font yang tertanam tersebut, yang tidak ditemukan di sistem, yang akan dikembalikan.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


Mencoba mengekstrak semua font yang digunakan dalam WordProcessing input
dokumen, termasuk font sistem.


*** ** * ** ***

Converter sedang menganalisis dokumen WordProcessing input dan menemukan semua font yang digunakan di sana. Jika semua font tersebut tertanam dalam dokumen input, converter mengekstrak dan mengembalikannya. Jika tidak, jika kumpulan font yang tertanam tidak mencakup semua font yang digunakan dalam dokumen, atau kosong, converter mencoba mengekstrak sumber daya font ini dari sistem, dengan menggunakan Windows Registry dan folder sistem.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
