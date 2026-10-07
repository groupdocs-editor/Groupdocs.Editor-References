---
title: "ResourceTypeDetector"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Вспомогательные статические методы для определения типов и форматов ресурсов"
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

Утилитные статические методы для определения типов ресурсов (форматов).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | Определяет тип по указанному имени файла и возвращает экземпляр |
соответствующего IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | Пытается проанализировать входной поток и создает один из поддерживаемых HTML |
ресурсов из него, учитывая указанный предполагаемый тип, если он
не равен null
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


Определяет тип по указанному имени файла и возвращает экземпляр
соответствующего IResourceType


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | имя файла | java.lang.String | Входное имя файла, из которого этот метод попытается извлечь реализованную IResourceType |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


Пытается проанализировать входной поток и создает один из поддерживаемых HTML
ресурсов из него, учитывая указанный предполагаемый тип, если он
не равен null


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | Входной поток, который предположительно содержит HTML‑ресурс. Если он недействителен, будет выброшено исключение. |
|
|  | name | java.lang.String | Имя ресурса, которое будет использовано для созданного и возвращённого ресурса при успешном выполнении. Не может быть NULL, пустым или состоящим только из пробелов |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | Предполагаемый формат входного HTML‑ресурса, полезный для достижения наилучшей производительности. Если полностью неизвестен, используйте значение NULL. Может быть неверным, что лишь ухудшит производительность. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

