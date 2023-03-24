---
title: EditableDocument
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Düzenleme öncesi ve sonrası içeriği içeren ara belge
type: docs
weight: 10
url: /tr/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Düzenleme öncesi ve sonrası içeriği içeren ara belge

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Mevcut tüm kaynakların bir listesini döndürür: tüm stil sayfaları, HTML'den görüntüler ve tüm stil sayfaları, yazı tipleri, audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Ses kaynaklarının bir listesini döndürür |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | CSS kaynaklarının bir listesini döndürür |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Bu HTML belgesi tarafından kullanılan harici yazı tipi kaynaklarının alınmasına izin verir |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Bu HTML belgesi tarafından kullanılan harici görüntü kaynaklarının (raster ve vektör görüntüleri) alınmasına izin verir. |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Bu Düzenlenebilir belgenin zaten atılıp atılmadığını (doğru) veya olmadığını (yanlış) belirler |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Bir HTML dosyasından EditableDocument örneğini oluşturan statik fabrika, *.html dosyasının kendisine giden bir yol ve bağlantılı kaynaklara sahip bir klasör |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | Statik fabrika, belirtilen HTML biçimlendirmesinden bir EditableDocument örneği ve karşılık gelen bağlantılı bir dizi kaynak oluşturur |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Tam path tarafından belirtilen klasörde bulunan, belirtilen bir HTML işaretlemesinden ve kaynaklardan bir EditableDocument örneği oluşturan statik fabrika |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Bu Düzenlenebilir belge örneğini atar, içeriğini atar ve yöntemlerini ve özelliklerini çalışmaz hale getirir |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | HTML belgesinin gövdesini (bu etiketler olmadan BODY etiketlerini açma ve kapatma arasındaki iç içeriği) bir dize olarak döndürür. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | HTML belgesinin bir gövdesini (bu etiketler olmadan BODY etiketlerinin açılması ve kapatılması arasındaki iç içerik) bir dize, olarak döndürür; burada harici kaynaklara bağlantılar belirtilen öneki içerir. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | HTML belgesinin genel içeriğini bir dize olarak döndürür. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | HTML belgesinin genel içeriğini, harici kaynaklara olan bağlantıların belirtilen öneki içerdiği bir dize olarak döndürür. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Tüm harici stil sayfalarının içeriğini, bir dizenin bir stil sayfasını temsil ettiği bir dizi listesi olarak döndürür. Bu belge için CSS yoksa boş liste döndürür. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Tüm harici stil sayfalarının içeriğini, bir dizenin bir stil sayfasını temsil ettiği bir dizi listesi olarak döndürür. Elde edilen her stil sayfasında harici kaynağa giden her bağlantıya belirtilen önek uygulanır. Bunun için CSS yoksa boş liste döndürür belge. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Bu HTML belgesinin tüm içeriğini, ilgili tüm kaynaklarla birlikte tek bir dize biçiminde döndürür; burada tüm kaynaklar, base64 kodlu bir biçimde HTML işaretlemesinin içine gömülüdür. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | Bu HTML belgesini, HTML işaretlemesinin depolanacağı belirtilen yoldaki dosyaya ve beraberindeki kaynaklarla birlikte klasöre kaydeder. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | Bu HTML belgesini, HTML işaretlemesinin depolanacağı belirtilen yoldaki dosyaya ve belirtilen yolda bulunan, kaynakları içeren eşlik eden klasöre kaydeder. |

## Olaylar

| İsim | Tanım |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Bu Düzenlenebilir belge imha edildiğinde, imha işlemi tamamlandıktan hemen sonra meydana gelen olay |

### Notlar

EditableDocument sınıfının örneği ' tarafından üretilebilir.[`Edit`](../editor/edit) yöntemi veya kullanıcının kendisi tarafından statik fabrikalar kullanılarak yaratılmıştır. EditableDocument, belgeyi GroupDocs.Editor'ın desteklediği tüm içe ve dışa aktarma biçimleri ile uyumlu (dönüştürülebilir) kendi kapalı biçiminde depolar. Belgeyi herhangi bir WYSIWYG istemci tarafı düzenleyicide (CKEditor veya TinyMCE gibi) düzenlenebilir hale getirmek için, EditableDocument, kullanıcı tarafından kabul edilebilecek HTML biçimlendirmesi ve kaynak üretme yöntemleri sağlar.

### Ayrıca bakınız

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* ad alanı [GroupDocs.Editor](../../groupdocs.editor)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
