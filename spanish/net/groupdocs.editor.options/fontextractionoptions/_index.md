---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Las opciones de extracción de fuentes controlan qué fuentes deben extraerse y de dónde"
type: docs
weight: 890
url: /es/net/groupdocs.editor.options/fontextractionoptions/
---
## FontExtractionOptions enumeration

Las opciones de extracción de fuentes controlan qué fuentes deben extraerse y de dónde

```csharp
public enum FontExtractionOptions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| NotExtract | `0` | No extrae ningún recurso de fuente ni del documento ni del sistema. Valor predeterminado. |
| ExtractAllEmbedded | `1` | Extrae todos los recursos de fuentes que están incrustados en el documento Word de entrada, sin importar si son personalizados o del sistema. |
| ExtractEmbeddedWithoutSystem | `2` | Extrae solo los recursos de fuentes incrustados que son personalizados (no del sistema). |
| ExtractAll | `3` | Intenta extraer todas las fuentes que se utilizan en el documento WordProcessing de entrada, incluidas las fuentes del sistema. |

### Ver también

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
