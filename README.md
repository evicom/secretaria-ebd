# ✝ EBD Frequência Geral 2026

Sistema completo para controle de frequência da Escola Bíblica Dominical — Assembleia de Deus.

**Demo / Instalar:** [https://SEU-USUARIO.github.io/ebd-2026](https://SEU-USUARIO.github.io/ebd-2026)

---

## 📲 Funcionalidades

- Cadastro de Igreja, Coordenador e Secretaria
- Até 20 professores com foto de nascimento com máscara automática
- Classes de alunos por nível/faixa etária
- Frequência semanal (todos os domingos de 2026)
- Destaque do Dia com preenchimento automático da data
- Exportação em PNG (boletim) e PDF (relatório semestral)
- Compartilhamento via WhatsApp e E-mail
- **PWA instalável** — funciona offline após primeiro acesso

---

## 🚀 Como publicar no GitHub Pages

### 1. Crie um repositório no GitHub

```
Nome sugerido: ebd-2026
Visibilidade: Public (necessário para GitHub Pages gratuito)
```

### 2. Faça o upload dos arquivos

Estrutura esperada:
```
ebd-2026/
├── index.html
├── manifest.json
├── sw.js
├── README.md
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

Você pode arrastar e soltar todos os arquivos diretamente na interface web do GitHub.

### 3. Ative o GitHub Pages

1. Vá em **Settings** do repositório
2. Clique em **Pages** no menu lateral
3. Em *Branch*, selecione **main** e pasta **/ (root)**
4. Clique em **Save**
5. Aguarde ~1 minuto e acesse a URL gerada

### 4. Instale no celular (Android/iOS)

- Abra a URL no Chrome (Android) ou Safari (iOS)
- Toque em **"Adicionar à tela inicial"** ou no banner de instalação
- O app funcionará offline e com ícone próprio

---

## 💾 Dados

Todos os dados são salvos localmente no dispositivo via `localStorage`. Nenhuma informação é enviada a servidores externos.

---

## 🛠️ Tecnologias

- HTML5 + CSS3 + JavaScript puro (zero dependências de build)
- [html2canvas](https://html2canvas.hertzen.com/) — exportação PNG
- [jsPDF](https://parall.ax/products/jspdf) — geração de PDF
- PWA (Service Worker + Web App Manifest)
