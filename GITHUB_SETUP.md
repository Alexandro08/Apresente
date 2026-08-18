# 📤 Guia: Enviando PowerPoint App Pro para GitHub

## ⚠️ Git não foi encontrado no PowerShell

Parece que Git não está no PATH do seu computador. Você tem 2 opções:

---

## **OPÇÃO 1: Usar GitHub Desktop (Recomendado)** ✨

GitHub Desktop é mais fácil e visual. Siga estes passos:

### Passo 1: Abrir GitHub Desktop
1. Abra a aplicação **GitHub Desktop** no seu computador
2. Faça login com sua conta GitHub

### Passo 2: Criar Repositório
1. Clique em **File** → **New Repository**
2. Preencha:
   - **Name**: `powerpoint-app-pro` (ou o nome que desejar)
   - **Description**: `PowerPoint App com modo apresentação especial`
   - **Local Path**: Selecione a pasta do projeto
   - **Initialize this repository with a README**: ✓ Deixe desmarcado (já temos)

### Passo 3: Fazer Publish
1. Clique em **Publish repository**
2. Escolha:
   - **Name**: `powerpoint-app-pro`
   - **Description**: `PowerPoint App Pro - UI moderna com painel na apresentação`
   - **Private/Public**: Escolha public para todos verem
3. Clique em **Publish Repository**

### Passo 4: Fazer Sync (Upload)
1. Clique no botão **Sync** no topo
2. Pronto! Seu código está no GitHub 🎉

---

## **OPÇÃO 2: Instalar Git** 

Se preferir usar linha de comando:

### Passo 1: Instalar Git
1. Acesse: https://git-scm.com/download/win
2. Baixe e instale (use as opções padrão)
3. Reinicie o PowerShell/Terminal

### Passo 2: Configurar Git (primeira vez)
```powershell
git config --global user.name "Seu Nome"
git config --global user.email "seu.email@github.com"
```

### Passo 3: Inicializar Repositório Local
```powershell
cd "c:\Users\ide_c\OneDrive\Área de Trabalho\Nova pasta"
git init
git add .
git commit -m "Initial commit: PowerPoint App Pro"
```

### Passo 4: Criar Repositório no GitHub
1. Acesse: https://github.com/new
2. Preencha:
   - **Repository name**: `powerpoint-app-pro`
   - **Description**: `PowerPoint App Pro - UI moderna com painel na apresentação`
   - **Public** ou **Private**: Escolha
   - Deixe as outras opções padrão
3. Clique em **Create repository**

### Passo 5: Conectar ao GitHub
Copie e cole no PowerShell (substitua `seu-usuario`):

```powershell
cd "c:\Users\ide_c\OneDrive\Área de Trabalho\Nova pasta"
git remote add origin https://github.com/seu-usuario/powerpoint-app-pro.git
git branch -M main
git push -u origin main
```

### Passo 6: Sincronizar Futuros Commits
```powershell
git add .
git commit -m "Sua mensagem de mudança"
git push
```

---

## **OPÇÃO 3: VS Code com Git**

VS Code tem integração com Git:

### Passo 1: Abrir Pasta no VS Code
1. Abra o VS Code
2. **File** → **Open Folder**
3. Selecione a pasta do projeto

### Passo 2: Inicializar Git
1. Clique em **Source Control** (ícone de ramo)
2. Clique em **Initialize Repository**

### Passo 3: Fazer Commit
1. Digite a mensagem: "Initial commit: PowerPoint App Pro"
2. Clique em **Commit** (ícone de check)

### Passo 4: Publicar no GitHub
1. Clique em **Publish to GitHub**
2. Escolha **Public** ou **Private**
3. Pronto! 🎉

---

## 📋 Checklist

- [ ] Tenho GitHub Desktop instalado e configurado
- [ ] Ou Git instalado e configurado
- [ ] Criei repositório no GitHub (https://github.com/new)
- [ ] Inicializei Git no projeto local
- [ ] Fiz commit inicial
- [ ] Fiz push para GitHub

---

## ✅ Resultado Final

Após seguir qualquer uma das opções, você terá:

```
https://github.com/seu-usuario/powerpoint-app-pro/
```

Todos podem ver seu projeto no GitHub! 🌟

---

## 🎯 Próximas Etapas

Depois que o repositório estiver no GitHub:

1. **Compartilhar link**: Envie para amigos/colegas
2. **Continuar desenvolvendo**: Faça commits conforme avança
3. **Clonar em outro computador**: `git clone https://github.com/seu-usuario/powerpoint-app-pro.git`

---

## 🆘 Se Tiver Problemas

### "Git não encontrado"
- Instale Git: https://git-scm.com/download/win
- Reinicie o terminal após instalar

### "Erro de autenticação"
- Configure SSH: https://docs.github.com/pt/authentication/connecting-to-github-with-ssh
- Ou use token pessoal: https://docs.github.com/pt/authentication/keeping-your-data-secure-with-github-tokens/creating-a-personal-access-token

### "Conflito de branches"
- Não se preocupe, é a primeira vez
- Siga os passos da Opção 2, Passo 5

---

## 📚 Links Úteis

- GitHub: https://github.com/
- GitHub Desktop: https://desktop.github.com/
- Git Downloads: https://git-scm.com/download/
- Git Documentation: https://git-scm.com/doc

---

**Escolha a opção mais fácil para você e execute! 🚀**

Se usar GitHub Desktop, é só clicar. Se quiser linha de comando, copie e cole os comandos.

**Seu PowerPoint App Pro em breve estará no GitHub! 🎉**
