---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara WordProcessing‑kompatibla dokument efter att de har redigerats"
type: docs
weight: 1240
url: /sv/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Tillåter att ange anpassade alternativ för generering och sparande av WordProcessing-kompatibla dokument efter att de har redigerats

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Denna parameterlösa konstruktor skapar en ny instans av WordProcessingSaveOptions med DOCX-utdataformat (kan sedan ändras via egenskapen [`OutputFormat`](./outputformat)) |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | Skapar en ny instans av WordProcessingSaveOptions med angivet obligatoriskt WordProcessing-utdataformat, medan alla andra parametrar har standardvärden |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Tillåter att aktivera eller inaktivera paginering som kommer att användas för att spara WordProcessing-dokumentet. Om det ursprungliga dokumentet öppnades och redigerades i pagineringsläge bör detta alternativ också aktiveras. Som standard är det inaktiverat. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Ansvarar för att bädda in teckensnittresurser i det utgående WordProcessing-dokumentet. Som standard bäddas inga teckensnitt in (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Tillåter att ange en överskrivning av standardlokal (språk) för WordProcessing-dokumentet, som kommer att tillämpas under dess skapande. När den inte anges (standardvärde) kommer MS Word (eller annat program) att upptäcka (eller välja) dokumentets lokal enligt sina egna inställningar eller andra faktorer. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Tillåter att ange en överskrivning av lokal (språk) för WordProcessing-dokumentet för RTL (höger-till-vänster) text, som kommer att tillämpas under dess skapande. När den inte anges (standardvärde) kommer MS Word (eller annat program) att upptäcka (eller välja) dokumentets RTL-lokal enligt sina egna inställningar eller andra faktorer. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Tillåter att överskriva lokalen (språket) för WordProcessing-dokumentet för östasiatisk text, som kommer att tillämpas under dess skapande. När den inte anges (standardvärde) kommer MS Word (eller annat program) att upptäcka (eller välja) dokumentets östasiatiska lokal enligt sina egna inställningar eller andra faktorer. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesanvändning. Att sätta detta alternativ till true kan avsevärt minska minnesförbrukningen vid generering av stora dokument på bekostnad av långsammare sparningstid. Standard är false (minnesoptimering är inaktiverad för bättre prestanda). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Tillåter att ange ett WordProcessing-format som kommer att användas för att spara dokumentet |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Tillåter att ange, ändra, hämta eller ta bort ett lösenord som kommer att användas för att kryptera det genererade WordProcessing-dokumentet. Ange NULL eller en tom sträng för att ta bort (rensa) lösenordet. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Tillåter att styra och tillämpa dokumentskyddsalternativ för WordProcessing-dokumentet i vilket format som helst som stödjer dokumentskydd. Som standard är det NULL – dokumentskydd kommer inte att användas. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Skapar och returnerar en fullständig kopia av denna instans av klassen WordProcessingSaveOptions |

### Anmärkningar

WordProcessingSaveOptions används i situationer när det finns en instans av klassen EditableDocument som innehåller redigerat dokumentinnehåll, och det krävs att spara detta innehåll till ett nytt dokument i WordProcessing-format.

### Se även

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
