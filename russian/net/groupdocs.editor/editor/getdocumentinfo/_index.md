---
title: "GetDocumentInfo"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Возвращает метаданные о документе, загруженном в этот экземпляр Editor."
type: docs
weight: 70
url: /ru/net/groupdocs.editor/editor/getdocumentinfo/
---
## Editor.GetDocumentInfo method

Возвращает метаданные о документе, загруженном в этот экземпляр 'Editor'.

```csharp
public IDocumentInfo GetDocumentInfo(string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| password | String | Пользователь может указать пароль для документа, если документ зашифрован паролем. Может быть NULL или пустой строкой, что эквивалентно отсутствию пароля. Для форматов документов, не поддерживающих защиту паролем, этот аргумент будет игнорироваться. Если документ зашифрован и пароль не указан в этом параметре, но был указан ранее в параметрах загрузки при создании экземпляра [`Editor`](../../editor), он будет использован. |

### Возвращаемое значение

Наследник интерфейса [`IDocumentInfo`](../../../groupdocs.editor.metadata/idocumentinfo), специфичный для формата, который указывает обнаруженный формат с метаданными, характерными для формата, или NULL, если документ не был распознан как поддерживаемый или повреждён.

### Исключения

| исключение | условие |
| --- | --- |
| ObjectDisposedException | Выбрасывается, когда экземпляр Editor уже был освобождён при вызове "GetDocumentInfo". |
| [PasswordRequiredException](../../passwordrequiredexception) | Выбрасывается, когда загруженный документ защищён паролем, но пароль не указан в параметре "*password*" и в параметрах загрузки при создании экземпляра. |
| [IncorrectPasswordException](../../incorrectpasswordexception) | Выбрасывается, когда загруженный документ защищён паролем, пароль указан, но неверен. |
| InvalidOperationException | Выбрасывается, когда произошла неожиданная ошибка неизвестного характера. |

### Замечания

Метод GetDocumentInfo полезен, когда неизвестно, в каком формате входной документ, защищён ли он паролем и/или сколько страниц/листов/слайдов он содержит. На основе этих метаданных, возвращаемых GetDocumentInfo, можно корректно настроить параметры загрузки и редактирования для основной конвейерной обработки.

Метод GetDocumentInfo всегда возвращает полные данные, он не зависит от режима пробной версии, его использование не списывает потреблённые байты или кредиты.

**Learn more**

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Extracting+document+metainfo)

### См. также

* interface [IDocumentInfo](../../../groupdocs.editor.metadata/idocumentinfo)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
