---
title: "CSS"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет получать ресурсы таблиц стилей CSS, как внешние, так и встроенные, но не инлайн, используемые этим HTML‑документом"
type: docs
weight: 60
url: /ru/net/groupdocs.editor/editabledocument/css/
---
## EditableDocument.Css property

Позволяет получить ресурсы таблиц стилей (CSS) (как внешние, так и встроенные, но не inline), которые используются этим HTML‑документом

```csharp
public List<CssText> Css { get; }
```

### Замечания

Этот метод возвращает поверхностную копию всех используемых ресурсов таблиц стилей: `List` создаётся заново при каждом вызове, но экземпляры ресурсов остаются теми же.

### См. также

* class [CssText](../../../groupdocs.editor.htmlcss.resources.textual/csstext)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
