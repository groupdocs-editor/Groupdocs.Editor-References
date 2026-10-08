---
title: "ExportCidUrls"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Especifica si se deben usar URLs CID ContentID para referenciar recursos como imágenes, fuentes y CSS incluidos en documentos MHTML. El valor predeterminado es false."
type: docs
weight: 20
url: /es/net/groupdocs.editor.options/mhtmlsaveoptions/exportcidurls/
---
## MhtmlSaveOptions.ExportCidUrls property

Especifica si se deben usar URLs CID (Content-ID) para referenciar recursos (imágenes, fuentes, CSS) incluidos en documentos MHTML. El valor predeterminado es `false`.

```csharp
public bool ExportCidUrls { get; set; }
```

### Observaciones

Por defecto, los recursos en documentos MHTML se referencian por nombre de archivo (por ejemplo, \"image.png\"), que se comparan con los encabezados \"Content-Location\" de las partes MIME. Esta opción habilita un método alternativo, donde las referencias a archivos de recursos se escriben como URLs CID (Content-ID) (por ejemplo, \"cid:image.png\") y se comparan con los encabezados \"Content-ID\".

En teoría, no debería haber diferencia entre los dos métodos de referencia y cualquiera de ellos debería funcionar correctamente en cualquier navegador o cliente de correo. En la práctica, sin embargo, algunos agentes no pueden obtener los recursos por nombre de archivo. Si su navegador o cliente de correo se niega a cargar los recursos incluidos en un documento MTHML (no muestra imágenes o no carga estilos CSS), intente exportar el documento con URLs CID.

### Ver también

* class [MhtmlSaveOptions](../../mhtmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
