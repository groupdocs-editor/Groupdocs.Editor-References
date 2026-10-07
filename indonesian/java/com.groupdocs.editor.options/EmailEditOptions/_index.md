---
title: "EmailEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk mengedit dokumen dalam berbagai format email elektronik"
type: docs
weight: 14
url: /id/java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Memungkinkan untuk menentukan opsi khusus untuk mengedit dokumen dalam berbagai format surat elektronik (email)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | Menginisialisasi instance baru dari kelas [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), di mana semua opsi diatur ke nilai defaultnya |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Menginisialisasi instance baru dari kelas [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) dengan |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parameter
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Memungkinkan mengontrol bagian mana dari pesan email yang harus dikirim ke output [EditableDocument](../../com.groupdocs.editor/editabledocument) dan kemudian ke HTML yang dihasilkan |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Memungkinkan mengontrol bagian mana dari pesan email yang harus dikirim ke output [EditableDocument](../../com.groupdocs.editor/editabledocument) dan kemudian ke HTML yang dihasilkan |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Menginisialisasi instance baru dari kelas [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), di mana semua opsi diatur ke nilai defaultnya


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Menginisialisasi instance baru dari kelas [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) dengan
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parameter


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | mailMessageOutput | int | Output pesan email, yang juga dapat ditentukan melalui properti |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Memungkinkan mengontrol bagian mana dari pesan email yang harus dikirim ke output [EditableDocument](../../com.groupdocs.editor/editabledocument) dan kemudian ke HTML yang dihasilkan
Nilai: enum bertanda yang mengontrol bagian-bagian pesan email, yang harus diproses. Nilai default adalah MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Memungkinkan mengontrol bagian mana dari pesan email yang harus dikirim ke output [EditableDocument](../../com.groupdocs.editor/editabledocument) dan kemudian ke HTML yang dihasilkan
Nilai: enum bertanda yang mengontrol bagian-bagian pesan email, yang harus diproses. Nilai default adalah MailMessageOutput.All


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

