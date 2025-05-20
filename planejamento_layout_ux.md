# Planejamento de Layout e Experiência UX para o Novo Loberiam Shop

## Introdução

Este documento apresenta o planejamento detalhado do layout e da experiência de usuário (UX) para o novo Loberiam Shop, com base nas melhores práticas identificadas nos principais marketplaces e no mapeamento de páginas e funcionalidades já definido. O objetivo é criar uma experiência visual coesa, profissional e otimizada para todos os dispositivos, mantendo a identidade única da Loberiam.

## Diretrizes Gerais de Design

### 1. Sistema de Design

#### 1.1 Paleta de Cores
- **Cores Primárias:**
  - Preto (#000000) - Para elementos de destaque, cabeçalho e rodapé
  - Branco (#FFFFFF) - Para fundos e áreas de conteúdo
  - Vermelho (#E63946) - Como cor de destaque para CTAs e promoções

- **Cores Secundárias:**
  - Cinza claro (#F8F9FA) - Para fundos alternativos e separação de seções
  - Cinza médio (#6C757D) - Para textos secundários e bordas
  - Cinza escuro (#343A40) - Para textos principais

- **Cores de Feedback:**
  - Verde (#28A745) - Para sucesso e disponibilidade
  - Vermelho (#DC3545) - Para erros e alertas
  - Amarelo (#FFC107) - Para avisos
  - Azul (#0D6EFD) - Para informações

#### 1.2 Tipografia
- **Família Principal:** Inter (sans-serif)
  - Extra-light (200): Para detalhes muito pequenos
  - Light (300): Para textos longos
  - Regular (400): Para a maioria dos textos
  - Medium (500): Para subtítulos
  - Semi-bold (600): Para títulos de seção
  - Bold (700): Para títulos principais e CTAs

- **Hierarquia Tipográfica:**
  - H1: 32px/36px (desktop), 24px/28px (mobile)
  - H2: 24px/30px (desktop), 20px/24px (mobile)
  - H3: 20px/26px (desktop), 18px/22px (mobile)
  - H4: 18px/24px (desktop), 16px/20px (mobile)
  - Corpo: 16px/24px (desktop), 14px/20px (mobile)
  - Pequeno: 14px/20px (desktop), 12px/16px (mobile)

#### 1.3 Iconografia
- **Estilo:** Linha fina com preenchimento opcional
- **Tamanhos:**
  - Pequeno: 16x16px
  - Médio: 24x24px
  - Grande: 32x32px
- **Biblioteca:** Font Awesome ou Material Icons
- **Consistência:** Manter o mesmo estilo em todo o site

#### 1.4 Espaçamento e Grid
- **Sistema de Grid:** 12 colunas
- **Breakpoints:**
  - Mobile: 0-576px
  - Tablet: 577px-991px
  - Desktop: 992px+
- **Espaçamento Base:** 8px
- **Escala de Espaçamento:**
  - XS: 4px
  - S: 8px
  - M: 16px
  - L: 24px
  - XL: 32px
  - XXL: 48px

#### 1.5 Componentes UI
- **Botões:**
  - Primário: Fundo preto, texto branco, hover com opacidade
  - Secundário: Borda preta, texto preto, hover com fundo cinza claro
  - Terciário: Sem borda, texto preto, hover com fundo cinza claro
  - Destaque: Fundo vermelho, texto branco, hover com opacidade

- **Inputs:**
  - Borda fina cinza
  - Focus com borda preta
  - Placeholder em cinza médio
  - Mensagens de erro em vermelho abaixo do campo

- **Cards:**
  - Fundo branco
  - Sombra sutil
  - Borda fina opcional
  - Cantos levemente arredondados (4px)

- **Badges:**
  - Promoção: Fundo vermelho, texto branco
  - Novo: Fundo preto, texto branco
  - Destaque: Fundo amarelo, texto preto
  - Esgotado: Fundo cinza, texto branco

### 2. Princípios de UX

#### 2.1 Responsividade
- Design mobile-first
- Layouts fluidos que se adaptam a diferentes tamanhos de tela
- Elementos touch-friendly (min. 44x44px) para interfaces móveis
- Menus colapsáveis em dispositivos menores
- Imagens otimizadas para diferentes resoluções

#### 2.2 Acessibilidade
- Contraste adequado entre texto e fundo (WCAG AA)
- Textos alternativos para imagens
- Navegação por teclado
- Estrutura semântica de HTML
- Formulários com labels associados
- Mensagens de erro claras e acessíveis

#### 2.3 Performance
- Carregamento progressivo de imagens
- Lazy loading para conteúdo abaixo da dobra
- Minificação de CSS e JavaScript
- Otimização de assets
- Cache eficiente
- Tempo de carregamento alvo: < 3 segundos

#### 2.4 Consistência
- Padrões de interação consistentes em todo o site
- Terminologia uniforme
- Posicionamento previsível de elementos comuns
- Feedback visual consistente para ações similares
- Hierarquia visual mantida em todas as páginas

## Layouts Detalhados por Página

### 1. Home Page

#### Desktop Layout
- **Cabeçalho:**
  - Altura: 120px
  - Logo à esquerda (max-height: 60px)
  - Barra de busca centralizada (40% da largura)
  - Ícones de usuário, favoritos e carrinho à direita
  - Menu de categorias horizontal abaixo (altura: 50px)

- **Hero Section:**
  - Carrossel de banner em destaque (altura: 400-500px)
  - Controles de navegação nas laterais
  - Indicadores de slide na parte inferior
  - Call-to-action destacado em cada slide

- **Categorias em Destaque:**
  - Grid de 6 categorias (2 linhas de 3)
  - Imagem circular ou quadrada com cantos arredondados
  - Nome da categoria abaixo da imagem
  - Espaçamento uniforme entre itens

- **Ofertas em Destaque:**
  - Título da seção com link "Ver todas"
  - Carrossel horizontal de produtos (4-5 visíveis)
  - Cards de produto com imagem, nome, preço antigo, preço atual, desconto em % e botão de compra rápida
  - Controles de navegação nas laterais

- **Banners Secundários:**
  - 2-3 banners horizontais ou grid de banners menores
  - Altura consistente (200-250px)
  - Call-to-action em cada banner

- **Produtos Mais Vendidos:**
  - Similar à seção de ofertas, mas com badge "Mais Vendido"
  - Possibilidade de filtro rápido por categoria

- **Marcas em Destaque:**
  - Carrossel horizontal de logos de marcas
  - Fundo neutro para destacar os logos
  - 6-8 marcas visíveis simultaneamente

- **Seção de Benefícios:**
  - Grid de 3-4 benefícios (frete grátis, pagamento seguro, etc.)
  - Ícone + título curto + descrição breve para cada item
  - Fundo sutilmente diferenciado

- **Newsletter:**
  - Fundo contrastante (preto)
  - Título atrativo
  - Campo de e-mail + botão de inscrição
  - Texto curto sobre benefícios da inscrição

- **Rodapé:**
  - Fundo preto, texto branco
  - 4-5 colunas de links (Institucional, Ajuda, Categorias, etc.)
  - Formas de pagamento e selos de segurança
  - Redes sociais e contato
  - Copyright e links legais na base

#### Mobile Layout
- **Cabeçalho:**
  - Altura reduzida (80px)
  - Menu hamburger à esquerda
  - Logo centralizado
  - Ícones de busca e carrinho à direita
  - Barra de busca expansível ou em tela separada

- **Hero Section:**
  - Carrossel adaptado para tela cheia
  - Altura proporcional à largura
  - Swipe para navegação
  - Indicadores menores

- **Categorias em Destaque:**
  - Carrossel horizontal (2-3 visíveis)
  - Tamanho aumentado para touch

- **Demais Seções:**
  - Empilhadas verticalmente
  - Carrosséis com 1-2 itens visíveis
  - Espaçamento reduzido mas suficiente para touch
  - Botões de ação maiores

- **Rodapé:**
  - Seções em acordeão
  - Ícones de redes sociais maiores
  - Botão de "voltar ao topo"

### 2. Página de Categoria/Listagem de Produtos

#### Desktop Layout
- **Cabeçalho:** Consistente com a home

- **Breadcrumb:**
  - Posicionado abaixo do cabeçalho
  - Fonte pequena (14px)
  - Separadores visuais claros

- **Banner de Categoria:**
  - Opcional, para categorias principais
  - Altura: 200-250px
  - Título da categoria sobreposto

- **Área de Filtros e Resultados:**
  - Filtros à esquerda (25% da largura)
    - Acordeões por tipo de filtro
    - Checkboxes para seleção múltipla
    - Range slider para preço
    - Botão para aplicar/limpar filtros
  
  - Resultados à direita (75% da largura)
    - Cabeçalho com total de resultados e ordenação
    - Grid de produtos (3-4 por linha)
    - Paginação na base
    - Opção de visualização (grid/lista)

- **Cards de Produto:**
  - Imagem principal (proporção 1:1)
  - Badge de desconto/novo quando aplicável
  - Nome do produto (max 2 linhas)
  - Avaliação em estrelas
  - Preço antigo (riscado) e atual
  - Opção de parcelamento
  - Botão de compra rápida
  - Ícone de favorito

#### Mobile Layout
- **Filtros:**
  - Botão "Filtrar" fixo no topo
  - Filtros em drawer lateral ou modal
  - Aplicação imediata ou botão de confirmar

- **Resultados:**
  - Grid de 2 produtos por linha
  - Informações essenciais apenas
  - Scroll infinito em vez de paginação

### 3. Página de Produto

#### Desktop Layout
- **Cabeçalho e Breadcrumb:** Consistentes

- **Conteúdo Principal:**
  - Layout em duas colunas (50/50 ou 60/40)
  
  - Coluna Esquerda:
    - Galeria de imagens grande
    - Imagem principal (70%)
    - Miniaturas verticais (30%)
    - Zoom ao hover
    - Botões de compartilhamento
  
  - Coluna Direita:
    - Nome do produto (24-28px)
    - SKU e disponibilidade
    - Avaliação em estrelas com número de reviews
    - Preço em destaque
    - Opções de variação (cores, tamanhos) com visual
    - Seletor de quantidade
    - Botão "Comprar" grande e destacado
    - Botão "Adicionar ao Carrinho" secundário
    - Cálculo de frete (CEP + resultados)
    - Políticas de entrega e devolução resumidas

- **Informações Detalhadas:**
  - Abas ou acordeões para:
    - Descrição
    - Especificações técnicas
    - Avaliações e comentários
    - Perguntas e respostas
  - Conteúdo rico com formatação adequada
  - Tabelas para especificações

- **Produtos Relacionados:**
  - Carrossel horizontal (4-5 visíveis)
  - Similar aos cards da home/categoria

#### Mobile Layout
- **Galeria:**
  - Carrossel horizontal de imagens
  - Swipe para navegação
  - Indicadores de slide
  - Botão de zoom para visualização ampliada

- **Informações:**
  - Empilhadas verticalmente
  - Botões de ação em largura total
  - Abas/acordeões para conteúdo extenso

### 4. Carrinho de Compras

#### Desktop Layout
- **Layout em Duas Colunas:**
  - Lista de produtos (70%)
  - Resumo do pedido (30%)

- **Lista de Produtos:**
  - Imagem thumbnail
  - Nome e variações
  - Preço unitário
  - Quantidade (com +/-)
  - Subtotal
  - Botão de remover
  - Linha divisória entre produtos

- **Resumo do Pedido:**
  - Card destacado com sombra
  - Subtotal
  - Desconto (se aplicável)
  - Frete (calculado ou a calcular)
  - Total em destaque
  - Campo para cupom
  - Botão "Finalizar Compra" destacado
  - Botão "Continuar Comprando" secundário
  - Métodos de pagamento aceitos (ícones)

- **Produtos Sugeridos:**
  - Abaixo da lista principal
  - "Frequentemente comprados juntos"
  - Carrossel horizontal (4-5 visíveis)

#### Mobile Layout
- **Layout Vertical:**
  - Lista de produtos
  - Campo de cupom
  - Resumo colapsado (expandir para detalhes)
  - Botões em largura total

### 5. Checkout

#### Desktop Layout
- **Progresso:**
  - Indicador de etapas no topo
  - Etapas: Identificação > Endereço > Frete > Pagamento > Confirmação
  - Etapa atual destacada

- **Layout em Duas Colunas:**
  - Formulário/conteúdo da etapa (65%)
  - Resumo do pedido (35%, similar ao carrinho)

- **Formulários:**
  - Campos agrupados logicamente
  - Labels claros acima dos campos
  - Validação em tempo real
  - Mensagens de erro específicas
  - Botões "Voltar" e "Continuar"

- **Etapa de Pagamento:**
  - Abas para diferentes métodos
  - Campos específicos por método
  - Ambiente seguro destacado (ícone de cadeado)
  - Termos e condições com checkbox

- **Confirmação:**
  - Resumo completo do pedido
  - Informações de entrega e pagamento
  - Número do pedido destacado
  - Instruções para acompanhamento
  - Botão para imprimir/salvar confirmação

#### Mobile Layout
- **Progresso:**
  - Simplificado, mostrando apenas etapa atual e próxima
  - Ou ícones menores para todas as etapas

- **Layout:**
  - Uma coluna vertical
  - Resumo colapsável
  - Formulários otimizados para touch
  - Teclados específicos por tipo de campo

### 6. Página de Login/Cadastro

#### Desktop Layout
- **Layout em Duas Colunas:**
  - Login à esquerda
  - Cadastro à direita
  - Ou tabs alternando entre os dois

- **Formulário de Login:**
  - E-mail/usuário
  - Senha (com mostrar/ocultar)
  - "Lembrar-me" checkbox
  - "Esqueci minha senha" link
  - Botão de login destacado
  - Opções de login social

- **Formulário de Cadastro:**
  - Campos essenciais apenas (nome, e-mail, senha)
  - Força da senha visual
  - Termos e condições checkbox
  - Opção de newsletter
  - Botão de cadastro destacado

- **Benefícios:**
  - Lista de vantagens de criar conta
  - Ícones ilustrativos

#### Mobile Layout
- **Tabs:**
  - Alternar entre login e cadastro
  - Formulários em largura total
  - Teclado otimizado por campo

### 7. Página Institucional (Sobre Nós)

#### Desktop Layout
- **Banner Principal:**
  - Imagem de alta qualidade
  - Título sobreposto
  - Altura: 300-400px

- **Conteúdo:**
  - Layout em uma coluna central (70% da largura)
  - Tipografia clara e espaçada
  - Títulos hierárquicos
  - Imagens intercaladas com texto
  - Blocos para missão, visão, valores
  - Equipe em grid (se aplicável)
  - Depoimentos em cards ou carrossel

#### Mobile Layout
- **Conteúdo:**
  - Largura total com padding
  - Imagens responsivas
  - Espaçamento adequado entre seções

## Componentes Reutilizáveis

### 1. Header
- Consistente em todas as páginas
- Versões para desktop e mobile
- Estados para logado/não logado
- Mini-carrinho expansível
- Menu de categorias com hover/click

### 2. Footer
- Consistente em todas as páginas
- Links agrupados por categoria
- Newsletter integrada
- Selos de segurança e pagamento
- Redes sociais
- Versão simplificada para mobile

### 3. Cards de Produto
- Variações para diferentes contextos (home, categoria, relacionados)
- Estados para hover, indisponível, promoção
- Botões de ação rápida
- Badges configuráveis

### 4. Formulários
- Estilos consistentes para inputs, selects, checkboxes
- Validação visual
- Mensagens de erro/sucesso
- Máscaras para campos específicos (CEP, telefone)

### 5. Botões
- Hierarquia visual clara (primário, secundário, terciário)
- Estados (hover, active, disabled)
- Variações de tamanho
- Com/sem ícones

### 6. Navegação
- Breadcrumbs
- Paginação
- Filtros
- Ordenação
- Menu mobile

## Microinterações e Feedback

### 1. Hover States
- Sutis mudanças de cor/opacidade
- Elevação (sombra) em cards
- Revelação de informações adicionais
- Zoom suave em imagens de produto

### 2. Transições
- Menu dropdown suave
- Carrossel com easing apropriado
- Fade in/out para modais
- Slide para drawers mobile

### 3. Feedback de Ação
- Confirmação visual para adição ao carrinho
- Notificações toast para ações importantes
- Animação de loading para processos
- Confirmação de formulários

### 4. Estados de Erro
- Validação em tempo real
- Mensagens de erro específicas
- Sugestões de correção
- Recuperação fácil

## Considerações de Implementação

### 1. Tecnologias Recomendadas
- HTML5 semântico
- CSS3 com Flexbox e Grid
- JavaScript moderno
- Framework responsivo (Bootstrap ou similar)
- Pré-processador CSS (SASS)

### 2. Assets e Recursos
- Sistema de ícones consistente
- Biblioteca de imagens otimizadas
- Placeholders para conteúdo dinâmico
- Documentação de componentes

### 3. Testes e Validação
- Testes em múltiplos dispositivos e navegadores
- Validação de acessibilidade (WCAG)
- Testes de performance (PageSpeed)
- Testes de usabilidade com usuários reais

## Próximos Passos

1. Criação de wireframes detalhados para cada página
2. Desenvolvimento de protótipos interativos
3. Validação dos protótipos
4. Implementação do design system
5. Desenvolvimento das páginas
6. Testes e ajustes
7. Lançamento

## Conclusão

Este planejamento de layout e UX estabelece as diretrizes para criar uma experiência de e-commerce moderna, profissional e centrada no usuário para o novo Loberiam Shop. A implementação dessas diretrizes resultará em um site visualmente atraente, fácil de usar e otimizado para conversão, mantendo a identidade única da marca Loberiam enquanto incorpora as melhores práticas dos principais marketplaces do mercado.
