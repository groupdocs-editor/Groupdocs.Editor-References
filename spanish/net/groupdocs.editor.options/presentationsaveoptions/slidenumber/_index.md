---
title: "SlideNumber"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite insertar la diapositiva editada en una presentación existente en lugar de crear una nueva presentación de una sola diapositiva (comportamiento predeterminado). El número de diapositiva es un número basado en 1 de una diapositiva en la presentación cargada en la clase Editor. Si es 0 (valor predeterminado) se creará una nueva presentación con una sola diapositiva editada. Si es mayor o menor que cero y hay una presentación válida cargada en la clase Editor, la diapositiva editada almacenada dentro de la instancia de EditableDocument de entrada se insertará en esa presentación."
type: docs
weight: 50
url: /es/net/groupdocs.editor.options/presentationsaveoptions/slidenumber/
---
## PresentationSaveOptions.SlideNumber property

Permite insertar la diapositiva editada en una presentación existente en lugar de crear una nueva presentación de una sola diapositiva (comportamiento predeterminado). El número de diapositiva es un número basado en 1 de una diapositiva en la presentación, cargada en la clase Editor. Si es 0 (valor predeterminado), la nueva presentación se creará con una sola diapositiva editada. Si es mayor o menor que cero, y existe una presentación válida cargada en la clase Editor, la diapositiva editada, almacenada dentro de la instancia de EditableDocument de entrada, se insertará en esa presentación.

```csharp
public int SlideNumber { get; set; }
```

### Observaciones

Propiedad entera SlideNumber, si no está en el estado predeterminado (valor reservado '0'), representa un número de diapositiva, por lo que comienza en 1, no en cero, y su valor máximo es la cantidad de todas las diapositivas existentes en una presentación. Sin embargo, si el valor especificado es mayor que la cantidad de todas las diapositivas, GroupDocs.Editor lo ajustará para marcar la última diapositiva. También se permiten valores negativos y cuentan diapositivas desde el final. Por ejemplo, "-1" implica la última diapositiva en una presentación, "-2" — la penúltima, etc. Al igual que con los valores positivos, cuando el número de diapositiva negativo supera el recuento total de diapositivas en la presentación dada, se ajustará a la primera diapositiva. La propiedad booleana [`InsertAsNewSlide`](../insertasnewslide) está estrechamente vinculada a esta.

### Ejemplos

Una presentación dada tiene 5 diapositivas: SlideNumber = 0; — ignora la presentación dada, crea una nueva presentación y coloca la diapositiva editada en ella. SlideNumber = 1; — reemplaza la primera diapositiva con la editada SlideNumber = 2; — reemplaza la segunda diapositiva con la editada SlideNumber = 5; — reemplaza la última (5ª) diapositiva con la editada SlideNumber = 6; — reemplaza la última (5ª) diapositiva con la editada, porque 6 es mayor que 5 y por lo tanto se ajusta SlideNumber = -1; — reemplaza la última (5ª) diapositiva con la editada, porque "-1" significa "última existente" SlideNumber = -2; — reemplaza la cuarta diapositiva con la editada SlideNumber = -3; — reemplaza la tercera diapositiva con la editada SlideNumber = -4; — reemplaza la segunda diapositiva con la editada SlideNumber = -5; — reemplaza la primera diapositiva con la editada SlideNumber = -6; — reemplaza la primera diapositiva con la editada, porque "-6" es mayor que 5 y por lo tanto se ajusta

### Ver también

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
