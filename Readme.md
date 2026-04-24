# 🧠 MyPIE Framework

**MyPIE**, **SCP: Secret Laboratory** için geliştirilmiş, EXILED benzeri ancak daha modüler ve optimize edilmiş bir eklenti çatısıdır.  
Harmony tabanlı olay sistemi, çok kaynaklı komut altyapısı, gelişmiş izin yönetimi ve zengin oyuncu API’si ile sunucunuza güçlü ve güvenli eklentiler yazmanızı sağlar.

---

## 🚀 Öne Çıkan Özellikler

- **Olay (Event) Motoru** – Öncelikli, iptal edilebilir ve hata yalıtımlı 35+ olay.
- **Komut Sistemi** – `[Command]` özniteliği ile Player / Console / RemoteAdmin desteği.
- **Zengin Oyuncu API’si** – `IPlayer` arayüzünde 100’den fazla özellik ve metot (sağlık, rol, envanter, efektler, teleport…).
- **Gelişmiş İzin Sistemi** – JSON tabanlı, grup ve kullanıcı bazlı, sınırsız özelleştirilebilir yetkilendirme.
- **Eklenti İzolasyonu** – Bir eklentide oluşan hata diğer eklentileri veya sunucuyu etkilemez.
- **LabAPI Entegrasyonu** – Tek bir Bootstrap DLL ile yüklenir, konfigürasyonu LabAPI yönetir.
- **Modüler Mimari** – API, Core, Hooks, Game ve Bootstrap katmanları bağımsız DLL’lerdir; kolayca güncellenebilir.

---

## ⚙️ Nasıl Çalışır?

MyPIE, **LabAPI** aracılığıyla sunucuya yüklenir.  
`MyPIE.Bootstrap.dll` LabAPI’nin eklenti klasörüne yerleştirilir; çekirdek kütüphaneler (`MyPIE.API.dll`, `MyPIE.Core.dll` vb.) ise **sunucunun ana dizininde** oluşturulan `MyPIE/` klasöründe bulunur.

İlk çalıştırmada gerekli tüm klasörler ve yapılandırma dosyaları otomatik olarak oluşturulur.

---

## 📄 Lisans

MIT Lisansı altında dağıtılmaktadır.  
Daha fazla bilgi için [`LICENSE`](LICENSE) dosyasına bakın.

---

## 🤝 İletişim

- Sorunlar ve öneriler için [GitHub Issues](https://github.com/MyPIE/MyPIE/issues) sayfasını kullanın.
- Belgeler ve daha fazlası için [Wiki](https://github.com/MyPIE/MyPIE/wiki) sayfasını ziyaret edin (yakında).

---

**MyPIE Ekibi tarafından ❤️ ile geliştirilmiştir.**
