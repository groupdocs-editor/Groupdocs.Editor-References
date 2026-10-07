---
title: "EmailSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen email elektronik."
type: docs
weight: 15
url: /id/java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen surat elektronik (email)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | Menginisialisasi instance baru dari kelas [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), di mana semua opsi diatur ke nilai default. |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | Menginisialisasi instance baru dari kelas [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) dengan |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parameter
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Memungkinkan untuk mengontrol bagian mana dari pesan email yang harus disampaikan ke dokumen email output, yang akan dihasilkan dan disimpan dengan metode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-). |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Memungkinkan untuk mengontrol bagian mana dari pesan email yang harus disampaikan ke dokumen email output, yang akan dihasilkan dan disimpan dengan metode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-). |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Menginisialisasi instance baru dari kelas [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), di mana semua opsi diatur ke nilai default.


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


Menginisialisasi instance baru dari kelas [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) dengan
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


Memungkinkan untuk mengontrol bagian mana dari pesan email yang harus disampaikan ke dokumen email output, yang akan dihasilkan dan disimpan dengan metode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-).
Nilai: enum bertanda yang mengontrol bagian-bagian pesan email, yang harus diproses. Nilai default adalah MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Memungkinkan untuk mengontrol bagian mana dari pesan email yang harus disampaikan ke dokumen email output, yang akan dihasilkan dan disimpan dengan metode [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-).
Nilai: enum bertanda yang mengontrol bagian-bagian pesan email, yang harus diproses. Nilai default adalah MailMessageOutput.All


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

