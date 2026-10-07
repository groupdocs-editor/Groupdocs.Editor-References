---
title: "MarkdownImageLoadingAction"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mendefinisikan mode pemuatan gambar saat membuka file untuk diedit dalam format Markdown"
type: docs
weight: 23
url: /id/java/com.groupdocs.editor.options/markdownimageloadingaction/
---
**Inheritance:**
java.lang.Object
```
public final class MarkdownImageLoadingAction
```

Mendefinisikan mode pemuatan gambar saat membuka file untuk diedit dalam format Markdown

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Default](#Default) | GroupDocs.Editor akan memuat sumber daya ini seperti biasa |
|
|  | [Skip](#Skip) | GroupDocs.Editor akan melewatkan pemuatan gambar ini |
|
|  | [UserProvided](#UserProvided) | GroupDocs.Editor akan menggunakan array byte yang disediakan pengguna dalam |
M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])
sebagai data gambar
|
### Default {#Default}
```
public static final int Default
```


GroupDocs.Editor akan memuat sumber daya ini seperti biasa


### Skip {#Skip}
```
public static final int Skip
```


GroupDocs.Editor akan melewatkan pemuatan gambar ini


### UserProvided {#UserProvided}
```
public static final int UserProvided
```


GroupDocs.Editor akan menggunakan array byte yang disediakan pengguna dalam
M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])
sebagai data gambar


