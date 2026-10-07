---
title: "TextualFormats"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحتوي على جميع الصيغ النصية المستندة إلى النص بما في ذلك الترميز XML HTML وغيرها. يتضمن الصيغ التالية Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /ar/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

يحتوي على جميع الصيغ النصية (المستندة إلى النص)، بما في ذلك الترميز (XML, HTML) وغيرها. يتضمن الصيغ التالية: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | يحصل على امتداد الملف لتنسيق المستند. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | يحصل على عائلة التنسيق التي ينتمي إليها تنسيق المستند. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | يحصل على المعرف الفريد لعائلة التنسيق. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | يحصل على نوع MIME لتنسيق المستند. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | يحصل على اسم عائلة التنسيق. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | يحصل على مجموعة قابلة للتعداد من جميع [`TextualFormats`](../textualformats). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | يسترجع مثيلاً من النوع المحدد [`TextualFormats`](../textualformats) الذي يمتلك امتداد الملف المحدد. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | يرجع رمز تجزئة (hash code) للكائن الحالي. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | يرجع سلسلة تمثل الكائن الحالي. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | يحوّل سلسلة تمثل امتداد ملف إلى كائن [`TextualFormats`](../textualformats). |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help هو تنسيق مساعدة ثنائي مملوك من مايكروسوفت على الإنترنت، يتكون من مجموعة من صفحات HTML، وفهرس، وأدوات تنقل أخرى. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | مستند HyperText Markup Language (HTML) هو الامتداد لصفحات الويب التي تُنشأ للعرض في المتصفحات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) هو تنسيق ملف مفتوح المعيار لمشاركة البيانات يستخدم نصًا قابلاً للقراءة البشرية لتخزين ونقل البيانات. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown هو لغة ترميز خفيفة الوزن لإنشاء نص منسق باستخدام محرر نص عادي. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME encapsulation of aggregate HTML documents هو تنسيق أرشيف صفحات ويب يُستخدم لدمج، في ملف حاسوبي واحد، كود HTML وموارده المرافقة. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | مستند نص عادي (TXT) يمثل مستند نص يحتوي على نص عادي على شكل أسطر. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | مستند لغة الترميز القابلة للامتداد (XML) يشبه HTML لكنه مختلف في استخدام العلامات لتعريف الكائنات. تعرف على المزيد حول هذه الصيغة [هنا](https://wiki.fileformat.com/web/xml). |

### انظر أيضًا

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
