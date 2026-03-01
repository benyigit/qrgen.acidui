# SYS.QR_GEN

SYS.QR_GEN, **Acid UI** felsefesi temel alınarak geliştirilmiş, endüstriyel estetiğe ve retro-fütüristik tasarıma sahip modern bir QR kod oluşturucudur. 

Bu proje, terminal benzeri arayüzü, mono-space tipografisi ve asit yeşili (Acid Green) vurgularıyla kullanıcılarına hem eşsiz bir görsel deneyim sunar hem de girdiğiniz bağlantıları / metinleri anında yüksek çözünürlüklü QR kodlarına dönüştürmenizi sağlar.

![SYS.QR_GEN Preview](https://via.placeholder.com/800x400/000000/ccff00?text=SYS.QR_GEN+TERMINAL+ACTIVE)

## 🧪 Acid UI Nedir?
**Acid UI**, brutalist ve teknik UI öğelerini harmanlayan, fütüristik terminal arayüzlerinden ilham alan deneysel bir tasarım sistemidir. Keskin hatlar, karanlık arka planlar, ince neon ızgaralar ve monospaced (eş aralıklı) fontlar kullanarak sistem ve kullanıcı arasında doğrudan, süslemelerden uzak, "hacklenmiş" veya "ham" bir hissiyat yaratır.

Bu projede Acid UI'nin sunduğu şu bileşenler ve tasarım kuralları kullanılmıştır:
- **Asit/Neon Renk Paleti:** `#ccff00` (Acid Green) ve koyu terminal arka planları
- **Teknik Yüzeyler:** Çerçevelenmiş paneller, köşeli input alanları
- **Interaktif Feedback:** Terminal yanılsamasını güçlendiren yanıp sönen kursörler ve tıklandığında parlayan butonlar
- **Bileşenler:** `acidui-core` paketi kullanılarak özelleştirilmiş buton, kart (card) ve girdi (input) mimarileri.

## 🚀 Özellikler
- **Anında QR Oluşturma:** Linki yazdığınız anda dinamik olarak QR kod üretilir.
- **Kişiselleştirme:** QR kodu için dilediğiniz **Ön Plan** (FG_HEX) ve **Arka Plan** (BG_HEX) rengini seçebilirsiniz.
- **Geçmiş Desteği (Cache):** Yerel depolama kullanarak oluşturduğunuz son QR kodlarını "CACHE_DATA" paneli altında saklar ve tek tıkla geri yükler.
- **Hızlı Dışa Aktarım:** Oluşturduğunuz QR kodlarını `EXTRACT_PNG` butonu ile yüksek kalitede bilgisayarınıza indirebilirsiniz.

## 🛠 Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin.

### 1 Gereksinimleri Yükleme
Projenin bağımlılıklarını kurmak için terminalinizde proje dizinindeyken aşağıdaki komutu çalıştırın:
```bash
npm install
```

*(Eğer `acidui-core` paketiyle ilgili eksik bir modül uyarısı alırsanız `npm i acidui-core` komutunu kullanarak tekrar yükleyebilirsiniz.)*

### 2. Geliştirme Sunucusunu Başlatma
Bağımlılıklar indirildikten sonra, uygulamayı yerel ortamda çalıştırmak için:
```bash
npm run dev
```

### 3. Tarayıcıda Görüntüleme
Terminalde çıkan çıktıya bağlı olarak (Genellikle `http://localhost:5173/`), tarayıcınıza bu adresi yapıştırarak SYS.QR_GEN uygulamasını hemen kullanmaya başlayabilirsiniz. Kod üzerinde değişiklik yaptığınızda (örneğin renkleri kendinize uygun bir Acid rengiyle değiştirdiğinizde) sayfa otomatik olarak güncellenecektir.

## ⚙️ Yapı ve Teknolojiler
- **React.js / Vite:** Hızlı geliştirme ortamı.
- **Framer Motion:** Arayüz bileşenlerinde pürüzsüz animasyon geçişleri ve mikro etkileşimler için.
- **Lucide React:** Minimalist ve teknik sistem ikonları.
- **QR Code SVG:** Özelleştirilmiş ve vektör tabanlı QR render sistemi.
- **AcidUI Core:** Arayüz tasarımı iskeleti ve endüstriyel brutalist stillar.

---
*Terminal Closed. // STATUS: SYSTEM RUNNING*
