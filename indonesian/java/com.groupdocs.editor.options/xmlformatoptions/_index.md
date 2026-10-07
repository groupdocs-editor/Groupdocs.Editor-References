---
title: "XmlFormatOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Berisi opsi yang memungkinkan penyesuaian pemformatan dokumen XML ketika direpresentasikan sebagai HTML"
type: docs
weight: 52
url: /id/java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

Berisi opsi yang memungkinkan menyesuaikan pemformatan dokumen XML ketika ditampilkan sebagai HTML.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | Ketika diaktifkan, setiap pasangan atribut-nilai dalam setiap elemen XML akan ditempatkan pada baris baru. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | Ketika diaktifkan, setiap pasangan atribut-nilai dalam setiap elemen XML akan ditempatkan pada baris baru. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | Ketika diaktifkan, node teks daun (konten tekstual di dalam elemen XML yang tidak memiliki anak) akan ditampilkan pada baris baru dengan indentasi kiri yang lebih besar. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | Ketika diaktifkan, node teks daun (konten tekstual di dalam elemen XML yang tidak memiliki anak) akan ditampilkan pada baris baru dengan indentasi kiri yang lebih besar. |
|
|  | [getLeftIndent()](#getLeftIndent--) | Memungkinkan menentukan offset untuk indentasi kiri setiap baris baru. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Memungkinkan menentukan offset untuk indentasi kiri setiap baris baru. |
|
|  | [isDefault()](#isDefault--) | Menunjukkan apakah instance opsi pemformatan XML ini memiliki nilai default |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


Ketika diaktifkan, setiap pasangan atribut-nilai dalam setiap elemen XML akan ditempatkan pada baris baru.
Secara default bernilai false (dinonaktifkan) \\u2014 semua pasangan atribut-nilai ditempatkan dalam satu baris.


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


Ketika diaktifkan, setiap pasangan atribut-nilai dalam setiap elemen XML akan ditempatkan pada baris baru.
Secara default bernilai false (dinonaktifkan) \\u2014 semua pasangan atribut-nilai ditempatkan dalam satu baris.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


Ketika diaktifkan, node teks daun (konten tekstual di dalam elemen XML yang tidak memiliki anak) akan ditampilkan pada baris baru dengan indentasi kiri yang lebih besar.
Secara default bernilai false (dinonaktifkan) \\u2014 node teks daun ditempatkan pada baris yang sama dengan induknya, tanpa indentasi baru.


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


Ketika diaktifkan, node teks daun (konten tekstual di dalam elemen XML yang tidak memiliki anak) akan ditampilkan pada baris baru dengan indentasi kiri yang lebih besar.
Secara default bernilai false (dinonaktifkan) \\u2014 node teks daun ditempatkan pada baris yang sama dengan induknya, tanpa indentasi baru.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


Memungkinkan menentukan offset untuk indentasi kiri setiap baris baru. Tidak dapat berupa nilai tanpa satuan yang tidak nol. Secara default adalah 10pt


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


Memungkinkan menentukan offset untuk indentasi kiri setiap baris baru. Tidak dapat berupa nilai tanpa satuan yang tidak nol. Secara default adalah 10pt


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Menunjukkan apakah instance opsi pemformatan XML ini memiliki nilai default


**Returns:**
boolean
