---
title: FileSaver
second_title: GroupDocs.Editor for Java API Reference
description:  Responsible for saving different resources from HTML and CSS to the files
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.serialization/filesaver/
---
**Inheritance:**
java.lang.Object
```
public class FileSaver
```

Responsible for saving different resources from HTML and CSS to the files
## Constructors

| Constructor | Description |
| --- | --- |
| [FileSaver()](#FileSaver--) |  |
## Methods

| Method | Description |
| --- | --- |
| [saveAllImagesInDeclarationBlock(CssDeclarationBlock input, String folderPath)](#saveAllImagesInDeclarationBlock-com.groupdocs.editor.htmlcss.css.CssDeclarationBlock-java.lang.String-) |  |
| [saveAllFonts(FontFaceRuleModel input, String folderPath)](#saveAllFonts-com.groupdocs.editor.htmlcss.css.atrules.FontFaceRuleModel-java.lang.String-) |  |
| [saveAllFonts(FontFaceRuleInput input, String folderPath)](#saveAllFonts-com.groupdocs.editor.htmlcss.css.atrules.FontFaceRuleInput-java.lang.String-) |  |
| [saveAllResourcesFromNestedAtRule(ConditionalGroupRuleBase input, String folderPath)](#saveAllResourcesFromNestedAtRule-com.groupdocs.editor.htmlcss.css.atrules.ConditionalGroupRuleBase-java.lang.String-) |  |
### FileSaver() {#FileSaver--}
```
public FileSaver()
```


### saveAllImagesInDeclarationBlock(CssDeclarationBlock input, String folderPath) {#saveAllImagesInDeclarationBlock-com.groupdocs.editor.htmlcss.css.CssDeclarationBlock-java.lang.String-}
```
public static int saveAllImagesInDeclarationBlock(CssDeclarationBlock input, String folderPath)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | [CssDeclarationBlock](../../com.groupdocs.editor.htmlcss.css/cssdeclarationblock) |  |
| folderPath | java.lang.String |  |

**Returns:**
int
### saveAllFonts(FontFaceRuleModel input, String folderPath) {#saveAllFonts-com.groupdocs.editor.htmlcss.css.atrules.FontFaceRuleModel-java.lang.String-}
```
public static int saveAllFonts(FontFaceRuleModel input, String folderPath)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | [FontFaceRuleModel](../../com.groupdocs.editor.htmlcss.css.atrules/fontfacerulemodel) |  |
| folderPath | java.lang.String |  |

**Returns:**
int
### saveAllFonts(FontFaceRuleInput input, String folderPath) {#saveAllFonts-com.groupdocs.editor.htmlcss.css.atrules.FontFaceRuleInput-java.lang.String-}
```
public static int saveAllFonts(FontFaceRuleInput input, String folderPath)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | [FontFaceRuleInput](../../com.groupdocs.editor.htmlcss.css.atrules/fontfaceruleinput) |  |
| folderPath | java.lang.String |  |

**Returns:**
int
### saveAllResourcesFromNestedAtRule(ConditionalGroupRuleBase input, String folderPath) {#saveAllResourcesFromNestedAtRule-com.groupdocs.editor.htmlcss.css.atrules.ConditionalGroupRuleBase-java.lang.String-}
```
public static int saveAllResourcesFromNestedAtRule(ConditionalGroupRuleBase input, String folderPath)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | [ConditionalGroupRuleBase](../../com.groupdocs.editor.htmlcss.css.atrules/conditionalgrouprulebase) |  |
| folderPath | java.lang.String |  |

**Returns:**
int
