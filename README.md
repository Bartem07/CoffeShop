# Jelibon Kafe - Modern Kahve Dükkanı Web Sitesi

Bu proje, Figma tasarımından HTML ve CSS kullanılarak oluşturulmuş modern ve responsive bir kahve dükkanı web sitesidir.

## 🚀 Özellikler

- **Modern Tasarım**: Figma tasarımına sadık kalınarak oluşturulmuş
- **Responsive**: Tüm cihazlarda mükemmel görünüm
- **Hamburger Menü**: Mobil cihazlarda kullanıcı dostu navigasyon
- **4'lü Grid Düzeni**: Menü ve özellikler bölümünde 4'er öğe
- **Türkçe İçerik**: Tamamen Türkçe içerik ve yerelleştirme
- **Smooth Animations**: Yumuşak geçişler ve hover efektleri
- **SEO Optimized**: Arama motorları için optimize edilmiş
- **Fast Loading**: Hızlı yükleme süreleri

## 📱 Responsive Tasarım

Web sitesi aşağıdaki cihazlarda test edilmiş ve optimize edilmiştir:
- **Desktop (1200px+)**: 4'lü grid düzeni
- **Large Desktop (1400px+)**: Tam genişlik
- **Tablet (992px - 1199px)**: 3'lü ve 2'li grid düzeni
- **Mobile Large (768px - 991px)**: Hamburger menü aktif
- **Mobile Medium (576px - 767px)**: Tek sütun düzeni
- **Mobile Small (400px - 575px)**: Kompakt tasarım

## 🎨 Bölümler

1. **Header**: Hamburger menü ile navigasyon
2. **Hero**: Ana başlık ve çağrı-eylem butonu
3. **Hakkımızda**: Şirket hakkında bilgiler
4. **Menü**: 4'lü grid ile kahve çeşitleri
5. **Neden Biz**: 4'lü grid ile özellikler
6. **Müşteri Yorumları**: Testimonial bölümü
7. **Özel Teklif**: Subscribe bölümü
8. **Newsletter**: E-posta aboneliği
9. **Footer**: İletişim bilgileri ve sosyal medya

## 🛠️ Teknolojiler

- **HTML5**: Semantic markup
- **CSS3**: Modern CSS özellikleri
  - CSS Grid (4'lü düzen)
  - Flexbox
  - CSS Variables
  - Media Queries
  - Animations & Transitions
- **JavaScript**: Hamburger menü fonksiyonalitesi
- **Google Fonts**: Playfair Display & Clicker Script
- **Responsive Design**: Mobile-first approach

## 📁 Dosya Yapısı

```
CoffeShop/
├── index.html          # Ana HTML dosyası (hamburger menü dahil)
├── style.css           # Ana CSS dosyası (responsive tasarım)
├── assets/
│   └── img/           # Tüm görseller (Figma'dan indirilmiş)
│       ├── hero-bg.jpg
│       ├── about-img.jpg
│       ├── cappuccino.jpg
│       ├── chai-latte.jpg
│       ├── macchiato.jpg
│       ├── espresso.jpg
│       ├── coffee-beans-icon.png
│       ├── badge-icon.png
│       ├── coffee-cup-icon.png
│       ├── best-price-icon.png
│       ├── subscribe-bg.jpg
│       ├── testimonial-avatar.jpg
│       ├── coffee-blast.png
│       ├── coffee-bean.png
│       ├── coffee-cup.png
│       ├── footer-coffee.png
│       └── footer-bg.jpg
└── README.md           # Bu dosya
```

## 🚀 Kurulum ve Çalıştırma

1. Projeyi bilgisayarınıza indirin
2. `index.html` dosyasını web tarayıcınızda açın
3. Veya bir local server kullanın:
   ```bash
   # Python ile
   python -m http.server 8000
   
   # Node.js ile
   npx serve .
   
   # Live Server (VS Code Extension)
   ```

## 🎯 Responsive Özellikler

### Hamburger Menü
- 768px altında aktif
- Smooth animasyonlar
- Tam ekran overlay
- Menü dışına tıklayınca kapanır
- Link tıklandığında otomatik kapanır

### Grid Düzenleri
- **Desktop**: 4'lü grid (menü ve özellikler)
- **Tablet**: 3'lü ve 2'li grid
- **Mobile**: Tek sütun

### CSS Variables
Kolay tema değişikliği için CSS custom properties:
```css
:root {
  --color-primary: #603809;
  --color-secondary: #F9C06A;
  --color-white: #FFFFFF;
  /* ... diğer değişkenler */
}
```

### Responsive Breakpoints
- **1400px+**: Large Desktop
- **1200px - 1399px**: Desktop (3'lü grid)
- **992px - 1199px**: Tablet (2'li grid)
- **768px - 991px**: Mobile Large (hamburger menü)
- **576px - 767px**: Mobile Medium (tek sütun)
- **400px - 575px**: Mobile Small (kompakt)

## 🎨 Renk Paleti

- **Primary**: #603809 (Kahve Kahverengi)
- **Secondary**: #F9C06A (Altın Sarısı)
- **Background**: #FFFEFC (Krem Beyaz)
- **Text**: #707070 (Gri)
- **Cards**: #FFF9F1 (Açık Krem)

## 📱 Mobil Optimizasyonlar

- Touch-friendly butonlar
- Optimized font sizes
- Hamburger menü
- Swipe gestures ready
- Fast loading images
- Minimal JavaScript

## 🔧 JavaScript Fonksiyonları

- Hamburger menü toggle
- Smooth scroll navigation
- Menu auto-close
- Body scroll prevention
- Click outside to close

## 📞 İletişim

Proje hakkında sorularınız için:
- Email: jelibonkafe@mail.com
- Website: www.jelibonkafe.com
- GitHub: [CoffeShop Repository](https://github.com/Bartem07/CoffeShop)

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

---

**Jelibon Kafe** - En iyi kahve deneyimi için! ☕

### 🎉 Yeni Özellikler

- ✅ Hamburger menü ile tam responsive tasarım
- ✅ 4'lü grid düzeni (desktop)
- ✅ Smooth animasyonlar
- ✅ Mobile-first approach
- ✅ Touch-friendly interface
- ✅ Modern CSS3 özellikleri