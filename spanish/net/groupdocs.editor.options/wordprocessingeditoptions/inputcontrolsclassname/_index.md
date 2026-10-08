---
title: "InputControlsClassName"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar un nombre de clase que se colocará en los atributos de clase de cada elemento HTML que representa algún campo en el documento WordProcessing de entrada. Por defecto es NULL; los atributos de clase no se aplican."
type: docs
weight: 60
url: /es/net/groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname/
---
## WordProcessingEditOptions.InputControlsClassName property

Permite especificar un nombre de clase, que se colocará en los atributos 'class' de cada elemento HTML que represente algún campo en el documento WordProcessing de entrada. Por defecto es NULL; los atributos 'class' no se aplican.

```csharp
public string InputControlsClassName { get; set; }
```

### Observaciones

Casi todos los formatos de la familia de formatos WordProcessing contienen campos — entidades específicas del documento que permiten obtener datos de entrada de los usuarios. Existe una gran variedad de campos: cuadros de texto, casillas de verificación, listas desplegables, botones, selectores de fecha/hora, etc. Todos ellos se traducen a las estructuras y elementos HTML más apropiados, conservando los datos introducidos por el usuario, si están presentes en el documento de entrada. En casos de uso específicos solo se requiere recopilar los datos introducidos en el cliente en lugar de editar todo el contenido del documento. Para ello es necesario identificar los controles de entrada de alguna manera para obtenerlos con sus datos del lado del cliente. Esta propiedad permite especificar un nombre de clase que se aplicará a cada control de entrada en el marcado HTML, de modo que el código del cliente pueda recorrer la estructura del documento HTML y recopilar los datos.

### Ver también

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
