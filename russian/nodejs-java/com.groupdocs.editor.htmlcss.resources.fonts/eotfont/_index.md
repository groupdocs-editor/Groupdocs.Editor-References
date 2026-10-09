---
title: "EotFont"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет один шрифт в формате EOT Embedded OpenType"
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

Представляет один шрифт в формате EOT (Embedded OpenType).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | Создаёт новый класс EotFont из содержимого, представленного в виде base64 |
строки и с указанным именем
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | Создаёт новый класс EotFont из содержимого, представленного в виде байтового потока, и |
с указанным именем
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Размер заголовка EOT (в байтах), необходимый для его проверки |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным шрифтом EOT |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная строка в формате base64 допустимым шрифтом EOT |
|
|  | [getType()](#getType--) | Возвращает FontType.Eot |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


Создаёт новый класс EotFont из содержимого, представленного в виде base64
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя шрифта EOT. Не может быть null, пустым или содержать только пробелы. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки, закодированной base64. Не может быть null, пустым или содержать только пробелы. Если это не содержимое EOT, будет выброшено исключение. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


Создаёт новый класс EotFont из содержимого, представленного в виде байтового потока, и
с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя шрифта EOT. Не может быть null, пустым или содержать только пробелы. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Размер заголовка EOT (в байтах), необходимый для его проверки


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным шрифтом EOT


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Поток байтов, который предположительно содержит ресурс EOT |
|

**Returns:**
boolean — True, если указанный поток содержит действительный шрифт EOT, иначе false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная строка в формате base64 допустимым шрифтом EOT


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предположительно шрифта EOT в виде строки, закодированной base64 |
|

**Returns:**
boolean — True, если указанная строка содержит действительный шрифт EOT, иначе false

### getType() {#getType--}
```
public FontType getType()
```


Возвращает FontType.Eot


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
