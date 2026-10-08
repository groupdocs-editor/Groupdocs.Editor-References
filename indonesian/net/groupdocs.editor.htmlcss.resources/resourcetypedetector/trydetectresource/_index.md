---
title: "TryDetectResource"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mencoba menganalisis aliran input dan membuat salah satu sumber daya HTML yang didukung darinya dengan mempertimbangkan tipe asumsi yang ditentukan jika tidak null."
type: docs
weight: 20
url: /id/net/groupdocs.editor.htmlcss.resources/resourcetypedetector/trydetectresource/
---
## ResourceTypeDetector.TryDetectResource method

Mencoba menganalisis aliran masukan dan membuat salah satu sumber daya HTML yang didukung darinya, dengan mempertimbangkan tipe asumsi yang ditentukan, jika tidak null

```csharp
public static IHtmlResource TryDetectResource(Stream inputResourceStream, string name, 
    IResourceType assumptiveFormat)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputResourceStream | Stream | Aliran input, yang kemungkinan berisi sumber daya HTML. Jika tidak valid, sebuah pengecualian akan dilempar. |
| nama | String | Nama sumber daya, yang akan digunakan untuk sumber daya yang dibuat dan dikembalikan pada keberhasilan. Tidak boleh NULL, kosong, atau spasi. |
| assumptiveFormat | IResourceType | Format asumsi dari sumber daya HTML input, yang berguna untuk mencapai kinerja terbaik. Jika benar-benar tidak diketahui, gunakan nilai NULL. Mungkin tidak tepat, ini hanya akan memperburuk kinerja. |

### Nilai Kembalian

Instance, yang mengimplementasikan antarmuka 'IHtmlResource' dan mewakili salah satu sumber daya HTML yang didukung pada keberhasilan, atau NULL pada kegagalan.

### Lihat Juga

* interface [IHtmlResource](../../ihtmlresource)
* interface [IResourceType](../../iresourcetype)
* class [ResourceTypeDetector](../../resourcetypedetector)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
