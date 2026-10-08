---
title: "Edit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Abre un documento previamente cargado para su edición utilizando opciones específicas de formato, generando y devolviendo una instancia de la clase EditableDocumentgroupdocs.editor/editabledocument que, a su vez, contiene métodos para producir marcado HTML y recursos asociados."
type: docs
weight: 60
url: /es/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

Abre un documento previamente cargado para su edición utilizando opciones específicas de formato, generando y devolviendo una instancia de la clase '[`EditableDocument`](../../editabledocument)', que, a su vez, contiene métodos para producir marcado HTML y recursos asociados.

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| editOptions | IEditOptions | Opciones de documento específicas de formato, que permiten afinar el proceso de conversión. Puede ser NULL — en ese caso GroupDocs.Editor detecta el formato del documento previamente cargado y aplica las opciones predeterminadas para este formato. No debe entrar en conflicto con las opciones de carga aplicadas previamente. |

### Valor devuelto

Instancia de la clase '[`EditableDocument`](../../editabledocument)', que encapsula el documento de entrada completo con todos sus recursos en formato intermedio. Este método, si finaliza con éxito, nunca devuelve NULL.

### Observaciones

Cuando el documento original de entrada se carga en la instancia 'Editor' mediante el constructor, este método permite abrir el documento para edición convirtiéndolo a formato intermedio, que está encapsulado dentro de una instancia de la clase 'EditableDocument'. '[`EditableDocument`](../../editabledocument)', devuelto por este método, contiene todos los métodos y propiedades necesarios para producir marcado HTML y los recursos correspondientes (como imágenes, fuentes y hojas de estilo) en todas las configuraciones necesarias para su posterior paso a cualquier editor HTML WYSIWYG. Esta sobrecarga obtiene opciones de edición, que son específicas para familias de formatos. **Aprende más**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Ver también

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

Abre un documento previamente cargado para edición usando opciones predeterminadas al generar y devolver una instancia de la clase '[`EditableDocument`](../../editabledocument)', que, a su vez, contiene métodos para producir marcado HTML y recursos asociados.

```csharp
public EditableDocument Edit()
```

### Valor devuelto

Instancia de la clase '[`EditableDocument`](../../editabledocument)', que encapsula el documento de entrada completo con todos sus recursos en formato intermedio. Este método, si finaliza con éxito, nunca devuelve NULL.

### Observaciones

Cuando el documento original de entrada se carga en la instancia 'Editor' mediante el constructor, este método permite abrir el documento para edición convirtiéndolo a formato intermedio, que está encapsulado dentro de una instancia de la clase '[`EditableDocument`](../../editabledocument)'. '[`EditableDocument`](../../editabledocument)', devuelto por este método, contiene todos los métodos y propiedades necesarios para producir marcado HTML y los recursos correspondientes (como imágenes, fuentes y hojas de estilo) en todas las configuraciones necesarias para su posterior paso a cualquier editor HTML WYSIWYG. Esta sobrecarga aplica opciones de edición, que son predeterminadas para el formato al que pertenece el documento de entrada. **Aprende más**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Ver también

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
