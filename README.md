# LifeShark :shark:

Este projeto de **LifeShark** faz parte do projeto para disciplina de **Programação Para Dispositivos Móveis em Android** desenvolvida com **React Native e TypeScript**. Os usuários podem encontrar nesse App informações gerais sobre tubarões em praias de Recife/PE, bem como dados turísticos e educativos sobre cada praia.

## 🚀 Funcionalidades

- **Feed de Notícias**: diversas materias relacionadas aos tubarões.
- **Informaçoes educativas sobre Fauna Marinha**: Mostra informações educativas sobre espécies marinhas em praias de Recife/PE.
- **Informações sobre praias**: ostra informações sobre clima, tábua de maré, turismo e linhs de ônibus de cada praia de Recife/PE.

## 🛠️ Tecnologias Utilizadas

- **React Native**
- **TypeScript**

## 📌 Como Usar

1. **Clone este repositório:**
   ```sh
   git clone https://github.com/jurandirDev/lifesahark-app.git
   ```
2. **Entre na pasta do projeto**
```cd lifeshark-app```
3. **Inicie o App**
```npx expo start```
4. **Utilize o aplicativo Expo Go para rodar o app LifeShark em aparelho Android**
```escanei o QR-code gerado```
5. **Utilize o navegador para rodar em pc, digite na barra de endeeço:**
```localhost:8081```

## Configurar o ambiente e Pré-requisitos

**Necessita ter instalado:**
```Node.js: https://nodejs.org```

**Expo CLI (para facilitar o desenvolvimento React Native):**
```npm install -g expo-cli```

## 📂 Estrutura do Projeto

```
Criar estrutura de pastas e arquivos.

📁lifeshark-app/
├──📁assets/                # Imagens, ícones, etc.
├──📁components/            # Componentes reutilizáveis (ex: Card, Header)
├──📁constants/             # Cores, estilos globais, configurações fixas
│   └──📄colors.ts
├──📁data/                  # Dados simulados (mock)
│   ├──📄tides.json
│   └──📄news.json
├──📁screens/               # Cada tela do app (interface principal)
│   ├──📄PrincipalScreen.tsx
│   ├──📄BeachScreen.tsx
├──📁services/              # Chamadas de API (com axios)
│   └──📄api.ts
├──📁navigation/            # Arquivo de navegação
│   └──📄TabNavigator.tsx
├──📄App.tsx                # Arquivo principal do app
├──📄package.json
└──📄tsconfig.json
```


## 📝 Licença

Projeto acadêmico e livre de licença.
