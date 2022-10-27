---
title: FixedLayoutFormats
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Encapsula todos los formatos de diseño fijo también conocidos como página fija que incluyen PDF y XPS esto no incluye imágenes rasterizadas
type: docs
weight: 80
url: /es/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats structure

Encapsula todos los formatos de diseño fijo (también conocidos como "página fija"), que incluyen PDF y XPS (esto no incluye imágenes rasterizadas)

```csharp
public struct FixedLayoutFormats : IDocumentFormat, IEquatable<FixedLayoutFormats>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/fixedlayoutformats/extension) { get; } | Devuelve una extensión (sin carácter de punto inicial) de este formato de diseño fijo en minúsculas |
| [Mime](../../groupdocs.editor.formats/fixedlayoutformats/mime) { get; } | Devuelve un código MIME para este formato |
| [Name](../../groupdocs.editor.formats/fixedlayoutformats/name) { get; } | Devuelve un nombre completo formal de este formato de diseño fijo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Devuelve instancia de[`FixedLayoutFormats`](../fixedlayoutformats)estructura, asociada a la extensión de nombre de archivo especificada, o genera una excepción, si la extensión no se puede analizar correctamente |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals)(FixedLayoutFormats) | Determina si esta instancia es igual a la otra instancia de FixedLayoutFormats especificada |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_1)(IDocumentFormat) | Determina si esta instancia es igual a la otra instancia de IDocumentFormat especificada |
| override [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_2)(object) | Determina si esta instancia es igual al otro objeto especificado, que presumiblemente es de FixedLayoutFormats en caja |
| override [GetHashCode](../../groupdocs.editor.formats/fixedlayoutformats/gethashcode)() | Devuelve un código hash, que es inmutable para esta instancia |
| override [ToString](../../groupdocs.editor.formats/fixedlayoutformats/tostring)() | Devuelve el nombre de este formato en particular, igual que la propiedad 'Nombre' |
| [operator ==](../../groupdocs.editor.formats/fixedlayoutformats/op_equality) | Comprueba dos instancias de FixedLayoutFormats dadas en igualdad |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit#op_explicit) | Devuelve un valor de byte del campo subyacente de la instancia de FixedLayoutFormats especificada (2 operators) |
| [operator !=](../../groupdocs.editor.formats/fixedlayoutformats/op_inequality) | Comprueba dos instancias de FixedLayoutFormats dadas en desigualdad |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | El formato de documento portátil (PDF) es un tipo de documento creado por Adobe en la década de 1990. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de la aplicación, el hardware y el sistema operativo. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/pdf/) . |
| static readonly [Xps](../../groupdocs.editor.formats/fixedlayoutformats/xps) | El archivo XPS representa archivos de diseño de página que se basan en las especificaciones de papel XML creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato de archivo PDF, pero usa XML en el diseño, la apariencia y la información de impresión de un documento. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/page-description-language/xps/) . |
| static readonly [All](../../groupdocs.editor.formats/fixedlayoutformats/all) | Devuelve una clase interna que proporciona posibilidades enumerables sobre todos los formatos de diseño fijo existentes |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [AllEnumerable](fixedlayoutformats.allenumerable) | Implementa la interfaz genérica IEnumerable, que permite una posibilidad 'foreach' para el tipo FixedLayoutFormats |

### Observaciones

Varias aplicaciones de visualización o publicación de documentos permiten a los usuarios abrir (Adobe Acrobat, XPS Viewer) y, en ocasiones, editar (Adobe InDesign) documentos de formatos específicos. Estas aplicaciones suelen producir los llamados documentos de formato de "página fija". Dicho formato de documento describe con precisión dónde se coloca el contenido de un documento en cada página. Internamente, el formato PDF o XPS contiene una descripción de cada página, así como instrucciones de dibujo, que especifican el diseño del contenido de la página. Esto es similar a los formatos de imagen, que describen dónde se muestra el contenido, ya sea en forma de trama o de vector.

### Ver también

* interface [IDocumentFormat](../idocumentformat)
* espacio de nombres [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
