---
title: "FromStartPageTillEndPage"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ نطاق صفحات يبدأ من رقم الصفحة المحدد شاملًا ويستمر حتى رقم الصفحة المحدد حصريًا"
type: docs
weight: 40
url: /ar/net/groupdocs.editor.options/pagerange/fromstartpagetillendpage/
---
## PageRange.FromStartPageTillEndPage method

ينشئ نطاق صفحة يبدأ من رقم الصفحة المحدد (شاملاً) ويستمر حتى رقم الصفحة المحدد (حصريًا)

```csharp
public static PageRange FromStartPageTillEndPage(ushort startPageNumber, ushort endPageNumber)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| startPageNumber | UInt16 | رقم الصفحة التي يبدأ منها نطاق الصفحات شاملًا. أرقام الصفحات تبدأ من 1، لذا يجب أن تكون أكبر من الصفر بشكل صارم |
| endPageNumber | UInt16 | رقم الصفحة التي يستمر حتىها نطاق الصفحات حصريًا. أرقام الصفحات تبدأ من 1، لذا يجب أن تكون أكبر من الصفر بشكل صارم، ويجب أيضًا أن تكون أكبر من *startPageNumber* بشكل صارم |

### انظر أيضًا

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
