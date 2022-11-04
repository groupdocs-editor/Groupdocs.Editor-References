---
title: AudioType
second_title: Справочник по API GroupDocs.Editor для .NET
description: Представляет один поддерживаемый аудиотип формат
type: docs
weight: 240
url: /ru/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

Представляет один поддерживаемый аудиотип (формат)

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | Представляет аудиоформат MPEG-1 Audio Layer III |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | Специальное значение, обозначающее неопределенный, неизвестный или неподдерживаемый аудиоформат |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | Расширение имени файла (без символа точки) для этого аудиоформата |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | Официальное название этого аудиоформата |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | MIME-код для этого аудиоформата |

## Методы

| Имя | Описание |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | Возвращает значение AudioType, эквивалентное расширению имени файла, которое извлекается из указанного файла name |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | Определяет, равен ли этот экземпляр указанному "AudioType" instance |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | Определяет, равен ли этот экземпляр указанному неприведенному объекту, который предположительно является другим "AudioType" instance |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | Возвращает хэш-код, который является постоянным числом для этого конкретного значения type |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | Проверяет, равны ли два значения «AudioType» |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | Проверяет, не равны ли два значения «AudioType» |

### Смотрите также

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* пространство имен [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->