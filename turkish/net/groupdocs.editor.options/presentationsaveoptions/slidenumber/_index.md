---
title: "SlideNumber"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Düzenlenmiş slaytı yeni tek slaytlık bir sunum oluşturmak yerine mevcut bir sunuma eklemeye olanak tanır; bu varsayılan davranıştır. Slayt numarası, Editor sınıfında yüklü sunumdaki slaytların 1 tabanlı numarasıdır. Değer 0 ise, yeni sunum tek düzenlenmiş slayt ile oluşturulur. Değer sıfırdan büyük veya küçük ve Editor sınıfında geçerli bir sunum yüklüyse, giriş EditableDocument örneğinde depolanan düzenlenmiş slayt bu sunuma eklenir."
type: docs
weight: 50
url: /tr/net/groupdocs.editor.options/presentationsaveoptions/slidenumber/
---
## PresentationSaveOptions.SlideNumber property

Yeni tek slaytlı bir sunum oluşturmak yerine (varsayılan davranış) düzenlenen slaytı mevcut sunuma eklemeye izin verir. Slayt numarası, Editor sınıfında yüklü sunumdaki slaytların 1 tabanlı numarasıdır. 0 ise (varsayılan değer), yeni sunum tek düzenlenmiş slayt ile oluşturulur. Sıfırdan büyük veya küçük ise ve Editor sınıfında geçerli bir sunum yüklüyse, giriş EditableDocument örneğinde depolanan düzenlenmiş slayt bu sunuma eklenecektir.

```csharp
public int SlideNumber { get; set; }
```

### Açıklamalar

SlideNumber tam sayı özelliği, varsayılan durumda (ayrılmış değer '0') değilse, bir slayt numarasını temsil eder; yani 1'den başlar, sıfırdan değil ve maksimum değeri bir sunumdaki mevcut tüm slaytların sayısıdır. Ancak, belirtilen değer tüm slaytların sayısından büyükse, GroupDocs.Editor bunu son slaytı işaretleyecek şekilde ayarlar. Negatif değerler de izin verilir ve slaytları sondan sayar. Örneğin, "-1" bir sunumdaki son slaytı, "-2" ise sondan bir önceki slaytı ifade eder, vb. Pozitif değerlerde olduğu gibi, negatif slayt numarası verilen sunumdaki toplam slayt sayısını aşarsa, ilk slayta ayarlanır. [`InsertAsNewSlide`](../insertasnewslide) boolean özelliği bu özellik ile sıkı bir şekilde ilişkilidir.

### Örnekler

Verilen sunumda 5 slayt vardır: SlideNumber = 0; — verilen sunumu yok say, yeni bir sunum oluştur ve düzenlenmiş slaytı içine yerleştir. SlideNumber = 1; — ilk slaytı düzenlenmiş slayt ile değiştir. SlideNumber = 2; — ikinci slaytı düzenlenmiş slayt ile değiştir. SlideNumber = 5; — son (5.) slaytı düzenlenmiş slayt ile değiştir. SlideNumber = 6; — son (5.) slaytı düzenlenmiş slayt ile değiştir, çünkü 6, 5'ten büyük ve bu yüzden ayarlanır. SlideNumber = -1; — son (5.) slaytı düzenlenmiş slayt ile değiştir, çünkü "-1" "son mevcut" anlamına gelir. SlideNumber = -2; — 4. slaytı düzenlenmiş slayt ile değiştir. SlideNumber = -3; — 3. slaytı düzenlenmiş slayt ile değiştir. SlideNumber = -4; — 2. slaytı düzenlenmiş slayt ile değiştir. SlideNumber = -5; — ilk slaytı düzenlenmiş slayt ile değiştir. SlideNumber = -6; — ilk slaytı düzenlenmiş slayt ile değiştir, çünkü "-6" 5'ten büyük ve bu yüzden ayarlanır.

### Ayrıca Bakınız

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
