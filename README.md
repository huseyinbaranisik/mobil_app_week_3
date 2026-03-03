# Next.js & Capacitor Projesi

Bu proje, mobil ve web platformlarında çalışacak şekilde tasarlanmış, modern teknolojilerle geliştirilmiş bir uygulamadır. Next.js gücünü Capacitor'ın mobil yetenekleriyle birleştirir.

## 🚀 Öne Çıkan Özellikler

*   **Modern Web Yapısı:** Next.js 15 (App Router) ile hızlı ve optimize edilmiş deneyim.
*   **Mobil Uyumluluk:** Capacitor entegrasyonu sayesinde tek kod tabanıyla Android/iOS desteği.
*   **Arayüz Bileşenleri:** Radix UI ve Tailwind CSS ile erişilebilir ve şık tasarım.
*   **Animasyonlar:** Framer Motion ile akışkan kullanıcı etkileşimleri.
*   **Backend Entegrasyonu:** Supabase ile gerçek zamanlı veri yönetimi ve kimlik doğrulama.

## 🛠 Kullanılan Teknolojiler

*   **Framework:** [Next.js](https://nextjs.org/)
*   **Platform:** [Capacitor](https://capacitorjs.com/)
*   **Veritabanı/Auth:** [Supabase](https://supabase.com/)
*   **Stil:** [Tailwind CSS](https://tailwindcss.com/)
*   **UI/UX:** [Radix UI](https://www.radix-ui.com/), [Lucide React](https://lucide.dev/), [Framer Motion](https://www.framer.com/motion/)
*   **Dil:** [TypeScript](https://www.typescriptlang.org/)

## 📦 Kurulum

Öncelikle bağımlılıkları yükleyin:

```bash
npm install
# veya
bun install
```

### Yerel Geliştirme (Web)

Geliştirme sunucusunu başlatın:

```bash
npm run dev
```

Tarayıcınızda [http://localhost:3000](http://localhost:3000) adresine gidin.

### Mobil Geliştirme (Android)

Android APK veya bundle oluşturmak için:

1.  Next.js projesini derleyin:
    ```bash
    npm run build
    ```
2.  Capacitor ile eşitleyin:
    ```bash
    npx cap sync
    ```
3.  Android Studio'yu açın:
    ```bash
    npx cap open android
    ```

## 🎥 Test ve Demo

Uygulamayı hızlıca denemek ve çalışma mantığını görmek için aşağıdaki dosyaları kullanabilirsiniz:

*   **Test Videosu:** `test_video.zip` dosyası içerisinde uygulamanın çalışma performansını ve özelliklerini gösteren bir demo videosu bulunmaktadır.
*   **Android APK:** `apk/app-debug.apk` dosyasını doğrudan Android cihazınıza veya emülatörünüze kurarak uygulamayı test edebilirsiniz.

## 📂 Proje Yapısı

*   `src/`: Uygulama kaynak kodları.
*   `public/`: Statik dosyalar (logolar, görseller).
*   `android/`: Android platformuna özel dosyalar.
*   `capacitor.config.ts`: Capacitor yapılandırma dosyası.
*   `next.config.ts`: Next.js yapılandırma dosyası.

---
*Bu README dosyası otomatik olarak proje gereksinimlerine göre güncellenmiştir.*
