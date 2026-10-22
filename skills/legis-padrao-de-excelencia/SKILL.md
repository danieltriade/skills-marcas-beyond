---
name: "legis-padrao-de-excelencia"
description: "Legis carousel quality standard based on the Legis_1hora and Legis_Faltam5Dias benchmarks; use when creating, reviewing or challenging any Legis social media carousel or story."
---

# Padrão de excelência — carrosséis Legis

O diretor humano definiu dois carrosséis como EXEMPLOS A SEREM SEGUIDOS em construção visual, narrativa, conceito e diagramação. Arquivo Figma: fileKey `wF7LNoElN1kasjouo4MDZf`, página "09 - SETEMBRO".

- **Legis_1hora** — seção `1473:435` (feed: `1473:1179`, `1473:886`, `1473:1255`, `1473:1410`). Referência de CONCEITO e NARRATIVA. Avaliação do Senior Reviewer: B, 82/100 (Concept 9, Composition 9, Clarity 9).
- **Legis_Faltam5Dias** — seção `1482:1982` (linha de cima = feed; de baixo = stories). Referência de SISTEMA DE DIAGRAMAÇÃO e NARRATIVA INFORMATIVA. Avaliação: B, 76/100 (Composition 8,5, Brand Fit 8,5).

Para a direção das IMAGENS (mundos WHITE/BLUE, objetos conceituais, materiais, pessoas, texto na imagem), a referência é o sistema `legis-image-art-direction`, que tem prioridade sobre este padrão quando houver conflito sobre estética de imagem.

## Como usar

1. **Ao criar** um carrossel Legis: na exploração inicial, antes de qualquer imagem, releia os princípios abaixo e escolha conscientemente qual modelo a peça segue — "conceitual" (1hora) ou "informativo em módulos" (Faltam5Dias) — ou a combinação. Aplique também a decomposição do `legis-image-art-direction` (mensagem → conceito → metáfora física → ação → WHITE ou BLUE → enquadramento) a cada card.
2. **Ao rodar o Creative Challenger** (`legis-creative-challenger`) ou o **Senior Reviewer** (`legis-art-director-review`): preencha o campo {PRINCIPIOS} do bloco de instruções operacionais com os princípios abaixo E um resumo do `legis-image-art-direction` (princípio central, DNA visual, os dois mundos de iluminação, objetos conceituais, texto na imagem, o que evitar, regra de qualidade), pedindo que a peça seja comparada a eles.
3. Estas referências têm prioridade sobre as demais peças da linha de base quando houver conflito.

## Fluxo oficial de produção Legis

1. **Brief/copy** — tema, objetivo, formato (feed 1080×1350 ou story 1080×1920) e copy de cada card (indicar se é fixa).
2. **Exploração inicial** — escolher o modelo (conceitual/1hora, informativo/Faltam5Dias ou combinação) e escrever o conceito e o roteiro visual card a card, em texto, com a decomposição do `legis-image-art-direction` e o mundo de iluminação (WHITE ou BLUE) de cada card. Nenhuma imagem ainda.
3. **Creative Challenger** (`legis-creative-challenger`) — estressa a ideia ANTES de qualquer imagem. Sem poder de veto: o vencedor é recomendação.
4. **Decisão humana** — o usuário escolhe manter, incorporar um elemento ou trocar a direção. Parar e aguardar.
5. **Geração** — seguir o `legis-image-art-direction` e as regras de geração abaixo.
6. **Montagem no Figma** — nova seção na página indicada, sem sobrepor seções existentes.
7. **Senior Reviewer** (`legis-art-director-review`) — avalia a execução da direção aprovada.
8. **Refinamento + Reviewer final** — no máximo 2 rodadas; depois reportar status, nota e pendências.
9. **Entrega** — resumo curto, pendências (fontes, Boost resolution, validações de produto).

## Regras de geração de imagens

