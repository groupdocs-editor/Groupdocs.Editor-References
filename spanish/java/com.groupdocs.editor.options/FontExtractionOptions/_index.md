---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Las opciones de extracción de fuentes controlan qué fuentes deben extraerse y de dónde"
type: docs
weight: 18
url: /es/java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Las opciones de extracción de fuentes controlan qué fuentes deben extraerse y de
dónde

## Campos

| Campo | Descripción |
| --- | --- |
|  | [NotExtract](#NotExtract) | No extrae ningún recurso de fuente ni del documento ni del |
sistema.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | Extrae todos los recursos de fuentes que están incrustados en el Word de entrada |
documento, sin importar si son: personalizadas o del sistema.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Extrae solo los recursos de fuentes incrustados que son personalizados (no |
sistema)
|
|  | [ExtractAll](#ExtractAll) | Intenta extraer todas las fuentes que se usan en el WordProcessing de entrada |
documento, incluyendo fuentes del sistema.
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


No extrae ningún recurso de fuente ni del documento ni del
sistema. Valor predeterminado.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


Extrae todos los recursos de fuentes que están incrustados en el Word de entrada
documento, sin importar si son: personalizadas o del sistema.


*** ** * ** ***

Converter encuentra y extrae todos los recursos de fuentes al 100%, que están incrustados en el documento WordProcessing de entrada, pero no determina si son del sistema o personalizadas; no toca el Registro de Windows ni las carpetas del sistema en absoluto.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


Extrae solo los recursos de fuentes incrustados que son personalizados (no
sistema)


*** ** * ** ***

Converter encuentra y extrae todos los recursos de fuentes incrustados, y luego intenta determinar cuáles de estas fuentes son del sistema y cuáles no. Para lograrlo, el convertidor intenta obtener una lista de todas las fuentes del sistema usando el Registro de Windows y las carpetas del sistema, y luego compara esta lista con el conjunto de fuentes incrustadas. Como resultado, solo se devolverá el subconjunto de esas fuentes incrustadas que no se encontraron en el sistema.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


Intenta extraer todas las fuentes que se usan en el WordProcessing de entrada
documento, incluyendo fuentes del sistema.


*** ** * ** ***

Converter está analizando un documento WordProcessing de entrada y encuentra todas las fuentes que se utilizan allí. Si todas esas fuentes están incrustadas en el documento de entrada, el convertidor las extrae y las devuelve. De lo contrario, si la colección de fuentes incrustadas no cubre todas las fuentes usadas en el documento, o está vacía, el convertidor intenta extraer esos recursos de fuentes del sistema, usando el Registro de Windows y las carpetas del sistema.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
