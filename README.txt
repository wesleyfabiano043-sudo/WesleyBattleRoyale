WESLEY BATTLE ROYALE — PROJETO ANDROID

Este é o projeto-fonte Android (WebView) do protótipo, não um APK já compilado.
O jogo abre em tela cheia e paisagem. O HTML está em app/src/main/assets/index.html.

IMPORTANTE:
- O protótipo carrega o motor Three.js por CDN (internet necessária ao abrir o jogo).
- Para gerar o APK: abra esta pasta no Android Studio, aguarde a sincronização do Gradle
  e escolha Build > Build Bundle(s) / APK(s) > Build APK(s).
- O APK de teste normalmente aparece em app/build/outputs/apk/debug/app-debug.apk.
- Para publicar/distribuir amplamente, gere uma versão assinada em
  Build > Generate Signed Bundle / APK.
- O Android Studio precisa de JDK/SDK compatíveis e internet para baixar dependências.
