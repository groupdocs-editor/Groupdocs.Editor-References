---
title: "PdfCompliance"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Menentukan tingkat kepatuhan standar PDF"
type: docs
weight: 28
url: /id/java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

Menentukan tingkat kepatuhan standar PDF

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Pdf17](#Pdf17) | Standar PDF 1.7 (ISO 32000-1) |
|
|  | [Pdf20](#Pdf20) | Standar PDF 2.0 (ISO 32000-2) |
|
|  | [PdfA1a](#PdfA1a) | Standar PDF/A-1a. |
|
|  | [PdfA1b](#PdfA1b) | PDF/A-1b (ISO 19005-1). |
|
|  | [PdfA2a](#PdfA2a) | Standar PDF/A-2a (ISO 19005-2). |
|
|  | [PdfA2u](#PdfA2u) | Standar PDF/A-2u (ISO 19005-2). |
|
|  | [PdfUa1](#PdfUa1) | Standar PDF/UA-1 (ISO 14289-1). |
|
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


Standar PDF 1.7 (ISO 32000-1)


### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


Standar PDF 2.0 (ISO 32000-2)


### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


Standar PDF/A-1a. Tingkat ini mencakup semua persyaratan PDF/A-1b dan tambahan memerlukan agar struktur dokumen disertakan
(juga dikenal sebagai "tagged"), dengan tujuan memastikan bahwa konten dokumen dapat dicari dan digunakan kembali.

<br />

*** ** * ** ***

Perhatikan bahwa mengekspor struktur dokumen secara signifikan meningkatkan konsumsi memori, terutama untuk dokumen besar.

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b (ISO 19005-1). PDF/A-1b memiliki tujuan memastikan reproduksi yang dapat diandalkan dari tampilan visual dokumen.


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


Standar PDF/A-2a (ISO 19005-2). Tingkat ini mencakup semua persyaratan PDF/A-2u dan tambahan memerlukan agar struktur dokumen disertakan (juga dikenal sebagai "tagged"), dengan tujuan memastikan bahwa konten dokumen dapat dicari dan digunakan kembali.

<br />

*** ** * ** ***

Perhatikan bahwa mengekspor struktur dokumen secara signifikan meningkatkan konsumsi memori, terutama untuk dokumen besar.

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


Standar PDF/A-2u (ISO 19005-2). PDF/A-2u memiliki tujuan mempertahankan tampilan visual statis dokumen seiring waktu, terlepas dari alat dan sistem yang digunakan untuk membuat, menyimpan, atau merender berkas. Selain itu, setiap teks yang terdapat dalam dokumen dapat diekstrak secara andal sebagai rangkaian kode poin Unicode.


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


Standar PDF/UA-1 (ISO 14289-1). Tujuan utama PDF/UA adalah mendefinisikan cara merepresentasikan dokumen elektronik dalam format PDF sehingga file dapat diakses.


