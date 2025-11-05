# 🎵 Youtube2mp3 & DBKaragaConverter

> **YouTube videolarını MP3’e dönüştürün veya DBKaragaConverter ile alternatif işlemler gerçekleştirin.**  
> “Youtube2mp3” sade bir YouTube → MP3 dönüştürücü; “DBKaragaConverter” ise diğer dönüşüm ihtiyaçları için alternatif bir web uygulaması.

---

## 📘 İçindekiler  
- [🚀 Tanıtım](#-tanıtım)  
- [✨ Özellikler](#-özellikler)  
- [🧩 Teknolojiler](#-teknolojiler)  
- [⚙️ Kurulum](#️-kurulum)  
- [🪄 Kullanım](#-kullanım)  
- [💡 Örnek](#-örnek)  
- [🔗 Web Uygulamaları](#-web-uygulamalar)  
- [🤝 Katkıda Bulunma](#-katkıda-bulunma)  
- [📄 Lisans](#-lisans)  
- [⚠️ Yasal Uyarı](#️-yasal-uyarı)

---

## 🚀 Tanıtım  
**Youtube2mp3**, YouTube video bağlantısını alıp doğrudan MP3 formatına dönüştüren sade bir web uygulamasıdır.  
🔗 **Repo:** https://github.com/bykaraga/Youtube2mp3  
![image](https://github.com/user-attachments/assets/219d6baf-cd0a-44f1-bae9-37279003e005)
  
**DBKaragaConverter**, alternatif bir dönüştürme uygulamasıdır; “dbkaragaconventer.com” adresinden erişilebilir.  
🔗 **Web uygulaması:** https://dbkaragaconventer.com/  

---

## ✨ Özellikler  
- YouTube URL’sinden hızlı MP3 dönüştürme (Youtube2mp3)  
- Alternatif dönüştürme işlemleri için DBKaragaConverter web uygulaması  
- Karanlık (dark) tema arayüz  
- Minimal, reklamsız deneyim  
- Tek tıkla indirme  
- Basit yapı — kolay özelleştirilebilir

---

## 🧩 Teknolojiler  
| Katman | Teknoloji |
|--------|-----------|
| 🖥️ Arayüz (Frontend)         | HTML5, CSS3, JavaScript |
| ⚙️ Sunucu (Backend)         | Node.js tabanlı yapı (örnek) |
| 📦 Bağımlılıklar             | `yt-dlp`, `express`, `ffmpeg` (muhtemel) |
| 🎨 Tema                     | Dark mode destekli sade tasarım |

---

## ⚙️ Kurulum  
> Geliştirme ortamı için Node.js (>=18) ve npm kurulu olmalıdır.

```bash
# Depoyu klonla
git clone https://github.com/bykaraga/Youtube2mp3.git
cd Youtube2mp3

# Bağımlılıkları yükle
npm install

# Geliştirme sunucusunu başlat
npm run dev

# Üretim için derleme
npm run build
