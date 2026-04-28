# 📱 Server Mobile App

> Versão mobile do dashboard para Android, permitindo o monitoramento e controle do servidor diretamente pelo celular.

## 🎯 Objetivo
Oferecer uma interface nativa e rápida para:
- Visualizar status do servidor (CPU, RAM, Disco) em tempo real.
- Gerenciar serviços críticos via `systemd`.
- Receber notificações de alerta.
- Explorar arquivos e gerenciar uploads.

## 🛠️ Tech Stack (Sugestão)
- **Framework**: React Native + Expo
- **Styling**: NativeWind (TailwindCSS para mobile)
- **Comunicação**: WebSockets (para stats) + REST API
- **Segurança**: Armazenamento seguro de tokens/códigos de acesso no dispositivo.

## 🚀 Funcionalidades
1. **Painel de Monitoramento**: Gauges circulares adaptados para telas pequenas.
2. **Gerenciador de Serviços**: Lista com filtros e botões de ação rápida.
3. **Explorador de Arquivos**: Interface otimizada para toque com suporte a visualização de logs.
4. **Login Biométrico**: (Futuro) Proteção extra para o app usando Digital/Rosto.

---

## 🏗️ Como Iniciar (Em Breve)
1. Instalar dependências: `npm install`
2. Iniciar Expo: `npx expo start`
3. Gerar APK: `npx expo run:android`

---

> **Nota**: Este projeto é destinado exclusivamente para uso pessoal no dispositivo Android do proprietário.
