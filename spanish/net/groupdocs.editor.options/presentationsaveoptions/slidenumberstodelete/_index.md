---
title: "SlideNumbersToDelete"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar una matriz con números basados en 1 de diapositivas que deben eliminarse de la presentación durante su guardado en caso de que la diapositiva editada se inserte en una presentación existente"
type: docs
weight: 60
url: /es/net/groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete/
---
## PresentationSaveOptions.SlideNumbersToDelete property

Permite especificar una matriz con números de diapositivas basados en 1 que deben eliminarse de la presentación durante su guardado, en caso de que la diapositiva editada se inserte en una presentación existente.

```csharp
public int[] SlideNumbersToDelete { get; set; }
```

### Observaciones

Cuando la diapositiva editada no se guarda como una nueva presentación de una sola diapositiva (comportamiento predeterminado), sino que se guarda en una presentación existente (usando la propiedad [`SlideNumber`](../slidenumber)), también es posible eliminar algunas diapositivas particulares de esa presentación especificando sus números en esta matriz.

Por defecto esta matriz es `null` — no se eliminarán diapositivas. Sin embargo, cuando esta matriz no es nula y no está vacía, y contiene al menos un número de diapositiva válido, después de que se genere el documento de Presentación de salida con el contenido de la diapositiva editada, las diapositivas con los números especificados se eliminarán de la presentación justo antes de escribir su contenido en el flujo de salida o archivo.

Los números de diapositiva en esta matriz son basados en 1, no en 0; los números inválidos (menores que 1 o mayores que el número total de diapositivas) serán ignorados.

### Ver también

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
