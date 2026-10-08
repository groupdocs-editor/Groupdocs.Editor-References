---
title: "HasInvalidFormFields"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Comprueba si el documento contiene campos de formulario inválidos."
type: docs
weight: 40
url: /es/net/groupdocs.editor/formfieldmanager/hasinvalidformfields/
---
## FormFieldManager.HasInvalidFormFields method

Comprueba si el documento contiene campos de formulario inválidos.

```csharp
public bool HasInvalidFormFields()
```

### Valor devuelto

`true` si el documento contiene uno o más campos de formulario no válidos; de lo contrario, `false`.

### Observaciones

El método `HasInvalidFormFields` escanea el contenido del documento para determinar si contiene campos de formulario con nombres inválidos. Un campo de formulario se considera inválido si duplica un identificador único con otros campos de formulario y no tiene un nombre de marcador único asociado. Estos nombres de marcador sirven como identificadores para cada campo de formulario. Este método es útil para comprobar rápidamente si el documento requiere una inspección adicional y una posible corrección de los nombres de los campos de formulario. ; ; ;

### Ver también

* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
