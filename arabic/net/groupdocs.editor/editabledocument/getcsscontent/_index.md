---
title: "GetCssContent"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يرجع محتوى جميع أوراق الأنماط الخارجية كقائمة من السلاسل حيث تمثل كل سلسلة ورقة نمط واحدة. يرجع قائمة فارغة إذا لم يكن هناك CSS لهذا المستند."
type: docs
weight: 140
url: /ar/net/groupdocs.editor/editabledocument/getcsscontent/
---
## GetCssContent() {#getcsscontent}

يرجع محتوى جميع أوراق الأنماط الخارجية كقائمة من السلاسل، حيث تمثل كل سلسلة ورقة نمط واحدة. يرجع قائمة فارغة إذا لم يكن هناك CSS لهذا المستند.

```csharp
public List<string> GetCssContent()
```

### قيمة الإرجاع

قائمة من السلاسل، حيث تحتوي كل سلسلة على محتوى وثيقة CSS واحدة.

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetCssContent(string, string) {#getcsscontent_1}

يرجع محتوى جميع أوراق الأنماط الخارجية كقائمة من السلاسل، حيث تمثل كل سلسلة ورقة نمط واحدة. سيتم تطبيق البادئة المحددة على كل رابط إلى المورد الخارجي في كل ورقة نمط ناتجة. يرجع قائمة فارغة إذا لم يكن هناك CSS لهذا المستند.

```csharp
public List<string> GetCssContent(string externalImagesPrefix, string externalFontsPrefix)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| externalImagesPrefix | String | من خلال هذا المعامل يمكن تحديد بادئة تُضاف إلى الروابط لجميع الصور الخارجية التي ستظهر في إعلانات CSS في سلاسل CSS الناتجة. إذا كان NULL أو فارغًا، لن تُضاف البادئات. |
| externalFontsPrefix | String | من خلال هذا المعامل يمكن تحديد بادئة تُضاف إلى الروابط لجميع الخطوط الخارجية في قواعد @font-face في سلاسل CSS الناتجة. إذا كان NULL أو فارغًا، لن تُضاف البادئات. |

### قيمة الإرجاع

قائمة من السلاسل، حيث تحتوي كل سلسلة على محتوى وثيقة CSS واحدة.

### انظر أيضًا

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
