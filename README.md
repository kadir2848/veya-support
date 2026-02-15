# Veya Static Support Site

Bu repo, GitHub Pages için hazırlanmış statik destek sitesidir.

## Dosyalar

- `index.html` → destek ana sayfası
- `privacy.html` → gizlilik politikası
- `terms.html` → kullanım koşulları
- `styles.css` → ortak stil dosyası

## Placeholder Alanları

Yayınlamadan önce şu alanları güncelleyin:

- `SUPPORT_EMAIL_PLACEHOLDER`
- `DEVELOPER_NAME_PLACEHOLDER`
- `LAST_UPDATED_PLACEHOLDER`
- `POLICY_VERSION_PLACEHOLDER`

## GitHub Pages Deploy

1. Bu dosyaları bir GitHub repository içine yükleyin.
2. Repository → **Settings** → **Pages** bölümüne gidin.
3. **Build and deployment** altında:
   - Source: **Deploy from a branch**
   - Branch: **main** (veya kullandığınız branch), Folder: **/(root)**
4. Kaydedin.
5. 1–3 dakika sonra yayın linki oluşur.

## Test Kontrolü (Öneri)

- iPhone Safari’da `index.html`, `privacy.html`, `terms.html` açıp kontrol edin.
- TR/EN butonlarının çalıştığını doğrulayın.
- E-posta linklerinin doğru adrese gittiğini test edin.
- App Store Connect’e support URL ve privacy policy URL olarak yayın URL’lerini girin.

