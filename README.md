# 🧮 Calculadora React Native

Aplicativo de calculadora simples desenvolvido com **React Native + Expo**, com interface baseada no **React Native Paper**.

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![React Native](https://img.shields.io/badge/React%20Native-Expo-blue)

## 📚 Sobre o projeto

Exercício da disciplina de **Soluções Mobile** — UNISATC.

- **Professora:** Mariane Joaquim Melo
- **Objetivo:** compreender o uso de componentes, frameworks visuais e Hooks em React Native.

## ✨ Funcionalidades

- Operações básicas: soma, subtração, multiplicação e divisão
- Botão para limpar o visor
- Interface responsiva com componentes do React Native Paper
- [adicione outras, como números decimais, apagar último dígito, etc.]

## 🧠 Conceitos aplicados

| Conceito | Onde foi usado |
|---|---|
| `useState` | Gerenciamento do valor exibido e da operação atual |
| Componentização com props | Componente `Botao` reutilizável para todas as teclas |
| React Native Paper | Framework visual para botões, textos e temas |

## 🛠️ Tecnologias

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [React Native Paper](https://callstack.github.io/react-native-paper/)

## 📋 Pré-requisitos

- [Node.js](https://nodejs.org/) (versão LTS)
- Aplicativo **Expo Go** no celular (Android ou iOS) ou um emulador configurado

## 🚀 Como rodar

1. Clone o repositório:

   ```bash
   git clone https://github.com/laraareck/[nome-do-repositorio].git
   cd [nome-do-repositorio]
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Inicie o projeto:

   ```bash
   npx expo start
   ```

4. Abra o app:
   - Escaneie o **QR Code** com o Expo Go no celular, ou
   - Pressione `a` para abrir no emulador Android, ou
   - Pressione `w` para abrir no navegador.

## 📁 Estrutura do projeto

```
.
├── App.js              # Tela principal e lógica da calculadora
├── components/
│   └── Botao.js        # Botão reutilizável (recebe props)
├── package.json
└── README.md
```

> Ajuste a estrutura acima conforme os arquivos reais do seu projeto.

## 📸 Preview

<!-- Adicione um print ou GIF do app: ![Calculadora](./assets/preview.png) -->

## 👩‍💻 Autora

Feito por **[Seu nome]** — [@laraareck](https://github.com/laraareck)
