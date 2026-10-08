---
title: "FormFieldManager"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Administre un formulario con campos de formulario heredados. Los campos de formulario heredados son los tipos de campo que estaban disponibles en versiones anteriores del procesamiento de Word. El grupo Formularios heredados visible después de hacer clic en el ícono Herramientas heredadas incluye tres tipos de campos de formulario que puede insertar en un documento: texto, casilla de verificación, lista desplegable, fecha, etc. vea más FormFieldType../groupdocs.editor.words.fieldmanagement/formfieldtype. Cada uno de estos campos de formulario permite al usuario del formulario seleccionar o ingresar información del tipo que usted considere apropiado."
type: docs
weight: 40
url: /es/net/groupdocs.editor/formfieldmanager/
---
## FormFieldManager class

Administre un formulario con campos de formulario heredados. Los campos de formulario heredados son los tipos de campo que estaban disponibles en versiones anteriores del procesamiento de Word. El grupo Formularios heredados (visible después de hacer clic en el ícono Herramientas heredadas) incluye tres tipos de campos de formulario que puede insertar en un documento: texto, casilla de verificación, lista desplegable, fecha, etc., vea más [`FormFieldType`](../../groupdocs.editor.words.fieldmanagement/formfieldtype). Cada uno de estos campos de formulario permite al usuario del formulario seleccionar o ingresar información del tipo que usted considere apropiado.

```csharp
public sealed class FormFieldManager
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FormFieldCollection](../../groupdocs.editor/formfieldmanager/formfieldcollection) { get; } | Obtiene la colección de campos de formulario en el documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FixInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/fixinvalidformfieldnames)(IEnumerable&lt;InvalidFormField&gt;) | Corrige los nombres de campos de formulario inválidos en el documento aplicando actualizaciones especificadas o generando automáticamente nombres únicos. |
| [GetInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/getinvalidformfieldnames)() | Obtiene una colección de nombres de campos de formulario inválidos del documento. |
| [HasInvalidFormFields](../../groupdocs.editor/formfieldmanager/hasinvalidformfields)() | Comprueba si el documento contiene campos de formulario inválidos. |
| [RemoveFormFields](../../groupdocs.editor/formfieldmanager/removeformfields)(IEnumerable&lt;IFormField&gt;) | Elimina varios campos de formulario del documento. |
| [RemoveFormFiled](../../groupdocs.editor/formfieldmanager/removeformfiled)(IFormField) | Elimina un campo de formulario específico del documento. |
| [UpdateFormFiled](../../groupdocs.editor/formfieldmanager/updateformfiled)(FormFieldCollection) | Actualiza los campos de formulario en el documento basándose en la colección de campos de formulario proporcionada. |

### Observaciones

La clase [`FormFieldManager`](../formfieldmanager) proporciona funcionalidad para manejar campos de formulario en un documento. Permite a los usuarios obtener, actualizar, corregir, comprobar la invalidez y eliminar campos de formulario del documento.

### Ver también

* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
