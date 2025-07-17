# 🎵 Spotify Claude Entegrasyonu

Bu proje, Claude AI masaüstü uygulaması ile Spotify API'yi entegre ederek müzik verilerine yapay zeka ile kolayca erişim sağlar. Claude'un **MCP (Microservice Command Protocol)** sistemi üzerinden Spotify bilgilerini alabilir, analiz edebilir ve kişisel müzik deneyimini zenginleştirebilirsin.

---

## 🚀 Özellikler

- Spotify şarkı, albüm, playlist bilgisi sorgulama  
- Kullanıcıya özel müzik önerileri  
- MCP üzerinden Claude ile etkileşim  

---

## 📁 Proje Yapısı

spotify-mcp/
├── README.md
├── mcp.config.example.json
└── .gitignore



---

## ⚙️ Kurulum

1. Claude Desktop uygulamasını bilgisayarına yükle.  
2. `mcp.config.example.json` dosyasını indirip kendi Spotify API bilgilerinle doldur.  
3. Dosyanın adını `mcp.config.json` olarak değiştir.  
4. `mcp.config.json` dosyasını şu klasöre yerleştir:  

C:\Users<kullanıcı_adı>\AppData\Roaming\Claude\


---

## 🔐 Gerekli API Bilgileri

- `SPOTIFY_CLIENT_ID`  
- `SPOTIFY_CLIENT_SECRET`  
- `SPOTIFY_REDIRECT_URI`  

Spotify Developer Dashboard’dan bu bilgileri edinebilirsin:  
https://developer.spotify.com/dashboard/

---

## 📌 Dikkat!

- Gerçek API anahtarlarını içeren `mcp.config.json` dosyasını **GitHub’a yükleme!**  
- Bunun yerine, `mcp.config.example.json` dosyasını paylaş ve gerçek bilgileri oraya koyma.  
- `.gitignore` dosyasına `mcp.config.json` ve `.env` dosyalarını ekleyerek koru.

---

## 🧠 Kullanım

Claude üzerinden Spotify verileri için sorular sorabilir, müzik listeleri ve şarkılar hakkında bilgi alabilirsin.

---

## 👩‍💻 Geliştiren

Hayat Aydın — 2025
