---
title: PresentationFormats
second_title: GroupDocs.Editor لمرجع .NET API
description: لتضمين جميع تنسيقات العروض التقديمية. يتضمن التنسيقات التالية Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. تعرف على المزيد حول تنسيقات العروض التقديميةهناhttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /ar/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

لتضمين جميع تنسيقات العروض التقديمية. يتضمن التنسيقات التالية: [`Odp`](./odp) ، [`Otp`](./otp) ، [`Pot`](./pot) ، [`Potm`](./potm) ، [`Potx`](./potx) ، [`Pps`](./pps) ، [`Ppsm`](./ppsm) ، [`Ppsx`](./ppsx) ، [`Ppt`](./ppt) ، [`Ppt95`](./ppt95) ، [`Pptm`](./pptm) ، [`Pptx`](./pptx). تعرف على المزيد حول تنسيقات العروض التقديمية[هنا](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | إرجاع امتداد (بدون النقطة البادئة) لتنسيق العرض التقديمي هذا بأحرف صغيرة |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | إرجاع رمز MIME لهذا التنسيق |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | إرجاع الاسم الكامل الرسمي لتنسيق العرض التقديمي هذا |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | إرجاع مثيل[`PresentationFormats`](../presentationformats) الهيكل ، المرتبط بامتداد اسم الملف المحدد ، أو يطرح استثناءً ، إذا كان التمديد لا يمكن تحليله بشكل صحيح |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | تحديد ما إذا كان هذا المثيل مساويًا لمثيل IDocumentFormat المحدد الآخر. |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | تحديد ما إذا كان هذا المثيل مساويًا للكائن المحدد الآخر ، والذي يُفترض أنه لـ PresentationFormats |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | تحديد ما إذا كان هذا المثيل مساويًا لتنسيقات PresentationFormats المحددة الأخرى. |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | إرجاع رمز تجزئة غير قابل للتغيير في هذا المثال |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | لفحص مثيلين من PresentationFormats معطى للمساواة |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | لفحص مثيلين من PresentationFormats معطى على عدم المساواة |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | يمثل ملف OpenDocument Presentation (ODP) تنسيق ملف العرض التقديمي المستخدم بواسطة OpenOffice.org في معيار OASISOpen . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | يمثل ملف قالب العرض التقديمي OpenDocument Presentation (OTP) ملفات قالب العرض التقديمي التي تم إنشاؤها بواسطة التطبيقات بتنسيق OASIS OpenDocument القياسي . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | يمثل ملف Microsoft PowerPoint 97-2003 Presentation Template (POT) ملفات قوالب Microsoft PowerPoint التي تم إنشاؤها بواسطة إصدارات PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML يعد قالب ممكّن بماكرو (POTM) ملفات مع دعم لوحدات الماكرو. يتم إنشاء ملفات POTM باستخدام PowerPoint 2007 أو إصدار أحدث وتحتوي على الإعدادات الافتراضية التي يمكن استخدامها لإنشاء المزيد من ملفات العروض التقديمية . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML يمثل ملف قالب خالٍ من الماكرو (POTX) عروض تقديمية لقوالب Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 والإصدارات الأحدث. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | يتم إنشاء ملفات Microsoft PowerPoint 97-2003 SlideShow (PPS) باستخدام Microsoft PowerPoint لغرض عرض الشرائح. يتم دعم قراءة ملف PPS وإنشائه بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML يتم إنشاء ملفات عرض الشرائح الممكنة بماكرو (PPSM) باستخدام Microsoft PowerPoint 2007 أو أعلى . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML يتم إنشاء ملف عرض شرائح خالٍ من الماكرو (PPSX) باستخدام Microsoft PowerPoint 2007 والإصدارات الأحدث لغرض عرض الشرائح . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint Presentation (.ppt) يمثل ملف PowerPoint يتكون من مجموعة من الشرائح لعرضها على هيئة SlideShow. تحدد تنسيق الملف الثنائي المستخدم بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | عرض تقديمي لـ Microsoft PowerPoint 95 (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML ملفات المستندات الممكنة بماكرو (PPTM) التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث. إنها تشبه ملفات PPTX مع اختلاف أن الجانب الجانبي لا يمكنه تنفيذ وحدات الماكرو على الرغم من أنه يمكن أن يحتوي على وحدات ماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML Presentation (.pptx) هو ملف عرض تقديمي تم إنشاؤه باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس الإصدار السابق من تنسيق ملف العرض التقديمي PPT الذي كان ثنائيًا ، يعتمد تنسيق PPTX على تنسيق ملف العرض التقديمي XML المفتوح لبرنامج Microsoft PowerPoint. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | إرجاع فئة داخلية توفر احتمالات لا تعد ولا تحصى على جميع تنسيقات العروض التقديمية الحالية |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | تطبيقات I واجهة عامة قابلة للعدد ، والتي تتيح إمكانية "foreach" للعرض التقديمي تنسيقات type |

### أنظر أيضا

* interface [IDocumentFormat](../idocumentformat)
* مساحة الاسم [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
