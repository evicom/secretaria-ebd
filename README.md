# ✝ EBD Frequência Geral 2026

Sistema completo de controle de frequência da **Escola Bíblica Dominical** — Assembleia de Deus.

Funciona como **PWA (Progressive Web App)** — pode ser instalado no celular ou computador como um aplicativo nativo, com suporte total a uso **offline**.

---

## 🚀 Como publicar no GitHub Pages (passo a passo)

### 1. Crie uma conta no GitHub
Acesse [github.com](https://github.com) e crie uma conta gratuita se ainda não tiver.

### 2. Crie um repositório novo
- Clique em **"New repository"** (botão verde no canto superior direito)
- Dê o nome: `ebd2026` (ou qualquer nome que preferir)
- Deixe como **Public**
- **Não** marque nenhuma opção extra
- Clique em **"Create repository"**

### 3. Faça upload dos arquivos
Na tela do repositório vazio, clique em **"uploading an existing file"** e envie **todos** os arquivos desta pasta:
```
index.html
manifest.json
sw.js
icons/         ← pasta inteira com todos os ícones
.github/       ← pasta inteira (workflow de deploy)
```

> 💡 **Dica:** Você pode arrastar a pasta inteira para a área de upload do GitHub.

Após o upload, clique em **"Commit changes"**.

### 4. Ative o GitHub Pages
- Vá em **Settings** → **Pages** (menu lateral esquerdo)
- Em **"Source"**, selecione: **GitHub Actions**
- Clique em **Save**

### 5. Aguarde o deploy
- Vá na aba **Actions** do repositório
- Você verá o workflow `Deploy EBD 2026 to GitHub Pages` rodando
- Quando aparecer o ✅ verde, o app está no ar!

### 6. Acesse seu app
O endereço será:
```
https://SEU_USUARIO.github.io/ebd2026/
```
(substitua `SEU_USUARIO` pelo seu nome de usuário do GitHub e `ebd2026` pelo nome do repositório)

---

## 📲 Como instalar no celular

### Android (Chrome)
1. Abra o link do app no Chrome
2. Aparecerá um banner **"Instalar EBD 2026"** na parte inferior
3. Toque em **Instalar** — o app aparecerá na tela inicial como qualquer outro aplicativo

### iPhone / iPad (Safari)
1. Abra o link no Safari
2. Toque no ícone de **compartilhar** (quadrado com seta para cima)
3. Role para baixo e toque em **"Adicionar à Tela de Início"**
4. Toque em **Adicionar**

### Computador (Chrome / Edge)
1. Abra o link no Chrome ou Edge
2. Clique no ícone 📲 na barra de endereços (ou use o banner)
3. Clique em **Instalar**

---

## ✨ Funcionalidades

| Módulo | Descrição |
|--------|-----------|
| 🔐 Login | Acesso com login `ebd` e senha `ebd123` |
| ⛪ Igreja | Cadastro completo da congregação |
| 🎓 Professores | Até 20 professores com frequência anual |
| 🏫 Classes | Turmas com professor responsável e auxiliar |
| 👨‍🎓 Alunos | Cadastro completo com ficha e frequência por domingo |
| ✅ Frequência | Marcação de presença/falta por bolinhas (professores e alunos) |
| 🌟 Destaque | Boletim do dia com gráfico automático |
| 📤 Exportar | PNG, PDF completo e compartilhamento via WhatsApp |
| 📵 Offline | Funciona sem internet após a primeira visita |

---

## 🔧 Dados e privacidade

- Todos os dados são salvos **localmente no dispositivo** (localStorage)
- Nenhuma informação é enviada para servidores externos
- O app funciona 100% offline após o primeiro carregamento

---

## 📁 Estrutura de arquivos

```
ebd2026/
├── index.html          ← App principal (tudo em um arquivo)
├── manifest.json       ← Configurações do PWA
├── sw.js               ← Service Worker (cache offline)
├── icons/
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-192.png
│   ├── icon-384.png
│   └── icon-512.png
└── .github/
    └── workflows/
        └── deploy.yml  ← Deploy automático via GitHub Actions
```

---

*EBD Frequência Geral 2026 — Assembleia de Deus*
