# 🎨 PowerPoint App Pro - Guia de Uso Completo

## 📋 Descrição
Aplicativo de apresentação tipo PowerPoint com interface moderna em cores azul e preto, incluindo todas as funcionalidades principais do PowerPoint e a capacidade de trocar de slides durante a apresentação sem sair do modo apresentação.

## 🚀 Como Iniciar

1. Abra um terminal na pasta do projeto
2. Execute: `npm run dev`
3. Acesse: `http://localhost:5173`

## 🎯 Funcionalidades Principais

### 1. **Editor de Slides**
- Painel esquerdo com lista de slides numerados
- Área central para editar título e conteúdo
- Cada slide tem uma cor diferente
- Arrastar e soltar slides para reordenar

### 2. **Barra de Ferramentas (Toolbar)**
| Botão | Função | Atalho |
|-------|--------|--------|
| ➕ Novo Slide | Adiciona um novo slide ao final | Ctrl+N |
| ↶ Desfazer | Desfaz a última ação | Ctrl+Z |
| ↷ Refazer | Refaz a última ação desfeita | Ctrl+Y |
| ⬇️ Baixar | Exporta a apresentação em JSON | - |
| ▶️ Apresentar | Inicia o modo apresentação | F5 |

### 3. **Edição de Slides**
**Para editar:**
1. Clique no slide no painel esquerdo para selecioná-lo
2. Clique no título ou conteúdo e digite
3. As alterações são salvas automaticamente

**Para duplicar um slide:**
1. Hover sobre o slide no painel
2. Clique no botão 📋

**Para deletar um slide:**
1. Hover sobre o slide no painel
2. Clique no botão ✕

### 4. **Modo Apresentação** ⭐ (FUNCIONALIDADE PRINCIPAL)
Clique em "▶️ Apresentar" para iniciar.

**Características:**
- ✅ Fundo preto para melhor visualização
- ✅ Texto branco em contraste
- ✅ Painel de slides lateral que NÃO sai
- ✅ Navegação fluida entre slides
- ✅ Controles intuitivos

**Controles na Apresentação:**
| Ação | Como Fazer |
|------|-----------|
| Próximo slide | Seta direita ou Espaço |
| Slide anterior | Seta esquerda |
| Trocar slide | Clique em qualquer slide no painel lateral |
| Mostrar/ocultar painel | Botão 👁️ ou tecla F |
| Sair da apresentação | Botão ✕ ou tecla Esc |

### 5. **Formatação de Texto**
Ao editar um título ou conteúdo, aparece a barra de formatação com:
- Seletor de fonte (Arial, Verdana, Georgia, etc)
- Tamanho de fonte (8-120px)
- Negrito, Itálico, Sublinhado
- Paleta de cores predefinidas
- Seletor de cor customizado

## 🎨 Cores do Aplicativo

**Tema Escuro com Acentos Turquesa:**
- Fundo principal: Preto escuro (#0f0f1e)
- Área de edição: Azul escuro (#16213e, #0f3460)
- Cor de destaque: Turquesa (#4ECDC4)
- Texto: Branco (#ffffff)

**Cores dos Slides:**
- Cada slide tem uma tonalidade diferente de azul/preto
- Facilita a visualização e diferenciação

## 💾 Salvamento de Dados

**Salvamento Automático:**
- A apresentação é salva automaticamente a cada mudança
- Os dados são armazenados no localStorage do navegador
- Ao recarregar a página, a apresentação é restaurada

**Exportar Apresentação:**
1. Clique em "⬇️ Baixar"
2. Um arquivo JSON será baixado com toda a apresentação
3. Pode ser importado novamente (funcionalidade futura)

## ⚡ Atalhos de Teclado

### Na Apresentação:
```
Seta →        Próximo slide
Seta ←        Slide anterior
Espaço        Próximo slide
F             Mostrar/esconder painel de slides
Esc           Sair da apresentação
```

### No Editor:
```
Ctrl+Z        Desfazer
Ctrl+Y        Refazer
```

## 📊 Exemplo de Uso Prático

1. **Criar uma apresentação:**
   ```
   1. Clique em "➕ Novo Slide" para adicionar slides
   2. Edite o título e conteúdo
   3. Formate o texto conforme necessário
   ```

2. **Reordenar slides:**
   ```
   1. Arraste e solte os slides no painel
   2. Ou use Desfazer/Refazer
   ```

3. **Apresentar:**
   ```
   1. Clique em "▶️ Apresentar"
   2. Use as setas ou espaço para navegar
   3. Clique em slides no painel lateral
   4. Pressione Esc para sair
   ```

## 🔒 Funcionalidade Especial Implementada

**"Não sair da apresentação ao trocar de slides"**

✅ **Completamente implementado!**

Como funciona:
- Ao iniciar a apresentação, um painel de slides aparece na lateral
- Você pode clicar em qualquer slide deste painel
- A apresentação PERMANECE ATIVA
- Somente ao pressionar Esc você sai
- O painel pode ser ocultado com F ou 👁️, mas a apresentação continua

Isto é diferente de outras apresentações onde você precisa sair, selecionar slide, e entrar novamente na apresentação.

## 🎯 Diferenças em Relação ao PowerPoint Padrão

| Característica | PowerPoint Padrão | Este App |
|---|---|---|
| Cores | Laranja/branco | Azul/preto |
| Painel na apresentação | ❌ | ✅ |
| Trocar slide sem sair | ❌ | ✅ |
| Salvamento automático | ✅ | ✅ |
| Desfazer/Refazer | ✅ | ✅ |
| Exportar | ❌ | ✅ (JSON) |

## 💡 Dicas Úteis

1. **Trabalhe rápido:** A edição é em tempo real
2. **Use drag-drop:** Para organizar slides rapidamente
3. **Salve frequentemente:** Use "⬇️ Baixar" para backup
4. **Customize cores:** Cada slide pode ter sua cor
5. **Pratique atalhos:** Use Ctrl+Z e Ctrl+Y para velocidade

## ⚠️ Limitações Conhecidas

- Suporta apenas texto (sem imagens ou formas por enquanto)
- Exportação em JSON (sem compatibilidade com PowerPoint)
- Sem transições de slide animadas
- Sem modo apresentador com notas

## 🔄 Possíveis Melhorias Futuras

- [ ] Adicionar suporte a imagens
- [ ] Transições de slide
- [ ] Modo apresentador
- [ ] Temas predefinidos
- [ ] Importar PowerPoint
- [ ] Compartilhar apresentações
- [ ] Colaboração em tempo real

## 📧 Suporte

Se encontrar problemas:
1. Recarregue a página
2. Limpe o cache do navegador
3. Verifique se a porta 5173 está disponível
4. Reinicie o servidor com `npm run dev`

## ✨ Desfrutando do App!

Agora você tem um PowerPoint App completo com interface moderna, cores personalizadas e a funcionalidade única de trocar slides durante a apresentação sem sair do modo apresentação!

**Bom uso! 🎉**
