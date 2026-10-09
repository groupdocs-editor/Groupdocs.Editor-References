---
title: "PdfCompliance"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Especifica el nivel de cumplimiento de los estándares PDF"
type: docs
weight: 28
url: /es/nodejs-java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

Especifica el nivel de cumplimiento de los estándares PDF

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Pdf17](#Pdf17) | Estándar PDF 1.7 (ISO 32000-1) |
|
|  | [Pdf20](#Pdf20) | Estándar PDF 2.0 (ISO 32000-2) |
|
|  | [PdfA1a](#PdfA1a) | Estándar PDF/A-1a. |
|
|  | [PdfA1b](#PdfA1b) | PDF/A-1b (ISO 19005-1). |
|
|  | [PdfA2a](#PdfA2a) | Estándar PDF/A-2a (ISO 19005-2). |
|
|  | [PdfA2u](#PdfA2u) | Estándar PDF/A-2u (ISO 19005-2). |
|
|  | [PdfUa1](#PdfUa1) | Estándar PDF/UA-1 (ISO 14289-1). |
|
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


Estándar PDF 1.7 (ISO 32000-1)


### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


Estándar PDF 2.0 (ISO 32000-2)


### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


Estándar PDF/A-1a. Este nivel incluye todos los requisitos de PDF/A-1b y adicionalmente requiere que se incluya la estructura del documento
(también conocido como "etiquetado"), con el objetivo de garantizar que el contenido del documento pueda ser buscado y reutilizado.

<br />

*** ** * ** ***

Tenga en cuenta que exportar la estructura del documento incrementa significativamente el consumo de memoria, especialmente en documentos grandes.

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b (ISO 19005-1). PDF/A-1b tiene el objetivo de asegurar una reproducción fiable de la apariencia visual del documento.


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


Estándar PDF/A-2a (ISO 19005-2). Este nivel incluye todos los requisitos de PDF/A-2u y adicionalmente requiere que se incluya la estructura del documento (también conocido como "etiquetado"), con el objetivo de garantizar que el contenido del documento pueda ser buscado y reutilizado.

<br />

*** ** * ** ***

Tenga en cuenta que exportar la estructura del documento incrementa significativamente el consumo de memoria, especialmente en documentos grandes.

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


Estándar PDF/A-2u (ISO 19005-2). PDF/A-2u tiene el objetivo de preservar la apariencia visual estática del documento a lo largo del tiempo, independiente de las herramientas y sistemas utilizados para crear, almacenar o renderizar los archivos. Además, cualquier texto contenido en el documento puede extraerse de manera fiable como una serie de puntos de código Unicode.


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


Estándar PDF/UA-1 (ISO 14289-1). El propósito principal de PDF/UA es definir cómo representar documentos electrónicos en formato PDF de manera que el archivo sea accesible.


