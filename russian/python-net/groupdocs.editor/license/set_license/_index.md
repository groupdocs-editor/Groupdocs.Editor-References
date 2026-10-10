---
title: "метод set_license"
second_title: "GroupDocs.Editor для Python через .NET: справочник API"
description: 
type: docs
url: /ru/python-net/groupdocs.editor/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Применить лицензию к текущему процессу.

```python
def set_license(self, license_source):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| license_source |  | Либо строковый путь к файлу ``.lic`` или объект, похожий на файл, который может быть прочитан и возвращает байты лицензии. Входные данные, похожие на файл, записываются во временный файл перед передачей в мост. |

| Вызывает | Описание |
| :- | :- |
| `TypeError` | Если ``license_source`` не является ни строковым путем, ни объектом, похожим на файл, доступным для чтения. |

### См. также
* class [`License`](/editor/python-net/groupdocs.editor/license/)
