---
title: "GroupDocs.Editor"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "El espacio de nombres GroupDocs.Editor proporciona clases para editar documentos usando editores WYSIWYG de frontend de terceros sin ninguna aplicación adicional."
type: docs
weight: 10
url: /es/net/groupdocs.editor/
---
El espacio de nombres GroupDocs.Editor proporciona clases para editar documentos utilizando editores WYSIWYG de front-end de terceros sin ninguna aplicación adicional.

## Clases

| Clase | Descripción |
| --- | --- |
| [EditableDocument](./editabledocument) | Documento intermedio, que contiene contenido antes y después de la edición |
| [Editor](./editor) | Clase principal, que encapsula los métodos de conversión. La clase Editor proporciona métodos para cargar, editar y guardar documentos de todos los formatos admitidos. Es desechable, por lo que use una directiva 'using' o libere sus recursos manualmente mediante la llamada al método 'Dispose()'. La carga de documentos se realiza a través de constructores. La edición de documentos — mediante el método 'Edit' — y el guardado del documento resultante después de la edición — mediante el método 'Save'. |
| [EncryptedException](./encryptedexception) | La excepción que se lanza cuando el usuario intenta abrir un documento que fue cifrado usando los X509Certificates. |
| [FormFieldManager](./formfieldmanager) | Administrar un formulario con campos de formulario heredados. Los campos de formulario heredados son los tipos de campo que estaban disponibles en versiones anteriores del procesamiento de Word. El grupo Formularios heredados (visible después de hacer clic en el ícono Herramientas heredadas) incluye tres tipos de campos de formulario que puede insertar en un documento: texto, casilla de verificación, lista desplegable, fecha, etc., vea más [`FormFieldType`](../groupdocs.editor.words.fieldmanagement/formfieldtype). Cada uno de estos campos de formulario permite al usuario del formulario seleccionar o ingresar información del tipo que considere apropiado. |
| [IncorrectPasswordException](./incorrectpasswordexception) | La excepción que se lanza cuando la contraseña especificada es incorrecta. |
| [InvalidFormatException](./invalidformatexception) | La excepción que se lanza cuando el usuario intenta abrir un documento con opciones específicas de formato que son incompatibles con el formato original del documento. |
| [License](./license) | Proporciona métodos para licenciar el componente. Obtenga más información sobre licencias [aquí](https://purchase.groupdocs.com/faqs/licensing). |
| [Metered](./metered) | Proporciona métodos para aplicar una licencia [Metered](https://purchase.groupdocs.com/faqs/licensing/metered). |
| [PasswordRequiredException](./passwordrequiredexception) | La excepción que se lanza cuando el usuario intenta abrir un documento cifrado protegido con contraseña de algún formato y no proporciona una contraseña para abrir este documento. |

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
