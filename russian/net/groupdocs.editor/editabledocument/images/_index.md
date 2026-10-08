---
title: "Изображения"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет получать внешние ресурсы изображений (растровые и векторные), используемые этим HTML‑документом"
type: docs
weight: 80
url: /ru/net/groupdocs.editor/editabledocument/images/
---
## EditableDocument.Images property

Позволяет получить внешние ресурсы изображений (растровые и векторные), которые используются этим HTML‑документом

```csharp
public List<IImageResource> Images { get; }
```

### Замечания

Этот метод возвращает поверхностную копию всех используемых ресурсов изображений: `List` создаётся заново при каждом вызове, но экземпляры ресурсов остаются теми же.

### См. также

* interface [IImageResource](../../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
