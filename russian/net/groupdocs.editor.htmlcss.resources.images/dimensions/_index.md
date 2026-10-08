---
title: "Dimensions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет линейные размеры ширины и высоты одного растрового прямоугольного изображения в произвольных единицах. Неизменяемая структура."
type: docs
weight: 450
url: /ru/net/groupdocs.editor.htmlcss.resources.images/dimensions/
---
## Dimensions structure

Представляет линейные размеры (ширину и высоту) одного растрового прямоугольного изображения в произвольных единицах. Неизменяемая структура.

```csharp
public struct Dimensions : ICloneable, IEquatable<Dimensions>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Dimensions](dimensions)(ushort, ushort) | Создаёт новый экземпляр с указанными шириной и высотой. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Empty](../../groupdocs.editor.htmlcss.resources.images/dimensions/empty) { get; } | Возвращает пустой экземпляр Dimensions |
| [Area](../../groupdocs.editor.htmlcss.resources.images/dimensions/area) { get; } | Возвращает площадь (Width x Height) |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/dimensions/aspectratio) { get; } | Соотношение сторон этих размеров как width/height |
| [Height](../../groupdocs.editor.htmlcss.resources.images/dimensions/height) { get; } | Возвращает высоту изображения. |
| [IsEmpty](../../groupdocs.editor.htmlcss.resources.images/dimensions/isempty) { get; } | Определяет, является ли данный экземпляр "Dimensions" пустым и значением по умолчанию, т.е. не содержит корректных ширины и высоты |
| [IsSquare](../../groupdocs.editor.htmlcss.resources.images/dimensions/issquare) { get; } | Определяет, представляет ли указанный 'Dimensions' квадрат, т.е. ширина равна высоте |
| [Width](../../groupdocs.editor.htmlcss.resources.images/dimensions/width) { get; } | Возвращает ширину изображения |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.editor.htmlcss.resources.images/dimensions/clone)() | Возвращает полную копию данного экземпляра |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals)(Dimensions) | Определяет, равен ли данный экземпляр указанному экземпляру "Dimensions" |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals_1)(object) | Определяет, равен ли данный экземпляр указанному неконвертированному объекту, который предположительно является другим экземпляром "Dimensions" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/dimensions/gethashcode)() | Возвращает хеш-код для данного экземпляра, который не может быть изменён в течение его жизни |
| [ProportionallyResizeForNewHeight](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewheight)(ushort) | Создаёт и возвращает новый экземпляр "Dimensions", пропорционально изменённый от текущего на основе указанной высоты |
| [ProportionallyResizeForNewWidth](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewwidth)(ushort) | Создаёт и возвращает новый экземпляр "Dimensions", пропорционально изменённый от текущего на основе указанной ширины |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/dimensions/tostring)() | Возвращает строковое представление этого "Dimensions" |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_equality) | Проверяет, равны ли два значения "Dimensions", т.е. имеют одинаковую ширину и высоту, либо оба пусты |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_inequality) | Проверяет, не равны ли два значения "Dimensions", т.е. их соответствующая ширина и/или высота различаются |

### См. также

* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
