---
title: "SlideNumber"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar los números de diapositiva que deben abrirse para edición"
type: docs
weight: 30
url: /es/net/groupdocs.editor.options/presentationeditoptions/slidenumber/
---
## PresentationEditOptions.SlideNumber property

Permite especificar los números de diapositiva que deben abrirse para edición

```csharp
public int SlideNumber { get; set; }
```

### Observaciones

El número de diapositiva es un índice basado en cero que permite especificar y seleccionar una diapositiva concreta de una presentación para editarla. Si es menor que 0, se seleccionará la primera diapositiva (igual que SlideNumber = 0). Si es mayor que la cantidad total de diapositivas en la presentación, se seleccionará la última diapositiva. Si la presentación de entrada contiene solo una diapositiva, esta opción se ignorará y esa única diapositiva se editará. Si se intenta abrir para edición una diapositiva oculta mientras la opción [`ShowHiddenSlides`](../showhiddenslides) está establecida en 'false', se lanzará una excepción.

### Ver también

* class [PresentationEditOptions](../../presentationeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
