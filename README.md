# Divide Aí 🍽️

Um aplicativo web moderno para dividir contas em ambientes sociais como bares, restaurantes e encontros com amigos.

## 📋 Sobre o Projeto

O **Divide Aí** é uma solução intuitiva para o problema comum de dividir contas em grupo. Com uma interface limpa e funcionalidades colaborativas, permite que grupos de pessoas gerenciem suas despesas de forma transparente e justa.

## ✨ Funcionalidades Principais

### 🔐 Sistema de Autenticação

- Login com email/senha
- Login com Google OAuth
- Cadastro de novos usuários
- Recuperação de senha

### 🏠 Dashboard Principal

- Estatísticas pessoais (total de mesas, gastos, média)
- Histórico de mesas anteriores
- Acesso rápido para criar ou entrar em mesas

### 🍽️ Gerenciamento de Mesas

- **Criar Mesa**: Defina um nome personalizado para sua mesa
- **Entrar em Mesa**: Use código de 6 dígitos para participar
- **Adicionar Participantes**: Convide amigos via link ou código
- **Gerenciar Itens**: Adicione, edite ou remova itens do pedido

### 💰 Divisão Inteligente de Contas

- **Seleção Individual**: Cada pessoa marca os itens que consumiu
- **Cálculo Automático**: Sistema calcula automaticamente a parte de cada um
- **Taxa de Serviço**: Configurável (padrão 10%)
- **Controle de Pagamentos**: Marque quem já pagou sua parte
- **Resumo Detalhado**: Visualize o total por pessoa com breakdown completo

### 🤝 Colaboração em Tempo Real

- Indicadores de usuários online/offline
- Feed de atividades em tempo real
- Notificações de ações dos participantes
- Sincronização automática entre dispositivos

### 📊 Histórico e Perfil

- **Histórico Completo**: Visualize todas as mesas anteriores
- **Busca e Filtros**: Encontre mesas específicas rapidamente
- **Perfil do Usuário**: Gerencie informações pessoais e preferências
- **Estatísticas Detalhadas**: Acompanhe seus gastos ao longo do tempo

## 🛠️ Tecnologias Utilizadas

- **Frontend**: Next.js 14 (App Router)
- **Estilização**: Tailwind CSS v4
- **Componentes**: shadcn/ui
- **Ícones**: Lucide React
- **Tipografia**: Geist Sans & Geist Mono
- **Tema**: Sistema de dark/light mode

## 🚀 Como Usar

### 1. Acesso Inicial

- Acesse o aplicativo
- Faça login ou crie uma conta
- Chegue ao dashboard principal

### 2. Criando uma Mesa

1. Clique em "Criar Nova Mesa"
2. Defina um nome para a mesa
3. Compartilhe o código ou link com os amigos
4. Aguarde os participantes entrarem

### 3. Gerenciando Itens

1. Adicione itens clicando no botão "+"
2. Defina nome e valor de cada item
3. Cada participante marca os itens que consumiu
4. Edite ou remova itens conforme necessário

### 4. Fechando a Conta

1. Clique em "Fechar a Conta"
2. Revise o resumo e ajuste a taxa de serviço se necessário
3. Cada pessoa marca quando pagar sua parte
4. Quando todos pagarem, encerre a mesa

## 📱 Interface Responsiva

O aplicativo foi desenvolvido com abordagem mobile-first, garantindo uma experiência otimizada em:

- 📱 Smartphones
- 📱 Tablets
- 💻 Desktops
- 🖥️ Monitores grandes

## 🎨 Design System

### Paleta de Cores

- **Primária**: Azul (#3B82F6)
- **Secundária**: Azul escuro (#1E40AF)
- **Neutros**: Cinzas e brancos
- **Suporte**: Dark mode completo

### Tipografia

- **Headings**: Geist Sans (vários pesos)
- **Corpo**: Geist Sans Regular
- **Código**: Geist Mono

## 📁 Estrutura do Projeto

\`\`\`
divide-ai/
├── app/
│ ├── auth/
│ │ ├── login/
│ │ ├── register/
│ │ └── forgot-password/
│ ├── table/[id]/
│ ├── join/[code]/
│ ├── history/
│ ├── profile/
│ └── page.tsx
├── components/
│ ├── ui/
│ └── theme-toggle.tsx
└── lib/
└── utils.ts
\`\`\`

## 🔄 Fluxo de Uso Típico

1. **Login** → Dashboard
2. **Criar Mesa** → Compartilhar código
3. **Adicionar Itens** → Marcar consumo
4. **Fechar Conta** → Controlar pagamentos
5. **Encerrar Mesa** → Voltar ao dashboard

## 🎯 Casos de Uso

- **Restaurantes**: Dividir conta entre amigos
- **Bares**: Controlar consumo individual
- **Festas**: Organizar gastos compartilhados
- **Viagens**: Gerenciar despesas em grupo
- **Eventos**: Dividir custos de forma transparente

## 🔒 Privacidade e Segurança

- Dados armazenados localmente no navegador
- Não há coleta de informações pessoais sensíveis
- Sistema de autenticação simulado para demonstração
- Interface segura e confiável

## 📞 Suporte

Para dúvidas, sugestões ou problemas:

- Abra uma issue no repositório
- Entre em contato através do perfil do desenvolvedor

---

**Divide Aí** - Tornando a divisão de contas simples e justa! 🎉
