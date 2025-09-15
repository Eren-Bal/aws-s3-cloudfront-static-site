# AWS S3 + CloudFront Statik Web Sitesi

Bu proje AWS üzerinde **S3** ve **CloudFront** kullanılarak statik bir web sitesi deploy etme sürecini göstermektedir.

## Kullanılan Servisler
- **Amazon S3** → Statik dosyaların (HTML, CSS, JS) host edilmesi
- **Amazon CloudFront** → İçeriğin CDN üzerinden global dağıtımı
- **IAM & Bucket Policy** → Public erişim ayarları

## Adımlar
1. AWS S3 bucket oluşturuldu.
2. Statik web site hosting aktif edildi.
3. `index.html` dosyası yüklendi.
4. CloudFront dağıtımı oluşturuldu.
5. CloudFront URL üzerinden siteye erişim sağlandı.
