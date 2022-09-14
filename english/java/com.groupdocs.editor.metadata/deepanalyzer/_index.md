---
title: DeepAnalyzer
second_title: GroupDocs.Editor for Java API Reference
description: 
type: docs
weight: 15
url: /java/com.groupdocs.editor.metadata/deepanalyzer/
---
**Inheritance:**
java.lang.Object
```
public class DeepAnalyzer
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DeepAnalyzer()](#DeepAnalyzer--) |  |
## Methods

| Method | Description |
| --- | --- |
| [tryAnalyzeCells(System.IO.Stream input, String password, ILogger logger)](#tryAnalyzeCells-com.aspose.ms.System.IO.Stream-java.lang.String-com.groupdocs.editor.logging.ILogger-) |  |
| [tryExtractPdf(System.IO.Stream input, String password, ILogger logger)](#tryExtractPdf-com.aspose.ms.System.IO.Stream-java.lang.String-com.groupdocs.editor.logging.ILogger-) |  |
### DeepAnalyzer() {#DeepAnalyzer--}
```
public DeepAnalyzer()
```


### tryAnalyzeCells(System.IO.Stream input, String password, ILogger logger) {#tryAnalyzeCells-com.aspose.ms.System.IO.Stream-java.lang.String-com.groupdocs.editor.logging.ILogger-}
```
public static SpreadsheetDocumentInfo tryAnalyzeCells(System.IO.Stream input, String password, ILogger logger)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | com.aspose.ms.System.IO.Stream |  |
| password | java.lang.String |  |
| logger | [ILogger](../../com.groupdocs.editor.logging/ilogger) |  |

**Returns:**
[SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo)
### tryExtractPdf(System.IO.Stream input, String password, ILogger logger) {#tryExtractPdf-com.aspose.ms.System.IO.Stream-java.lang.String-com.groupdocs.editor.logging.ILogger-}
```
public static FixedLayoutDocumentInfo tryExtractPdf(System.IO.Stream input, String password, ILogger logger)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | com.aspose.ms.System.IO.Stream |  |
| password | java.lang.String |  |
| logger | [ILogger](../../com.groupdocs.editor.logging/ilogger) |  |

**Returns:**
[FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo)
