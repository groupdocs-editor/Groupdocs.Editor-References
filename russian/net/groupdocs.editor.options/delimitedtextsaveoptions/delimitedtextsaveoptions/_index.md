---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Этот конструктор без параметров создает новый экземпляр DelimitedTextSaveOptions с точкой с запятой в качестве разделителя по умолчанию; затем его можно изменить через свойство Separatorgroupdocs.editor.options/delimitedtextsaveoptions/separator."
type: docs
weight: 10
url: /ru/net/groupdocs.editor.options/delimitedtextsaveoptions/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions() {#constructor}

Этот конструктор без параметров создает новый экземпляр DelimitedTextSaveOptions с точкой с запятой (;) в качестве разделителя по умолчанию (может быть изменён затем через свойство [`Separator`](../separator)).

```csharp
public DelimitedTextSaveOptions()
```

### См. также

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

---

## DelimitedTextSaveOptions(string) {#constructor_1}

Создаёт экземпляр класса параметров для разделённого текста с обязательным разделителем (делимитером)

```csharp
public DelimitedTextSaveOptions(string separator)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | String | Строковый разделитель (delimiter), который не может быть NULL или пустым. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда указанный разделитель имеет значение null или пустую строку. |

### См. также

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
