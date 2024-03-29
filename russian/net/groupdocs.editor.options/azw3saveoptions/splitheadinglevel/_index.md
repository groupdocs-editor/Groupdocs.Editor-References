---
title: SplitHeadingLevel
second_title: Справочник по API GroupDocs.Editor для .NET
description: Указывает следует ли разбивать содержимое электронной книги AZW3 на пакеты и если да то максимальный уровень заголовков на котором следует разбивать содержимое AZW3. Значение по умолчанию2 . Установка на0отключит разделение поэтому все содержимое электронной книги будет объединено в единый пакет внутри AZW3.
type: docs
weight: 20
url: /ru/net/groupdocs.editor.options/azw3saveoptions/splitheadinglevel/
---
## Azw3SaveOptions.SplitHeadingLevel property

Указывает, следует ли разбивать содержимое электронной книги AZW3 на пакеты, и если да, то максимальный уровень заголовков, на котором следует разбивать содержимое AZW3. Значение по умолчанию`2` . Установка на`0`отключит разделение, поэтому все содержимое электронной книги будет объединено в единый пакет внутри AZW3.

```csharp
public int SplitHeadingLevel { get; set; }
```

### Примечания

В некоторых случаях предпочтительнее разделить содержимое электронной книги на несколько меньших пакетов, расположенных внутри выходного файла AZW3. Это свойство определяет, должно ли выполняться такое разделение, и если да, то каким образом.

Если для этого свойства задано значение от 1 до 9, документ будет разбит на абзацы, отформатированные с помощью .**Заголовок 1** ,**Заголовок 2** ,**Заголовок 3** и т. д. стили до указанного уровня заголовка.

По умолчанию (значение`2` ), только**Заголовок 1** и**Заголовок 2** абзацы приводят к разделению документа. Установка этого свойства в ноль приведет к тому, что документ вообще не будет разбиваться на абзацы заголовков.

### Смотрите также

* class [Azw3SaveOptions](../../azw3saveoptions)
* пространство имен [GroupDocs.Editor.Options](../../azw3saveoptions)
* сборка [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
