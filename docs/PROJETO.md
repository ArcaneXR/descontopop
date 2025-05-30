# DescontoPop - Documentação do Projeto

## 1. Introdução
Este documento detalha a concepção do DescontoPop, uma plataforma digital moderna projetada para revolucionar a forma como clientes interagem com programas de fidelidade e como lojistas gerenciam esses programas. O objetivo principal é oferecer uma solução centralizada, intuitiva e atraente, substituindo os tradicionais cartões de papel por uma experiência digital completa.

### Público-alvo:
- **Clientes Finais**: Consumidores que buscam uma maneira fácil de acumular pontos, selos e resgatar recompensas em seus estabelecimentos favoritos.
- **Lojistas**: Pequenos, médios e grandes estabelecimentos comerciais que desejam implementar ou modernizar seus programas de fidelidade para aumentar o engajamento e retenção de clientes.

### Proposta de Valor:
- **Para Clientes**: 
  - Conveniência de ter todos os cartões fidelidade em um único app
  - Acompanhamento fácil do progresso
  - Descoberta de novas lojas e promoções
  - Processo de resgate de recompensas simplificado

- **Para Lojistas**: 
  - Ferramenta eficaz para fidelizar clientes
  - Aumentar a frequência de visitas
  - Coletar dados valiosos sobre o comportamento do consumidor
  - Reduzir custos com material impresso
  - Promover ofertas de forma direcionada

## 2. Tecnologias Utilizadas

### Frontend:
- React: Biblioteca JavaScript para construção de interfaces de usuário interativas e componentizadas
- Bootstrap CSS (via CDN): Framework CSS para estilização base
- Outras CDNs:
  - Font Awesome: Para ícones vetoriais
  - Google Fonts: Para tipografia moderna
  - axios: Para requisições HTTP ao backend
- React Router: Para gerenciamento de rotas

### Backend:
- Node.js com Express.js: Framework para construção da API RESTful
- Autenticação: JWT (JSON Web Tokens)
- Banco de Dados: PostgreSQL

## 3. Design e UI/UX

### Conceito Visual:
Design moderno, minimalista, limpo e altamente intuitivo. Foco em uma navegação fluida e na apresentação clara das informações.

### Paleta de Cores Principal:
- Primária: #4A90E2 (Azul moderno e confiável)
- Secundária: #50E3C2 (Verde-azulado vibrante)
- Neutras: 
  - #F4F7F6 (Cinza claro)
  - #787A91 (Cinza médio)
  - #333333 (Cinza escuro)

### Tipografia:
- Títulos: Montserrat
- Corpo do Texto: Open Sans

### Responsividade:
Design totalmente responsivo, adaptando-se a desktops, tablets e smartphones, com prioridade para mobile-first.

## 4. Telas e Funcionalidades

### 4.1. Perfil Cliente
- Tela de Boas-vindas / Onboarding
- Tela de Cadastro
- Tela de Login
- Dashboard do Cliente
- Tela do Cartão Fidelidade
- Tela "Meu QR Code"
- Tela de Lojas Participantes
- Tela de Recompensas
- Tela de Perfil
- Tela de Notificações

### 4.2. Perfil Lojista
- Tela de Cadastro/Login
- Dashboard do Lojista
- Gerenciamento do Programa
- Tela de Validação
- Tela de Clientes
- Tela de Relatórios
- Configurações da Loja

### 4.3. Perfil Administrador
- Dashboard Administrativo
- Gerenciamento de Lojistas
- Gerenciamento de Clientes
- Configurações do Sistema
- Monitoramento e Logs

## 5. Esquema do Backend

### API RESTful:
- Endpoints CRUD para todas as entidades
- Documentação via Swagger/OpenAPI
- Autenticação JWT
- Validação de dados
- Tratamento de erros

### Modelos do Banco de Dados:
- Clientes
- Lojistas
- ProgramasFidelidade
- Recompensas
- CartoesCliente
- TransacoesFidelidade
- Administradores

## 6. Instruções para o Frontend

### 6.1. Teste do Mockup
- Configuração do Projeto React
- Estrutura de Pastas
- Desenvolvimento dos Componentes
- Dados Mockados
- Interatividade
- Responsividade

### 6.2. Desenvolvimento Pós-Mockup
- Integração com Backend
- Gerenciamento de Estado
- Autenticação
- Validação de Formulários
- Testes

## 7. Próximos Passos

### MVP:
- Cadastro/login de cliente e lojista
- Criação de programa simples
- Pontuação via QR Code
- Resgate básico

### Estratégia de Monetização:
- Planos gratuitos e pagos
- Destaque de lojas
- Taxas por transação

### Funcionalidades Futuras:
- Geolocalização avançada
- Gamificação
- Recomendações personalizadas
- Integração com PDV
- Campanhas de marketing 