---
title: Editor
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Dönüştürme yöntemlerini içeren ana sınıf. Editor sınıfı tüm desteklenen biçimlerdeki belgeleri yüklemek düzenlemek ve kaydetmek için yöntemler sağlar. Tek kullanımlıktır bu nedenle bir kullanma yönergesi kullanın veya kaynaklarını Dispose yöntem çağrısı aracılığıyla manuel olarak atın. Belge yükleme oluşturucular aracılığıyla gerçekleştirilir. Belge düzenleme  Düzenle yöntemiyle ve düzenlemeden sonra ortaya çıkan belgeye geri kaydetme  Kaydet yöntemiyle.
type: docs
weight: 20
url: /tr/net/groupdocs.editor/editor/
---
## Editor class

Dönüştürme yöntemlerini içeren ana sınıf. Editor sınıfı, tüm desteklenen biçimlerdeki belgeleri yüklemek, düzenlemek ve kaydetmek için yöntemler sağlar. Tek kullanımlıktır, bu nedenle bir "kullanma" yönergesi kullanın veya kaynaklarını "Dispose()" yöntem çağrısı aracılığıyla manuel olarak atın. Belge yükleme, oluşturucular aracılığıyla gerçekleştirilir. Belge düzenleme - 'Düzenle' yöntemiyle ve düzenlemeden sonra ortaya çıkan belgeye geri kaydetme - 'Kaydet' yöntemiyle.

```csharp
public sealed class Editor : IAuxDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Editor](editor#constructor)(Func&lt;Stream&gt;) | Belirtilen girdi belgesiyle (akış olarak) yeni Düzenleyici örneğini başlatır |
| [Editor](editor#constructor_2)(string) | Belirtilen girdi belgesiyle (tam dosya yolu olarak) yeni Düzenleyici örneğini başlatır |
| [Editor](editor#constructor_1)(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) | Yükleme seçenekleri ile belirtilen girdi belgesiyle (akış olarak) yeni Düzenleyici örneğini başlatır. |
| [Editor](editor#constructor_3)(string, Func&lt;ILoadOptions&gt;) | Yükleme seçenekleri ile belirtilen girdi belgesiyle (tam dosya yolu olarak) yeni Düzenleyici örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Bu Editor örneğinin zaten atılıp atılmadığını ve artık kullanılamayacağını (doğru) veya henüz atılmadığını ve bu nedenle etkin olup olmadığını (yanlış) gösterir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Düzenleyicinin bu örneğini atar, böylece tüm dahili kaynakları serbest bırakır ve daha fazla kullanım için kullanılamaz hale gelir |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | ' örneğini oluşturup döndürerek varsayılan seçenekleri kullanarak önceden yüklenmiş bir belgeyi düzenleme için açar.[`EditableDocument`](../editabledocument) HTML işaretlemesi ve ilgili kaynakları üretmek için yöntemler içeren sınıf. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | ' örneğini oluşturup döndürerek belirtilen biçime özgü seçenekleri kullanarak önceden yüklenmiş bir belgeyi düzenleme için açar.[`EditableDocument`](../editabledocument) HTML işaretlemesi ve ilgili kaynakları üretmek için yöntemler içeren sınıf. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Bu 'Düzenleyici' örneğine yüklenen belge hakkında meta verileri döndürür |
| [Save](../../groupdocs.editor/editor/save#save)(EditableDocument, Stream, ISaveOptions) | ' örneği olarak gösterilen, belirtilen düzenlenmiş belgeyi dönüştürür[`EditableDocument`](../editabledocument) , belirtilen biçimdeki sonuçtaki belgeye ve içeriğini belirtilen stream 'ye kaydeder |
| [Save](../../groupdocs.editor/editor/save#save_1)(EditableDocument, string, ISaveOptions) | ' örneği olarak gösterilen, belirtilen düzenlenmiş belgeyi dönüştürür[`EditableDocument`](../editabledocument) , belirtilen biçimdeki sonuçtaki belgeye gönderir ve içeriğini belirtilen dosya yolu ile dosyaya kaydeder. |

## Olaylar

| İsim | Tanım |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Bu Editor örneği, tüm dahili kaynaklarıyla elden çıkarıldığında meydana gelen olay |

### Notlar

Editor sınıfı, GroupDocs.Editor'un bir giriş noktası ve kök nesnesi olarak düşünülmelidir. Tüm işlemler bu sınıf kullanılarak gerçekleştirilir. Tam bir belge düzenleme ardışık düzeni gerçekleştirmek için Editor sınıfının tipik kullanımı şu şekildedir: next:

1. Yapıcı aracılığıyla Editor örneğine bir belge yükleyin.
2. İsteğe bağlı olarak, bir belge türünü[`GetDocumentInfo`](./getdocumentinfo) yöntem.
3. Bir belgeyi arayarak düzenleme için açın.[`Edit`](./edit) yöntemi ve bir örneğinin elde edilmesi[`EditableDocument`](../editabledocument) ondan sınıf.
4. Herhangi bir WYSIWYG HTML düzenleyici kullanarak istemci tarafında bir belge içeriğini düzenleme.
5. Yeni bir örnek oluşturma[`EditableDocument`](../editabledocument) düzenlenmiş belge içeriğinden.
6. Düzenlenmiş bir belgeyi bir çıktı formatına çağırarak kaydetme[`Save`](./save) yöntem.
7. Editor sınıfının bir örneğini 'kullanma' operatörü aracılığıyla veya manuel olarak elden çıkarmak.

### Ayrıca bakınız

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* ad alanı [GroupDocs.Editor](../../groupdocs.editor)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
