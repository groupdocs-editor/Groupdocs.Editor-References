---
title: "GetHashCode"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Возвращает хеш‑код текущего объекта."
type: docs
weight: 40
url: /ru/net/groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode/
---
## FormatFamilyBase.GetHashCode method

Возвращает хеш‑код текущего объекта.

```csharp
public override int GetHashCode()
```

### Возвращаемое значение

Хеш‑код текущего объекта, подходящий для использования в алгоритмах хеширования и структурах данных, таких как хеш‑таблица.

### Замечания

Этот метод переопределяет GetHashCode. Хеш‑код вычисляется с использованием свойств объекта `Id` и `Name`. Контекст `unchecked` позволяет переполнение, что приемлемо в контексте вычисления хеш‑кода.

### См. также

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
