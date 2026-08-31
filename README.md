# 📻 Quansheng UV-K5 / K6 / 5R Plus - Türkçe Firmware [TA1EEI]

Bu proje, popüler [Egzumer](https://github.com/egzumer/uv-k5-firmware-custom) firmware'inin **tamamen Türkçe menü ve arayüze dönüştürülmüş**, gereksiz modüllerden arındırılarak stabilize edilmiş sürümüdür.
Bu sürümde %95'in üzerinde bir çeviri oranı vardır. Gizli özelliklerin bazıların Türkçe Çeviri bulunmamaktadır.

---

## ✨ Yapılan Değişiklikler ve Özellikler

- 🇹🇷 **Tamamen Türkçe Menü:** Tüm ana menü başlıkları, alt parametreler (`KPL`, `AC`, `DSK`, `YKSK` vb.) ve ekran uyarıları Türkçeleştirildi.
- ⚡ **Optimize Edilmiş Hafıza:** Flash hafızayı rahatlatmak ve takılmaları önlemek adına gereksiz/kullanılmayan DTMF arama modülleri kapatıldı.
- 🛠️ **Gelişmiş Özellikler:**
  - Genişletilmiş bant desteği ve spektrum analizörü
  - AM modülasyon iyileştirmesi (AM Fix)
  - Özel tuş atamaları (F1, F2 kısa ve uzun basma)
  - Batarya voltaj/yüzde kalibrasyonu ve göstergeleri

---

## 🚀 Web Üzerinden Yükleme (En Kolay Yol)

Telsizinize herhangi bir program kurmadan Chrome veya Edge tarayıcısı üzerinden yükleyebilirsiniz:

1. Telsizi kapatın.
2. **PTT tuşuna basılı tutarak** telsizi açın (Fener LED'i sabit yanacak, ekran karanlık kalacaktır).
3. Programlama kablosunu bilgisayara ve telsize tam oturacak şekilde takın.
4. **[UV Tools Web Flasher](https://egzumer.github.io/uvtools/)** sayfasına gidin.
5. `Releases` kısmından indirdiğiniz **`firmware.packed.bin`** dosyasını seçip **Flash Firmware** butonuna tıklayın.

---

## 📦 Manuel Derleme (GitHub Actions)

Kendi değişikliklerinizi yapmak isterseniz:
1. Bu repoyu fork'layın.
2. `src/ui/menu.c` veya `Makefile` üzerinde dilediğiniz ayarları yapın.
3. Değişiklikleri kaydettiğinizde GitHub Actions otomatik olarak yeni `.bin` dosyanızı derleyip **Actions -> Artifacts** altında sunacaktır.

---

## ⚠️ Sorumluluk Reddi ve Teşekkür

Bu yazılım açık kaynaklıdır ve amatör telsizcilik kullanımına uygundur. Mevzuat gereği telsiz lisansınızın bulunmadığı frekanslarda gönderme (TX) yapmayınız.

* **Orijinal Proje:** [DualTachyon](https://github.com/DualTachyon/uv-k5-firmware) & [Egzumer](https://github.com/egzumer/uv-k5-firmware-custom)
* **Türkçeleştirme & Düzenleme:** [WaiiXD](https://github.com/WaiiXD) [TA1EEI]
