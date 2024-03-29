---
title: GetDocumentInfo
second_title: GroupDocs.Editor for .NET API 参考
description: 返回有关文档的元数据该文档已加载到此编辑器实例
type: docs
weight: 60
url: /zh/net/groupdocs.editor/editor/getdocumentinfo/
---
## Editor.GetDocumentInfo method

返回有关文档的元数据，该文档已加载到此“编辑器”实例

```csharp
public IDocumentInfo GetDocumentInfo(string password)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 用户可以为文件指定密码，如果这个文件是用密码加密的。 可以是 NULL 或空字符串，相当于没有密码。对于那些没有密码保护功能的文档格式，该参数将被忽略。如果文档已加密，并且未在此参数中指定密码，但之前在创建此文件时在加载选项中指定了密码[`Editor`](../../editor)例如，它将被使用。 |

### 返回值

格式特定的继承者[`IDocumentInfo`](../../../groupdocs.editor.metadata/idocumentinfo)接口，指示检测到的格式与特定于格式的元数据，或 NULL, 如果文档未被识别为可支持或已损坏。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ObjectDisposedException | 在调用“GetDocumentInfo”时已处理编辑器实例时抛出 |
| [PasswordRequiredException](../../passwordrequiredexception) | 当加载的文档受密码保护但密码未在参数中指定时抛出“*password*“ |
| [IncorrectPasswordException](../../incorrectpasswordexception) | 当加载的文档受密码保护时抛出，密码已指定，但不正确 |
| InvalidOperationException | 当发生未知性质的意外错误时抛出 |

### 评论

当不清楚输入文档是哪种格式、它是否受密码保护和/或它包含多少页/工作表/幻灯片时，GetDocumentInfo 方法很有用。基于 GetDocumentInfo 返回的元数据，可以正确调整主处理管道的加载和编辑选项。

GetDocumentInfo 方法始终返回完整数据，不受试用模式的影响，其使用不会注销消耗的字节或积分。

**了解更多**

* 了解有关在代码中获取文档特定属性的更多信息： [如何使用 GroupDocs.Editor 获取文档信息](https://docs.groupdocs.com/display/editornet/Extracting+document+metainfo)

### 也可以看看

* interface [IDocumentInfo](../../../groupdocs.editor.metadata/idocumentinfo)
* class [Editor](../../editor)
* 命名空间 [GroupDocs.Editor](../../editor)
* 部件 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
