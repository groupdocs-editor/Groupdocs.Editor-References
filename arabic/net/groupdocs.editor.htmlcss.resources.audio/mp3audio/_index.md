---
title: Mp3Audio
second_title: GroupDocs.Editor لمرجع .NET API
description: يمثل مصدرًا صوتيًا واحدًا بتنسيق عشوائي
type: docs
weight: 250
url: /ar/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
## Mp3Audio class

يمثل مصدرًا صوتيًا واحدًا بتنسيق عشوائي

```csharp
public sealed class Mp3Audio : IEquatable<Mp3Audio>, IHtmlResource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Mp3Audio](mp3audio)(string, Stream) | إنشاء فئة Mp3Audio جديدة من محتوى MP3 ، يتم تمثيلها على شكل دفق بايت ، وباسم محدد |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/bytecontent) { get; } | إرجاع محتوى هذا الخط كـ byte stream |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/filenamewithextension) { get; } | إرجاع اسم الملف الصحيح لمحتوى MP3 هذا ، والذي يتكون من الاسم والامتداد. من الناحية النظرية يمكن أن تختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isdisposed) { get; } | يحدد ما إذا كان محتوى MP3 هذا قد تم التخلص منه أم لا |
| [Name](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/name) { get; } | إرجاع اسم محتوى MP3 هذا. عادة لا يحتوي على امتداد اسم الملف ويمكن نظريًا أن يختلف عن اسم الملف. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/textcontent) { get; } | إرجاع محتوى مورد MP3 هذا كسلسلة مشفرة باستخدام base64. يتم تخزين هذه القيمة مؤقتًا بعد الاستدعاء الأول. |
| [Type](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/type) { get; } | إرجاع نوع صوتي. mp3 |

## طُرق

| اسم | وصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/dispose)() | التخلص من مورد MP3 هذا ، والتخلص من محتواه وجعل معظم الأساليب والخصائص لا تعمل |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals_1)(IHtmlResource) | التحقق من هذا المثيل بمورد HTML المحدد عند المساواة في المرجع |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals)(Mp3Audio) | التحقق من هذا المثيل باستخدام مورد الخط المحدد عند المساواة المرجعية |
| [Save](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/save)(string) | يحفظ مورد MP3 هذا في الملف المحدد |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isvalid)(Stream) | للتحقق مما إذا كان الدفق المحدد محتوى MP3 صالحًا |

## الأحداث

| اسم | وصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/disposed) | الحدث الذي يحدث عند التخلص من محتوى MP3 هذا |

### أنظر أيضا

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->