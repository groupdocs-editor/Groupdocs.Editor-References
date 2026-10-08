---
title: "AudioType"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет один поддерживаемый формат аудиотипа"
type: docs
weight: 320
url: /ru/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

Представляет один поддерживаемый тип аудио (формат)

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | Представляет аудиоформат MPEG-1 Audio Layer III |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | Специальное значение, которое обозначает неопределённый, неизвестный или неподдерживаемый аудиоформат |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | Расширение имени файла (без символа точки) для этого аудиоформата |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | Официальное название этого аудиоформата |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | MIME‑код для этого аудиоформата |

## Методы

| Имя | Описание |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | Возвращает значение AudioType, которое эквивалентно расширению имени файла, извлечённому из указанного имени файла |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | Определяет, равен ли данный экземпляр указанному экземпляру \"AudioType\" |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | Определяет, равен ли данный экземпляр указанному неконвертированному объекту, который, предположительно, является другим экземпляром \"AudioType\" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | Возвращает хеш‑код, который является постоянным числом для этого конкретного типа значения |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | Проверяет, равны ли два значения \"AudioType\" |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | Проверяет, не равны ли два значения \"AudioType\" |

### См. также

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
