---
title: "EnablePagination"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite habilitar o deshabilitar la paginación en el documento HTML resultante. Por defecto está deshabilitado false."
type: docs
weight: 30
url: /es/net/groupdocs.editor.options/ebookeditoptions/enablepagination/
---
## EbookEditOptions.EnablePagination property

Permite habilitar o deshabilitar la paginación en el documento HTML resultante. Por defecto está deshabilitada (`false`).

```csharp
public bool EnablePagination { get; set; }
```

### Observaciones

En esencia, la mayoría de los formatos de libros electrónicos son internamente un formato de flujo como Office Open XML, donde el contenido es continuo y se divide en capítulos pero no en páginas. Sin embargo, contiene información específica de página como números de página, notas al pie, encabezados/pies de página, etc. Algunos lectores de libros electrónicos realizan una división del contenido en páginas, mientras que otros (especialmente móviles) — no lo hacen. Esta opción permite controlar cómo debe representarse el contenido del libro electrónico en HTML/CSS durante la edición — en vista flotante (`false`) o paginada (`true`).

### Ver también

* class [EbookEditOptions](../../ebookeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
