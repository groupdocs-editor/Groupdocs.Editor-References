---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задавать пользовательские параметры для создания и сохранения документов презентаций, совместимых с PowerPoint."
type: docs
weight: 1100
url: /ru/net/groupdocs.editor.options/presentationsaveoptions/
---
## PresentationSaveOptions class

Позволяет задавать пользовательские параметры для создания и сохранения документов презентаций (совместимых с PowerPoint)

```csharp
public sealed class PresentationSaveOptions : ISaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | Этот конструктор без параметров создаёт новый экземпляр PresentationSaveOptions с форматом вывода PPTX (может быть изменён затем через свойство [`OutputFormat`](./outputformat)). |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(PresentationFormats) | Создаёт новый экземпляр PresentationSaveOptions с указанным обязательным форматом вывода презентации, при этом все остальные параметры имеют значения по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [InsertAsNewSlide](../../groupdocs.editor.options/presentationsaveoptions/insertasnewslide) { get; set; } | Логический флаг, указывающий, должна ли отредактированная слайд заменять существующий слайд в оригинальной презентации на позиции, указанной свойством [`SlideNumber`](./slidenumber), или она должна быть вставлена между существующим слайдом и предыдущим, без замены его содержимого. По умолчанию — `false` — существующий слайд будет заменён. Это свойство игнорируется, если значение свойства [`SlideNumber`](./slidenumber) установлено в '0'. |
| [OutputFormat](../../groupdocs.editor.options/presentationsaveoptions/outputformat) { get; set; } | Позволяет указать формат презентации, который будет использоваться для сохранения документа. |
| [Password](../../groupdocs.editor.options/presentationsaveoptions/password) { get; set; } | Позволяет указать, изменить и получить пароль, который будет использоваться для кодирования полученного документа презентации. По умолчанию — NULL — пароль не будет установлен. Установите NULL или пустую строку, чтобы удалить пароль, если он был установлен ранее. |
| [SlideNumber](../../groupdocs.editor.options/presentationsaveoptions/slidenumber) { get; set; } | Позволяет вставлять отредактированный слайд в существующую презентацию вместо создания новой одно‑слайдовой презентации (поведение по умолчанию). Номер слайда — это нумерация, начинающаяся с 1, слайда в презентации, загруженной в классе Editor. Если он равен 0 (значение по умолчанию), будет создана новая презентация с одним отредактированным слайдом. Если он больше или меньше нуля, и существует корректная презентация, загруженная в классе Editor, отредактированный слайд, хранящийся во входном экземпляре EditableDocument, будет вставлен в эту презентацию. |
| [SlideNumbersToDelete](../../groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete) { get; set; } | Позволяет указать массив номеров слайдов (нумерация начинается с 1), которые должны быть удалены из презентации при её сохранении, если отредактированный слайд вставлен в существующую презентацию. |

### Замечания

Экземпляр этого класса должен быть передан в метод, чтобы сохранить отредактированную презентацию в конечный документ некоторого формата, специфичного для презентаций. Все остальные параметры являются необязательными и могут быть опущены; по умолчанию формат сохраняемой презентации — PPTX, но его можно изменить через конструктор или свойство.

### См. также

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
