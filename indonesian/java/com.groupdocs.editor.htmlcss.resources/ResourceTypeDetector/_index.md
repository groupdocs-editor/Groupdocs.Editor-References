---
title: "ResourceTypeDetector"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Metode statis utilitas untuk mendeteksi format tipe sumber daya"
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

Metode statis utilitas untuk mendeteksi tipe sumber daya (format).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | Mendeteksi tipe dari nama file yang ditentukan dan mengembalikan sebuah instance dari |
IResourceType yang bersangkutan
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | Mencoba menganalisis aliran input dan membuat salah satu HTML yang didukung |
sumber daya darinya, dengan mempertimbangkan tipe asumsi yang ditentukan, jika itu
tidak null
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


Mendeteksi tipe dari nama file yang ditentukan dan mengembalikan sebuah instance dari
IResourceType yang bersangkutan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama file | java.lang.String | Nama file input, dari mana metode ini akan mencoba mengekstrak implementasi IResourceType yang dihasilkan |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


Mencoba menganalisis aliran input dan membuat salah satu HTML yang didukung
sumber daya darinya, dengan mempertimbangkan tipe asumsi yang ditentukan, jika itu
tidak null


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | Aliran input, yang kemungkinan berisi sumber daya HTML. Jika tidak valid, sebuah pengecualian akan dilempar. |
|
|  | nama | java.lang.String | Nama sumber daya, yang akan digunakan untuk sumber daya yang dibuat dan dikembalikan pada keberhasilan. Tidak boleh NULL, kosong, atau spasi |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | Format yang diasumsikan dari sumber daya HTML input, yang berguna untuk mencapai kinerja terbaik. Jika benar-benar tidak diketahui, gunakan nilai NULL. Mungkin tidak tepat, ini hanya akan memperburuk kinerja. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

