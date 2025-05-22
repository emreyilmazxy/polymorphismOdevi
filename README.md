# 📐 Polymorphism Uygulaması – Kare, Dikdörtgen ve Dik Üçgen

## 🎯 Amaç
Bu örnek, C# dilinde kalıtım (inheritance) ve çok biçimlilik (polymorphism) kavramlarını sade bir şekilde göstermeyi amaçlar.

## 🏗️ Yapı
- `BaseGeometrikSekil`: Ortak özellikleri ve metodu içerir (genişlik, yükseklik, alan hesaplama).
- `Kare` ve `Dikdortgen`: Aynı hesaplama yöntemini kullandıkları için base sınıfın metodunu kullanır.
- `DikUcgen`: Alan hesaplaması farklı olduğu için `AlanHesapla()` metodunu override eder.

## 🚀 Çalışma Mantığı
Her şekil için `AlanHesapla()` çağrılır. `virtual` ve `override` kullanılarak polymorphism sağlanır. Alanlar ekrana yazdırılır.

## 📦 Kullanım
- Console uygulaması olarak çalışır.
- Her şekilden bir nesne oluşturulup ölçüler atanır.
- Alanlar hesaplanarak ekrana yazdırılır.

## 🧠 Kazanımlar
- Kalıtım (inheritance)
- Virtual & Override kullanımı
- Çok biçimlilik (polymorphism)
