---
title: "Save"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Guarda este documento HTML en el archivo en la ruta especificada donde se almacenará el marcado HTML y en la carpeta adjunta con los recursos."
type: docs
weight: 160
url: /es/net/groupdocs.editor/editabledocument/save/
---
## Save(string) {#save_1}

Guarda este documento HTML en el archivo en la ruta especificada, donde se almacenará el marcado HTML, y en la carpeta adjunta con los recursos.

```csharp
public void Save(string htmlFilePath)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| htmlFilePath | String | Ruta completa al archivo donde se almacenará el marcado HTML. El archivo será creado o sobrescrito si ya existe. La carpeta de recursos adjunta se creará en la misma carpeta donde exista el archivo HTML. |

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(string, string) {#save_2}

Guarda este documento HTML en el archivo en la ruta especificada, donde se almacenará el marcado HTML, y en la carpeta adjunta con los recursos, que se encuentra en la ruta especificada.

```csharp
public void Save(string htmlFilePath, string resourcesFolderPath)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| htmlFilePath | String | Ruta completa al archivo donde se almacenará el marcado HTML. No puede ser NULL o estar vacío. El archivo será creado o sobrescrito si ya existe. |
| resourcesFolderPath | String | Ruta completa a la carpeta adjunta donde se almacenarán todos los recursos relacionados. Si es NULL o está vacía, la carpeta se creará automáticamente en el mismo directorio donde está el archivo *.html. Si se especifica y no existe, se creará. |

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(TextWriter, HtmlSaveOptions) {#save}

Guarda el contenido de este [`EditableDocument`](../../editabledocument) como documento HTML en el escritor de texto especificado, mientras que el segundo parámetro de opciones permite personalizar el procedimiento de guardado y especificar la devolución de llamada de guardado de recursos.

```csharp
public void Save(TextWriter htmlMarkup, HtmlSaveOptions saveOptions)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| htmlMarkup | TextWriter | Implementación del escritor de texto, en el que se escribirá el marcado HTML. No puede ser nulo. |
| saveOptions | HtmlSaveOptions | Opciones de guardado de HTML, que controlan el procedimiento de guardado: cómo se almacena el marcado HTML (nombres de etiquetas, tipos de comillas) y cómo y dónde se guardarán los CSS y otros recursos como imágenes o fuentes. El usuario debe especificar el heredero de la interfaz en la propiedad [`SavingCallback`](../../../groupdocs.editor.options/htmlsaveoptions/savingcallback) para controlar cómo se deben guardar y referenciar los recursos desde el marcado HTML. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Cualquiera de los argumentos especificados o la propiedad `SavingCallback` en *saveOptions* es `null` |

### Ver también

* class [HtmlSaveOptions](../../../groupdocs.editor.options/htmlsaveoptions)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
