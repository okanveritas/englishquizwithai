# Katkıda Bulunma Rehberi

YDS Hazırlık Platformu'na katkıda bulunduğunuz için teşekkür ederiz! Bu rehber, projeye nasıl katkıda bulunabileceğinizi açıklar.

## 🚀 Hızlı Başlangıç

1. **Repository'yi Fork edin**
2. **Lokal olarak clone edin**
   ```bash
   git clone https://github.com/yourusername/yds-platform.git
   cd yds-platform
   ```
3. **Basit HTTP server başlatın**
   ```bash
   python -m http.server 8000
   # veya
   npx serve .
   ```

## 📋 Katkı Türleri

### 🐛 Bug Reports
- Issue template'ini kullanın
- Ayrıntılı açıklama sağlayın
- Hata tekrarlanabilir olmalı
- Ekran görüntüleri ekleyin

### ✨ Feature Requests
- Detaylı açıklama yapın
- Use case'leri belirtin
- Mockup'lar ekleyin (opsiyonel)

### 🔧 Code Contributions

#### Pull Request Süreci
1. Feature branch oluşturun
   ```bash
   git checkout -b feature/amazing-feature
   ```
2. Değişikliklerinizi yapın
3. Test edin
4. Commit mesajlarını düzenli yazın
5. Push edin
   ```bash
   git push origin feature/amazing-feature
   ```
6. Pull Request oluşturun

#### Coding Standards
- **JavaScript**: ES6+ kullanın
- **CSS**: Modern CSS (Grid, Flexbox)
- **HTML**: Semantic HTML5
- **Accessibility**: WCAG 2.1 uyumlu
- **Comments**: Karmaşık logic'leri açıklayın

## 🎯 Geliştirme Alanları

### Öncelikli Alanlar
- **Mobile UX**: Touch interactions
- **Accessibility**: Screen reader support
- **Performance**: Loading optimizations
- **SEO**: Meta tags ve structured data

### Yeni Özellik Fikirleri
- **Offline Support**: ServiceWorker
- **Statistics**: Detailed analytics
- **Social Features**: Progress sharing
- **Export Options**: PDF/Excel export

## 🧪 Test Etme

### Manual Testing
- [ ] Desktop browsers (Chrome, Firefox, Safari)
- [ ] Mobile devices (iOS, Android)
- [ ] Accessibility tools
- [ ] Different screen sizes

### Test Checklist
- [ ] Quiz functionality
- [ ] Flashcard system
- [ ] Navigation
- [ ] Theme switching
- [ ] Responsive design

## 📝 Dokümantasyon

### README Güncellemeleri
- Yeni özellikler için açıklama ekleyin
- Screenshot'ları güncelleyin
- Installation talimatlarını kontrol edin

### Code Documentation
- JSDoc comments kullanın
- Complex functions için örnekler
- API documentation güncel tutun

## 🌍 Internationalization

### Desteklenen Diller
- **Türkçe** (Ana dil)
- **İngilizce** (Gelecek için hazır)

### Yeni Dil Ekleme
1. Language dosyası oluşturun
2. Translation keys ekleyin
3. Language selector implementasyonu

## 🔒 Security

### Güvenlik Politikaları
- XSS prevention
- Input validation
- Secure data handling
- Privacy compliance

### Reporting Security Issues
Security issue'ları public issue olarak değil, doğrudan maintainer'lara bildirin.

## 📊 Code Review

### Review Kriterleri
- **Functionality**: Kod çalışıyor mu?
- **Performance**: Optimized mi?
- **Maintainability**: Okunabilir mi?
- **Testing**: Test edilmiş mi?

### Review Process
1. Automatic checks
2. Manual code review
3. Testing verification
4. Documentation review

## 🎉 Recognition

### Contributors
Tüm contributor'lar README'de credit alır.

### Commit Attribution
Meaningful commit mesajları yazmayı unutmayın:
```bash
git commit -m "feat: add dark theme toggle functionality"
git commit -m "fix: resolve mobile navigation issue"
git commit -m "docs: update installation instructions"
```

## 📞 İletişim

### Sorularınız için:
- **GitHub Issues**: Bug reports ve feature requests
- **GitHub Discussions**: Genel sorular ve tartışmalar
- **Pull Request Comments**: Code-specific sorular

### Response Times
- **Issues**: 24-48 saat içinde yanıt
- **Pull Requests**: 3-5 gün içinde review
- **Security Issues**: 24 saat içinde yanıt

## 🏆 Best Practices

### Git Workflow
- **Branch naming**: `feature/`, `bugfix/`, `hotfix/`
- **Commit messages**: Conventional commits
- **Pull requests**: Küçük, focused changes

### Code Organization
- **Modularity**: Single responsibility
- **Reusability**: DRY principle
- **Comments**: Self-documenting code

## 📅 Release Cycle

### Versioning
Semantic versioning kullanıyoruz: `MAJOR.MINOR.PATCH`

### Release Schedule
- **Major releases**: 6 ayda bir
- **Minor releases**: Aylık
- **Patch releases**: Gerektiğinde

---

**Katkılarınız için teşekkürler! 🙏**