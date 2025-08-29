# 📚 NetCoreAI Project 14 - Multi-Level Text Summarizer

Bu proje, **.NET Console Application** kullanarak **OpenAI Chat Completions API** üzerinden farklı seviyelerde metin özetleme yapmaktadır.  
Kullanıcıdan girilen uzun metin 3 farklı seviyede özetlenir: **Kısa, Orta, Detaylı**.  

---

## 🛠️ Kullanılan Teknolojiler
- .NET 8 / 9 Console Application  
- OpenAI API (Chat Completions - `gpt-3.5-turbo`)  
- HttpClient (API isteği için)  
- Newtonsoft.Json (JSON serialize/deserialize)  

---

## 📂 Proje Yapısı
- `Program.cs` → Kullanıcıdan metin alır, OpenAI API’ye gönderir ve farklı seviyelerde özet döndürür.  
- `.csproj` → Proje yapılandırma dosyası  

---

## ⚙️ Kurulum ve Çalıştırma
1. Repo’yu klonla:
   git clone https://github.com/kullaniciadiniz/NetCoreAI_Project_14_TextSummarizer.git
   cd NetCoreAI_Project_14_TextSummarizer
Program.cs içinde kendi OpenAI API anahtarını ekle:
private static readonly string apiKey = "YOUR_API_KEY";
Konsol uygulamasını çalıştır:
dotnet run
Konsolda örnek kullanım:
Uzun metninizi veya makalenizi giriniz:
> Yapay zeka sistemleri günümüzde birçok alanda kullanılmaktadır...

Girmiş olduğunuz metin AI tarafından özetleniyor...

Özetler
----------------------
** Kısa Özet: ** Yapay zeka birçok alanda yaygın olarak kullanılmaktadır.
----------------------
** Orta Uzunlukta Özet: ** Yapay zeka günümüzde sağlık, eğitim ve ticaret gibi alanlarda kullanılmakta; süreçleri hızlandırmakta ve verimliliği artırmaktadır.
----------------------
** Detaylı Özet: ** apay zeka, geniş kapsamlı kullanım alanlarıyla modern dünyanın ayrılmaz bir parçası haline gelmiştir. Sağlıkta teşhis, eğitimde kişiselleştirilmiş öğrenme ve iş dünyasında karar destek sistemleri gibi uygulamalarla toplumsal fayda sağlamaktadır.
----------------------

✨ Özellikler
✔️ Kullanıcıdan uzun metin alır

✔️ OpenAI API ile farklı seviyelerde özet çıkarır

✔️ Kısa, Orta ve Detaylı özet üretir

✔️ Hata durumlarını konsola yazdırır﻿
