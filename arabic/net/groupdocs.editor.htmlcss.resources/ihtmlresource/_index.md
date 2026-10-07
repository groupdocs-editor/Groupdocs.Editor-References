---
title: "IHtmlResource"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل مثلاً واحدًا من مورد HTML غير المعروف النقطي أو المتجه أو الصورة أو ورقة الأنماط أو الخط أو النص أو المورد CSS أو XML أو الصوت وما إلى ذلك."
type: docs
weight: 430
url: /ar/net/groupdocs.editor.htmlcss.resources/ihtmlresource/
---
## IHtmlResource interface

يمثل مثلاً واحداً من مورد HTML غير المعروف (صورة نقطية أو متجهة، ورقة أنماط، خط، مورد نصي (CSS, XML)، صوت إلخ)

```csharp
public interface IHtmlResource : IAuxDisposable, IEquatable<IHtmlResource>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/bytecontent) { get; } | محتوى مورد HTML في شكل تدفق بايت |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) { get; } | اسم الملف الصحيح للمورد المحدد مع الامتداد المناسب |
| [Name](../../groupdocs.editor.htmlcss.resources/ihtmlresource/name) { get; } | اسم مورد HTML |
| [TextContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/textcontent) { get; } | محتوى مورد HTML في شكل سلسلة نصية مشفرة بقاعدة64 للموارد الثنائية أو نص بسيط للموارد النصية |
| [Type](../../groupdocs.editor.htmlcss.resources/ihtmlresource/type) { get; } | نوع مورد HTML |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Save](../../groupdocs.editor.htmlcss.resources/ihtmlresource/save)(string) | يحفظ المورد الحالي إلى الملف المحدد |

### انظر أيضًا

* interface [IAuxDisposable](../iauxdisposable)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
