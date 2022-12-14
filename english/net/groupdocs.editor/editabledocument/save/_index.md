---
title: Save
second_title: GroupDocs.Editor for .NET API Reference
description: Saves this HTML document to the file on specified path where HTML markup will be stored and to the accompanying folder with resources.
type: docs
weight: 160
url: /net/groupdocs.editor/editabledocument/save/
---
## Save(string) {#save}

Saves this HTML document to the file on specified path, where HTML markup will be stored, and to the accompanying folder with resources.

```csharp
public void Save(string htmlFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| htmlFilePath | String | Full path to the file, where HTML markup will be stored. File will be created or overwritten, if exists. Accompanying resource folder will be created in the same folder, where HTML file exist. |

### See Also

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../editabledocument)
* assembly [GroupDocs.Editor](../../../)

---

## Save(string, string) {#save_1}

Saves this HTML document to the file on specified path, where HTML markup will be stored, and to the accompanying folder with resources, which is located on specified path.

```csharp
public void Save(string htmlFilePath, string resourcesFolderPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| htmlFilePath | String | Full path to the file, where HTML markup will be stored. Cannot be NULL or empty. File will be created or overwritten, if exists. |
| resourcesFolderPath | String | Full path to the accompanying folder, where all related resources will be stored. If NULL or empty, folder will be created automatically in the same directory, where *.html file. If specified and not exists, will be created. |

### See Also

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../editabledocument)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
