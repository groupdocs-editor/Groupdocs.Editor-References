---
title: "WordProcessingProtection"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Инкапсулирует параметры защиты документа WordProcessing, который генерируется из HTML"
type: docs
weight: 46
url: /ru/java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

Инкапсулирует параметры защиты документа WordProcessing,
который генерируется из HTML

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | Конструктор без параметров — все параметры имеют значения по умолчанию |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | Позволяет задать все параметры при создании экземпляра класса |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Позволяет задать тип защиты документа. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Позволяет задать тип защиты документа. |
|
|  | [getPassword()](#getPassword--) | Пароль для защиты документа. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Пароль для защиты документа. |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


Конструктор без параметров — все параметры имеют значения по умолчанию


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


Позволяет задать все параметры при создании экземпляра класса


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | protectionType | int | Установите тип защиты документа |
|
|  | пароль | java.lang.String | Установите пароль защиты |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Позволяет установить тип защиты документа. По умолчанию установлен параметр не
защищать документ вообще.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Позволяет установить тип защиты документа. По умолчанию установлен параметр не
защищать документ вообще.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Пароль для защиты документа. Если значение null или пустая строка —
защита не будет применена к документу.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Пароль для защиты документа. Если значение null или пустая строка —
защита не будет применена к документу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
