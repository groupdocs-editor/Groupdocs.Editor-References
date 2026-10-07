---
title: "MarkdownEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk mengedit dokumen dalam format Markdown."
type: docs
weight: 21
url: /id/java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Memungkinkan untuk menentukan opsi khusus untuk mengedit dokumen dalam format Markdown.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | Membuat dan mengembalikan instance baru dari kelas MarkdownEditOptions, |
di mana semua opsi diatur ke nilai defaultnya
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Mengizinkan kontrol cara gambar disimpan saat mengonversi dokumen Markdown |
ke Html.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Mengizinkan kontrol cara gambar disimpan saat mengonversi dokumen Markdown |
ke Html.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


Membuat dan mengembalikan instance baru dari kelas MarkdownEditOptions,
di mana semua opsi diatur ke nilai defaultnya


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Mengizinkan kontrol cara gambar disimpan saat mengonversi dokumen Markdown
ke Html.
Nilai: Callback penyimpanan gambar.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Mengizinkan kontrol cara gambar disimpan saat mengonversi dokumen Markdown
ke Html.
Nilai: Callback penyimpanan gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

