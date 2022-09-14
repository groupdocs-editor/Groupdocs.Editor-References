---
title: EmailSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description:  Allows to specify custom options for generating and saving electronic mail email documents
type: docs
weight: 13
url: /java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving electronic mail (email) documents
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailSaveOptions()](#EmailSaveOptions--) | Initializes a new instance of the [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) class, where all options are set to their default values |
| [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | Initializes a new instance of the [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) class with \`\`\` MailMessageOutput \`\`\`([\#getMailMessageOutput](../../null/\#getMailMessageOutput)/[\#setMailMessageOutput](../../null/\#setMailMessageOutput)) parameter |
## Methods

| Method | Description |
| --- | --- |
| [getMailMessageOutput()](#getMailMessageOutput--) | Allows to control which parts of the mail message should be delivered to the output email document, which will be generated and saved with the [Editor\#save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor\#save-EditableDocument-Stream-ISaveOptions-) method |
| [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Allows to control which parts of the mail message should be delivered to the output email document, which will be generated and saved with the [Editor\#save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor\#save-EditableDocument-Stream-ISaveOptions-) method |
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Initializes a new instance of the [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) class, where all options are set to their default values

### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


Initializes a new instance of the [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) class with \`\`\` MailMessageOutput \`\`\`([\#getMailMessageOutput](../../null/\#getMailMessageOutput)/[\#setMailMessageOutput](../../null/\#setMailMessageOutput)) parameter

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailMessageOutput | int | The mail message output, which also can be specified through the property |

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Allows to control which parts of the mail message should be delivered to the output email document, which will be generated and saved with the [Editor\#save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor\#save-EditableDocument-Stream-ISaveOptions-) method

Value: Flagged enum that controls the parts of the mail message, which should be processed. Default value is \`\`\` MailMessageOutput.All \`\`\`

**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Allows to control which parts of the mail message should be delivered to the output email document, which will be generated and saved with the [Editor\#save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor\#save-EditableDocument-Stream-ISaveOptions-) method

Value: Flagged enum that controls the parts of the mail message, which should be processed. Default value is \`\`\` MailMessageOutput.All \`\`\`

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

