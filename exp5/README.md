# 💰 Aura - Gestão Financeira Inteligente

## 📝 Descrição do Projeto
**Aura** é uma plataforma completa de gestão financeira pessoal com inteligência artificial integrada. Desenvolvida como projeto acadêmico avançado, a aplicação oferece um dashboard intuitivo em glassmorphism para acompanhar receitas, despesas, metas financeiras e gerar insights preditivos baseados em IA.

O projeto foi desenvolvido como parte da disciplina de **Desenvolvimento Web Avançado e Inteligência Artificial**, demonstrando a integração de:
- Design moderno com efeitos visuais (glassmorphism)
- Análise financeira em tempo real
- Inteligência Artificial para recomendações
- Processamento de documentos (OCR para notas fiscais)
- Exportação de relatórios fiscais

## 🎬 Demonstração Visual
A plataforma apresenta:
- **Dashboard elegante** com tema escuro (dark mode) e efeitos de vidro translúcido
- **KPI Cards** mostrando saldo, receitas, despesas e metas
- **Gráfico de fluxo de caixa** com análise de 6 meses
- **Gestão de transações** com categorias e histórico
- **Metas financeiras** com rastreamento de progresso

## 🚀 Tecnologias Utilizadas

### Frontend
* **HTML5** com semântica moderna
* **CSS3** avançado com:
  - Glassmorphism (backdrop-filter, blur)
  - Gradientes dinâmicos
  - Animações suaves (keyframes)
  - Layout flexbox e grid
  - Variáveis CSS customizáveis
* **JavaScript Vanilla** para interatividade
* **Fonts:** Google Fonts (Syne, DM Sans)

### Diferenciais Técnicos
* **Tema escuro otimizado** com paleta de cores vibrante
* **Privacy Mode** para ocultar valores sensíveis
* **Renderização dinâmica** de dados com JavaScript
* **Responsividade** para mobile e desktop

## 📦 Arquivos do Projeto

```
exp5/
├── aura-finance.html              # Aplicação completa em arquivo único
├── Aura_N7Tech_Documento_Projeto.docx  # Documentação acadêmica
└── README.md                      # Este arquivo
```

## 🎯 Funcionalidades Principais

### ✅ Dashboard & KPIs
- **Saldo Total:** R$ 18.450 com variação percentual
- **Receitas Mensais:** Rastreamento de entradas
- **Despesas Mensais:** Monitoramento de saídas
- **Meta de Economia:** Progresso visual com indicador percentual

### 📊 Análise Financeira
- **Gráfico de Fluxo de Caixa:** Comparação receitas vs. despesas em 6 meses
- **Categorização de Gastos:** Moradia (41%), Alimentação (26%), Transporte (12%), etc.
- **Histórico de Transações:** Últimas 6 transações com ícones e categorias
- **Metas Financeiras:** 
  - Fundo de Emergência 🛡 (70% completa)
  - Viagem Europa ✈ (40% completa)
  - MacBook Pro 💻 (68% completa)

### 🤖 Diferenciais 1: AI Insights Engine
Sistema inteligente de análise preditiva que oferece:
- **⚠ Alertas:** Identifica gastos anormais (ex: Lazer +34%)
- **💡 Dicas:** Recomendações de economia baseadas em padrões
- **✦ Previsões:** Estimativas de atingimento de metas

### 🗂️ Diferenciais 2: Smart Receipt Vault
Gerenciamento inteligente de recibos:
- **Upload via Drag & Drop:** Interface intuitiva
- **OCR Automático:** Extração de dados de notas fiscais
- **Criptografia AES-256:** Segurança de dados sensíveis
- **Histórico organizado:** Rastreamento de documentos

### ⬇️ Diferenciais 3: Tax Export
Exportação de relatórios fiscais:
- **PDF Completo:** Pronto para impressão e declaração
- **CSV/Excel:** Compatível com declaração de IR 2025
- **Período customizável:** Jan–Mai 2025 (47 transações)
- **Itens dedutíveis:** Identificação automática (R$ 2.140)

### 🔒 Diferenciais 4: Privacy Mode
Proteção de dados sensíveis:
- **Toggle rápido:** Ativar/desativar ocultação de valores
- **Blur effect:** Aplicado a saldos, transações e metas
- **Status visual:** Indicador claro de modo ativo

### 🔐 Firebase Integration
Status em tempo real de serviços:
- Auth, Firestore, Storage, Remote Config, Analytics, Hosting
- Indicadores visuais de sincronização

## 📚 Reflexão Acadêmica

O projeto inclui uma seção dedicada a questões éticas e educacionais:

### Questão A: Competências Indispensáveis para Desenvolvedores
- **Engenharia de Prompt:** Decomposição lógica de problemas complexos
- **Code Review Avançado:** Auditoria de segurança e vulnerabilidades
- **Pensamento Crítico:** Avaliação de soluções geradas por IA

