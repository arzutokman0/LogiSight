# 🛠️ Tech Stack & Yapay Zeka Seçim Gerekçeleri

## Kullanılan Teknolojiler & Servisler
* **Frontend:** Flutter Web (Dart) - *Barındırma: Netlify*
* **Backend:** Python, FastAPI, Uvicorn - *Barındırma: Render*
* **Makine Öğrenmesi (ML):** Scikit-learn (Sürücü davranış sınıflandırması ve anormallik tespiti için).
* **Büyük Dil Modeli (LLM):** Google Gemini API (Gelişmiş veri yorumlama ve doğal dil raporlama için).

## Seçim Gerekçeleri
* **FastAPI:** Asenkron veri işleme yeteneği sayesinde yoğun sensör verilerini minimum gecikmeyle yönetebilmektedir.
* **Flutter Web:** Tek bir kod tabanı kullanarak ileride projeyi hızlıca yerel mobil uygulamalara (iOS/Android) dönüştürme esnekliği sunmaktadır.
* **Ayrık (Decoupled) Mimari:** Frontend ve backend yapılarının tamamen bağımsız kurgulanması, sistemin ölçeklenebilirliğini artırmakta ve ileride farklı platformlara (örn. araç içi donanımlar) hizmet verebilmesini kolaylaştırmaktadır.

## Geliştirme Sürecinde AI Kullanımı
Geliştirme aşamasında yapay zeka asistanları aktif bir "Pair Programmer" olarak kullanılmıştır. Özellikle mimari kararların alınmasında, karmaşık deployment (canlıya alma) süreçlerinin yönetiminde ve Git branch çakışmalarının çözülmesinde LLM desteğinden yararlanılmıştır.