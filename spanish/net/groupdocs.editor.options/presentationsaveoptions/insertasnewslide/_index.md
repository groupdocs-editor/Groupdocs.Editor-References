---
title: "InsertAsNewSlide"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Bandera booleana que indica si la diapositiva editada debe reemplazar la diapositiva existente en la presentación original en la posición especificada por la propiedad SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber o si debe insertarse entre la diapositiva existente y la anterior sin reemplazar su contenido. Por defecto es false, la diapositiva existente será reemplazada. Esta propiedad se ignora si el valor de la propiedad SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber se establece en 0."
type: docs
weight: 20
url: /es/net/groupdocs.editor.options/presentationsaveoptions/insertasnewslide/
---
## PresentationSaveOptions.InsertAsNewSlide property

Bandera booleana que indica si la diapositiva editada debe reemplazar la diapositiva existente en la presentación original en la posición especificada por la propiedad [`SlideNumber`](../slidenumber), o si debe insertarse entre la diapositiva existente y la anterior sin reemplazar su contenido. Por defecto es `false` — la diapositiva existente será reemplazada. Esta propiedad se ignora si el valor de la propiedad [`SlideNumber`](../slidenumber) se establece en `'0'`.

```csharp
public bool InsertAsNewSlide { get; set; }
```

### Observaciones

Por defecto la diapositiva se reemplaza. Esto significa que si la presentación tiene 5 diapositivas, y [`SlideNumber`](../slidenumber)=4, entonces la cuarta diapositiva será reemplazada por la nueva diapositiva editada, mientras que la cantidad total de diapositivas en la presentación (5) permanecerá sin cambios. Sin embargo, si el valor de esta propiedad se establece en true, la nueva diapositiva editada se insertará como cuarta diapositiva, y todas las diapositivas posteriores se desplazarán al final: la cuarta diapositiva \"old\" pasa a ser la quinta, y la quinta pasa a ser la sexta, y la cantidad total de diapositivas en la presentación se incrementará en uno, quedando en 6.

### Ver también

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
