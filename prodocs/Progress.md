# Progress (Geliştirme Günlüğü)

## Yapılan İşlemler & Kilometre Taşları
* **Hafta 1-2:** Fikir validasyonu, lojistik sektöründeki problemin tespiti ve sensör (ivme/gyro) veri setlerinin incelenmesi.
* **Hafta 3-4:** Python ile FastAPI backend omurgasının kodlanması. Scikit-learn model yapısının sisteme dahil edilmesi.
* **Hafta 5-6:** Flutter Web ile frontend ekranlarının tasarlanması, servis katmanlarının yazılması.
* **Hafta 7:** Backend sistemine Gemini API entegre edilerek yapay zekanın sürüş verilerini doğal dilde yorumlaması sağlandı.

## Karşılaşılan Zorluklar & Alınan Kararlar
* **Hata / Çakışma:** Projenin ilk aşamalarında frontend ve backend yapılarının aynı sunucu ortamında monolitik olarak çalıştırılması kararlaştırılmıştı ancak bağımlılık çakışmaları yaşandı.
* **Karar / Çözüm:** Sektör standardı olan **Decoupled (Ayrık) Mimari** yapısına geçiş yapıldı. Backend Render'da, Frontend ise Netlify üzerinde iki bağımsız uygulama olarak canlıya alındı. Bu sayede sistem kararlı bir yapıya kavuştu.