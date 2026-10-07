---
title: "PageRange"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Encapsula un rango de páginas que puede tener límites abiertos o cerrados."
type: docs
weight: 27
url: /es/java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Encapsula un rango de páginas, que puede tener límites abiertos o cerrados. Por defecto es "totalmente abierto" - incluye todas las páginas existentes. La numeración de páginas comienza en 1, no en 0.

<br />

*** ** * ** ***

Estructura inmutable que encapsula un rango de páginas, que no está relacionado con ningún documento específico y puede representar un rango de páginas para cualquier documento.

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
|  | [AllPages](#AllPages) | Representa todas las páginas existentes de un documento. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | Número de página inicial inclusivo, desde el cual comienza este rango de páginas. |
|
|  | [getEndNumber()](#getEndNumber--) | Número de página final exclusivo, hasta el cual continúa este rango de páginas y en el que se detiene de forma exclusiva. |
|
|  | [getCount()](#getCount--) | Números de páginas dentro del rango. |
|
|  | [isDefault()](#isDefault--) | Indica si esta instancia representa un rango de páginas predeterminado "totalmente abierto", es decir. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Detecta si esta instancia de PageRange es igual a la especificada |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | Crea un rango de páginas que comienza desde la primera página y tiene una cantidad especificada de páginas |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Crea un rango de páginas que comienza desde el número de página especificado y continúa hasta el final del documento |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Crea un rango de páginas que comienza desde el número de página especificado y tiene una cantidad especificada de páginas, o un recuento ilimitado de páginas (hasta el final) |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Crea un rango de páginas que comienza desde el número de página especificado (inclusivamente) y continúa hasta el número de página especificado (exclusivamente) |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


Representa todas las páginas existentes de un documento. Valor predeterminado.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


Número de página inicial inclusivo, desde el cual comienza este rango de páginas. Si es 1, el rango de páginas comienza desde la primera página de un documento


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Número de página final exclusivo, hasta el cual continúa este rango de páginas y en el que se detiene de forma exclusiva. Si es 0, el rango de páginas se extiende hasta el final del documento


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Números de páginas dentro del rango. Si es 0, el rango de páginas se extiende hasta el final del documento sin importar cuántas páginas contiene


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indica si esta instancia representa un rango de páginas predeterminado "totalmente abierto", es decir, contiene todas las páginas de un documento


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


Detecta si esta instancia de PageRange es igual a la especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Otra instancia de PageRange para comprobar la igualdad |
|

**Returns:**
booleano - true si son iguales; false si son diferentes

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


Crea un rango de páginas que comienza desde la primera página y tiene una cantidad especificada de páginas


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageCount | int | Número de páginas, debe ser estrictamente mayor que cero |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


Crea un rango de páginas que comienza desde el número de página especificado y continúa hasta el final del documento


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | startPageNumber | int | Número de página, desde la cual comienza el rango de páginas, inclusive. Los números de página son basados en 1, por lo que deben ser estrictamente mayores que cero |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Crea un rango de páginas que comienza desde el número de página especificado y tiene una cantidad especificada de páginas, o un recuento ilimitado de páginas (hasta el final)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | startPageNumber | int | Número de página, desde la cual comienza el rango de páginas, inclusive. Los números de página son basados en 1, por lo que deben ser estrictamente mayores que cero |
|
|  | pageCount | int | Número de páginas, debe ser estrictamente mayor que cero. Si es cero, esto significa todas las páginas hasta el final de un documento |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Crea un rango de páginas que comienza desde el número de página especificado (inclusivamente) y continúa hasta el número de página especificado (exclusivamente)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | startPageNumber | int | Número de página, desde la cual comienza el rango de páginas, inclusive. Los números de página son basados en 1, por lo que deben ser estrictamente mayores que cero |
|
|  | endPageNumber | int | Número de página, hasta la cual continúa el rango de páginas, exclusivamente. Los números de página son basados en 1, por lo que deben ser estrictamente mayores que cero, y también deben ser estrictamente mayores que startPageNumber |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
