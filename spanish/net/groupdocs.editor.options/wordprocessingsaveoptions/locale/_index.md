---
title: "Locale"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite establecer una sobrescritura del idioma de la configuración regional predeterminada para el documento WordProcessing que se aplicará durante su creación. Cuando no se especifica, el valor predeterminado de MS Word u otro programa detectará o elegirá la configuración regional del documento según sus propias configuraciones u otros factores."
type: docs
weight: 40
url: /es/net/groupdocs.editor.options/wordprocessingsaveoptions/locale/
---
## WordProcessingSaveOptions.Locale property

Permite establecer anular la configuración regional predeterminada (idioma) para el documento WordProcessing, que se aplicará durante su creación. Cuando no se especifica (valor predeterminado), MS Word (u otro programa) detectará (o elegirá) la configuración regional del documento según sus propias configuraciones u otros factores.

```csharp
public CultureInfo Locale { get; set; }
```

### Observaciones

Esta opción aplica forzadamente la configuración regional especificada a todo el texto del documento. No la use si el documento contiene diferentes partes de texto escritas en distintos idiomas.

### Ver también

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
