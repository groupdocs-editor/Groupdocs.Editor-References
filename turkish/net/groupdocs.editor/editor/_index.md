---
title: "Editor"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Dönüştürme yöntemlerini kapsülleyen ana sınıf. Editor sınıfı, tüm desteklenen formatlarda belgeleri yükleme, düzenleme ve kaydetme yöntemleri sağlar. Kullanım süresi sona erdiğinde, bir using yönergesi kullanın veya kaynaklarını manuel olarak Dispose yöntemiyle serbest bırakın. Belge yükleme, yapıcılar aracılığıyla gerçekleştirilir. Belge düzenleme, Edit yöntemiyle ve düzenleme sonrası ortaya çıkan belgeyi kaydetme, Save yöntemiyle yapılır."
type: docs
weight: 20
url: /tr/net/groupdocs.editor/editor/
---
## Editor class

Tüm dönüştürme yöntemlerini kapsayan ana sınıf. Editor sınıfı, tüm desteklenen formatlardaki belgeleri yükleme, düzenleme ve kaydetme yöntemleri sağlar. Bu sınıf kullanılabilir, bu yüzden bir 'using' yönergesi kullanın veya kaynaklarını manuel olarak 'Dispose()' yöntemiyle serbest bırakın. Belge yükleme, yapıcılar aracılığıyla gerçekleştirilir. Belge düzenleme – 'Edit' yöntemiyle, düzenleme sonrası ortaya çıkan belgeyi kaydetme ise 'Save' yöntemiyle yapılır.

```csharp
public sealed class Editor : IAuxDisposable
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [Editor](editor#constructor)(DocumentFormatBase) | Yeni bir [`Editor`](../editor) sınıfı örneği başlatır ve belirtilen biçime göre yeni boş bir belge oluşturur. |
| [Editor](editor#constructor_1)(Stream) | Belirtilen giriş belgesi (akış olarak) ile yeni bir Editor örneği başlatır. |
| [Editor](editor#constructor_3)(string) | Belirtilen giriş belgesi (tam dosya yolu olarak) ve Editor ayarlarıyla yeni bir Editor örneği başlatır. |
| [Editor](editor#constructor_2)(Stream, ILoadOptions) | Belirtilen giriş belgesi (akış olarak) ve yükleme seçenekleriyle yeni bir Editor örneği başlatır. |
| [Editor](editor#constructor_4)(string, ILoadOptions) | Belirtilen giriş belgesi (tam dosya yolu olarak) ve yükleme seçenekleriyle yeni bir Editor örneği başlatır. |

## Properties

| Name | Açıklama |
| --- | --- |
| [FormFieldManager](../../groupdocs.editor/editor/formfieldmanager) { get; } | Belge içindeki form alanlarını yönetmek için işlevselliğe erişim sağlar. |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Bu Editor örneğinin zaten dağıtılmış olup artık kullanılamayacağını (true) ya da henüz dağıtılmadığını ve bu yüzden etkin olduğunu (false) gösterir. |

## Methods

| Name | Açıklama |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Editor örneğini dağıtarak tüm iç kaynakları serbest bırakır ve sonraki kullanım için kullanılamaz hâle getirir. |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Varsayılan seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme için açar; bunun için '[`EditableDocument`](../editabledocument)' sınıfının bir örneğini oluşturur ve döndürür; bu örnek de HTML işaretlemesi ve ilgili kaynakları üretmek için yöntemler içerir. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Belirtilen biçim‑özel seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme için açar; bunun için '[`EditableDocument`](../editabledocument)' sınıfının bir örneğini oluşturur ve döndürür; bu örnek de HTML işaretlemesi ve ilgili kaynakları üretmek için yöntemler içerir. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Bu 'Editor' örneğine yüklenen belgeye ait meta verileri döndürür. |
| [Save](../../groupdocs.editor/editor/save#save)(Stream) | Geçerli belge içeriğini belirtilen çıktı akışına kaydeder. |
| [Save](../../groupdocs.editor/editor/save#save_3)(EditableDocument, string) | Belirtilen düzenlenmiş belgeyi, '[`EditableDocument`](../editabledocument)' örneği olarak temsil edilen, dosya adı uzantısına göre belirlenen biçimdeki sonuç belgeye dönüştürür ve içeriğini belirtilen dosya yoluyla bir dosyaya kaydeder. |
| [Save](../../groupdocs.editor/editor/save#save_1)(Stream, WordProcessingSaveOptions) | Orijinal belgeyi, değişiklikten (örneğin, [`FormFieldManager`](./formfieldmanager)) sonra, belirtilen biçimdeki sonuç belgeye dönüştürür ve içeriğini sağlanan akışa kaydeder. |
| [Save](../../groupdocs.editor/editor/save#save_2)(EditableDocument, Stream, ISaveOptions) | Belirtilen düzenlenmiş belgeyi, '[`EditableDocument`](../editabledocument)' örneği olarak temsil edilen, belirtilen biçimdeki sonuç belgeye dönüştürür ve içeriğini belirtilen akışa kaydeder. |
| [Save](../../groupdocs.editor/editor/save#save_4)(EditableDocument, string, ISaveOptions) | Belirtilen düzenlenmiş belgeyi, '[`EditableDocument`](../editabledocument)' örneği olarak temsil edilen, belirtilen biçimdeki sonuç belgeye dönüştürür ve içeriğini belirtilen dosya yolu ile bir dosyaya kaydeder. |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Bu Editor örneği tüm iç kaynaklarıyla birlikte dağıtıldığında gerçekleşen olay. |

### Açıklamalar

Editor sınıfı, GroupDocs.Editor'ın giriş noktası ve kök nesnesi olarak düşünülmelidir. Tüm işlemler bu sınıf kullanılarak gerçekleştirilir. Tam bir belge düzenleme işlem hattını yürütmek için Editor sınıfının tipik kullanımı aşağıdaki gibidir:

1. Bir belgeyi, yapıcı yöntemi aracılığıyla Editor örneğine yükleyin.
2. İsteğe bağlı olarak, bir [`GetDocumentInfo`](./getdocumentinfo) yöntemi kullanarak belge türünü tespit edin.
3. Bir belgeyi düzenleme için açmak üzere bir [`Edit`](./edit) yöntemi çağırın ve ondan bir [`EditableDocument`](../editabledocument) sınıfı örneği elde edin.
4. Herhangi bir WYSIWYG HTML editörü kullanarak istemci tarafında belge içeriğini düzenleyin.
5. Düzenlenmiş belge içeriğinden yeni bir [`EditableDocument`](../editableddocument) örneği oluşturun.
6. Düzenlenmiş belgeyi bir [`Save`](./save) yöntemi çağırarak bir çıktı biçimine kaydedin.
7. Editor sınıfının bir örneğini 'using' operatörüyle veya manuel olarak yok etme.

### Ayrıca Bakınız

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
