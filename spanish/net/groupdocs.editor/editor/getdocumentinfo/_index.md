---
title: "GetDocumentInfo"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Devuelve los metadatos del documento que se cargó en esta instancia de Editor"
type: docs
weight: 70
url: /es/net/groupdocs.editor/editor/getdocumentinfo/
---
## Editor.GetDocumentInfo method

Devuelve los metadatos del documento que se cargó en esta instancia de 'Editor'.

```csharp
public IDocumentInfo GetDocumentInfo(string password)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| password | String | El usuario puede especificar una contraseña para un documento, si este documento está cifrado con contraseña. Puede ser NULL o una cadena vacía, lo que equivale a la ausencia de contraseña. Para aquellos formatos de documento que no disponen de una función de protección con contraseña, este argumento será ignorado. Si el documento está cifrado y la contraseña no se especifica en este parámetro, pero se especificó previamente en las opciones de carga al crear esta instancia de [`Editor`](../../editor), se utilizará. |

### Valor devuelto

Herencia específica de formato de la interfaz [`IDocumentInfo`](../../../groupdocs.editor.metadata/idocumentinfo), que indica el formato detectado con metadatos específicos del formato, o NULL, si el documento no fue reconocido como compatible o está corrupto.

### Excepciones

| excepción | condición |
| --- | --- |
| ObjectDisposedException | Se lanza cuando la instancia de Editor ya ha sido eliminada al invocar "GetDocumentInfo" |
| [PasswordRequiredException](../../passwordrequiredexception) | Se lanza cuando el documento cargado está protegido con contraseña, pero la contraseña no se especificó en el parámetro "*password*" ni en las opciones de carga durante la creación de la instancia |
| [IncorrectPasswordException](../../incorrectpasswordexception) | Se lanza cuando el documento cargado está protegido con contraseña, la contraseña está especificada, pero es incorrecta |
| InvalidOperationException | Se lanza cuando ocurre un error inesperado de naturaleza desconocida |

### Observaciones

El método GetDocumentInfo es útil cuando no está claro cuál es el formato del documento de entrada, si está protegido con contraseña y/o cuántas páginas/hojas de cálculo/diapositivas contiene. Con base en estos metadatos, devueltos por GetDocumentInfo, es posible ajustar correctamente las opciones de carga y edición para la canalización principal de procesamiento.

El método GetDocumentInfo siempre devuelve datos completos, no se ve afectado por el modo de prueba, y su uso no descuenta los bytes o créditos consumidos.

**Learn more**

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Extracting+document+metainfo)

### Ver también

* interface [IDocumentInfo](../../../groupdocs.editor.metadata/idocumentinfo)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
