# DESIGN — DealPulse site

## Intenção

Landing pública de curadoria de ofertas, voltada a pessoas no Brasil que querem entender a proposta antes de entrar no grupo Telegram. A página tem **uma ação principal**: abrir o convite do Telegram. É um **site de apresentação**, não um painel, loja, catálogo de produtos ou ambiente de operação do bot.

## North star

**Ofertas no radar. Você no controle.** A promessa editorial é facilitar a descoberta de oportunidades, com convite direto ao Telegram. A página vende o benefício de participar, não a arquitetura do bot. Nunca prometer economia garantida, quantidade de ofertas ou resultados ainda não comprovados.

## Identidade

- Azul-marinho #10273f e azul profundo #081b30: confiança e base para a composição do fluxo.
- Azul elétrico #315fed: ação e ênfase com parcimônia.
- Verde-água #6ce2c9: sinal/fluxo; não confundir com selo de aprovação ou status comercial.
- Papel azulado #f2f7fa, branco #ffffff: respiração e leitura.
- Cinza de texto #516b80, linha #d2e0e8: apoio editorial.
- Foco acessível laranja #ed853b.

A fonte principal é a pilha local Segoe UI / Inter / sistema / Arial. Pequenos rótulos do painel usam monoespaçada do sistema. Não carregar fontes remotas.

## Composição

- **Hero dividido:** convite e benefício do grupo à esquerda; um painel com os três passos do visitante à direita.
- **Assinatura visual:** painel "Menos busca. Mais descobertas.", com a sequência de participação (entrar, acompanhar, escolher). É uma promessa de experiência, **não uma amostra de produto nem métrica inventada**.
- **Seção de benefícios:** descoberta em um só lugar, dados úteis quando disponíveis e liberdade para decidir.
- **Bloco de posicionamento e último convite:** uma única ação prioritária, repetida no topo, hero e fim para facilitar a conversão.

## Comportamento e acessibilidade

- HTML/CSS estático, pt-BR e sem scripts ou rastreadores próprios.
- Âncoras reais para seções e links externos; foco visível, contraste e alvos clicáveis.
- Adaptar em telas estreitas sem horizontal scroll, preservar CTA e leitura.
- Respeitar prefers-reduced-motion; nenhum conteúdo deve depender de animação.
- Para grupos privados: se o convite estiver no site público, **ele é publicamente visível**, mesmo que a visibilidade do grupo no Telegram seja privada.

## Copy e integridade

- Priorizar benefício imediato ao visitante e tom convidativo; deixar a informação de que o grupo está começando em texto discreto e visível, sem afirmar que já distribui ofertas reais.
- Não confundir links de afiliados próprios com URLs diretas; identificar publicidade quando implementada.
- Não implicar vínculo oficial com Amazon, Shopee, Magalu, Mercado Livre ou Telegram.
- Evitar contadores de membros, descontos, urgência artificial, depoimentos fictícios ou promessas de frequência.
