---
title: "IImageResource"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili sumber daya gambar dari tipe apa pun, raster atau vektor"
type: docs
weight: 13
url: /id/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Mewakili sumber daya gambar dari jenis apa pun, raster atau vektor.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getType()](#getType--) | Dalam implementasi, tipe harus mengembalikan tipe gambar spesifik sebagai sebuah |
instansi ImageType spesifik, yang mengenkapsulasi semua info khusus tipe
|
|  | [getAspectRatio()](#getAspectRatio--) | Dalam implementasi, tipe harus mengembalikan rasio aspek gambar tertentu |
tanpa mempedulikan tipenya.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Dalam implementasi, tipe harus mengembalikan dimensi linier gambar. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


Dalam implementasi, tipe harus mengembalikan tipe gambar spesifik sebagai sebuah
instansi ImageType spesifik, yang mengenkapsulasi semua info khusus tipe


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


Dalam implementasi, tipe harus mengembalikan rasio aspek gambar tertentu
tanpa mempedulikan tipenya. Baik gambar vektor maupun raster memiliki
rasio aspek antara lebar dan tingginya.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


Dalam implementasi, tipe harus mengembalikan dimensi linier gambar. Untuk
gambar raster, dimensi intrinsik dalam piksel. Gambar vektor, dalam
sebaliknya, tidak memiliki dimensi tetap, tetapi metadata mereka dapat berisi
beberapa dimensi dasar dalam satuan pengukuran yang berbeda.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
