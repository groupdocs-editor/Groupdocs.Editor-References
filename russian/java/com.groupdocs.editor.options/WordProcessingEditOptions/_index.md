---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет указать пользовательские параметры для редактирования документов всех поддерживаемых форматов, совместимых с WordProcessing Words, таких как DOCX, RTF, ODT и т.д."
type: docs
weight: 44
url: /ru/java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Позволяет указать пользовательские параметры для редактирования документов всех поддерживаемых
Форматы WordProcessing (соответствующие Words), такие как DOC(X), RTF, ODT и т.д.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | Создаёт и возвращает новый экземпляр WordProcessingEditOptions |
класс, в котором все параметры установлены в значения по умолчанию
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | Создаёт и возвращает новый экземпляр WordProcessingEditOptions |
класс с указанной пагинацией и всеми другими параметрами по умолчанию
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Указывает, экспортируется ли информация о языке в разметку HTML в |
форме HTML‑атрибутов 'lang'.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Указывает, экспортируется ли информация о языке в разметку HTML в |
форме HTML‑атрибутов 'lang'.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Получает или задаёт значение, указывающее, следует ли извлекать только те ресурсы шрифтов, которые |
используются в текстовом содержимом документа.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Получает или задаёт значение, указывающее, следует ли извлекать только те ресурсы шрифтов, которые |
используются в текстовом содержимом документа.
|
|  | [getFontExtraction()](#getFontExtraction--) | Отвечает за извлечение ресурсов шрифтов, которые используются во входном |
документе WordProcessing.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Отвечает за извлечение ресурсов шрифтов, которые используются во входном |
документе WordProcessing.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | Позволяет указать имя класса, которое будет помещено в атрибут 'class' |
в каждом HTML‑элементе, представляющем какое‑то поле во входных
документе WordProcessing.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Позволяет указать имя класса, которое будет помещено в атрибут 'class' |
в каждом HTML‑элементе, представляющем какое‑то поле во входных
документе WordProcessing.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Управляет тем, где хранить данные стилей и форматирования входного документа WordProcessing: во внешней таблице стилей ( |
false
) или как встроенные стили в разметке HTML (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Управляет тем, где хранить данные стилей и форматирования входного документа WordProcessing: во внешней таблице стилей ( |
false
) или как встроенные стили в разметке HTML (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


Создаёт и возвращает новый экземпляр WordProcessingEditOptions
класс, в котором все параметры установлены в значения по умолчанию


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


Создаёт и возвращает новый экземпляр WordProcessingEditOptions
класс с указанной пагинацией и всеми другими параметрами по умолчанию


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | enablePagination | boolean | Флаг пагинации, который включает вывод HTML, адаптированный для постраничного режима |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. По
по умолчанию отключено (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. По
по умолчанию отключено (false).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Указывает, экспортируется ли информация о языке в разметку HTML в
форма HTML‑атрибутов 'lang'. Эта опция может быть полезна для обратного
преобразования многоязычных документов. По умолчанию отключена
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Указывает, экспортируется ли информация о языке в разметку HTML в
форма HTML‑атрибутов 'lang'. Эта опция может быть полезна для обратного
преобразования многоязычных документов. По умолчанию отключена
(false).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Получает или задаёт значение, указывающее, следует ли извлекать только те ресурсы шрифтов, которые
используются в текстовом содержимом документа.
Значение:  true  если требуется извлекать только те ресурсы шрифтов, которые используются в текстовом содержимом документа; иначе  false . Значение по умолчанию —  false .


*** ** * ** ***

Не все шрифты, используемые в документе WordProcessing, используются на 100 % напрямую (применяются к какому‑то тексту). Может возникнуть ситуация, когда шрифт упомянут в документе и даже может быть встроен, но не применяется к ни одному фрагменту текста. Например, некоторый шрифт может быть привязан к какому‑то стилю, но этот стиль не применяется к любой части текста. Эта опция управляет тем, как обрабатывать такие случаи.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Получает или задаёт значение, указывающее, следует ли извлекать только те ресурсы шрифтов, которые
используются в текстовом содержимом документа.
Значение:  true  если требуется извлекать только те ресурсы шрифтов, которые используются в текстовом содержимом документа; иначе  false . Значение по умолчанию —  false .


*** ** * ** ***

Не все шрифты, используемые в документе WordProcessing, используются на 100 % напрямую (применяются к какому‑то тексту). Может возникнуть ситуация, когда шрифт упомянут в документе и даже может быть встроен, но не применяется к ни одному фрагменту текста. Например, некоторый шрифт может быть привязан к какому‑то стилю, но этот стиль не применяется к любой части текста. Эта опция управляет тем, как обрабатывать такие случаи.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Отвечает за извлечение ресурсов шрифтов, которые используются во входном
Документ WordProcessing. По умолчанию не извлекает никакие шрифты
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Отвечает за извлечение ресурсов шрифтов, которые используются во входном
Документ WordProcessing. По умолчанию не извлекает никакие шрифты
(NotExtract).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Позволяет указать имя класса, которое будет помещено в атрибут 'class'
в каждом HTML‑элементе, представляющем какое‑то поле во входных
Документ WordProcessing. По умолчанию NULL — атрибуты 'class' не
применено.


*** ** * ** ***

Почти все форматы из семейства форматов обработки текстов содержат поля \\u2014 специфические сущности документа, позволяющие получать вводимые пользователями данные. Существует широкий набор полей: текстовые поля, флажки, комбобоксы, выпадающие списки, кнопки, элементы выбора даты/времени и т.д. Все они преобразуются в наиболее подходящие HTML‑структуры и элементы с сохранением введённых пользователем данных, если они присутствуют во входном документе. В некоторых сценариях требуется лишь собрать введённые данные на клиентской стороне вместо редактирования всего содержимого документа. Для такого случая необходимо каким‑то образом идентифицировать элементы ввода, чтобы получить их вместе с данными на клиенте. Это свойство позволяет указать имя класса, которое будет применено к каждому элементу ввода в разметке HTML, чтобы клиентский код мог обходить структуру HTML‑документа и собирать данные.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Позволяет указать имя класса, которое будет помещено в атрибут 'class'
в каждом HTML‑элементе, представляющем какое‑то поле во входных
Документ WordProcessing. По умолчанию NULL — атрибуты 'class' не
применено.


*** ** * ** ***

Почти все форматы из семейства форматов обработки текстов содержат поля \\u2014 специфические сущности документа, позволяющие получать вводимые пользователями данные. Существует широкий набор полей: текстовые поля, флажки, комбобоксы, выпадающие списки, кнопки, элементы выбора даты/времени и т.д. Все они преобразуются в наиболее подходящие HTML‑структуры и элементы с сохранением введённых пользователем данных, если они присутствуют во входном документе. В некоторых сценариях требуется лишь собрать введённые данные на клиентской стороне вместо редактирования всего содержимого документа. Для такого случая необходимо каким‑то образом идентифицировать элементы ввода, чтобы получить их вместе с данными на клиенте. Это свойство позволяет указать имя класса, которое будет применено к каждому элементу ввода в разметке HTML, чтобы клиентский код мог обходить структуру HTML‑документа и собирать данные.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


Управляет тем, где хранить данные стилей и форматирования входного документа WordProcessing: во внешней таблице стилей (
false
) или как встроенные стили в разметке HTML (
true
). По умолчанию используются внешние стили (
false
).


**Returns:**
boolean
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


Управляет тем, где хранить данные стилей и форматирования входного документа WordProcessing: во внешней таблице стилей (
false
) или как встроенные стили в разметке HTML (
true
). По умолчанию используются внешние стили (
false
).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

