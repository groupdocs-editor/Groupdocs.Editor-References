---
title: "TextDirection"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет 3 возможных варианта обработки направления текста в простых текстовых документах"
type: docs
weight: 38
url: /ru/nodejs-java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Представляет 3 возможных варианта обработки направления текста в простом тексте
документы

## Поля

| Поле | Описание |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | Направление слева направо, обычный текст, значение по умолчанию. |
|
|  | [RightToLeft](#RightToLeft) | Направление справа налево |
|
|  | [Auto](#Auto) | Автоматическое определение направления. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


Направление слева направо, обычный текст, значение по умолчанию.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


Направление справа налево


### Auto {#Auto}
```
public static final int Auto
```


Автоматическое определение направления. Когда эта опция выбрана и текст содержит
символы, принадлежащие RTL‑скриптам, направление документа будет установлено
автоматически на RTL.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
