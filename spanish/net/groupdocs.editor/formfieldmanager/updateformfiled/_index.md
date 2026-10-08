---
title: "UpdateFormFiled"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Actualiza los campos de formulario en el documento basándose en la colección de campos de formulario proporcionada."
type: docs
weight: 70
url: /es/net/groupdocs.editor/formfieldmanager/updateformfiled/
---
## FormFieldManager.UpdateFormFiled method

Actualiza los campos de formulario en el documento basándose en la colección de campos de formulario proporcionada.

```csharp
public void UpdateFormFiled(FormFieldCollection formFieldCollection)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| formFieldCollection | FormFieldCollection | La colección de campos de formulario que contiene las actualizaciones a aplicar al documento. |

### Observaciones

El método `UpdateFormFiled` actualiza los campos de formulario en el documento según la *formFieldCollection* proporcionada. Cada campo de formulario en la colección corresponde a un campo de formulario en el documento, y las actualizaciones especificadas en la colección se aplican en consecuencia. Este método es útil para sincronizar los datos de los campos de formulario entre el documento y una fuente externa, como una interfaz de usuario o una base de datos.

### Ver también

* class [FormFieldCollection](../../../groupdocs.editor.words.fieldmanagement/formfieldcollection)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
