---
title: "LocaleId"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Obtiene o establece el ID de configuración regional del campo de formulario que representa la cultura o la configuración regional asociada al campo de formulario."
type: docs
weight: 30
url: /es/net/groupdocs.editor.words.fieldmanagement/dropdownformfield/localeid/
---
## DropDownFormField.LocaleId property

Obtiene o establece el ID de configuración regional del campo de formulario, que representa la cultura o la configuración regional asociada al campo de formulario.

```csharp
public int LocaleId { get; set; }
```

### Observaciones

La propiedad LocaleId especifica un identificador de configuración regional (LCID) que corresponde a una cultura o región específica.

### Ejemplos

El siguiente ejemplo muestra cómo establecer la propiedad LocaleId:

```csharp
Set the LocaleId to represent the English (United States) culture
dropDownField.LocaleId = new CultureInfo("en-US").LCID;
```

### Ver también

* class [DropDownFormField](../../dropdownformfield)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
