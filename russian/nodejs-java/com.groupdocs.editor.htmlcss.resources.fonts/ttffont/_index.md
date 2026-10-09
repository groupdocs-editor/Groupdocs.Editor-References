---
title: "TtfFont"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет один шрифт в формате TTF TrueType Font"
type: docs
weight: 15
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

Представляет один шрифт в формате TTF (TrueType Font).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | Создаёт новый класс TtfFont из содержимого, представленного в виде base64 |
строки и с указанным именем
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | Создаёт новый класс TtfFont из содержимого, представленного в виде байтового потока, и |
с указанным именем
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Размер заголовка TTF (в байтах), необходимый для его проверки |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным шрифтом TTF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная строка, закодированная в base64, действительным шрифтом TTF |
|
|  | [getType()](#getType--) | Возвращает FontType.Ttf |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


Создаёт новый класс TtfFont из содержимого, представленного в виде base64
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя шрифта TTF. Не может быть null, пустым или содержать только пробелы. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки, закодированной в base64. Не может быть null, пустым или содержать только пробелы. Если это не содержимое TTF, будет выброшено исключение. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


Создаёт новый класс TtfFont из содержимого, представленного в виде байтового потока, и
с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя шрифта TTF. Не может быть null, пустым или содержать только пробелы. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Размер заголовка TTF (в байтах), необходимый для его проверки


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным шрифтом TTF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Байтовый поток, который предположительно содержит ресурс TTF |
|

**Returns:**
boolean - true, если указанный поток содержит действительный шрифт TTF, false в противном случае

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная строка, закодированная в base64, действительным шрифтом TTF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предполагаемого шрифта TTF в виде строки, закодированной в base64 |
|

**Returns:**
boolean - true, если указанная строка содержит действительный шрифт TTF, false в противном случае

### getType() {#getType--}
```
public FontType getType()
```


Возвращает FontType.Ttf


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
