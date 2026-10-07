---
title: "PageRange"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Инкапсулирует один диапазон страниц, который может иметь открытые или закрытые границы."
type: docs
weight: 27
url: /ru/java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Инкапсулирует один диапазон страниц, который может иметь открытые или закрытые границы. По умолчанию он «полностью открыт» — включает все существующие страницы. Нумерация страниц начинается с 1, а не с 0.

<br />

*** ** * ** ***

Неизменяемая структура, инкапсулирующая диапазон страниц, не привязанный к какому‑либо конкретному документу и способный представлять диапазон страниц для любого документа.

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [AllPages](#AllPages) | Представляет все существующие страницы документа. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | Включающий начальный номер страницы, с которой начинается этот диапазон страниц. |
|
|  | [getEndNumber()](#getEndNumber--) | Исключающий конечный номер страницы, до которой продолжается этот диапазон страниц и на которой он останавливается исключительно. |
|
|  | [getCount()](#getCount--) | Номера страниц в диапазоне. |
|
|  | [isDefault()](#isDefault--) | Указывает, представляет ли данный экземпляр диапазон страниц по умолчанию «полностью открытый», т.е. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Определяет, равен ли данный экземпляр PageRange указанному |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | Создаёт диапазон страниц, начинающийся с первой страницы и имеющий указанное количество страниц |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Создаёт диапазон страниц, начинающийся с указанного номера страницы и продолжающийся до конца документа |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Создаёт диапазон страниц, начинающийся с указанного номера страницы и имеющий указанное количество страниц, либо неограниченное количество страниц (до конца) |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Создаёт диапазон страниц, начинающийся с указанного номера страницы (включительно) и продолжающийся до указанного номера страницы (исключительно) |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


Представляет все существующие страницы документа. Значение по умолчанию.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


Включающий начальный номер страницы, с которой начинается этот диапазон страниц. Если 1 — диапазон начинается с первой страницы документа


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Исключающий конечный номер страницы, до которой продолжается диапазон страниц и на которой он останавливается исключительно. Если 0 — диапазон распространяется до конца документа


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Номера страниц в диапазоне. Если 0 — диапазон распространяется до конца документа независимо от количества страниц


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Указывает, представляет ли данный экземпляр диапазон страниц по умолчанию «полностью открытый», т.е. включает все страницы документа


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


Определяет, равен ли данный экземпляр PageRange указанному


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Другой экземпляр PageRange для проверки на равенство |
|

**Returns:**
логический тип — true, если равны; false, если не равны

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


Создаёт диапазон страниц, начинающийся с первой страницы и имеющий указанное количество страниц


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageCount | int | Количество страниц, должно быть строго больше нуля |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


Создаёт диапазон страниц, начинающийся с указанного номера страницы и продолжающийся до конца документа


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | startPageNumber | int | Номер страницы, с которой начинается диапазон страниц, включительно. Номера страниц начинаются с 1, поэтому должны быть строго больше нуля |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Создаёт диапазон страниц, начинающийся с указанного номера страницы и имеющий указанное количество страниц, либо неограниченное количество страниц (до конца)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | startPageNumber | int | Номер страницы, с которой начинается диапазон страниц, включительно. Номера страниц начинаются с 1, поэтому должны быть строго больше нуля |
|
|  | pageCount | int | Количество страниц, должно быть строго больше нуля. Если ноль — это означает все страницы до конца документа |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Создаёт диапазон страниц, начинающийся с указанного номера страницы (включительно) и продолжающийся до указанного номера страницы (исключительно)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | startPageNumber | int | Номер страницы, с которой начинается диапазон страниц, включительно. Номера страниц начинаются с 1, поэтому должны быть строго больше нуля |
|
|  | endPageNumber | int | Номер страницы, до которой продолжается диапазон страниц, исключительно. Номера страниц начинаются с 1, поэтому должны быть строго больше нуля и также должны быть строго больше, чем startPageNumber |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
