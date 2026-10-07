---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Las opciones de incrustación de fuentes controlan qué recursos de fuentes deben incrustarse en el documento WordProcessing de salida"
type: docs
weight: 17
url: /es/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Las opciones de incrustación de fuentes controlan qué recursos de fuentes deben incrustarse en
el documento WordProcessing de salida


*** ** * ** ***

Las opciones de incrustación de fuentes se aplican durante el guardado del documento (desde EditableDocument intermedio al formato WordProcessing de salida), este enum se incluye como una propiedad en WordProcessingSaveOptions, desde donde debe usarse

<br />


## Campos

| Campo | Descripción |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | No incruste ningún recurso de fuente ni de EditableDocument ni del |
sistema.
|
|  | [EmbedAll](#EmbedAll) | Analice el contenido del documento del EditableDocument de entrada, encuentre todas las fuentes utilizadas |
y incrústelos en el documento WordProcessing de salida.
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | Exacto a [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), pero excluye esas fuentes, |
que son tratados por el OS como fuentes del sistema
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


No incruste ningún recurso de fuente ni de EditableDocument ni del
sistema. Valor predeterminado.


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


Analice el contenido del documento del EditableDocument de entrada, encuentre todas las fuentes utilizadas
y los incrusta en el documento WordProcessing de salida. En primer lugar
GroupDocs.Editor toma fuentes de los recursos de fuentes dentro de EditableDocument.
Si son insuficientes o faltan, entonces GroupDocs.Editor toma fuentes
del OS.


*** ** * ** ***

En primer lugar GroupDocs.Editor analiza el contenido de EditableDocument y forma una lista de todas las fuentes utilizadas. Luego estas fuentes se buscan en los recursos de fuentes de EditableDocument. Si EditableDocument contiene algunos recursos de fuentes que no están involucrados en el contenido del documento, dichos recursos se ignoran. Si hay algunas fuentes usadas en el contenido del documento que no tienen recursos de fuentes correspondientes en EditableDocument, entonces GroupDocs.Editor intenta encontrarlas en el OS. Esta opción se asemeja a la opción "Embed fonts in the file" con todas las subopciones desactivadas en Microsoft Word 2007 y versiones posteriores.

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


Exacto a [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll), pero excluye esas fuentes,
que son tratados por el OS como fuentes del sistema


*** ** * ** ***

MS Windows tiene el concepto de fuentes del sistema, que son las fuentes más básicas y usadas por el propio Windows. Al usar esta opción, GroupDocs.Editor actúa como en el caso de [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll) pero finalmente revisa el conjunto de fuentes obtenidas y excluye aquellas que son tratadas por el OS como fuentes del sistema. Esta opción se asemeja a las opciones "Embed fonts in the file" + "Do not embed common system fonts" en Microsoft Word 2007 y versiones posteriores.

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
