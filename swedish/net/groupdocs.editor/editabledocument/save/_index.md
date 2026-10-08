---
title: "Save"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Sparar detta HTML‑dokument till filen på den angivna sökvägen där HTML‑markupen kommer att lagras samt till den medföljande resursmappen."
type: docs
weight: 160
url: /sv/net/groupdocs.editor/editabledocument/save/
---
## Save(string) {#save_1}

Sparar detta HTML‑dokument till filen på den angivna sökvägen, där HTML‑markup kommer att lagras, och till den medföljande mappen med resurser.

```csharp
public void Save(string htmlFilePath)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| htmlFilePath | String | Fullständig sökväg till filen där HTML‑markupen kommer att lagras. Filen kommer att skapas eller skrivas över om den redan finns. Den medföljande resursmappen skapas i samma mapp där HTML‑filen finns. |

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(string, string) {#save_2}

Sparar detta HTML‑dokument till filen på den angivna sökvägen, där HTML‑markup kommer att lagras, och till den medföljande mappen med resurser, som ligger på den angivna sökvägen.

```csharp
public void Save(string htmlFilePath, string resourcesFolderPath)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| htmlFilePath | String | Fullständig sökväg till filen där HTML‑markupen kommer att lagras. Får inte vara NULL eller tom. Filen kommer att skapas eller skrivas över om den redan finns. |
| resourcesFolderPath | String | Fullständig sökväg till den medföljande mappen där alla relaterade resurser kommer att lagras. Om NULL eller tom skapas mappen automatiskt i samma katalog där *.html‑filen finns. Om den anges och inte finns, kommer den att skapas. |

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(TextWriter, HtmlSaveOptions) {#save}

Sparar innehållet i detta [`EditableDocument`](../../editabledocument) som ett HTML‑dokument till den angivna text‑skrivaren, medan det andra alternativ‑parametern möjliggör anpassning av sparproceduren och specificering av återanrop för resurssparning.

```csharp
public void Save(TextWriter htmlMarkup, HtmlSaveOptions saveOptions)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| htmlMarkup | TextWriter | Implementering av text‑skrivaren som HTML‑markupen kommer att skrivas till. Får inte vara null. |
| saveOptions | HtmlSaveOptions | HTML‑sparalternativ som styr sparproceduren: hur HTML‑markupen lagras (taggnamn, citattecken) och hur och var CSS samt andra resurser som bilder eller teckensnitt sparas. Användaren bör specificera en implementering av gränssnittet i egenskapen [`SavingCallback`](../../../groupdocs.editor.options/htmlsaveoptions/savingcallback) för att kontrollera hur resurser ska sparas och refereras från HTML‑markupen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Något av de angivna argumenten eller `SavingCallback`‑egenskapen i *saveOptions* är `null`. |

### Se även

* class [HtmlSaveOptions](../../../groupdocs.editor.options/htmlsaveoptions)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
