---
title: "GetContent"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Возвращает полное содержимое HTML‑документа в виде байтового потока, записывая это содержимое в указанный поток с заданной кодировкой текста"
type: docs
weight: 130
url: /ru/net/groupdocs.editor/editabledocument/getcontent/
---
## GetContent&lt;TStream&gt;(TStream, Encoding) {#getcontent_2}

Возвращает полное содержимое HTML‑документа в виде байтового потока, записывая это содержимое в указанный поток с заданной кодировкой текста

```csharp
public TStream GetContent<TStream>(TStream storage, Encoding encoding)
    where TStream : Stream
```

| Параметр | Описание |
| --- | --- |
| TStream | Любая реализация Stream |
| storage | Ненулевой байтовый поток, поддерживающий запись |
| encoding | Ненулевая текстовая кодировка, которая должна применяться при записи текстового содержимого в указанный *storage* |

### Возвращаемое значение

Экземпляр указанного *хранилища*

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Любой из входных аргументов равен null |
| ArgumentException | Указанный поток не поддерживает запись |

### См. также

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent() {#getcontent}

Возвращает полное содержимое HTML‑документа в виде строки.

```csharp
public string GetContent()
```

### Возвращаемое значение

Строка, содержащая содержимое HTML‑документа

### См. также

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent(string, string) {#getcontent_1}

Возвращает полное содержимое HTML‑документа в виде строки, где ссылки на внешние ресурсы содержат указанный шаблон с заполнителями.

```csharp
public string GetContent(string externalImagesTemplate, string externalCssTemplate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| externalImagesTemplate | String | С помощью этого параметра можно указать строковый шаблон с одним заполнителем, который будет применён к ссылкам на все внешние изображения в элементах IMG, присутствующих в результирующей строке HTML. Если значение NULL или пусто, шаблон не будет добавлен, и в результирующей разметке HTML будут присутствовать только имена файлов. Если шаблон недействителен, он будет рассматриваться как префикс, поэтому имена файлов будут конкатенированы к его концу. |
| externalCssTemplate | String | С помощью этого параметра можно указать строковый шаблон с одним заполнителем, который будет добавлен к ссылкам на все внешние таблицы стилей в элементах LINK, присутствующих в результирующей строке HTML. Если NULL или пустой, шаблон не будет добавлен, и в результирующей разметке HTML будут присутствовать только имена файлов. Если шаблон недействителен, он будет рассматриваться как префикс, поэтому имена файлов будут конкатенированы к его концу. |

### Возвращаемое значение

Строка, содержащая содержимое HTML‑документа со ссылками, адаптированными к внешним ресурсам

### См. также

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
