---
title: "MetaImageBase"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Базовый абстрактный класс для форматов изображений WMF и EMF"
type: docs
weight: 11
url: /ru/java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

Базовый абстрактный класс для форматов изображений WMF и EMF

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Общий конструктор, который подготавливает создание экземпляра WMF или EMF из |
строка, закодированная в base64
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Общий конструктор, который подготавливает создание экземпляра WMF или EMF из |
поток байтов
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Определяет, содержит ли указанный поток байтов корректное изображение WMF |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Определяет, содержит ли указанная строка корректное изображение WMF, которое |
закодировано в base64
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Определяет, содержит ли указанный поток байтов корректное изображение EMF |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Определяет, содержит ли указанная строка корректное изображение EMF, которое |
закодировано в base64
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | В реализации тип должен сохранить текущий векторный мета‑изображение в |
векторный формат SVG в указанный поток байтов
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Общий конструктор, который подготавливает создание экземпляра WMF или EMF из
строка, закодированная в base64


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Обязательное имя |
|
|  | contentInBase64 | java.lang.String | Содержимое в виде строки base64. Не должно быть NULL или пустым. |
|
|  | isWmf | boolean | true для WMF, false для EMF |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Общий конструктор, который подготавливает создание экземпляра WMF или EMF из
поток байтов


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Обязательное имя |
|
|  | binaryContent | java.io.InputStream | Содержимое в виде потока байтов. Должно быть корректным. |
|
|  | isWmf | boolean | true для WMF, false для EMF |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


Определяет, содержит ли указанный поток байтов корректное изображение WMF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Входной поток байтов. Должен быть корректным. |
|

**Returns:**
boolean - Возвращает 'true', если корректно, и 'false', если некорректно

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


Определяет, содержит ли указанная строка корректное изображение WMF, которое
закодировано в base64


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Строка, которая, как предполагается, содержит изображение WMF, закодированное в base64 |
|

**Returns:**
boolean - Возвращает 'true', если корректно, и 'false', если некорректно

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


Определяет, содержит ли указанный поток байтов корректное изображение EMF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Входной поток байтов. Должен быть корректным. |
|

**Returns:**
boolean - Возвращает 'true', если корректно, и 'false', если некорректно

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


Определяет, содержит ли указанная строка корректное изображение EMF, которое
закодировано в base64


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Строка, предполагаемая содержащей base64‑закодированное изображение EMF |
|

**Returns:**
boolean - Возвращает 'true', если корректно, и 'false', если некорректно

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


В реализации тип должен сохранить текущий векторный мета‑изображение в
векторный формат SVG в указанный поток байтов


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Поток байтов, в который будет сохранена версия SVG этого векторного мета‑изображения. Не должен быть NULL и должен поддерживать запись. |
|