### Questão B: Originalidade vs. Plágio Digital
- **O Princípio da Transformação Aditiva:** Framework ético para uso de IA
- **Diferenciais implementados:** 4 features inéditas (AI Insights, Receipt Vault, Tax Export, Privacy Mode)

## 🔧 Como Executar

### Opção 1: Arquivo Único (Recomendado)
1. Clone o repositório:
```bash
git clone https://github.com/rafasantosdevv/faculdade.git
cd faculdade/exp5/
```

2. Abra `aura-finance.html` no navegador:
   - Duplo clique no arquivo, ou
   - Arraste para o navegador, ou
   - Use um server local: `python -m http.server 8000`

### Opção 2: Com Servidor Local (Recomendado para produção)
```bash
cd exp5/
python3 -m http.server 8000
# Acesse http://localhost:8000/aura-finance.html
```

Ou com Node.js:
```bash
npx http-server .
```

### Requisitos
- Navegador moderno (Chrome, Firefox, Safari, Edge)
- JavaScript habilitado
- Não requer dependências externas

## 📊 Dados de Exemplo

### Transações
- Salário N7Tech: +R$ 5.500 (Renda)
- Freelance UX: +R$ 1.700 (Renda)
- Aluguel: -R$ 1.600 (Moradia)
- Supermercado: -R$ 620 (Alimentação)
- Netflix: -R$ 85 (Lazer)
- Farmácia: -R$ 140 (Saúde)

### Metas
- Fundo de Emergência: R$ 8.500 / R$ 12.000 (70%)
- Viagem Europa: R$ 3.200 / R$ 8.000 (40%)
- MacBook Pro: R$ 5.100 / R$ 7.499 (68%)

## 🎨 Design & Estética

### Paleta de Cores
```css
--bg-deep: #080b14 (Fundo principal)
--accent-violet: #7c3aed (Primária)
--accent-cyan: #00d4ff (Destaque)
--accent-emerald: #10b981 (Sucesso)
--accent-rose: #f43f5e (Alerta)
--accent-amber: #f59e0b (Warning)
```

### Efeitos Visuais
- **Glassmorphism:** Backdrop blur com transparência
- **Orb Field:** Animações de fundo com gradientes
- **Gradient Text:** Logo com efeito degradê
- **Smooth Transitions:** Animações fluidas de 0.2s a 0.8s

## 🔐 Segurança e Privacidade

- **Modo Privado:** Ocultação visual de dados sensíveis
- **Criptografia AES-256:** Para documentos armazenados (Receipt Vault)
- **Dados locais:** Aplicação funciona offline
- **Sem tracking:** Sem envio de dados para terceiros

## 📱 Responsividade

Breakpoints otimizados:
- **Mobile:** < 600px (coluna única)
- **Tablet:** 600px - 900px (2 colunas)
- **Desktop:** > 900px (layout completo com sidebar)

## 🧪 Testes Interativos

### Funcionalidades testáveis:
1. **Privacy Toggle:** Clique em "Modo Privado" para ocultar valores
2. **Nova Transação:** Clique em "+ Nova Transação" para abrir modal
3. **Receipt Upload:** Arraste/clique na seção Receipt Vault
4. **AI Analysis:** Clique em "✦ Atualizar Análise" para simular IA
5. **Tax Export:** Selecione formato (PDF/CSV) e gere relatório

## 📚 Aprendizados

Este projeto demonstra:
- **CSS Avançado:** Glassmorphism, animações, responsividade
- **JavaScript Vanilla:** DOM manipulation, event handling, localStorage simulation
- **Design Thinking:** UX/UI para fintech
- **Gestão Financeira:** Lógica de cálculos e análises
- **Ética em Desenvolvimento:** Discussão sobre IA e originalidade

## 📄 Documentação

Consulte `Aura_N7Tech_Documento_Projeto.docx` para:
- Requisitos detalhados
- Arquitetura do sistema
- Descrição completa de cada feature
- Análise técnica aprofundada
- Conclusões e recomendações

## 🎓 Contexto Acadêmico

**Disciplina:** Desenvolvimento Web Avançado + Inteligência Artificial  
**Período:** 2025.1  
**Instituição:** [Sua Faculdade]  
**Desenvolvedor:** Rafael Santos (@rafasantosdevv)  
**Equipe:** N7Tech  

## 🚀 Possíveis Extensões

- Backend com Node.js + Express
- Integração real com Firebase
- ML real para previsões (TensorFlow.js)
- Aplicativo mobile (React Native)
- Integração com Open Banking
- Dashboard em tempo real

## 🤝 Contribuições
Este é um projeto acadêmico. Para sugestões, abra uma issue no repositório.

## 📞 Contato
Rafael Santos - [@rafasantosdevv](https://github.com/rafasantosdevv)

---
[Voltar ao repositório principal](https://github.com/rafasantosdevv/faculdade)
