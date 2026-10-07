---
title: "WordProcessingProtectionType"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет все доступные типы защиты документа WordProcessing"
type: docs
weight: 47
url: /ru/java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

Представляет все доступные типы защиты документа WordProcessing

## Поля

| Поле | Описание |
| --- | --- |
|  | [NoProtection](#NoProtection) | Документ не защищён. |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | Пользователь может только добавлять метки правок в документ |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | Пользователь может только изменять комментарии в документе |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | Пользователь может только вводить данные в поля формы в документе |
|
|  | [ReadOnly](#ReadOnly) | Изменения в документе не допускаются |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


Документ не защищён. Значение по умолчанию.


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


Пользователь может только добавлять метки правок в документ


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


Пользователь может только изменять комментарии в документе


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


Пользователь может только вводить данные в поля формы в документе


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Изменения в документе не допускаются


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
