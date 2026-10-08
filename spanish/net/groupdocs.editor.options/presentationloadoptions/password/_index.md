---
title: "Contraseña"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar, modificar y obtener la contraseña que se utilizará para abrir el documento Presentation si está codificado. Establézcalo en NULL o cadena vacía para eliminar la contraseña."
type: docs
weight: 20
url: /es/net/groupdocs.editor.options/presentationloadoptions/password/
---
## PresentationLoadOptions.Password property

Permite especificar, modificar y obtener la contraseña que se usará para abrir el documento Presentation, si está codificado. Establézcalo en NULL o cadena vacía para eliminar la contraseña.

```csharp
public string Password { get; set; }
```

### Observaciones

Por defecto, esta propiedad tiene valor NULL — la contraseña no está establecida. Si el documento Presentation de entrada está protegido con contraseña, la contraseña es obligatoria y se lanzará una excepción si no se especifica o es inválida. Si el documento Presentation de entrada NO está protegido con contraseña, pero se establece una contraseña, será ignorada.

### Ver también

* class [PresentationLoadOptions](../../presentationloadoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
