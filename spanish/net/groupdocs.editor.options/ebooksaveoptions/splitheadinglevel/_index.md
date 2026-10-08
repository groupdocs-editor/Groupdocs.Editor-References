---
title: "SplitHeadingLevel"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Especifica el nivel máximo de encabezados en el que dividir el archivo eBook. El valor predeterminado es 2. Configurarlo en 0 desactivará la división, de modo que todo el contenido del eBook se incorporará en un solo paquete dentro del archivo resultante."
type: docs
weight: 40
url: /es/net/groupdocs.editor.options/ebooksaveoptions/splitheadinglevel/
---
## EbookSaveOptions.SplitHeadingLevel property

Especifica el nivel máximo de encabezados en el que dividir el archivo e-Book. El valor predeterminado es `2`. Configurarlo en `0` desactivará la división, de modo que todo el contenido del e-Book se incorporará en un solo paquete dentro del archivo resultante.

```csharp
public int SplitHeadingLevel { get; set; }
```

### Observaciones

Cuando esta propiedad se establece en un valor de 1 a 9, el documento se dividirá en los párrafos formateados con los estilos **Heading 1**, **Heading 2**, **Heading 3**, etc., hasta el nivel de encabezado especificado.

Por defecto, solo los párrafos **Heading 1** y **Heading 2** hacen que el documento se divida. Configurar esta propiedad a cero (o a un valor inferior a cero) hará que el documento no se divida en los párrafos de encabezado en absoluto.

### Ver también

* class [EbookSaveOptions](../../ebooksaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
