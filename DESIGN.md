# DESIGN — DealPulse site

## Intenção

Landing pública de curadoria de ofertas, voltada a pessoas no Brasil que querem entender a proposta antes de entrar no grupo Telegram. A página tem **uma ação principal**: abrir o convite do Telegram. É um **site de apresentação**, não um painel, loja, catálogo de produtos ou ambiente de operação do bot.

## North star

**Mais contexto. Menos barulho.** Clareza editorial de um projeto técnico que prioriza informações verificáveis e respeita o tempo do visitante. A experiência não deve prometer preços, receita, aprovação de programas ou disponibilidade de ofertas não comprovados.

## Identidade

- Azul-marinho #10273f e azul profundo #081b30: confiança e base para a composição do fluxo.
- Azul elétrico #315fed: ação e ênfase com parcimônia.
- Verde-água #6ce2c9: sinal/fluxo; não confundir com selo de aprovação ou status comercial.
- Papel azulado #f2f7fa, branco #ffffff: respiração e leitura.
- Cinza de texto #516b80, linha #d2e0e8: apoio editorial.
- Foco acessível laranja #ed853b.

A fonte principal é a pilha local Segoe UI / Inter / sistema / Arial. Pequenos rótulos do painel usam monoespaçada do sistema. Não carregar fontes remotas.

## Composição

- **Hero dividido:** tese concisa à esquerda e o **fluxo de curadoria** à direita.
- **Assinatura visual:** painel "A oferta chega. O contexto fica.", com sequência real de três etapas (identificar, organizar, compartilhar). É uma representação do processo planejado, **não uma amostra de produto nem métrica inventada**.
- **Seção de princípios:** informação, frequência e transparência.
- **Bloco de manifesto e último convite:** um único destino, repetido no topo, hero e fim para reduzir esforço de navegação.

## Comportamento e acessibilidade

- HTML/CSS estático, pt-BR e sem scripts ou rastreadores próprios.
- Âncoras reais para seções e links externos; foco visível, contraste e alvos clicáveis.
- Adaptar em telas estreitas sem horizontal scroll, preservar CTA e leitura.
- Respeitar prefers-reduced-motion; nenhum conteúdo deve depender de animação.
- Para grupos privados: se o convite estiver no site público, **ele é publicamente visível**, mesmo que a visibilidade do grupo no Telegram seja privada.

## Copy e integridade

- Deixar explícito o estágio de preparação/testes e não afirmar que o sistema já distribui ofertas reais.
- Não confundir links de afiliados próprios com URLs diretas; identificar publicidade quando implementada.
- Não implicar vínculo oficial com Amazon, Shopee, Magalu, Mercado Livre ou Telegram.
- Evitar contadores de membros, descontos ou depoimentos fictícios.
