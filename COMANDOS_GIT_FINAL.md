# Upload do Dashboard via Git - Passos Finais

## Seu repositório foi criado! 🎉

**GitHub**: https://github.com/Niveelpro/dashboard-niveel

---

## Opção A: Upload via Git (MAIS RÁPIDO) ⚡

### Passo 1: Abra o Terminal/Prompt

**Windows**: 
- Clica em Iniciar → Pesquisa "cmd" → Abre "Prompt de Comando"
- OU: Git Bash (se tiver instalado)

**Mac/Linux**:
- Abre Terminal

### Passo 2: Vá pra pasta do projeto

```bash
cd ~/Downloads/dashboard-niveel
```

(Ou o caminho onde você descompactou o ZIP)

### Passo 3: Execute estes comandos na ordem

```bash
git init
```

```bash
git add .
```

```bash
git commit -m "Initial commit: Dashboard Financeiro Niveel Pro"
```

```bash
git branch -M main
```

```bash
git remote add origin https://github.com/Niveelpro/dashboard-niveel.git
```

```bash
git push -u origin main
```

**Pronto!** Os arquivos já tão no GitHub 🎊

---

## Opção B: Descompactar e Fazer Upload Manual (Mais Lento)

1. Baixa o arquivo `dashboard-niveel.zip`
2. Descompacta (clica com botão direito → Extrair tudo)
3. Abre a pasta `dashboard-niveel`
4. Sai selecionando os arquivos e pastas, e faz upload no GitHub (web)
   - Precisa criar a pasta `app/` primeiro
   - Depois `components/ui/`
   - Depois os arquivos
   - Cansa 😅

**Recomendo a Opção A (Git) — é bem mais rápido!**

---

## Depois do Upload: Próximos Passos

### Conectar com Netlify (Deploy Gratuito)

1. Vai pra https://netlify.com
2. Clica "Login with GitHub"
3. Conecta com sua conta
4. Clica "Connect from Git"
5. Seleciona o repositório `dashboard-niveel`
6. Deixa as configurações padrão (detecta Next.js sozinho)
7. Clica "Deploy"
8. **Pronto!** Dashboard tá online em ~2-3 min

Link vai ser algo como: `https://dashboard-niveel-abc123.netlify.app`

---

## Se der erro no Deploy do Netlify

**Erro comum**: "Cannot find module 'recharts'"

**Solução**: Vá pra `Settings` → `Build & Deploy` → `Environment` e adicione:
```
CI = false
```

Depois clica em "Deploy" novamente.

---

## Proxim…

 (DEPOIS DO DEPLOY ESTAR RODANDO)

- Integração com Google Sheets
- Funcionalidade completa de lançamento de gastos
- Atualização em tempo real

---

**Precisa de ajuda em algum passo? Avisa!** 🚀
