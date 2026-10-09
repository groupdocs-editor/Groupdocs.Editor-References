---
title: "TextDirection"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa 3 variantes posibles de cómo tratar la dirección del texto en documentos de texto plano"
type: docs
weight: 38
url: /es/nodejs-java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Representa 3 variantes posibles de cómo tratar la dirección del texto en el texto plano
documentos

## Campos

| Campo | Descripción |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | Dirección de izquierda a derecha, texto habitual, valor predeterminado. |
|
|  | [RightToLeft](#RightToLeft) | Dirección de derecha a izquierda |
|
|  | [Auto](#Auto) | Detectar dirección automáticamente. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


Dirección de izquierda a derecha, texto habitual, valor predeterminado.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


Dirección de derecha a izquierda


### Auto {#Auto}
```
public static final int Auto
```


Detectar dirección automáticamente. Cuando esta opción está seleccionada y el texto contiene
caracteres pertenecientes a scripts RTL, la dirección del documento se establecerá
automáticamente a RTL.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
