# 🎨 QR Code Styling - Gerador de Códigos QR Estilizados

## 📝 Descrição do Projeto
Um gerador interativo e estilizável de códigos QR desenvolvido com **React + TypeScript** e **Vite**. O projeto permite criar e personalizar códigos QR com diversas opções de design, incluindo cores, pontos, cantos e imagens customizadas.

Este é um projeto acadêmico desenvolvido como parte da disciplina de **Desenvolvimento Web Avançado**, demonstrando habilidades em:
- Desenvolvimento frontend moderno com React
- Tipagem estrita com TypeScript
- Build otimizado com Vite
- Integração com APIs (Gemini API)
- Design responsivo e interativo

## 🎬 Demonstração
O projeto apresenta uma interface limpa e intuitiva onde os usuários podem:
- Gerar códigos QR a partir de URLs ou textos
- Customizar cores dos pontos e fundo
- Personalizar design dos cantos (square, rounded, circle)
- Adicionar imagens/logos dentro do QR Code
- Exportar em diversos formatos

## 🚀 Tecnologias Utilizadas
* **Frontend:** React 18+
* **Linguagem:** TypeScript
* **Build Tool:** Vite
* **Styling:** Tailwind CSS
* **Dependências:** Vite + React Plugin
* **API:** Google Gemini API (para análise de dados)
* **Ambiente:** Node.js 18+

## 📊 Estrutura do Projeto
```
exp4/
├── src/
│   ├── main.tsx           # Entry point da aplicação
│   ├── App.tsx            # Componente principal
│   ├── index.css          # Estilos globais
│   └── [componentes]      # Componentes React
├── index.html             # Template HTML
├── vite.config.ts         # Configuração do Vite
├── env.example.txt        # Variáveis de ambiente exemplo
├── tsconfig.json          # Configuração TypeScript
└── package.json           # Dependências do projeto
```

## 🔧 Como Executar

### Pré-requisitos
- Node.js 18+ instalado
- npm ou yarn

### Passos

1. **Clone o repositório:**
```bash
git clone https://github.com/rafasantosdevv/faculdade.git
cd faculdade/exp4/
```

2. **Instale as dependências:**
```bash
npm install
# ou
yarn install
```

3. **Configure as variáveis de ambiente:**
```bash
cp env.example.txt .env.local
# Edite o arquivo .env.local e adicione sua GEMINI_API_KEY
```

4. **Execute em modo desenvolvimento:**
```bash
npm run dev
# ou
yarn dev
```

5. **Build para produção:**
```bash
npm run build
# ou
yarn build
```

6. **Preview do build:**
```bash
npm run preview
# ou
yarn preview
```

## 📋 Funcionalidades Principais

### ✅ Implementadas
- Geração de QR Codes dinamicamente
- Customização de cores
- Personalização de estilos de pontos e cantos
- Upload de imagens para logo
- Exportação de imagens
- Interface responsiva

### 🎯 Diferenciais
- Integração com Gemini API para análise inteligente
- Hot Module Replacement (HMR) durante desenvolvimento
- TypeScript para maior segurança de tipos
- Build otimizado com Vite para máxima performance

## 📚 Aprendizados

O projeto demonstra:
- **React Hooks:** useState, useEffect, useContext
- **TypeScript:** Tipagem forte, interfaces, tipos genéricos
- **Vite:** Configuração de bundler moderno
- **Tailwind CSS:** Utilidade-first styling
- **Variáveis de ambiente:** Gerenciamento seguro de credenciais
- **Responsividade:** Design adaptável para diferentes telas

## 🔐 Segurança

- As chaves de API são carregadas via `.env.local` (não versionado)
- HMR pode ser desabilitado via `DISABLE_HMR` env var
- Código TypeScript oferece proteção contra erros em tempo de build

## 📝 Notas Importantes

- **Gemini API Key:** Obtenha em [Google AI Studio](https://makersuite.google.com/app/apikey)
- **Compatibilidade:** Funciona em navegadores modernos (Chrome, Firefox, Safari, Edge)
- **Licença:** Uso acadêmico e educacional

## 🤝 Contribuições
Este é um projeto acadêmico. Para sugestões ou melhorias, abra uma issue no repositório.

## 📞 Contato
Desenvolvedor: Rafael Santos (@rafasantosdevv)

---
[Voltar ao repositório principal](https://github.com/rafasantosdevv/faculdade)
