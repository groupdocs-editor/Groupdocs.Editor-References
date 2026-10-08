---
title: "FixInvalidFormFieldNames"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Corrige los nombres de campos de formulario inválidos en el documento aplicando actualizaciones especificadas o generando automáticamente nombres únicos."
type: docs
weight: 20
url: /es/net/groupdocs.editor/formfieldmanager/fixinvalidformfieldnames/
---
## FormFieldManager.FixInvalidFormFieldNames method

Corrige los nombres de campos de formulario inválidos en el documento aplicando actualizaciones especificadas o generando automáticamente nombres únicos.

```csharp
public void FixInvalidFormFieldNames(IEnumerable<InvalidFormField> updateInvalidFormFieldNames)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| updateInvalidFormFieldNames | IEnumerable`1 | Una colección de actualizaciones para nombres de campos de formulario inválidos. Cada actualización contiene el nombre original del campo de formulario y su nuevo nombre correspondiente. Si se deja vacío, los nombres de campos de formulario inválidos se renombrarán automáticamente para garantizar la unicidad. |

### Observaciones

El método `FixInvalidFormFieldNames` resuelve conflictos o inconsistencias de nomenclatura dentro de los campos de formulario del documento aplicando las actualizaciones especificadas en la colección *updateInvalidFormFieldNames*, o generando automáticamente nombres únicos si la colección está vacía. Este método es útil cuando ciertos nombres de campos de formulario son inválidos o entran en conflicto con otros elementos del documento, y necesitan ser corregidos para garantizar un funcionamiento adecuado. ; ;

### Ver también

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
