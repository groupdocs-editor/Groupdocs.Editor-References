---
title: "Woff2Font"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет один шрифт в формате WOFF2 Web Open Font Format"
type: docs
weight: 16
url: /ru/java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

Представляет один шрифт в формате WOFF2 (Web Open Font Format).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | Создаёт новый класс Woff2Font из содержимого, представленного в виде base64‑закодированного |
строки и с указанным именем
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | Создаёт новый класс Woff2Font из содержимого, представленного в виде потока байтов, и |
с указанным именем
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Размер заголовка WOFF2 (в байтах), необходимый для его проверки |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным шрифтом WOFF2 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная base64‑закодированная строка действительным шрифтом WOFF2 |
|
|  | [getType()](#getType--) | Возвращает FontType.Woff2 |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


Создаёт новый класс Woff2Font из содержимого, представленного в виде base64‑закодированного
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя шрифта WOFF2. Не может быть null, пустым или содержать только пробелы. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде base64‑закодированной строки. Не может быть null, пустым или содержать только пробелы. Если это не содержимое WOFF2, будет выброшено исключение. |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


Создаёт новый класс Woff2Font из содержимого, представленного в виде потока байтов, и
с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя шрифта WOFF2. Не может быть null, пустым или содержать только пробелы. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Размер заголовка WOFF2 (в байтах), необходимый для его проверки


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным шрифтом WOFF2


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Поток байтов, который, предположительно, содержит ресурс WOFF2 |
|

**Returns:**
логический тип - True, если указанный поток содержит действительный шрифт WOFF2, иначе false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная base64‑закодированная строка действительным шрифтом WOFF2


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предположительно WOFF2 шрифта в виде base64‑закодированной строки |
|

**Returns:**
логический тип - True, если указанная строка содержит действительный шрифт WOFF2, иначе false

### getType() {#getType--}
```
public FontType getType()
```


Возвращает FontType.Woff2


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
