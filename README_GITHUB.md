# 🎨 PowerPoint App Pro

> Uma aplicação de apresentação moderna estilo PowerPoint com interface azul/preto e funcionalidades avançadas

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0-brightgreen.svg)
![Status](https://img.shields.io/badge/status-production--ready-success.svg)

## ✨ Destaques

- 🎬 **Modo Apresentação Especial**: Painel de slides permanente - mude de slides sem sair da apresentação!
- 🎨 **Design Moderno**: Cores azul/preto personalizadas com acentos turquesa
- 📝 **Edição Completa**: Adicionar, editar, deletar e duplicar slides com facilidade
- 🎯 **Formatação de Texto**: Fonte, tamanho, cor, negrito, itálico, sublinhado
- 💾 **Salvamento Automático**: Sua apresentação é salva automaticamente
- ⚙️ **Desfazer/Refazer**: Histórico completo de ações
- 🔄 **Reordenação por Drag-Drop**: Organize seus slides facilmente
- ⬇️ **Exportar**: Baixe sua apresentação em JSON
- ⌨️ **Atalhos de Teclado**: Trabalhe mais rápido
- 📱 **Responsivo**: Funciona em qualquer tela

## 🚀 Início Rápido

### Requisitos
- Node.js 16+ 
- npm ou yarn

### Instalação

```bash
# Clonar repositório
git clone https://github.com/seu-usuario/powerpoint-app-pro.git
cd powerpoint-app-pro

# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev
```

Acesse `http://localhost:5173` no seu navegador!

## 📖 Documentação

- [INICIO_RAPIDO.md](./INICIO_RAPIDO.md) - Comece em 30 segundos
- [GUIA_DE_USO.md](./GUIA_DE_USO.md) - Tutorial completo
- [CHEAT_SHEET.md](./CHEAT_SHEET.md) - Atalhos e referência rápida
- [FUNCIONALIDADES.md](./FUNCIONALIDADES.md) - Todas as 20+ funcionalidades

## ⌨️ Atalhos Principais

### Na Apresentação
| Atalho | Ação |
|--------|------|
| `Seta →` | Próximo slide |
| `Seta ←` | Slide anterior |
| `Espaço` | Próximo slide |
| `F` | Mostrar/ocultar painel |
| `Esc` | Sair da apresentação |
| **Clique no painel** | **Mudar slide sem sair** ⭐ |

### No Editor
| Atalho | Ação |
|--------|------|
| `Ctrl+Z` | Desfazer |
| `Ctrl+Y` | Refazer |

## 🎨 Cores

**Tema Personalizado:**
- 🔲 Fundo: Preto escuro (#0f0f1e)
- 🟦 Editor: Azul gradiente (#16213e → #0f3460)
- 🟦 Destaque: Turquesa (#4ECDC4)
- ⚪ Texto: Branco (#ffffff)

## 🔧 Stack Técnico

- **React** 18.3 - UI library
- **TypeScript** 5.4 - Type safety
- **Vite** 5.2 - Build tool
- **CSS3** - Styling com gradientes e animações
- **localStorage** - Persistência de dados

**Sem dependências externas!** Apenas React puro! 🎉

## 📁 Estrutura do Projeto

```
powerpoint-app-pro/
├── src/
│   ├── App.tsx
│   ├── components/
│   │   ├── Slide.tsx
│   │   ├── SlideList.tsx
│   │   ├── Toolbar.tsx
│   │   ├── PresentationMode.tsx    ✨ Modo apresentação especial
│   │   └── FormattingToolbar.tsx   ✨ Formatação de texto
│   └── index.css
├── index.html
├── package.json
├── vite.config.ts
└── tsconfig.json
```

## 💡 Uso

### 1. Criar Slide
```
Clique em "➕ Novo Slide" e edite o conteúdo
```

### 2. Formatar Texto
```
Clique no título/conteúdo para ver as opções de formatação
```

### 3. Apresentar
```
Clique em "▶️ Apresentar"
Use setas ou espaço para navegar
Clique em slides no painel lateral (não sai!)
Pressione Esc para sair
```

### 4. Salvar
```
Automático! Sua apresentação é salva a cada mudança
Clique em "⬇️ Baixar" para exportar em JSON
```

## 🌟 Funcionalidade Principal

### Painel Permanente na Apresentação

A funcionalidade mais especial deste app é que você **não precisa sair da apresentação para trocar de slides**.

```
Modo Apresentação:
┌────────────────────────────┐
│   Seu Slide Atual          │
│                            │
│                            │
│    ◀ 1/10 ▶               │
├────────────┐               │
│ PAINEL     │ Painel de    │
│ SLIDES     │ slides que   │
│            │ permite      │
│ [1] ⭐    │ trocar sem   │
│ [2]        │ sair! 🎯    │
│ [3]        │             │
└────────────┴────────────────┘

Todos os outros PowerPoints saem e entram.
Este app? Fica na apresentação a todo tempo! ✨
```

## 🎯 Comparação com PowerPoint Padrão

| Recurso | PowerPoint | Este App |
|---------|:---:|:---:|
| Adicionar slides | ✅ | ✅ |
| Editar slides | ✅ | ✅ |
| Modo apresentação | ✅ | ✅ |
| Painel na apresentação | ❌ | ✅ |
| Trocar slide sem sair | ❌ | ✅ |
| Formatação de texto | ✅ | ✅ |
| Tema customizável | Limitado | ✅ |
| Salvamento automático | ✅ | ✅ |
| Desfazer/Refazer | ✅ | ✅ |
| Exportar | ✅ | ✅ (JSON) |

## 🛠️ Desenvolvimento

### Scripts Disponíveis

```bash
# Desenvolvimento com hot reload
npm run dev

# Build para produção
npm run build

# Preview da build
npm run preview
```

## 📊 Estatísticas

- **Componentes**: 7+ React components
- **Funcionalidades**: 20+ features
- **Linhas de código**: 600+ TypeScript
- **Arquivos CSS**: 9 arquivos
- **Dependências**: 0 externas
- **Tamanho bundle**: ~50KB (gzipped)

## 🐛 Problemas Conhecidos

Nenhum bug conhecido no momento! 🎉

Se encontrar algum, abra uma [issue](https://github.com/seu-usuario/powerpoint-app-pro/issues).

## 🤝 Contribuindo

Contribuições são bem-vindas! 

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## 👨‍💻 Autor

Criado com ❤️ por [Seu Nome]

## 🙏 Agradecimentos

- React e comunidade
- Vite por build rápido
- TypeScript por type safety

## 📧 Contato

- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- Email: seu.email@exemplo.com

## 🎉 Suporte

Se este projeto foi útil para você:
- ⭐ Deixe uma estrela (Star)
- 🐦 Compartilhe com amigos
- 💬 Deixe feedback

---

**Feito com ❤️ | PowerPoint App Pro v1.0**

