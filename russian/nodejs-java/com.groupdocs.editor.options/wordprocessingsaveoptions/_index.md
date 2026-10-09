---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Позволяет указать пользовательские параметры для создания и сохранения документов, совместимых с WordProcessing, после их редактирования"
type: docs
weight: 48
url: /ru/nodejs-java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Позволяет указать пользовательские параметры для генерации и сохранения
Документы, совместимые с WordProcessing, после их редактирования


*** ** * ** ***

WordProcessingSaveOptions применяется в ситуациях, когда существует экземпляр класса EditableDocument, содержащий отредактированное содержимое документа, и необходимо сохранить это содержимое в новый документ формата WordProcessing.

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Этот конструктор без параметров создает новый экземпляр WordProcessingSaveOptions с форматом вывода DOCX (может быть изменён затем через |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) свойство)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Создаёт новый экземпляр WordProcessingSaveOptions с указанным |
обязательным форматом вывода WordProcessing, в то время как все остальные параметры
по умолчанию
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Позволяет включать или отключать разбиение на страницы, которое будет использоваться при сохранении |
документе.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Позволяет включать или отключать разбиение на страницы, которое будет использоваться при сохранении |
документе.
|
|  | [getPassword()](#getPassword--) | Позволяет указать, изменить, получить или удалить пароль, который будет |
использоваться для кодирования сгенерированного документа WordProcessing.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Позволяет указать, изменить, получить или удалить пароль, который будет |
использоваться для кодирования сгенерированного документа WordProcessing.
|
|  | [getOutputFormat()](#getOutputFormat--) | Позволяет указать формат WordProcessing, который будет использоваться для сохранения |
документа
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Позволяет указать формат WordProcessing, который будет использоваться для сохранения |
документа
|
|  | [getLocale()](#getLocale--) | Позволяет задать переопределение локали по умолчанию (языка) для WordProcessing |
документа, которое будет применено во время его создания.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | Позволяет задать переопределение локали по умолчанию (языка) для WordProcessing |
документа, которое будет применено во время его создания.
|
|  | [getLocaleBi()](#getLocaleBi--) | Позволяет задать переопределение локали (языка) для документа WordProcessing |
для RTL (right-to-left) текста, которое будет применено во время его
создания.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | Позволяет задать переопределение локали (языка) для документа WordProcessing |
для RTL (right-to-left) текста, которое будет применено во время его
создания.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | Позволяет переопределить локаль (язык) для документа WordProcessing |
для восточноазиатского текста, которое будет применено во время его создания.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | Позволяет переопределить локаль (язык) для документа WordProcessing |
для восточноазиатского текста, которое будет применено во время его создания.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Включает механизмы оптимизации памяти во время генерации документа из |
HTML, что ухудшает производительность в качестве цены за снижение использования памяти.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Включает механизмы оптимизации памяти во время генерации документа из |
HTML, что ухудшает производительность в качестве цены за снижение использования памяти.
|
|  | [getProtection()](#getProtection--) | Позволяет управлять и применять параметры защиты документа для |
документа WordProcessing любого формата, который поддерживает
защиту.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Позволяет управлять и применять параметры защиты документа для |
документа WordProcessing любого формата, который поддерживает
защиту.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Отвечает за встраивание ресурсов шрифтов в выходной документ WordProcessing |
документе.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Отвечает за встраивание ресурсов шрифтов в выходной документ WordProcessing |
документе.
|
|  | [deepClone()](#deepClone--) | Создает и возвращает полную копию этого экземпляра |
Класс WordProcessingSaveOptions
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Этот конструктор без параметров создает новый экземпляр WordProcessingSaveOptions с форматом вывода DOCX (может быть изменён затем через
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) свойство)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Создаёт новый экземпляр WordProcessingSaveOptions с указанным
обязательным форматом вывода WordProcessing, в то время как все остальные параметры
по умолчанию


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | Обязательный формат вывода, в котором документ WordProcessing должен быть сохранён |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Позволяет включать или отключать разбиение на страницы, которое будет использоваться при сохранении
документ. Если оригинальный документ был открыт и отредактирован в режиме пагинации
режиме, эта опция также должна быть включена. По умолчанию отключена.


**Returns:**
boolean —
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Позволяет включать или отключать разбиение на страницы, которое будет использоваться при сохранении
документ. Если оригинальный документ был открыт и отредактирован в режиме пагинации
режиме, эта опция также должна быть включена. По умолчанию отключена.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Позволяет указать, изменить, получить или удалить пароль, который будет
используется для кодирования сгенерированного документа WordProcessing. Укажите NULL или
пустую строку для удаления (очистки) пароля.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Позволяет указать, изменить, получить или удалить пароль, который будет
используется для кодирования сгенерированного документа WordProcessing. Укажите NULL или
пустую строку для удаления (очистки) пароля.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Позволяет указать формат WordProcessing, который будет использоваться для сохранения
документа


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Позволяет указать формат WordProcessing, который будет использоваться для сохранения
документа


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


Позволяет задать переопределение локали по умолчанию (языка) для WordProcessing
документ, который будет применён во время его создания. Когда не
указано (значение по умолчанию), MS Word (или другая программа) обнаружит (или
выберет) локаль документа в соответствии со своими настройками или другими
факторами.


*** ** * ** ***

Эта опция принудительно применяет указанную локаль ко всему тексту в документе. Не используйте её, если документ содержит разные части текста, написанные на разных языках.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


Позволяет задать переопределение локали по умолчанию (языка) для WordProcessing
документ, который будет применён во время его создания. Когда не
указано (значение по умолчанию), MS Word (или другая программа) обнаружит (или
выберет) локаль документа в соответствии со своими настройками или другими
факторами.

*** ** * ** ***


Эта опция принудительно применяет указанную локаль ко всему тексту в
документ. Не используйте её, если документ содержит разные части
текста, написанные на разных языках.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


Позволяет задать переопределение локали (языка) для документа WordProcessing
для RTL (right-to-left) текста, которое будет применено во время его
создания. Когда не указано (значение по умолчанию), MS Word (или другая
программа) обнаружит (или выберет) RTL‑локаль документа в соответствии со своими
настройками или другими факторами.

*** ** * ** ***


Эта опция принудительно применяет указанную локаль ко всему RTL‑тексту
в документе. Не используйте её, если документ содержит разные части
текста, написанные на разных языках.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


Позволяет задать переопределение локали (языка) для документа WordProcessing
для RTL (right-to-left) текста, которое будет применено во время его
создания. Когда не указано (значение по умолчанию), MS Word (или другая
программа) обнаружит (или выберет) RTL‑локаль документа в соответствии со своими
настройками или другими факторами.

*** ** * ** ***


Эта опция принудительно применяет указанную локаль ко всему RTL‑тексту
в документе. Не используйте её, если документ содержит разные части
текста, написанные на разных языках.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


Позволяет переопределить локаль (язык) для документа WordProcessing
для восточно‑азиатского текста, который будет применён во время его создания. Когда
не указано (значение по умолчанию), MS Word (или другая программа) обнаружит
(или выберет) восточно‑азиатскую локаль документа в соответствии со своими настройками
или другие факторы.

*** ** * ** ***


Эта опция принудительно применяет указанную локаль ко всему
Восточно-азиатский текст в документе. Не используйте её, если документ содержит
разные части текста, написанные на разных
языках.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


Позволяет переопределить локаль (язык) для документа WordProcessing
для восточно‑азиатского текста, который будет применён во время его создания. Когда
не указано (значение по умолчанию), MS Word (или другая программа) обнаружит
(или выберет) восточно‑азиатскую локаль документа в соответствии со своими настройками
или другие факторы.

*** ** * ** ***


Эта опция принудительно применяет указанную локаль ко всему
Восточно-азиатский текст в документе. Не используйте её, если документ содержит
разные части текста, написанные на разных
языках.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Включает механизмы оптимизации памяти во время генерации документа из
HTML, что ухудшает производительность в качестве цены за снижение использования памяти.
Установка этой опции в значение true может значительно снизить потребление памяти
при генерации больших документов за счёт более медленного сохранения.
По умолчанию false (оптимизация памяти отключена ради лучшей
производительности).


**Returns:**
boolean —
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Включает механизмы оптимизации памяти во время генерации документа из
HTML, что ухудшает производительность в качестве цены за снижение использования памяти.
Установка этой опции в значение true может значительно снизить потребление памяти
при генерации больших документов за счёт более медленного сохранения.
По умолчанию false (оптимизация памяти отключена ради лучшей
производительности).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Позволяет управлять и применять параметры защиты документа для
документа WordProcessing любого формата, который поддерживает
защита. По умолчанию NULL — защита документа не будет использоваться.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Позволяет управлять и применять параметры защиты документа для
документа WordProcessing любого формата, который поддерживает
защита. По умолчанию NULL — защита документа не будет использоваться.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Отвечает за встраивание ресурсов шрифтов в выходной документ WordProcessing
документ. По умолчанию не встраивает шрифты (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Отвечает за встраивание ресурсов шрифтов в выходной документ WordProcessing
документ. По умолчанию не встраивает шрифты (NotEmbed).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


Создает и возвращает полную копию этого экземпляра
Класс WordProcessingSaveOptions


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

