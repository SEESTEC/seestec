# Ideias de Design - Landing Page Seestec

<response>
<probability>0.08</probability>
<text>
**Design Movement**: Brutalismo Industrial Moderno

**Core Principles**:
- Geometria angular e assimétrica inspirada em estruturas industriais
- Tipografia bold e condensada que remete a sinalização de fábrica
- Contraste extremo entre áreas densas de informação e espaços vazios
- Elementos de circuito impresso como textura de fundo sutil

**Color Philosophy**: Paleta de verde militar profundo (#1a3d1a) como âncora de confiança e tradição industrial, contrastado com verde oliva (#6b8c3a) para criar profundidade. Cinza concreto (#f0f0f0) como base neutra que permite que os verdes se destaquem sem competir. A intenção emocional é transmitir solidez, experiência técnica e inovação sustentável.

**Layout Paradigm**: Grid quebrado com seções em diagonal usando clip-path CSS. Hero section ocupa 70vh com imagem de técnico trabalhando em ângulo diagonal. Cards de serviços dispostos em layout hexagonal irregular (inspirado no logo Hexagon do PPTX). Formulário de contato em sidebar fixa à direita em desktop, colapsável em mobile.

**Signature Elements**:
- Linhas de circuito animadas conectando seções (SVG path animation)
- Hexágonos como containers de ícones e informações-chave
- Bordas diagonais entre seções (clip-path polygon)

**Interaction Philosophy**: Interações tácteis e diretas. Hover em cards revela informações técnicas com transição de slide-up. Scroll trigger para animação de linhas de circuito que "conectam" seções. Botão WhatsApp com pulse animation constante para chamar atenção sem ser intrusivo.

**Animation**: Entrance animations com stagger (cada elemento entra 50ms após o anterior). Parallax sutil no hero (imagem se move 30% mais devagar que o scroll). Hover states com transform: scale(1.02) e shadow elevation. Transições rápidas (200ms) para manter sensação industrial e eficiente.

**Typography System**: 
- Display: Rajdhani Bold (900) para títulos principais - fonte condensada que remete a sinalização industrial
- Headings: Rajdhani SemiBold (600) para subtítulos
- Body: Inter Regular (400) para legibilidade em textos longos
- Accent: Rajdhani Medium (500) para CTAs e labels
</text>
</response>

<response>
<probability>0.07</probability>
<text>
**Design Movement**: Neo-Modernismo Suíço Adaptado

**Core Principles**:
- Grid rigoroso de 12 colunas com alinhamento matemático preciso
- Hierarquia tipográfica extremamente clara (ratios de 1.618 - golden ratio)
- Uso generoso de whitespace como elemento ativo de design
- Fotografia em preto e branco com overlay de cor verde seletivo

**Color Philosophy**: Verde como acento cirúrgico (#4a7c2f) aplicado apenas em elementos interativos e de destaque. Base monocromática (preto #000000, branco #ffffff, cinzas intermediários) cria canvas neutro que permite que o verde "salte" visualmente. Emocionalmente, transmite precisão suíça, clareza técnica e sustentabilidade consciente.

**Layout Paradigm**: Sistema modular baseado em cards de tamanho uniforme (280x280px em desktop). Hero minimalista com 50% da tela em branco puro, 50% com imagem de alta qualidade. Seções alternadas entre full-width e container estreito (max-width: 720px) para criar ritmo visual. Formulário como modal centralizado ativado por CTA fixo no topo.

**Signature Elements**:
- Linhas finas (1px) em verde que dividem seções e criam grid visual
- Números grandes (120px font-size) em outline stroke para indicar seções
- Círculos vazios (border-only) como bullet points e decoração

**Interaction Philosophy**: Micro-interações minimalistas e intencionais. Hover em botões causa expansão de borda de 2px para 4px. Click em card causa fade-out de todos os outros cards (focus mode). Scroll suave com snap-to-section em desktop. Formulário valida em tempo real com feedback verde/vermelho discreto.

**Animation**: Fade-in com opacity 0 → 1 (400ms ease-out) para todos os elementos. Sem bounces, sem elastic - apenas linear e ease curves. Transições de página com wipe horizontal (slide-in-right). Loading states com spinner minimalista (rotating circle outline).

**Typography System**:
- Display: Space Grotesk Bold (700) para headlines - geométrica e moderna
- Headings: Space Grotesk Medium (500) para h2-h4
- Body: IBM Plex Sans Regular (400) para parágrafos - alta legibilidade
- Mono: IBM Plex Mono (400) para dados técnicos e números
</text>
</response>

<response>
<probability>0.06</probability>
<text>
**Design Movement**: Organicismo Tecnológico (Tech-Nature Fusion)

**Core Principles**:
- Formas orgânicas e fluidas contrastando com elementos técnicos rígidos
- Gradientes sutis que imitam luz natural em superfícies metálicas
- Bordas arredondadas variáveis (8px a 32px) criando sensação de suavidade
- Integração de padrões naturais (folhas, circuitos como nervuras) com tecnologia

**Color Philosophy**: Verde como gradiente vivo - do verde-floresta escuro (#1a3d1a) ao verde-limão vibrante (#8bc34a) - representando a jornada da energia tradicional para sustentável. Tons terrosos (marrom #5d4e37, bege #f5f5dc) como base acolhedora. Emocionalmente, evoca crescimento, renovação e harmonia entre indústria e natureza.

**Layout Paradigm**: Seções com bordas onduladas (SVG wave dividers) criando fluxo contínuo entre áreas. Hero com split assimétrico 40/60 (texto à esquerda, imagem à direita com mask circular). Cards de serviços em layout bento-box (tamanhos variados, alguns 1x1, outros 2x1). Formulário integrado na página com fundo translúcido (backdrop-filter: blur).

**Signature Elements**:
- SVG wave dividers entre todas as seções (variando amplitude e frequência)
- Blob shapes (border-radius: 30% 70% 70% 30% / 30% 30% 70% 70%) como containers
- Partículas flutuantes animadas (CSS animation) no hero background

**Interaction Philosophy**: Interações orgânicas e fluidas. Hover em elementos causa morphing suave de forma (transition: border-radius 600ms). Scroll reveal com slide + fade + scale (transform: translateY(30px) scale(0.95) → 0 scale(1)). Botão WhatsApp com ripple effect ao clicar. Formulário com inputs que "crescem" ao focar (height animation).

**Animation**: Entrance com elastic easing (cubic-bezier(0.68, -0.55, 0.265, 1.55)) para sensação de "bounce" natural. Parallax multi-layer no hero (fundo move 50%, meio-termo 30%, frente 10%). Hover states com lift effect (translateY(-4px) + shadow increase). Loading com pulse animation orgânico.

**Typography System**:
- Display: Outfit Bold (700) para títulos - arredondada e amigável
- Headings: Outfit SemiBold (600) para subtítulos
- Body: Nunito Regular (400) para textos - humanista e legível
- Accent: Outfit Medium (500) para CTAs e destaques
</text>
</response>

---

## Abordagem Selecionada: **Brutalismo Industrial Moderno**

Esta abordagem foi escolhida por alinhar perfeitamente com a identidade da Seestec: uma empresa de engenharia com mais de 13 anos de experiência em setores industriais pesados (mineração, portos, construção). O brutalismo industrial transmite solidez, confiança técnica e experiência, enquanto os elementos modernos (animações de circuito, hexágonos) demonstram inovação e adaptação tecnológica.

A geometria angular e as linhas de circuito conectam visualmente com o trabalho da empresa em telecomunicações e sistemas elétricos. O uso de hexágonos referencia diretamente o cliente Hexagon mencionado no PPTX, criando coesão com materiais corporativos existentes.
