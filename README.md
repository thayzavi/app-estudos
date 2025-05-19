# 📘 MoodLogger - Agenda de Estudos de Linguagens

Este é um aplicativo simples feito em **React Native** que funciona como uma **agenda de estudos**, permitindo que você registre a linguagem que está estudando no momento (como React, Java ou PHP), com **data e hora**, visualize um histórico e até compartilhe seu último estudo com outras pessoas.

## ✨ Funcionalidades

- ✅ Registrar linguagem estudada com data e hora
- 📅 Visualizar histórico de estudos
- 📤 Compartilhar último registro de estudo
- 💾 Persistência dos dados com **AsyncStorage**

## 🧠 Como funciona?

O usuário escolhe uma linguagem através de botões com emojis, e o app salva o estudo atual no armazenamento local com a hora e a data. Esse registro é exibido em uma lista, que persiste mesmo após fechar o aplicativo.

## 🚀 Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/)
- [React Native Share API](https://reactnative.dev/docs/share)

## 📦 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/mood-logger.git
cd mood-logger

---Instale as dependências:
npm install

---Execute com o Expo:
npx expo start
