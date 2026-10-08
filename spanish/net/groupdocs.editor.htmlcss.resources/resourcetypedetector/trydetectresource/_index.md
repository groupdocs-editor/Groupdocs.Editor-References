---
title: "TryDetectResource"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Intenta analizar una secuencia de entrada y crea uno de los recursos HTML compatibles a partir de ella, teniendo en cuenta un tipo asumido especificado si no es null"
type: docs
weight: 20
url: /es/net/groupdocs.editor.htmlcss.resources/resourcetypedetector/trydetectresource/
---
## ResourceTypeDetector.TryDetectResource method

Intenta analizar un flujo de entrada y crea uno de los recursos HTML compatibles a partir de él, teniendo en cuenta un tipo supuestamente especificado, si no es nulo

```csharp
public static IHtmlResource TryDetectResource(Stream inputResourceStream, string name, 
    IResourceType assumptiveFormat)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| inputResourceStream | Stream | Secuencia de entrada, que presumiblemente contiene un recurso HTML. Si es inválida, se lanzará una excepción. |
| nombre | String | Nombre del recurso, que se utilizará para el recurso creado y devuelto en caso de éxito. No puede ser NULL, vacío o solo espacios |
| assumptiveFormat | IResourceType | Formato asumido del recurso HTML de entrada, que es útil para lograr el mejor rendimiento. Si es completamente desconocido, use el valor NULL. Puede ser incorrecto, lo que solo empeorará el rendimiento. |

### Valor devuelto

Instancia, que implementa la interfaz 'IHtmlResource' y representa uno de los recursos HTML compatibles en caso de éxito, o NULL en caso de fallo

### Ver también

* interface [IHtmlResource](../../ihtmlresource)
* interface [IResourceType](../../iresourcetype)
* class [ResourceTypeDetector](../../resourcetypedetector)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
