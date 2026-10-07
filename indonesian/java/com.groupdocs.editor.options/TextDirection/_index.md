---
title: "TextDirection"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili 3 varian kemungkinan cara memperlakukan arah teks dalam dokumen teks biasa."
type: docs
weight: 38
url: /id/java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Mewakili 3 varian kemungkinan cara memperlakukan arah teks dalam teks biasa.
dokumen

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | Arah Kiri-ke-Kanan, teks biasa, nilai default. |
|
|  | [RightToLeft](#RightToLeft) | Arah Kanan-ke-Kiri |
|
|  | [Auto](#Auto) | Deteksi arah otomatis. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


Arah Kiri-ke-Kanan, teks biasa, nilai default.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


Arah Kanan-ke-Kiri


### Auto {#Auto}
```
public static final int Auto
```


Deteksi arah otomatis. Ketika opsi ini dipilih dan teks berisi
karakter yang termasuk dalam skrip RTL, arah dokumen akan diatur
secara otomatis ke RTL.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
