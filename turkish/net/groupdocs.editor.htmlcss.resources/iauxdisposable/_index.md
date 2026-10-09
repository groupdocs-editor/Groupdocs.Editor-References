---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Standart IDisposable arayüzünü genişleterek bir nesnenin mevcut durumunu elde etmeyi ve imha olayı için abone olmayı sağlar"
type: docs
weight: 420
url: /tr/net/groupdocs.editor.htmlcss.resources/iauxdisposable/
---
## IAuxDisposable interface

Standart IDisposable arayüzünü genişletir, bir nesnenin mevcut durumunu elde etmeyi ve disposing olayına abone olmayı sağlar

```csharp
public interface IAuxDisposable : IDisposable
```

## Properties

| Name | Açıklama |
| --- | --- |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources/iauxdisposable/isdisposed) { get; } | Bir kaynağın kapalı olup olmadığını belirler (true) veya (false) |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources/iauxdisposable/disposed) | Nesne imha edildiğinde gerçekleşir |

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
