---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Позволяет указать пользовательские параметры для создания и сохранения документов PDF Portable Document Format"
type: docs
weight: 31
url: /ru/nodejs-java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

Позволяет указать пользовательские параметры для создания и сохранения PDF (Portable
Document Format) документы

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPassword()](#getPassword--) | Пароль, который будет применён к сгенерированному PDF‑документу как пользовательский пароль, требуемый для открытия. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Пароль, который будет применён к сгенерированному PDF‑документу как пользовательский пароль, требуемый для открытия. |
|
|  | [getCompliance()](#getCompliance--) | Указывает уровень соответствия стандартам PDF для выходных документов. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | Указывает уровень соответствия стандартам PDF для выходных документов. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Отвечает за встраивание ресурсов шрифтов в результирующий PDF‑документ, которые используются в исходном документе. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Отвечает за встраивание ресурсов шрифтов в результирующий PDF‑документ, которые используются в исходном документе. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Включает механизмы оптимизации памяти при генерации документа из HTML, что ухудшает производительность в качестве цены за снижение использования памяти. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Включает механизмы оптимизации памяти при генерации документа из HTML, что ухудшает производительность в качестве цены за снижение использования памяти. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Пароль, который будет применён к сгенерированному PDF‑документу как пользовательский пароль, требуемый для открытия.
Если NULL или пусто, пароль к документу не будет применён. В противном случае документ будет зашифрован с помощью RC4 (длина ключа 128 бит).
По умолчанию равно NULL \\u2014 пароль не применяется.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Пароль, который будет применён к сгенерированному PDF‑документу как пользовательский пароль, требуемый для открытия.
Если NULL или пусто, пароль к документу не будет применён. В противном случае документ будет зашифрован с помощью RC4 (длина ключа 128 бит).
По умолчанию равно NULL \\u2014 пароль не применяется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Указывает уровень соответствия стандартам PDF для выходных документов. По умолчанию — PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Указывает уровень соответствия стандартам PDF для выходных документов. По умолчанию — PdfCompliance.Pdf17.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Отвечает за встраивание ресурсов шрифтов в результирующий PDF‑документ, которые используются в оригинальном документе. По умолчанию не встраивает никаких шрифтов (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Отвечает за встраивание ресурсов шрифтов в результирующий PDF‑документ, которые используются в оригинальном документе. По умолчанию не встраивает никаких шрифтов (NotEmbed).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Включает механизмы оптимизации памяти при генерации документа из HTML, что ухудшает производительность в качестве цены за снижение использования памяти.
Установка этой опции в true может значительно снизить потребление памяти при генерации больших документов за счёт более медленного времени сохранения.
По умолчанию false (оптимизация памяти отключена ради лучшей производительности).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Включает механизмы оптимизации памяти при генерации документа из HTML, что ухудшает производительность в качестве цены за снижение использования памяти.
Установка этой опции в true может значительно снизить потребление памяти при генерации больших документов за счёт более медленного времени сохранения.
По умолчанию false (оптимизация памяти отключена ради лучшей производительности).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

