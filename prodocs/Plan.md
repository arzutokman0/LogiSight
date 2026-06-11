# Proje Planı & Kullanıcı Hikayeleri (User Stories)

## 1. Kullanıcı Hikayeleri
* **Bir Filo Yöneticisi olarak;** sisteme güvenli bir şekilde giriş yapabilmek istiyorum, böylece paneli yetkisiz kişilerden koruyabilirim.
* **Bir Filo Yöneticisi olarak;** başlatılan bir seferin sensör analiz sonuçlarını görebilmek istiyorum, böylece sürücünün risk durumunu anlayabilirim.
* **Bir Sistem Yapısı olarak;** gelen 6 eksenli sensör verilerini anında ML modeline göndermek ve çıkan analizi kullanıcıya sunmak istiyorum.

## 2. Teknik Geliştirme Adımları
* [x] FastAPI ile backend altyapısının kurulması ve login/analiz endpoint'lerinin yazılması.
* [x] Scikit-learn modelinin backend sistemine entegre edilmesi.
* [x] Google Gemini API bağlantısının kurulması ve prompt optimizasyonu.
* [x] Flutter Web ile arayüz tasarımlarının ve API entegrasyonlarının tamamlanması.
* [x] Backend sisteminin Render, Frontend yapısının Netlify üzerinde canlıya alınması.