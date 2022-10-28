---
title: Editor
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Inicializa la nueva instancia del Editor con el documento de entrada especificado como flujo
type: docs
weight: 10
url: /es/net/groupdocs.editor/editor/editor/
---
## Editor(Func&lt;Stream&gt;) {#constructor}

Inicializa la nueva instancia del Editor con el documento de entrada especificado (como flujo)

```csharp
public Editor(Func<Stream> document)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | Delegado, eso debería devolver una secuencia con el contenido del documento. No debe ser NULL. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos compatibles con GroupDocs.Editor: [Formatos de documentos compatibles con GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Editor para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Ver también

* class [Editor](../../editor)
* espacio de nombres [GroupDocs.Editor](../../editor)
* asamblea [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_1}

Inicializa la nueva instancia del Editor con el documento de entrada especificado (como flujo) con sus opciones de carga

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | Delegado, eso debería devolver una secuencia con el contenido del documento. No debe ser NULL. |
| loadOptions | Func`1 | Delegado, eso debería devolver las opciones de carga de un documento. Puede ser NULL y puede devolver nulo - en ese caso, el tipo de documento se detectará automáticamente y se aplicarán las opciones de carga predeterminadas para ese tipo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos compatibles con GroupDocs.Editor: [Formatos de documentos compatibles con GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Editor para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Más información sobre cómo abrir y editar documentos protegidos con contraseña y documentos de diferentes almacenamientos: [Cargue y edite documentos usando GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Ver también

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* espacio de nombres [GroupDocs.Editor](../../editor)
* asamblea [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_2}

Inicializa la nueva instancia del Editor con el documento de entrada especificado (como una ruta de archivo completa)

```csharp
public Editor(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Ruta completa al archivo. No debe ser NULL. Debe ser válido y el archivo debe existir. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos compatibles con GroupDocs.Editor: [Formatos de documentos compatibles con GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Editor para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Ver también

* class [Editor](../../editor)
* espacio de nombres [GroupDocs.Editor](../../editor)
* asamblea [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_3}

Inicializa la nueva instancia del Editor con el documento de entrada especificado (como una ruta de archivo completa) con sus opciones de carga

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Ruta completa al archivo. No debe ser NULL. Debe ser válido y el archivo debe existir. |
| loadOptions | Func`1 | Delegado, eso debería devolver las opciones de carga de un documento. Puede ser NULL y puede devolver nulo - en ese caso, el tipo de documento se detectará automáticamente y se aplicarán las opciones de carga predeterminadas para ese tipo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos compatibles con GroupDocs.Editor: [Formatos de documentos compatibles con GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Editor para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Más información sobre cómo abrir y editar documentos protegidos con contraseña y documentos de diferentes almacenamientos: [Cargue y edite documentos usando GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Ver también

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* espacio de nombres [GroupDocs.Editor](../../editor)
* asamblea [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
