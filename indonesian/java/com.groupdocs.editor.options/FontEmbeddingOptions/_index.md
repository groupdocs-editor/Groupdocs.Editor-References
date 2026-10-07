---
title: "FontEmbeddingOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Opsi penyematan font mengontrol sumber daya font mana yang harus disematkan ke dalam dokumen WordProcessing output"
type: docs
weight: 17
url: /id/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Opsi penyematan font mengontrol sumber daya font mana yang harus disematkan ke dalam
dokumen WordProcessing output


*** ** * ** ***

Opsi penyematan font diterapkan selama penyimpanan dokumen (dari EditableDocument menengah ke format WordProcessing output), enum ini termasuk sebagai properti dalam WordProcessingSaveOptions, dari mana harus digunakan

<br />


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | Jangan sematkan sumber daya font apa pun baik dari EditableDocument maupun dari |
sistem.
|
|  | [EmbedAll](#EmbedAll) | Analisis konten dokumen dari EditableDocument input, temukan semua font yang digunakan |
dan sematkan ke dalam dokumen WordProcessing output.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Sama persis dengan [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), tetapi kecualikan font-font tersebut, |
yang diperlakukan oleh OS sebagai font sistem
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


Jangan sematkan sumber daya font apa pun baik dari EditableDocument maupun dari
sistem. Nilai default.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Analisis konten dokumen dari EditableDocument input, temukan semua font yang digunakan
dan menyematkannya ke dalam dokumen WordProcessing output. Pada awalnya
GroupDocs.Editor mengambil font dari sumber daya font dalam EditableDocument.
Jika tidak mencukupi atau hilang, maka GroupDocs.Editor mengambil font
dari OS.


*** ** * ** ***

Pertama-tama GroupDocs.Editor menganalisis konten EditableDocument dan membuat daftar semua font yang digunakan. Kemudian font-font tersebut dicari dalam sumber daya font EditableDocument. Jika EditableDocument berisi beberapa sumber daya font yang tidak terlibat dalam konten dokumen, sumber daya tersebut diabaikan. Jika ada beberapa font yang digunakan dalam konten dokumen tetapi tidak memiliki sumber daya font yang sesuai di EditableDocument, maka GroupDocs.Editor mencoba menemukannya di OS. Opsi ini mirip dengan opsi "Embed fonts in the file" dengan semua sub-opsi dimatikan di Microsoft Word 2007 dan yang lebih tinggi

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Sama persis dengan [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), tetapi kecualikan font-font tersebut,
yang diperlakukan oleh OS sebagai font sistem


*** ** * ** ***

MS Windows memiliki konsep font sistem, yang merupakan font paling dasar dan paling banyak digunakan oleh Windows itu sendiri. Saat menggunakan opsi ini, GroupDocs.Editor berperilaku seperti pada kasus [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), tetapi akhirnya meninjau kumpulan font yang diperoleh dan mengecualikan font yang diperlakukan oleh OS sebagai font sistem. Opsi ini mirip dengan opsi "Embed fonts in the file" + "Do not embed common system fonts" di Microsoft Word 2007 dan yang lebih tinggi

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
