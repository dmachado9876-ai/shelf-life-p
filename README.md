Shelf Life 30% Check — Capacitor-ready web assets (Android)

O que contém:
- Pasta `www/` com `index.html`, `manifest.json`, `service-worker.js` e ícones.
- `package.json` com scripts de ajuda.
- `capacitor.config.json` configurado com appId = com.shelflife.check.

Passos para gerar o app Android (no seu computador):
1. Instale Node.js e Android Studio.
2. Abra um terminal na pasta deste projeto.
3. Rode:
   npm install @capacitor/core @capacitor/cli
   npx cap init "Shelf Life 30% Check" com.shelflife.check --web-dir=www
   npx cap add android
   npx cap sync
   npx cap open android

4. O Android Studio abrirá o projeto nativo; a partir daí você pode rodar em emulador ou dispositivo e gerar APK/AAB.

Observações:
- Este zip contém apenas os web-assets e configuração do Capacitor. O passo `npx cap add android` precisa ser executado localmente para criar a pasta `android/` completa (que é específica do sistema e do Android SDK).
- Caso queira, posso tentar gerar a pasta `android/` aqui, mas isso requer executar ferramentas nativas que não estão disponíveis no ambiente de geração do ZIP.

Ícones gerados automaticamente: icon-192.png e icon-512.png
