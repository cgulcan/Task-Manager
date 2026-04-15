# ⚡ HF IT Görev Takip

Halk Faktoring IT Birimi Görev Takip Uygulaması.
Firebase Firestore + GitHub Pages + PWA.

## Dosyalar

- `index.html` — Tüm uygulama (Babel YOK, saf JavaScript)
- `manifest.json` — PWA desteği
- `icon-192.png` / `icon-512.png` — Uygulama ikonu
- `.github/workflows/deploy.yml` — Otomatik deploy

## Kurulum

1. Firebase Console → Proje oluştur → Firestore aç → Web app ekle
2. `index.html` içindeki `FIREBASE_CONFIG` bölümünü doldur
3. GitHub'da repo oluştur → dosyaları yükle
4. Settings → Pages → Source: **GitHub Actions**
5. iPhone Safari → URL aç → Paylaş → Ana Ekrana Ekle

## Güncelleme

```bash
git add . && git commit -m "güncelleme" && git push
```

Halk Faktoring IT © 2026
