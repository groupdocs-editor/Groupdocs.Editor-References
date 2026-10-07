---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Инкапсулирует параметры защиты листа, позволяющие защитить лист в результирующем документе Spreadsheet от изменения указанного типа с указанным паролем."
type: docs
weight: 49
url: /ru/java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

Инкапсулирует параметры защиты листа, позволяющие защитить лист
в результирующем документе Spreadsheet от изменения указанного типа с
указанным паролем.


*** ** * ** ***

Большинство форматов Spreadsheet, таких как XLSX, позволяют защищать лист от редактирования с помощью пароля. Этот класс позволяет включить такую защиту и задать её параметры.

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | Создаёт новый экземпляр с параметрами по умолчанию. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | Создаёт новый экземпляр с указанным типом защиты листа и |
пароль
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Позволяет указать тип защиты листа. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Позволяет указать тип защиты листа. |
|
|  | [getPassword()](#getPassword--) | Пароль, используемый для защиты листа. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Пароль, используемый для защиты листа. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


Создаёт новый экземпляр с параметрами по умолчанию. Если не изменён и передан
в SpreadsheetSaveOptions, защита листа применяться не будет


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


Создаёт новый экземпляр с указанным типом защиты листа и
пароль


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | protectionType | int | Тип защиты листа |
|
|  | пароль | java.lang.String | Пароль, который блокирует защиту |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Позволяет указать тип защиты листа. По умолчанию — 'None' -
защита не применяется.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Позволяет указать тип защиты листа. По умолчанию — 'None' -
защита не применяется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Пароль, используемый для защиты листа. Если NULL или пустая
строка, защита применяться не будет.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Пароль, используемый для защиты листа. Если NULL или пустая
строка, защита применяться не будет.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

