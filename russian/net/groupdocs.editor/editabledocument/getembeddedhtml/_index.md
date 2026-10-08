---
title: "GetEmbeddedHtml"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Возвращает всё содержимое этого HTML‑документа со всеми связанными ресурсами в виде единой строки, где все ресурсы встроены в разметку HTML в виде base64‑закодированных данных."
type: docs
weight: 150
url: /ru/net/groupdocs.editor/editabledocument/getembeddedhtml/
---
## EditableDocument.GetEmbeddedHtml method

Возвращает всё содержимое этого HTML‑документа со всеми связанными ресурсами в виде единой строки, где все ресурсы встроены в разметку HTML в виде base64‑закодированных данных.

```csharp
public string GetEmbeddedHtml()
```

### Возвращаемое значение

Строка, которая в любом случае не является NULL или пустой.

### Исключения

| исключение | условие |
| --- | --- |
| ObjectDisposedException | Этот экземпляр EditableDocument уже был освобождён |

### Замечания

Этот метод преобразует данный EditableDocument в HTML и сериализует его в одну строку, где все ресурсы встроены в строку вместе с разметкой HTML:

* All images from HTML-&gt;BODY are converted to base64 format and are located in the IMG 'src' attribute
* All stylesheets are stored in the STYLE elements inside HTML-&gt;HEAD sections
* All images from stylesheets are converted to base64 format and located in the appropriate CSS declarations
* All fonts from stylesheets are converted to base64 format and located in the appropriate @font-face at-rules

### См. также

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
