# 🎨 PowerPoint App

Um aplicativo de apresentação moderna com tema laranja e dourado, construído com React, TypeScript e Vite.

## 🚀 Funcionalidades

- ✅ Criar, editar e deletar slides
- ✅ Tema visual moderno com gradientes em laranja/dourado
- ✅ Editor visual em tempo real
- ✅ Painel lateral com miniaturas de slides
- ✅ Interface responsiva e intuitiva
- ✅ Edição de título e conteúdo dos slides

## 📋 Pré-requisitos

- **Node.js** (versão 16 ou superior)
- **npm** ou **yarn**

Se você ainda não tem o Node.js instalado, baixe em: https://nodejs.org/

## 💻 Instalação

1. Abra o terminal na pasta do projeto
2. Instale as dependências:

```bash
npm install
```

## 🏃 Executar o projeto

Para iniciar o servidor de desenvolvimento:

```bash
npm run dev
```

Acesse `http://localhost:5173` no seu navegador.

## 🔨 Build para produção

Para criar uma versão otimizada para produção:

```bash
npm run build
```

Para visualizar a build de produção:

```bash
npm run preview
```

## 📁 Estrutura do projeto

```
src/
├── components/
│   ├── Slide.tsx           # Componente do editor de slide
│   ├── Slide.css
│   ├── SlideList.tsx       # Painel com miniaturas dos slides
│   ├── SlideList.css
│   ├── Toolbar.tsx         # Barra de ferramentas superior
│   └── Toolbar.css
├── App.tsx                  # Componente principal
├── App.css
├── main.tsx                 # Arquivo de entrada
└── index.css               # Estilos globais
```

## 🎯 Como usar

1. **Novo Slide**: Clique no botão "➕ Novo Slide" na barra de ferramentas
2. **Editar Slide**: Clique em um slide na lista lateral para selecioná-lo e editar seu título e conteúdo
3. **Deletar Slide**: Passe o mouse sobre um slide na lista lateral e clique no "✕"
4. **Cores**: Cada slide tem uma cor de fundo predefinida (laranja, amarelo-ouro, etc.)

## 🎨 Paleta de cores

- **Laranja Queimado**: #FF6B35
- **Laranja**: #FFA500
- **Dourado**: #FFD700
- **Chocolate**: #FF8C00
- **Coral**: #FF7F50

## 📦 Dependências principais

- **React 18**: Framework UI
- **TypeScript**: Tipagem estática
- **Vite**: Build tool rápido
- **@vitejs/plugin-react**: Plugin React para Vite

## 🤝 Contribuições

Sinta-se à vontade para fazer fork, criar issues ou enviar pull requests!

## 📄 Licença

Este projeto está licenciado sob a MIT License.

---

**Desenvolvido com ❤️ usando React e TypeScript**
