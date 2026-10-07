---
title: "IHtmlResource"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu instance dari sumber daya HTML yang tidak diketahui, raster atau vektor, gambar, stylesheet, font, teks, sumber daya CSS, XML, dll."
type: docs
weight: 12
url: /id/java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

Mewakili satu instance dari sumber daya HTML yang tidak diketahui (raster atau vektor gambar,
stylesheet, font, sumber daya teks (CSS, XML), dll.)

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getName()](#getName--) | Nama sumber daya HTML |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Nama file yang benar dari sumber daya yang ditentukan dengan file yang sesuai |
ekstensi
|
|  | [getType()](#getType--) | Tipe sumber daya HTML |
|
|  | [getByteContent()](#getByteContent--) | Konten sumber daya HTML dalam bentuk aliran byte |
|
|  | [getTextContent()](#getTextContent--) | Konten sumber daya HTML dalam bentuk string teks yang dienkode base64 |
untuk sumber daya biner atau teks sederhana untuk sumber daya tekstual
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Menyimpan sumber daya saat ini ke file yang ditentukan |
|
### getName() {#getName--}
```
public abstract String getName()
```


Nama sumber daya HTML


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


Nama file yang benar dari sumber daya yang ditentukan dengan file yang sesuai
ekstensi


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


Tipe sumber daya HTML


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


Konten sumber daya HTML dalam bentuk aliran byte


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Konten sumber daya HTML dalam bentuk string teks yang dienkode base64
untuk sumber daya biner atau teks sederhana untuk sumber daya tekstual


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Menyimpan sumber daya saat ini ke file yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Jalur lengkap ke file, yang akan dibuat atau ditimpa dengan konten sumber daya saat ini |
|

