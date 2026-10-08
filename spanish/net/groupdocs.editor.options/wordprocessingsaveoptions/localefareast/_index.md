---
title: "LocaleFarEast"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite sobrescribir el idioma de la configuración regional para el documento WordProcessing para el texto EastAsian que se aplicará durante su creación. Cuando no se especifica, el valor predeterminado de MS Word u otro programa detectará o elegirá la configuración regional EastAsian del documento según sus propias configuraciones u otros factores."
type: docs
weight: 60
url: /es/net/groupdocs.editor.options/wordprocessingsaveoptions/localefareast/
---
## WordProcessingSaveOptions.LocaleFarEast property

Permite anular la configuración regional (idioma) para el documento WordProcessing para el texto de Asia Oriental, que se aplicará durante su creación. Cuando no se especifica (valor predeterminado), MS Word (u otro programa) detectará (o elegirá) la configuración regional de Asia Oriental del documento según sus propias configuraciones u otros factores.

```csharp
public CultureInfo LocaleFarEast { get; set; }
```

### Observaciones

Esta opción aplica forzadamente la configuración regional especificada a todo el texto East-Asian del documento. No la use si el documento contiene diferentes partes de texto escritas en distintos idiomas.

### Ver también

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
