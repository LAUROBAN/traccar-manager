# Traccar Manager - Versão Simplificada com Google Maps

Uma aplicação Flutter simples e funcional para rastreamento com Google Maps, Street View e traçado de rotas.

## 🎯 Funcionalidades

- ✅ Google Maps integrado
- ✅ Geolocalização em tempo real
- ✅ Marcadores de localização
- ✅ Botão "Minha Localização"
- ✅ Interface limpa e intuitiva
- ✅ Compatível com Android e iOS

## 📋 Requisitos

- Flutter 3.0+
- Dart 3.0+
- Android SDK 21+
- iOS 11.0+

## 🚀 Como Compilar

### Android

```bash
flutter build apk --release
```

O APK estará em: `build/app/outputs/flutter-apk/app-release.apk`

### iOS

```bash
flutter build ios --release
```

O app estará em: `build/ios/iphoneos/`

## 🔑 Configuração da Chave de API

A chave de API do Google Maps já está configurada em:
- `android/app/src/main/AndroidManifest.xml`
- `ios/Runner/Info.plist`

Se precisar mudar, atualize em ambos os arquivos.

## 📱 Instalar no Dispositivo

### Android

```bash
flutter install
```

### iOS

1. Abra `ios/Runner.xcworkspace` no Xcode
2. Configure certificados de assinatura
3. Clique em "Run"

## 🔧 Estrutura do Projeto

```
traccar-manager-simplified/
├── lib/
│   └── main.dart          # Código principal
├── android/               # Configurações Android
├── ios/                   # Configurações iOS
├── pubspec.yaml           # Dependências
└── codemagic.yaml         # Configuração de build automático
```

## 📦 Dependências

- `google_maps_flutter: ^2.5.0` - Google Maps
- `geolocator: ^9.0.0` - Geolocalização
- `permission_handler: ^11.4.0` - Permissões
- `http: ^1.1.0` - Requisições HTTP

## 🤝 Contribuindo

Sinta-se livre para fazer fork e enviar pull requests!

## 📄 Licença

Apache License 2.0

## 📞 Suporte

Para problemas ou dúvidas, abra uma issue no repositório.

---

**Versão**: 1.0.0  
**Data**: Dezembro 2025  
**Status**: ✅ Funcional e Pronto para Usar
