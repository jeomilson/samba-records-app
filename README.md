# Samba Records — Android

Projeto Android baseado diretamente no HTML fornecido do site Samba Records.

## O que já está preparado
- Site HTML empacotado dentro do APK via WebView.
- Layout responsivo para telemóvel.
- JavaScript e armazenamento DOM ativados.
- Links externos e esquemas como `tel:`, `whatsapp:` e similares podem abrir no Android.
- Botão Voltar usa o histórico da página.

## Como gerar o APK
1. Abra esta pasta no Android Studio.
2. Aguarde o Gradle sincronizar.
3. Use Build > Build APK(s).
4. O APK de debug será gerado em `app/build/outputs/apk/debug/`.

O ambiente desta sessão não possui Android SDK/Gradle configurado, por isso o APK binário não foi compilado aqui.
