# 📱 Server Mobile App

> Versão mobile do dashboard para Android, permitindo o monitoramento e controle do servidor diretamente pelo celular usando **React Native + Expo**.

## 🚀 Tecnologias

- **Framework**: React Native + [Expo](https://expo.dev/)
- **Linguagem**: TypeScript
- **Navegação**: Expo Router (File-based routing)
- **Estilização**: React Native Styles (ou NativeWind)
- **Comunicação**: Fetch API + WebSockets

---

## 🛠️ Como Iniciar o Desenvolvimento

1. **Instalar dependências**:
   ```bash
   cd app/
   npm install
   ```

2. **Iniciar o servidor do Expo**:
   ```bash
   npm run android
   # Ou apenas:
   npx expo start
   ```

3. **Ver no Celular**:
   - Baixe o app **Expo Go** na Play Store.
   - Escaneie o QR Code que aparecerá no terminal.

---

## 🎯 Funcionalidades Planejadas

1. **Monitoramento (Home)**: Visualização de CPU, RAM e Disco em tempo real.
2. **Controle Systemd**: Lista de serviços com botões para Start/Stop/Restart.
3. **Explorador de Arquivos**: Navegação simplificada e visualização de logs.
4. **Notificações**: Alertas de sobrecarga enviados diretamente para o dispositivo.

---

## 🏗️ Estrutura do Projeto
- `app/`: Contém as rotas do app (Expo Router).
- `components/`: Componentes reutilizáveis (Gauges, Botões, Cards).
- `constants/`: Cores, fontes e URLs da API.
- `hooks/`: Lógica compartilhada (ex: `useStats`, `useAuth`).

---

> **Nota**: Este projeto é destinado exclusivamente para uso pessoal no dispositivo Android do proprietário.
