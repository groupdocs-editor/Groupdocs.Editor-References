---
title: "DelimitedTextSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "هذا المُنشئ بدون معلمات ينشئ مثيلًا جديدًا من DelimitedTextSaveOptions مع فاصل افتراضي هو الفاصلة المنقوطة؛ يمكن تعديل الفاصل لاحقًا عبر الخاصية Separatorgroupdocs.editor.options/delimitedtextsaveoptions/separator."
type: docs
weight: 10
url: /ar/net/groupdocs.editor.options/delimitedtextsaveoptions/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions() {#constructor}

هذا المُنشئ بدون معلمات ينشئ مثيلًا جديدًا من DelimitedTextSaveOptions مع فاصل افتراضي هو الفاصلة المنقوطة (;) (يمكن تعديله لاحقًا عبر الخاصية [`Separator`](../separator)).

```csharp
public DelimitedTextSaveOptions()
```

### انظر أيضًا

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

---

## DelimitedTextSaveOptions(string) {#constructor_1}

ينشئ نسخة من فئة الخيارات للنص المفصول بفاصل (delimiter) إلزامي.

```csharp
public DelimitedTextSaveOptions(string separator)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| separator | String | فاصل السلسلة (delimiter) لا يمكن أن يكون NULL أو فارغًا. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم رمي الاستثناء عندما يكون الفاصل المحدد null أو سلسلة فارغة. |

### انظر أيضًا

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
