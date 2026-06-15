# Crítica e correções — landpages INTELECTO

Crítica via `/impeccable critique` (register brand). Score inicial das 4 originais: **28/40**.
O herói 3D é distinto; a **camada de conteúdo** caía nos tells de IA. Esta pasta tem as versões **corrigidas**.

## O que o detector + a review acharam (originais)

| Problema | Onde | Severidade |
|---|---|---|
| `gradient-text` em todo headline | TODAS (5×) | P1 — ban absoluto |
| glassmorphism como padrão (todo painel é blur) | V2/V3/V4 | P1 — ban absoluto |
| fonte por reflexo (Syne reflex-reject; Inter+single-font na V1) | todas | P2 |
| eyebrows mono repetidos + card grids idênticos | todas | P2 |
| em dashes na copy | todas | P2 — ban de copy |
| dark-glow (box-shadow colorido) + gray-on-color (contraste) | V2/V3/V4 + V1 | P3 |

## O que mudou nas páginas desta pasta

| Antes | Depois |
|---|---|
| Headline em gradiente (`background-clip:text`) | Cor sólida; ênfase por peso/tamanho; 1 palavra em acento sólido |
| Cada seção num painel de vidro fosco | Folha de conteúdo sólida (sem `backdrop-filter`); 3D só no hero e no CTA final |
| Syne + Inter | **Bricolage Grotesque** (display) + **Hanken Grotesk** (corpo); mono **só no HUD** |
| Eyebrow mono sobre cada h2 | Removido; abertura por número editorial / headline forte |
| 6 trilhas / 8 corredores / 4 features em cards idênticos | Lista editorial numerada (trilhas), fileira de tags (corredores), linhas com regra (features) |
| Copy com "—" | Sem em dash (vírgula/dois-pontos/ponto) |
| Botões com glow colorido de 30px | Preenchimento sólido + leve elevação no hover |
| Cores ad-hoc | Paleta em **OKLCH**, neutros tintados pro tom da marca |

Mantido: o 3D (iglu de vidro + fogo no núcleo na quente), a degradação graciosa de WebGL, os CTAs pra inema.vip e o conceito "frio fora, calor dentro".

## Arquivos
- `inverno.html` — versão quente corrigida (frio fora, calor dentro)
- `igloo-pro.html` — versão fria corrigida
