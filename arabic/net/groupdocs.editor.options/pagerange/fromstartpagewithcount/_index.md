---
title: "FromStartPageWithCount"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "ينشئ نطاق صفحات يبدأ من رقم الصفحة المحدد ويحتوي على عدد محدد من الصفحات أو عدد غير محدود من الصفحات حتى النهاية"
type: docs
weight: 50
url: /ar/net/groupdocs.editor.options/pagerange/fromstartpagewithcount/
---
## PageRange.FromStartPageWithCount method

ينشئ نطاق صفحة يبدأ من رقم الصفحة المحدد ويحتوي على عدد محدد من الصفحات، أو عدد صفحات غير محدود (حتى النهاية)

```csharp
public static PageRange FromStartPageWithCount(ushort startPageNumber, ushort pageCount)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| startPageNumber | UInt16 | رقم الصفحة التي يبدأ منها نطاق الصفحات شاملًا. أرقام الصفحات تبدأ من 1، لذا يجب أن تكون أكبر من الصفر بشكل صارم |
| pageCount | UInt16 | عدد الصفحات، يجب أن يكون أكبر من الصفر بشكل صارم. إذا كان الصفر - فهذا يعني جميع الصفحات حتى نهاية المستند |

### قيمة الإرجاع

كائن جديد من PageRange

### انظر أيضًا

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
