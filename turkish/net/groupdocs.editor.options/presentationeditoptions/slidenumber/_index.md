---
title: "SlideNumber"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Düzenleme için açılması gereken slayt numaralarını belirtmeye izin verir."
type: docs
weight: 30
url: /tr/net/groupdocs.editor.options/presentationeditoptions/slidenumber/
---
## PresentationEditOptions.SlideNumber property

Düzenleme için açılması gereken slayt numaralarını belirtmeye izin verir

```csharp
public int SlideNumber { get; set; }
```

### Açıklamalar

Slayt numarası, bir sunumdan düzenlemek için belirli bir slaytı seçmeye yarayan sıfır tabanlı bir indeksdir. 0'dan küçükse, ilk slayt seçilir (SlideNumber = 0 ile aynı). Sunumdaki toplam slayt sayısından büyükse, son slayt seçilir. Giriş sunumu yalnızca tek bir slayt içeriyorsa, bu seçenek yoksayılır ve bu tek slayt düzenlenir. Gizli bir slaytı düzenlemek için açmaya çalışılırken, [`ShowHiddenSlides`](../showhiddenslides) seçeneği 'false' olarak ayarlıysa, bir istisna fırlatılır.

### Ayrıca Bakınız

* class [PresentationEditOptions](../../presentationeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
