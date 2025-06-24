# 🎉 Quiz App

Bu proje, React ile geliştirilmiş eğlenceli bir Quiz uygulamasıdır. Kullanıcıya 10 soru sorulur, her soru için 30 saniye süre verilir ve ilk 4 saniye boyunca cevap şıkları gizlenir. Sonuç ekranında doğru, yanlış ve boş bırakılan sorular detaylı şekilde gösterilir.

## 🚀 Özellikler

- 10 farklı soru ve görsel desteği
- Her soru için 30 saniye zamanlayıcı ⏳
- İlk 4 saniye şıklar gizli
- Cevap verildikten sonra otomatik olarak sonraki soruya geçiş
- Sonuç ekranında detaylı analiz (doğru, yanlış, boş)
- Testi tekrar başlatma ve ana sayfaya dönüş
- Modern ve responsive tasarım
- Mobil uyumlu tasarım

## 🛠️ Kurulum

1. Bu repoyu klonlayın.
2. Bağımlılıkları yükleyin:

   ```bash
   npm install
   ```

3. Geliştirme sunucusunu başlatın:

   ```bash
   npm run dev
   ```

4. Uygulamayı tarayıcınızda açın: [http://localhost:5173](http://localhost:5173)

## 🌐 Canlı Demo

Projenin canlı halini buradan görebilirsiniz:  
**[Tıklayınız.](https://melihcandemir-question-app.netlify.app/)**

## 📁 Proje Yapısı

```
/
├── public/
│   └── pictures/         # Soru görselleri
├── src/
│   ├── Components/
│   │   ├── Quiz.jsx
│   │   ├── Quiz.css
│   │   └── TimerDisplay.jsx
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
│   └── index.css
├── package.json
├── vite.config.js
└── README.md
```

## 🧩 Kullanılan Teknolojiler

- [React 19](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [React Router DOM](https://reactrouter.com/)
- [React Circular Progressbar](https://www.npmjs.com/package/react-circular-progressbar)
- [ESLint](https://eslint.org/)

---
