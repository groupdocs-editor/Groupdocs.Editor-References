---
title: "RecognizeLists"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar cómo se reconocen los elementos de listas numeradas cuando el documento se importa desde formato de texto plano. El valor predeterminado es verdadero."
type: docs
weight: 60
url: /es/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

Permite especificar cómo se reconocen los elementos de listas numeradas cuando el documento se importa desde formato de texto plano. El valor predeterminado es verdadero.

```csharp
public bool RecognizeLists { get; set; }
```

### Observaciones

Si esta opción se establece en false, el algoritmo de reconocimiento de listas detecta los párrafos de lista cuando los números de lista terminan con un punto, un corchete derecho o símbolos de viñeta (como "•", "*", "-" o "o"). Si esta opción se establece en true, también se utilizan los espacios en blanco como delimitadores de número de lista: el algoritmo de reconocimiento de listas para numeración al estilo árabe (1., 1.1.2.) usa tanto los espacios en blanco como el símbolo de punto (".").

### Ver también

* class [TextEditOptions](../../texteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
