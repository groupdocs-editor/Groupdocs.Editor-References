---
title: "Mp3Audio"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل مورد صوتي واحد بأي صيغة"
type: docs
weight: 330
url: /ar/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
## Mp3Audio class

يمثل مورد صوتي واحد بأي صيغة

```csharp
public sealed class Mp3Audio : IEquatable<Mp3Audio>, IHtmlResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Mp3Audio](mp3audio)(string, Stream) | ينشئ فئة Mp3Audio جديدة من محتوى MP3 الممثل كتدفق بايت، ومع اسم محدد |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/bytecontent) { get; } | يعيد محتوى هذا الخط كتدفق بايت |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/filenamewithextension) { get; } | يعيد اسم الملف الصحيح لهذا المحتوى MP3، والذي يتكون من الاسم والامتداد. نظريًا قد يختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isdisposed) { get; } | يحدد ما إذا كان هذا المحتوى MP3 قد تم التخلص منه أم لا |
| [Name](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/name) { get; } | يعيد اسم هذا المحتوى MP3. عادةً لا يحتوي على امتداد اسم الملف ونظريًا قد يختلف عن اسم الملف. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/textcontent) { get; } | يعيد محتوى هذا المورد MP3 كسلسلة مشفرة بقاعدة64. يتم تخزين هذه القيمة مؤقتًا بعد الاستدعاء الأول. |
| [Type](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/type) { get; } | يعيد AudioType.Mp3 |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/dispose)() | يتخلص من هذا المورد MP3، مما يتخلص من محتواه ويجعل معظم الطرق والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals_1)(IHtmlResource) | يتحقق من مساواة هذا الكائن مع مورد HTML المحدد على أساس المساواة المرجعية |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals)(Mp3Audio) | يتحقق من مساواة هذا الكائن مع مورد الخط المحدد على أساس المساواة المرجعية |
| [Save](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/save)(string) | يحفظ مورد MP3 هذا إلى الملف المحدد |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isvalid)(Stream) | يتحقق مما إذا كان التيار المحدد يحتوي على محتوى MP3 صالح |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/disposed) | الحدث الذي يحدث عندما يتم التخلص من محتوى MP3 هذا |

### انظر أيضًا

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
