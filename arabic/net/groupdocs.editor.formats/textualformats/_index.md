---
title: TextualFormats
second_title: GroupDocs.Editor لمرجع .NET API
description: يشمل جميع التنسيقات النصية المستندة إلى النص  بما في ذلك التنسيقات XML و HTML وغيرها . يتضمن التنسيقات التالية Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /ar/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

يشمل جميع التنسيقات النصية (المستندة إلى النص) ، بما في ذلك التنسيقات (XML و HTML) وغيرها . يتضمن التنسيقات التالية: [`Html`](./html) ، [`Txt`](./txt) ، [`Xml`](./xml) . [`Md`](./md) ، [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | إرجاع امتداد (بدون حرف النقطة البادئة) لهذا التنسيق النصي بأحرف صغيرة |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | إرجاع رمز MIME لهذا التنسيق |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | إرجاع الاسم الكامل الرسمي لهذا التنسيق النصي |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | إرجاع مثيل[`TextualFormats`](../textualformats)الهيكل ، المرتبط بامتداد اسم الملف المحدد ، أو يطرح استثناءً ، إذا كان التمديد لا يمكن تحليله بشكل صحيح |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | تحديد ما إذا كان هذا المثيل مساويًا لمثيل IDocumentFormat المحدد الآخر. |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | تحديد ما إذا كان هذا المثيل مساويًا للكائن المحدد الآخر ، والذي يُفترض أنه من تنسيقات TextualFormats المعبأة |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | تحديد ما إذا كان هذا المثيل يساوي مثيل TextualFormats المحدد الآخر. |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | إرجاع رمز تجزئة غير قابل للتغيير في هذا المثال |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | إرجاع اسم هذا التنسيق المحدد ، مثل "الاسم" property |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | لفحص مثيلين معينين من TextualFormats عند المساواة |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | لفحص مثيلين معينين من TextualFormats على عدم المساواة |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help هو تنسيق ثنائي للمساعدة عبر الإنترنت مملوك لشركة Microsoft ، ويتألف من مجموعة من صفحات HTML ، وفهرس وأدوات تنقل أخرى . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | مستند لغة ترميز النص التشعبي (HTML) هو امتداد لصفحات الويب التي تم إنشاؤها للعرض في المستعرضات . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) هو تنسيق ملف قياسي مفتوح لمشاركة البيانات التي تستخدم نصًا يمكن للبشر قراءته لتخزين البيانات ونقلها. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown هي لغة ترميز خفيفة الوزن لإنشاء نص منسق باستخدام محرر نص عادي. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | تغليف MIME لمستندات HTML المجمعة هو تنسيق أرشيف لصفحة ويب يُستخدم لدمج كود HTML والموارد المصاحبة له في ملف كمبيوتر واحد . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | مستند نصي عادي (TXT) يمثل مستندًا نصيًا يحتوي على نص عادي في شكل أسطر . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | مستند لغة التوصيف القابلة للتمدد (XML) الذي يشبه HTML ولكنه يختلف في استخدام العلامات لتحديد الكائنات . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | إرجاع فئة داخلية توفر احتمالات لا تعد ولا تحصى على جميع التنسيقات النصية الموجودة. |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | تطبيقات I واجهة عامة قابلة للعدد ، تتيح إمكانية "foreach" لتنسيقات TextualFormats type |

### أنظر أيضا

* interface [IDocumentFormat](../idocumentformat)
* مساحة الاسم [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->