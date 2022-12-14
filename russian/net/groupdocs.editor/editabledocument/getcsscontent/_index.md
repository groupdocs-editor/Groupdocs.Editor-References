---
title: GetCssContent
second_title: Справочник по API GroupDocs.Editor для .NET
description: Возвращает содержимое всех внешних таблиц стилей в виде списка строк где одна строка представляет одну таблицу стилей. Возвращает пустой список если для этого документа нет CSS.
type: docs
weight: 140
url: /ru/net/groupdocs.editor/editabledocument/getcsscontent/
---
## GetCssContent() {#getcsscontent}

Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где одна строка представляет одну таблицу стилей. Возвращает пустой список, если для этого документа нет CSS.

```csharp
public List<string> GetCssContent()
```

### Возвращаемое значение

Список строк, где каждая строка содержит содержимое одного документа CSS.

### Смотрите также

* class [EditableDocument](../../editabledocument)
* пространство имен [GroupDocs.Editor](../../editabledocument)
* сборка [GroupDocs.Editor](../../../)

---

## GetCssContent(string, string) {#getcsscontent_1}

Возвращает содержимое всех внешних таблиц стилей в виде списка строк, где одна строка представляет одну таблицу стилей. Указанный префикс будет применяться к каждой ссылке на внешний ресурс в каждой результирующей таблице стилей. Возвращает пустой список, если для этого нет CSS документ.

```csharp
public List<string> GetCssContent(string externalImagesPrefix, string externalFontsPrefix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| externalImagesPrefix | String | Через этот параметр можно указать префикс, который будет добавляться к links ко всем внешним изображениям, которые будут присутствовать в объявлениях CSS в результирующих строках CSS. Если значение NULL или пустое, префиксы добавляться не будут. |
| externalFontsPrefix | String | Через этот параметр можно указать префикс, который будет добавляться к links ко всем внешним шрифтам в at-правилах @font-face в результирующих строках CSS. Если значение NULL или пустое, префиксы добавляться не будут. |

### Возвращаемое значение

Список строк, где каждая строка содержит содержимое одного документа CSS.

### Смотрите также

* class [EditableDocument](../../editabledocument)
* пространство имен [GroupDocs.Editor](../../editabledocument)
* сборка [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
