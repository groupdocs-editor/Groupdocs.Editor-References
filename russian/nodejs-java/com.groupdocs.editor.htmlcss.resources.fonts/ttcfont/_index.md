---
title: "TtcFont"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет один шрифт в формате TTC TrueType Collection."
type: docs
weight: 14
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

Представляет один шрифт в формате TTC (TrueType Collection).


Смотрите подробнее: https://docs.fileformat.com/font/ttc/

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | Создаёт новый класс TtcFont из содержимого, представленного в виде base64‑закодированного. |
строки и с указанным именем
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | Создаёт новый класс TtcFont из содержимого, представленного в виде потока байтов, и |
с указанным именем
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Размер заголовка TTC (в байтах), необходимый для его проверки. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Проверяет, является ли указанный поток действительным шрифтом TTC. |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Проверяет, является ли указанная base64‑закодированная строка действительным шрифтом TTC. |
|
|  | [getType()](#getType--) | Возвращает FontType.Ttc |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | Версия заголовка TTC, может быть "1" или "2". |
|
|  | [getFontsNumber()](#getFontsNumber--) | Количество шрифтов в этом TTC. |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | Указывает, содержит ли этот TTC таблицу DSIG. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


Создаёт новый класс TtcFont из содержимого, представленного в виде base64‑закодированного.
строки и с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя шрифта TTC. Не может быть null, пустым или состоящим только из пробелов. |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде base64‑закодированной строки. Не может быть null, пустым или состоящим только из пробелов. Если это не содержимое TTC, будет выброшено исключение. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


Создаёт новый класс TtcFont из содержимого, представленного в виде потока байтов, и
с указанным именем


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя шрифта TTC. Не может быть null, пустым или состоящим только из пробелов. |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Чтение начинается с исходной позиции. Не может быть null. Должен быть читаемым и поддерживать поиск. Если этот экземпляр будет освобождён, этот поток также будет освобождён. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Размер заголовка TTC (в байтах), необходимый для его проверки.


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Проверяет, является ли указанный поток действительным шрифтом TTC.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Поток байтов, который, предположительно, содержит ресурс TTC. |
|

**Returns:**
boolean - true, если указанный поток содержит действительный шрифт TTC, false в противном случае

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Проверяет, является ли указанная base64‑закодированная строка действительным шрифтом TTC.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Содержимое предполагаемого шрифта TTC в виде строки, закодированной в base64 |
|

**Returns:**
boolean - true, если указанная строка содержит действительный шрифт TTC, false в противном случае

### getType() {#getType--}
```
public FontType getType()
```


Возвращает FontType.Ttc


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


Версия заголовка TTC, может быть "1" или "2".


**Returns:**
byte
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


Количество шрифтов в этом TTC.


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


Указывает, содержит ли этот TTC таблицу DSIG. Таблица DSIG может присутствовать
только если у TTC есть заголовок версии 2.0.


**Returns:**
boolean
