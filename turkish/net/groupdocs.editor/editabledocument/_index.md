---
title: "EditableDocument"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Düzenleme öncesi ve sonrası içeriği içeren ara belge"
type: docs
weight: 10
url: /tr/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Düzenlemeden önce ve sonra içeriği içeren ara belge

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Properties

| Name | Açıklama |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Mevcut tüm kaynakların bir listesini döndürür: tüm stil sayfaları, HTML'den gelen görüntüler ve tüm stil sayfaları, yazı tipleri, ses |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Ses kaynaklarının bir listesini döndürür |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Bu HTML belgesi tarafından kullanılan stil sayfası (CSS) kaynaklarını (harici ve gömülü, ancak satır içi olmayan) elde etmeyi sağlar |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Bu HTML belgesi tarafından kullanılan harici yazı tipi kaynaklarını elde etmeyi sağlar |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Bu HTML belgesi tarafından kullanılan harici görüntü kaynaklarını (raster ve vektör görüntüler) elde etmeyi sağlar |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Bu Editable belgesinin zaten yok edilip edilmediğini (true) ya da (false) belirler |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Bir HTML dosyasından, *.html dosyasının kendisine ve bağlı kaynakların bulunduğu klasöre verilen yol ile bir EditableDocument örneği oluşturan statik fabrika |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | Belirtilen HTML işaretlemesinden bir [`EditableDocument`](../editabledocument) örneği oluşturan statik fabrika |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | Belirtilen HTML işaretlemesi ve ilgili bağlı kaynakların bir setinden bir EditableDocument örneği oluşturan statik fabrika |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Belirtilen HTML işaretlemesinden ve tam yol ile belirtilen klasörde bulunan kaynaklardan bir EditableDocument örneği oluşturan statik fabrika |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Bu Editable belge örneğini yok eder, içeriğini temizler ve yöntemlerini ve özelliklerini çalışmaz hâle getirir |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | HTML belgesinin gövdesini (açılış ve kapanış BODY etiketleri arasındaki içeriği, etiketler olmadan) bir dize olarak döndürür. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | HTML belgesinin gövdesini (açılış ve kapanış BODY etiketleri arasındaki içeriği, etiketler olmadan) bir dize olarak döndürür; dış kaynaklara bağlantılar belirtilen yer tutucularla şablonu içerir. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | HTML belgesinin tüm içeriğini bir dize olarak döndürür. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | HTML belgesinin tüm içeriğini bir dize olarak döndürür; dış kaynaklara bağlantılar belirtilen yer tutucularla şablonu içerir. |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | Belirtilen metin kodlamasıyla bu içeriği belirtilen akıma yazarak HTML belgesinin tüm içeriğini bir bayt akışı olarak döndürür |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Tüm harici stil sayfalarının içeriğini, her bir stil sayfasını temsil eden bir dize olarak bir liste şeklinde döndürür. Bu belge için CSS yoksa boş liste döndürür. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Tüm harici stil sayfalarının içeriğini, her bir stil sayfasını temsil eden bir dize olarak bir liste şeklinde döndürür. Belirtilen önek, her sonuç stil sayfasındaki dış kaynağa yapılan her bağlantıya uygulanır. Bu belge için CSS yoksa boş liste döndürür. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Bu HTML belgesinin tüm içeriğini ve ilgili tüm kaynakları tek bir dize olarak döndürür; tüm kaynaklar HTML işaretlemesi içinde base64 kodlu olarak gömülüdür. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | HTML işaretlemesinin saklanacağı belirtilen yoldaki dosyaya ve ilgili kaynak klasörüne bu HTML belgesini kaydeder. |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | HTML işaretlemesinin saklanacağı belirtilen yoldaki dosyaya ve belirtilen yolda bulunan ilgili kaynak klasörüne bu HTML belgesini kaydeder. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | Bu [`EditableDocument`](../editabledocument) içeriğini belirtilen metin yazarına HTML belgesi olarak kaydeder; ikinci seçenek parametresi kaydetme prosedürünü özelleştirmeye ve kaynak kaydetme geri çağrısını belirtmeye olanak tanır |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Bu Editable belge serbest bırakıldığında, serbest bırakma işlemi tamamlandıktan hemen sonra gerçekleşen olay |

### Açıklamalar

`EditableDocument` sınıfının bir örneği, '[`Edit`](../editor/edit)' yöntemiyle üretilebilir veya kullanıcının kendisi statik fabrikalar kullanarak oluşturabilir. `EditableDocument` belgeyi kendi kapalı formatında depolar; bu format, GroupDocs.Editor tarafından desteklenen tüm içe ve dışa aktarma formatlarıyla uyumludur (dönüştürülebilir). Belgeyi herhangi bir WYSIWYG istemci tarafı editöründe (ör. CKEditor veya TinyMCE) düzenlenebilir kılmak için, `EditableDocument` HTML işaretlemesi oluşturma ve kullanıcı tarafından kabul edilebilecek kaynaklar üretme yöntemleri sağlar.

### Ayrıca Bakınız

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
