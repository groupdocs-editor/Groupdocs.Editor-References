---
title: "GetCssContent"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где каждая строка представляет одну таблицу стилей. Возвращает пустой список, если для этого документа нет CSS."
type: docs
weight: 140
url: /ru/net/groupdocs.editor/editabledocument/getcsscontent/
---
## GetCssContent() {#getcsscontent}

Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где каждая строка представляет одну таблицу стилей. Возвращает пустой список, если для этого документа нет CSS.

```csharp
public List<string> GetCssContent()
```

### Возвращаемое значение

Список строк, где каждая строка содержит содержимое одного CSS‑документа

### См. также

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetCssContent(string, string) {#getcsscontent_1}

Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где каждая строка представляет одну таблицу стилей. Указанный префикс будет применён к каждой ссылке на внешний ресурс в каждой полученной таблице стилей. Возвращает пустой список, если для этого документа нет CSS.

```csharp
public List<string> GetCssContent(string externalImagesPrefix, string externalFontsPrefix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| externalImagesPrefix | String | С помощью этого параметра можно указать префикс, который будет добавлен к ссылкам на все внешние изображения, присутствующие в CSS‑объявлениях результирующих CSS‑строк. Если NULL или пусто, префиксы добавляться не будут. |
| externalFontsPrefix | String | С помощью этого параметра можно указать префикс, который будет добавлен к ссылкам на все внешние шрифты в правилах @font-face результирующих CSS‑строк. Если NULL или пусто, префиксы добавляться не будут. |

### Возвращаемое значение

Список строк, где каждая строка содержит содержимое одного CSS‑документа

### См. также

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