- Modelo padrão: Seedream 5 Pro 2K (~100 créditos por imagem). "Boost resolution" é aplicado pelo usuário no Figma quando a imagem for cortada/ampliada ou usada em stories.
- 1 opção por imagem. Refinar e analisar o prompt com todo o contexto antes de gerar (incluindo a regra de qualidade do `legis-image-art-direction`); só gerar uma segunda quando a primeira não servir.
- O prompt nomeia explicitamente o mundo (WHITE infinite ou BLUE radial), o protagonista, o material, a lente, a profundidade de campo, a proporção de azul e o que evitar.
- A imagem anterior NÃO entra automaticamente como referência da próxima: usar referência só quando a continuidade realmente for necessária (mesmo personagem, objeto-símbolo ou cenário que precisa se repetir).
- Texto dentro da imagem: minimizar e usar só textos semanticamente importantes e curtos (ex.: "1 Hr.", "58 min.", "Processo localizado"), no primeiro plano; fundo sem texto. Escrever o texto exato entre aspas no prompt, conferir a ortografia no resultado e, se vier errado, corrigir no Figma (sobreposição) em vez de gerar de novo, quando possível.

## Princípios — do Legis_1hora (conceito e narrativa)

1. Um único objeto-símbolo atravessa todos os cards e muda de estado para contar a história (ex.: cubo "1 Hr." → "58" na mão → na mesa).
2. Abrir com uma pergunta ao leitor, não com uma afirmação do produto; o produto só "responde" no fechamento.
3. Um único ponto de alta luz por card, e ele é o símbolo; o resto fica 2–3 stops abaixo.
4. A resolução repete o enquadramento do card anterior mudando só um elemento (ex.: laptop aberto → fechado).
5. Alternar a escala de plano a cada card (close → médio humano → aberto → aberto resolvido); nunca dois closes seguidos.
6. Texto no terço superior, centralizado, sem competir com a área do objeto; headline até 3 linhas, subcopy até 2.
7. Logo só no primeiro e no último card, centralizado embaixo; cards do meio limpos.
8. Destaque cromático em no máximo um trecho por headline (palavra-chave em negrito azul, ou degradê no fim da frase).
9. Pessoa aparece cortada e em ação, com o gesto carregando o símbolo — não rosto e sorriso posados.
10. Uma "virada" de copy em tom menor ("Ou simplesmente…") antes do fechamento humaniza a promessa.

## Princípios — do Legis_Faltam5Dias (sistema e diagramação)

1. Sistema de módulos: fundo em degradê azul com moldura de ~31 px; card branco de texto + card de foto com o mesmo raio, encostados; alternar texto em cima/embaixo ao longo do carrossel.
2. Uma frase, um negrito: título é uma frase única, trecho-chave em Semibold e o resto Regular, mesma cor; evitar título + subtítulo quando uma frase resolve.
3. Informação prática (local, data, próximo passo) em chips/pílulas azuis com ícone, sempre como último elemento do card.
4. Foto como prova: em peças informativas (evento, lugar, pessoa real), preferir imagem factual à ilustrativa; se o texto afirma, a foto mostra. Em peças conceituais, vale o objeto conceitual do `legis-image-art-direction`.
5. Card 1 promete, os do meio entregam, o último convida; a promessa do card 1 tem de ser paga.
6. Um só contraste quente, guardado para o card de resolução; base azul no resto.
7. Variar escala de plano a cada card (multidão, retrato, objeto, arquitetura).
8. Marcadores de interface com moderação: notificação "Legis – agora mesmo" OU os pontinhos no canto — um por card, não ambos.
9. Legenda de pessoa em vidro: nome Semibold + cargo Regular num retângulo translúcido perto do ombro, sem cobrir o rosto.

## O que NÃO copiar desses exemplos

- Degradê que corta palavras ao meio ("termina|ria"): o degradê deve cair em palavras inteiras.
- Saltar de peso tipográfico entre cards (Regular → Semibold) sem sistema; escalas de título variando de 54 a 88 px; logo mudando de lugar sem regra.
- Visor/elemento-símbolo ilegível no payoff; fechamento de copy genérico ("trabalha por você") sem prova concreta nem CTA.
- Usar o BLUE radial sem função narrativa: o padrão da marca é o WHITE infinite; o BLUE só entra quando a mensagem pede impacto, tensão ou hero shot, e o ambiente azul precisa iluminar o objeto.
- Faixas escuras sem função; objeto escuro sobre fundo escuro que some na miniatura.
- Ícones de vidro de IA flutuando e linhas de órbita em volta de retrato (clichê, já repetido no ecossistema).
- Conceito só no texto (ex.: o "5" que nunca vira imagem); informação em 3 níveis de texto num mesmo card.
- Reutilizar o mesmo objeto-símbolo em outras peças — a força vem de ele ser inédito para o tema.
- Fotos de terceiros sem confirmar direitos de uso.