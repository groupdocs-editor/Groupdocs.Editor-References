---
title: "OtfFont"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет один шрифт в формате OTF Open Type Format"
type: docs
weight: 13
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

Представляет один шрифт в формате OTF (Open Type Format).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | Создаёт новый класс OtfFont из содержимого, представленного в виде base64 |
строки и с указанным именем
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | Создаёт новый класс OtfFont из содержимого, представленного в виде потока байтов, и |
с указанным именем
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Размер заголовка OTF (в байтах), необходимый для его проверки |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным шрифтом OTF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная строка, закодированная base64, действительным шрифтом OTF |
|
|  | [getType()](#getType--) | Возвращает |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


Создаёт новый класс OtfFont из содержимого, представленного в виде base64
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя шрифта OTF. Не может быть null, пустым или содержать только пробелы. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки, закодированной base64. Не может быть null, пустым или содержать только пробелы. Если это не содержимое OTF, будет выброшено исключение. |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


Создаёт новый класс OtfFont из содержимого, представленного в виде потока байтов, и
с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя шрифта OTF. Не может быть null, пустым или содержать только пробелы. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Размер заголовка OTF (в байтах), необходимый для его проверки


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным шрифтом OTF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Поток байтов, который предположительно содержит ресурс OTF |
|

**Returns:**
boolean — True, если указанный поток содержит действительный шрифт OTF, иначе false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная строка, закодированная base64, действительным шрифтом OTF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предположительно шрифта OTF в виде строки, закодированной base64 |
|

**Returns:**
boolean — True, если указанная строка содержит действительный шрифт OTF, иначе false

### getType() {#getType--}
```
public FontType getType()
```


Возвращает
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
