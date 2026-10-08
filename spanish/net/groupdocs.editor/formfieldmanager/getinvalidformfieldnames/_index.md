---
title: "GetInvalidFormFieldNames"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Obtiene una colección de nombres de campos de formulario inválidos del documento."
type: docs
weight: 30
url: /es/net/groupdocs.editor/formfieldmanager/getinvalidformfieldnames/
---
## FormFieldManager.GetInvalidFormFieldNames method

Obtiene una colección de nombres de campos de formulario inválidos del documento.

```csharp
public IEnumerable<InvalidFormField> GetInvalidFormFieldNames()
```

### Valor devuelto

Una colección enumerable de cadenas que representan los nombres de los campos de formulario inválidos encontrados en el documento.

### Observaciones

El método `GetInvalidFormFieldNames` escanea el contenido del documento para identificar campos de formulario con nombres inválidos. Devuelve una colección de cadenas que contiene los nombres de esos campos de formulario inválidos. Un campo de formulario se considera inválido si duplica un identificador único con otros campos de formulario y no tiene un nombre de marcador único asociado. Estos nombres de marcador sirven como identificadores para cada campo de formulario. La colección devuelta mantiene el orden de los nombres de los campos de formulario tal como aparecen en el documento. Este método es útil para detectar y analizar problemas de nomenclatura dentro de los campos de formulario, que pueden necesitar ser abordados mediante el método [`FixInvalidFormFieldNames`](../fixinvalidformfieldnames).

### Ver también

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
