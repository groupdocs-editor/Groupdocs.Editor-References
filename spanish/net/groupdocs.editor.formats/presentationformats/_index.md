---
title: PresentationFormats
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Encapsula todos los formatos de presentación. Incluye los siguientes formatos Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. Obtenga más información sobre los formatos de presentaciónaquíhttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /es/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

Encapsula todos los formatos de presentación. Incluye los siguientes formatos: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). Obtenga más información sobre los formatos de presentación[aquí](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | Devuelve una extensión (sin carácter de punto inicial) de este formato de presentación en minúsculas |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | Devuelve un código MIME para este formato |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | Devuelve un nombre completo formal de esta presentación format |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Devuelve instancia de[`PresentationFormats`](../presentationformats) estructura, asociada a la extensión de nombre de archivo especificada, o genera una excepción, si la extensión no se puede analizar correctamente |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | Determina si esta instancia es igual a la otra instancia de IDocumentFormat especificada |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | Determina si esta instancia es igual al otro objeto especificado, que presumiblemente es de PresentationFormats en caja |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | Determina si esta instancia es igual a la otra instancia de PresentationFormats especificada |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | Devuelve un código hash, que es inmutable para esta instancia |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | Comprueba dos instancias de PresentationFormats dadas en igualdad |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | Comprueba dos instancias de PresentationFormats dadas en desigualdad |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | El archivo OpenDocument Presentation (ODP) representa el formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASISOpen. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | El archivo de plantilla de presentación OpenDocument (OTP) representa archivos de plantilla de presentación creados por aplicaciones en formato estándar OASIS OpenDocument. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | El archivo de plantilla de presentación (POT) de Microsoft PowerPoint 97-2003 representa los archivos de plantilla de Microsoft PowerPoint creados por las versiones de PowerPoint 97-2003. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Plantilla habilitada para macros (POTM) son archivos compatibles con macros. Los archivos POTM se crean con PowerPoint 2007 o superior y contienen configuraciones predeterminadas que se pueden usar para crear más archivos de presentación. Obtenga más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | El archivo Microsoft Office Open XML PresentationML Macro-Free Template (POTX) representa las presentaciones de plantilla de Microsoft PowerPoint creadas con Microsoft PowerPoint 2007 y superior. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Los archivos de presentación de diapositivas (PPS) de Microsoft PowerPoint 97-2003 se crean utilizando Microsoft PowerPoint para fines de presentación de diapositivas. La lectura y creación de archivos PPS es compatible con Microsoft PowerPoint 97-2003. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Los archivos Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM) se crean con Microsoft PowerPoint 2007 o superior. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | El archivo de presentación de diapositivas sin macros (PPSX) de Microsoft Office Open XML PresentationML se crea con Microsoft PowerPoint 2007 y superior para el propósito de presentación de diapositivas. Obtenga más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Presentación de PowerPoint (.ppt) representa un archivo de PowerPoint que consta de una colección de diapositivas para mostrarlas como presentación de diapositivas. Especifica el formato de archivo binario utilizado por Microsoft PowerPoint 97-2003. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Presentación de Microsoft PowerPoint 95 (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Archivos de Microsoft Office Open XML PresentationML Macro-Enabled Document (PPTM) creados con Microsoft PowerPoint 2007 o versiones superiores. Son similares a los archivos PPTX con la diferencia de que los laterales no pueden ejecutar macros aunque pueden contener macros. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML Presentation (.pptx) es un archivo de presentación creado con la popular aplicación Microsoft PowerPoint. A diferencia de la versión anterior del formato de archivo de presentación PPT, que era binario, el formato PPTX se basa en el formato de archivo de presentación XML abierto de Microsoft PowerPoint. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | Devuelve una clase interna, que proporciona posibilidades enumerables sobre todos los formatos de presentación existentes |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | Implementa la interfaz genérica IEnumerable, que permite la posibilidad de 'foreach' para PresentationFormats type |

### Ver también

* interface [IDocumentFormat](../idocumentformat)
* espacio de nombres [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
