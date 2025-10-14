# Aslan Energy Website - GitHub Pages Deployment Script

## Adımlar:

### 1. GitHub'da Yeni Repository Oluşturun
- GitHub hesabınıza giriş yapın
- "New repository" tıklayın  
- Repository adı: `aslan-energy-website` (veya istediğiniz ad)
- ✅ **Public** olarak ayarlayın (GitHub Pages için gerekli)
- ✅ "Add a README file" seçeneğini İŞARETLEMEYİN (zaten hazırladık)
- "Create repository" tıklayın

### 2. Bu Klasördeki Dosyaları GitHub'a Yükleyin

Bu klasördeki tüm dosyaları yeni oluşturduğunuz repository'e yükleyin:

```
github-pages-deploy/
├── index.html          # Ana sayfa (Vue.js build)
├── css/               # Stil dosyaları
├── js/                # JavaScript dosyaları  
├── README.md          # Repository açıklaması
├── .nojekyll          # GitHub Pages ayarı
└── .gitignore         # Git ignore dosyası
```

### 3. GitHub Pages'i Etkinleştirin

1. Repository'nizin **Settings** sekmesine gidin
2. Sol menüden **Pages** seçin
3. Source: **Deploy from a branch** seçin
4. Branch: **main** seçin
5. Folder: **/ (root)** seçin  
6. **Save** tıklayın

### 4. Website Adresi

5-10 dakika sonra website şu adreste erişilebilir olacak:
`https://korayaslaan.github.io/aslanenergywebgenel/`

## 🔄 Güncelleme İşlemi

Website'de değişiklik yaptığınızda:

1. Bu projede `npm run build` çalıştırın
2. `docs/` klasörünün içeriğini GitHub repository'sine yükleyin
3. GitHub otomatik olarak website'i güncelleyecek

## 📝 Notlar

- ✅ Tüm statik dosyalar optimize edildi
- ✅ GitHub Pages için hazırlandı
- ✅ Responsive tasarım test edildi
- ✅ Cross-browser uyumluluğu sağlandı

## 🎯 Sonuç

Bu klasördeki dosyalar doğrudan GitHub Pages'de çalışmaya hazırdır!