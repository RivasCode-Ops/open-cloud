# ☁️ Open Cloud — RivasCode-Ops

> Seu próprio assistente de IA para linha de comando, baseado em Claude Code, integrado ao OpenRouter.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node](https://img.shields.io/badge/node-%3E%3D18.0.0-green.svg)
![Status](https://img.shields.io/badge/status-ativo-brightgreen.svg)

---

## 🚀 O que é o Open Cloud?

O **Open Cloud** é uma versão customizada do Claude Code — um assistente de IA poderoso para desenvolvedores que roda direto no terminal. Ele foi configurado para funcionar com o **OpenRouter**, permitindo usar modelos como Claude, GPT-4, Gemini e muito mais com uma única API key.

---

## 🧰 Pré-requisitos

Antes de começar, você vai precisar ter instalado:

- [Node.js](https://nodejs.org) v18+ (ou [Bun](https://bun.sh))
- [Git](https://git-scm.com)
- Uma conta no [OpenRouter](https://openrouter.ai) com sua API Key

---

## ⚙️ Instalação

### 1. Clone o repositório base

```bash
git clone https://github.com/codeaashu/claude-code.git
cd claude-code
```

### 2. Instale as dependências

```bash
npm install
```

### 3. Configure sua API Key do OpenRouter

Crie um arquivo `.env` na raiz do projeto:

```bash
cp .env.example .env
```

Edite o arquivo `.env` e adicione sua chave:

```env
OPENROUTER_API_KEY=sua_chave_aqui
```

> 💡 Você pode pegar sua API Key em: https://openrouter.ai/keys

### 4. Build e execução

```bash
npm run build
npm start
```

---

## 🔑 Como obter sua API Key no OpenRouter

1. Acesse [openrouter.ai](https://openrouter.ai) e crie sua conta
2. Vá em **Keys** no painel
3. Clique em **Create Key**
4. Copie a chave e cole no seu arquivo `.env`

---

## 🛠️ Personalização

Você pode customizar este projeto da seguinte forma:

- Alterar o nome e logo no `package.json`
- Adicionar instruções em português nos prompts
- Trocar o modelo padrão pelo de sua preferência no OpenRouter
- Adicionar scripts personalizados para seu fluxo de trabalho

---

## 📁 Estrutura do Projeto

```
open-cloud/
├── src/           # Código fonte principal
├── .env           # Variáveis de ambiente (não commitar!)
├── .env.example   # Exemplo de configuração
├── package.json   # Dependências e scripts
└── README.md      # Este arquivo
```

---

## 🤝 Contribuindo

1. Fork este repositório
2. Crie uma branch: `git checkout -b minha-feature`
3. Commit suas mudanças: `git commit -m 'feat: minha nova feature'`
4. Push para a branch: `git push origin minha-feature`
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<div align="center">
  Feito com ❤️ por <a href="https://github.com/RivasCode-Ops">RivasCode-Ops</a>
  </div>
