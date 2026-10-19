# Android

O projeto usa Capacitor para gerar um aplicativo Android nativo completo.

## Requisitos locais

- Android Studio com Android SDK instalado
- JDK 21 ou a versão recomendada pelo Android Studio
- `ANDROID_HOME` configurado
- Node.js 22 e pnpm

## Criar o projeto Android nativo

Depois de clonar o repositório, execute uma vez:

```bash
pnpm install
pnpm android:setup
```

Esse comando compila a interface e cria a pasta nativa `android/`, incluindo o Gradle Wrapper.

## Gerar o APK

```bash
pnpm android:apk
```

O APK de desenvolvimento será criado em:

```text
android/app/build/outputs/apk/debug/app-debug.apk
```

## Abrir no Android Studio

```bash
pnpm android:open
```

Também é possível gerar o APK pelo Android Studio em **Build > Build APK(s)**.
