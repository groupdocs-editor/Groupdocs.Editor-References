---
title: Editor
second_title: Справочник по API GroupDocs.Editor для .NET
description: Инициализирует новый экземпляр редактора с указанным входным документом в виде потока
type: docs
weight: 10
url: /ru/net/groupdocs.editor/editor/editor/
---
## Editor(Func&lt;Stream&gt;) {#constructor}

Инициализирует новый экземпляр редактора с указанным входным документом (в виде потока)

```csharp
public Editor(Func<Stream> document)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Делегат, который должен возвращать поток с содержимым документа. Не должен быть NULL. |

### Примечания

**Учить больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs. Editor: [Форматы документов, поддерживаемые GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Editor для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Смотрите также

* class [Editor](../../editor)
* пространство имен [GroupDocs.Editor](../../editor)
* сборка [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_1}

Инициализирует новый экземпляр редактора с указанным входным документом (в виде потока) с параметрами загрузки

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Делегат, который должен возвращать поток с содержимым документа. Не должен быть NULL. |
| loadOptions | Func`1 | Делегат, который должен возвращать параметры загрузки документа. Может быть NULL и может возвращать null - , в этом случае тип документа будет определен автоматически и будут применены параметры загрузки по умолчанию для этого типа. |

### Примечания

**Учить больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs. Editor: [Форматы документов, поддерживаемые GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Editor для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Подробнее о том, как открывать и редактировать защищенные паролем документы и документы из разных хранилищ: [Загружайте и редактируйте документы с помощью GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Смотрите также

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* пространство имен [GroupDocs.Editor](../../editor)
* сборка [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_2}

Инициализирует новый экземпляр редактора с указанным входным документом (как полный путь к файлу)

```csharp
public Editor(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Полный путь к файлу. Не должен быть NULL. Должен быть действительным, и файл должен существовать. |

### Примечания

**Учить больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs. Editor: [Форматы документов, поддерживаемые GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Editor для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Смотрите также

* class [Editor](../../editor)
* пространство имен [GroupDocs.Editor](../../editor)
* сборка [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_3}

Инициализирует новый экземпляр редактора с указанным входным документом (как полный путь к файлу) с параметрами загрузки

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Полный путь к файлу. Не должен быть NULL. Должен быть действительным, и файл должен существовать. |
| loadOptions | Func`1 | Делегат, который должен возвращать параметры загрузки документа. Может быть NULL и может возвращать null - , в этом случае тип документа будет определен автоматически и будут применены параметры загрузки по умолчанию для этого типа. |

### Примечания

**Учить больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs. Editor: [Форматы документов, поддерживаемые GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Editor для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Подробнее о том, как открывать и редактировать защищенные паролем документы и документы из разных хранилищ: [Загружайте и редактируйте документы с помощью GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Смотрите также

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* пространство имен [GroupDocs.Editor](../../editor)
* сборка [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
