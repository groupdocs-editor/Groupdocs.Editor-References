---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para editar documentos de todos los formatos de hoja de cálculo compatibles con Excel."
type: docs
weight: 35
url: /es/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Permite especificar opciones personalizadas para editar documentos de todos los compatibles
Formatos de hoja de cálculo (compatibles con Excel)

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Permite especificar el índice basado en cero de la hoja de cálculo (pestaña) de la entrada |
Documento de hoja de cálculo, que debe convertirse a HTML (ver
observaciones).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Permite especificar el índice basado en cero de la hoja de cálculo (pestaña) de la entrada |
Documento de hoja de cálculo, que debe convertirse a HTML (ver
observaciones).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Permite excluir hojas de cálculo ocultas en el documento de hoja de cálculo de entrada, de modo que |
serán totalmente ignoradas.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Permite excluir hojas de cálculo ocultas en el documento de hoja de cálculo de entrada, de modo que |
serán totalmente ignoradas.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | Cuando está habilitado, las celdas horizontales adyacentes vacías del documento de hoja de cálculo de entrada serán |
representadas en el documento HTML editable como fusionadas en una sola celda con el correspondiente
atributo colspan.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | Cuando está habilitado, la tabla HTML en el documento HTML generado contiene una fila oculta inferior vacía con |
altura cero y celdas vacías, donde solo se especifica el ancho.
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Permite especificar el índice basado en cero de la hoja de cálculo (pestaña) de la entrada
Documento de hoja de cálculo, que debe convertirse a HTML (ver
observaciones).


*** ** * ** ***

La mayoría de los documentos de hoja de cálculo admiten el concepto de pestañas, es decir, pueden tener múltiples pestañas. Por otro lado, el formato HTML no soporta esa estructura. Debido a esto, GroupDocs.Editor solo puede convertir a HTML una pestaña específica del documento de entrada, y esta opción permite especificarla. El índice de pestaña es basado en cero, los valores negativos están prohibidos. Si el índice especificado supera el número total de pestañas, se lanzará una excepción. Si el documento de hoja de cálculo de entrada contiene solo una pestaña, esta opción se ignorará. El valor predeterminado es 0 (primera pestaña).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Permite especificar el índice basado en cero de la hoja de cálculo (pestaña) de la entrada
Documento de hoja de cálculo, que debe convertirse a HTML (ver
observaciones).


*** ** * ** ***

La mayoría de los documentos de hoja de cálculo admiten el concepto de pestañas, es decir, pueden tener múltiples pestañas. Por otro lado, el formato HTML no soporta esa estructura. Debido a esto, GroupDocs.Editor solo puede convertir a HTML una pestaña específica del documento de entrada, y esta opción permite especificarla. El índice de pestaña es basado en cero, los valores negativos están prohibidos. Si el índice especificado supera el número total de pestañas, se lanzará una excepción. Si el documento de hoja de cálculo de entrada contiene solo una pestaña, esta opción se ignorará. El valor predeterminado es 0 (primera pestaña).

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Permite excluir hojas de cálculo ocultas en el documento de hoja de cálculo de entrada, de modo que
serán totalmente ignoradas. El valor predeterminado es false - las hojas de cálculo ocultas son
disponibles y procesadas normalmente.


*** ** * ** ***

Varios formatos binarios de hoja de cálculo (como XLSX) admiten el concepto de hojas de cálculo ocultas (pestañas). Un documento de dicho formato, si tiene más de una hoja, puede contener hojas ocultas adicionales. Por defecto, esas hojas ocultas están disponibles para el procesamiento, pero con esta opción es posible ignorarlas, como si esas hojas ocultas no existieran. Cuando esta opción está habilitada, no se puede seleccionar una hoja oculta con la propiedad ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Permite excluir hojas de cálculo ocultas en el documento de hoja de cálculo de entrada, de modo que
serán totalmente ignoradas. El valor predeterminado es false - las hojas de cálculo ocultas son
disponibles y procesadas normalmente.


*** ** * ** ***

Varios formatos binarios de hoja de cálculo (como XLSX) admiten el concepto de hojas de cálculo ocultas (pestañas). Un documento de dicho formato, si tiene más de una hoja, puede contener hojas ocultas adicionales. Por defecto, esas hojas ocultas están disponibles para el procesamiento, pero con esta opción es posible ignorarlas, como si esas hojas ocultas no existieran. Cuando esta opción está habilitada, no se puede seleccionar una hoja oculta con la propiedad ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


Cuando está habilitado, las celdas horizontales adyacentes vacías del documento de hoja de cálculo de entrada serán
representadas en el documento HTML editable como fusionadas en una sola celda con el correspondiente
atributo colspan. Por defecto está deshabilitado (false).


Por defecto, GroupDocs.Editor convierte una tabla del documento de hoja de cálculo de entrada al
documento HTML preservando cada celda. Sin embargo, los documentos de hoja de cálculo pueden ser escasos \\u2014 ellos
pueden contener una gran cantidad de "áreas vacías", donde muchas celdas están vacías. Esta opción, cuando
está habilitada, fusiona esas celdas vacías en una sola con el atributo colspan en el elemento TD,
y así puede reducir significativamente el tamaño del marcado HTML generado.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


Cuando está habilitado, la tabla HTML en el documento HTML generado contiene una fila oculta inferior vacía con
altura cero y celdas vacías, donde solo se especifica el ancho. Esta fila con celdas vacías contiene
valores de ancho exactos para cada columna y mejora la conversión inversa de HTML a Spreadsheet. Por
el valor predeterminado está habilitado (true).


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

