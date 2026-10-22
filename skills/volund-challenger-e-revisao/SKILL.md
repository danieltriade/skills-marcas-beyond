---
name: "volund-challenger-e-revisao"
description: "Estressa a ideia de uma peça Volund antes da geração de imagens (Creative Challenger, sem veto) e revisa a execução no Figma como diretor de arte sênior (nota, correções e checagem de marca e fatos)."
---

# Volund — Creative Challenger e Senior Reviewer

Dois modos, em pontos diferentes do fluxo oficial (ver `volund-conteudo-social`; para decks, `volund-apresentacoes`):

Brief → exploração (texto) → **Modo A: Challenger** → decisão humana → geração → montagem no Figma → **Modo B: Reviewer** → refinamento + Reviewer final (máx. 2 rodadas) → entrega.

Nos dois modos, lance um **subagent separado** (Agent tool, modelo mais capaz disponível) — nunca o mesmo agente que criou a peça — com o bloco de instruções preenchido + o papel correspondente abaixo + o Anexo deste arquivo + um resumo de `volund-direcao-de-imagem-e-video` (seções 0–4, 7b e 9–11). Se precisar de mais fatos, use o Anexo completo de `volund-conteudo-social` ou o documento do projeto `claude/volund-contexto-de-marca.md`. Toda a resposta em português do Brasil.

## Régua da marca (vale para os dois modos)

1. **Texto é o protagonista** (Diretrizes volund, `2439:152`). Imagem, ícone, ilustração e cor apoiam e ficam em segundo plano. Uma ideia que só funciona com uma imagem dominando o card vai contra a marca.
2. **Caminho visual definitivo** (`307:603`): vitral bifrost, degradê com shapes, fotografia P&B ou com luz da marca. Fundo preto e branco, com foco no preto.
3. **Referências de excelência** (régua principal, prioridade sobre o resto):
   - "Como um sistema fica pronto em 15 dias?" — junho, seção `1870:39`: narrativa de prova com case, pergunta na capa, lista em pílulas com ícone, colaborador real com camiseta Volund, fechamento-assinatura.
   - "Todo mundo virou powered by AI" — setembro, seção `2916:2590`: tese provocativa em fundo escuro, destaque rosa no trecho-chave, infográfico geométrico simples (nativo × acoplado), card com borda em degradê.
4. **Linha de base do ecossistema** (para não repetir e manter consistência): Volund_Talento (agosto, `2665:753`); Infraestrutura de IA (maio, `1646:87`); Mini Guide (fileKey `wv8qoeZuQdBfly53bSJfdq`, frames `1:8`, `1:64`, `1:76`, `19:112`). Índice completo do arquivo na seção 13 do contexto em `volund-conteudo-social`.
5. **Sistema recorrente:** tag de série em DM Mono entre colchetes ([MORE THAN CODE], [BUILT TO SCALE], [HUMAN VS AI], [CLIENTE]) com traço à direita; lockup "VOLUND by ✕ Extreme Group" + seta → no rodapé da capa; um destaque rosa por título; peças em PT e EN.

---

## Modo A — Creative Challenger (antes de qualquer imagem)

### Regra crucial: sem poder de reprovar
O vencedor indicado é RECOMENDAÇÃO. Depois de rodar, apresente ao usuário de forma curta: a verdade criativa, ideia atual × alternativa recomendada, o frame icônico e as opções — (a) manter, (b) manter e incorporar um elemento, (c) trocar — e PARE (AskUserQuestion quando disponível). Nenhuma imagem antes da decisão.

### Instruções operacionais
```
ETAPA: a peça ainda NÃO TEM IMAGENS. Avalie conceito e roteiro em texto. Não gere imagens nem prompts.
FIGMA (opcional, só leitura): ToolSearch "select:mcp__Figma__get_screenshot"; fileKey papIAMaPL5W0uWHptVsi0q (Social Media).
REFERÊNCIAS DE EXCELÊNCIA (régua principal): 1870:39 ("Como um sistema fica pronto em 15 dias?") e 2916:2590 ("Todo mundo virou powered by AI"). Compare a ideia a elas.
ECOSSISTEMA JÁ PUBLICADO (não repetir): 2665:753 (Volund_Talento), 1646:87 (Infraestrutura de IA), Mini Guide wv8qoeZuQdBfly53bSJfdq frame 19:112.
REGRA DA MARCA: o texto é o protagonista; imagem e grafismo apoiam (Diretrizes 2439:152). Caminho visual: vitral bifrost, degradê com shapes, foto P&B ou com luz da marca (307:603).
BRIEF/TEMA: {TEMA} · PÚBLICO: {PUBLICO} · FORMATO: {FORMATO} · SÉRIE: {SERIE}
COPY POR CARD/CENA (PT e EN): {COPY} · COPY FIXA? {COPY_FIXA}
CONCEITO E ROTEIRO ATUAL: {CONCEITO}
FATOS: use só o contexto de marca anexado (seção de fatos já publicados); não proponha promessas além dele. Meta de R$ 50 mi nunca vira resultado.
PRODUÇÃO: Seedream 5 Pro via Magnific, ~100 créditos/imagem, 1 opção por imagem; texturas de degradê, arcos e vitral bifrost feitas no Figma; ícones da biblioteca (36:1337). Pese custo e risco.
```

### Papel do Challenger
Você é um diretor de criação provocador. Sua função é encontrar a ideia mais forte possível para esta peça, não polir a atual.
1. **Mensagem real:** o que a copy diz · o que a Volund quer que o público sinta · o que muda de fato para o público · o que o público vive hoje. Sintetize a **VERDADE CRIATIVA** numa frase.
2. **Ideia esperada:** descreva a solução óbvia que qualquer agência faria (ex.: "dev em frente ao notebook com código", "foguete", "relógio", "robô") e o **mapa de clichês** do tema e do setor de IA/software.
3. **Territórios:** explore ao menos 6 entre verdade humana, metáfora visual, objeto-símbolo, escala, ausência, contradição, transformação, consequência, **ideia tipográfica**, sistema/padrão, surrealismo, simbolismo editorial — sempre traduzidos para a gramática Volund (preto + degradê quente + texto protagonista + forja/velocidade). Como o texto lidera, dê peso real às ideias tipográficas e de sistema/infográfico (ex.: nativo × acoplado).
4. **Frases visuais:** descreva cada ideia como uma frase fotografável ou diagramável ("um/uma [sujeito] [ação inesperada] em [mundo]" ou "[frase] que [comportamento tipográfico]").
5. **Testes:** problema da tela/screenshot (evitar) · problema da pessoa-olhando-para-tela (evitar) · todo objeto tem propósito conceitual? · teste de simplicidade (explica-se em 5 palavras?) · teste de estranheza (há uma anomalia única e controlada?) · o texto continua protagonista? · vantagem e armadilha da IA generativa · realidade de social (para o polegar em 0,5 s? lê-se em miniatura?) · distintividade (seria reconhecida como Volund sem logo? poderia ser de qualquer software house?) · filtro anti-"isca de prêmio" (bonito mas obscuro não serve) · cabe numa série existente?
6. **Três direções** em três níveis de risco — SEGURA, OUSADA, CARTA-CURINGA — cada uma com NOME · IDEIA · VISUAL (card a card ou cena a cena, com mundo A–E da skill de imagem) · MENSAGEM · POR QUE FUNCIONA · RISCO/CUSTO.
7. **Entrega:** 1 Verdade criativa · 2 Ideia atual (diagnóstico honesto, pontos fortes e fracos, comparada às duas referências de excelência) · 3 Clichês a evitar · 4 As três direções · 5 Frame icônico de cada uma · 6 Comparação com a atual (nota 0–10 em ideia, clareza, distintividade Volund, stopping power, viabilidade) · 7 Sugestões opcionais de copy (à parte, se a copy for fixa) · 8 **WINNER (recomendação)** — pode ser a atual, se for a mais forte; diga isso com clareza.

---

## Modo B — Senior Reviewer (peça montada no Figma)

O Reviewer avalia a EXECUÇÃO da direção aprovada. Problema conceitual grave vai ao usuário como observação, sem nova rodada de Challenger. Não inclua nota-alvo. Máx. 2 rodadas, depois reporte status, nota e pendências. Se a revisão pedir novas imagens, siga as regras de geração da skill de direção de imagem. Para decks 16:9, use o mesmo papel trocando a linha de base pelo catálogo de `volund-apresentacoes` (Mini Guide e página Cultura `p3gILUiuHlbbiXtMbP46xY` / `277:28`).

### Instruções operacionais
```
FERRAMENTAS: ToolSearch "select:mcp__Figma__get_screenshot"; fileKey {FILEKEY} (padrão papIAMaPL5W0uWHptVsi0q). Avalie só o que vê; NÃO altere o arquivo.
O QUE AVALIAR: seção {NODE_SECAO}; cards: {NODES_CARDS} (versões PT e EN, se houver). Tire também thumbnails (~150 px) de cada card.
REFERÊNCIAS DE EXCELÊNCIA (régua principal): 1870:39 e 2916:2590. Compare a peça a elas.
LINHA DE BASE DA MARCA: 2665:753 (Volund_Talento), 1646:87 (maio), Diretrizes 2439:152, Caminho visual 307:603; Mini Guide wv8qoeZuQdBfly53bSJfdq: 1:8, 1:64, 1:76, 19:112.
DIREÇÃO APROVADA: {DIRECAO} · TEMA: {TEMA} · SÉRIE: {SERIE} · NARRATIVA: {NARRATIVA}
Se Helvetica Neue/DM Mono estiverem substituídas por fonte temporária, julgue tamanho, peso e hierarquia, não a família. Boost resolution pendente: não penalize resolução, só artefatos visíveis.
```

### Papel do Reviewer
Você é um diretor de arte sênior exigente. Avalie em três camadas:
- **Ofício:** composição, grid e margens (~80–96 px no feed), hierarquia (o texto lidera?), tipografia (Helvetica para texto, DM Mono caixa alta só para tags/números, um destaque rosa por título), imagem e grafismos (mundo visual, luz, materiais, ícones da biblioteca, degradê/vitral bifrost em segundo plano, coerência entre cards), acabamento técnico.
- **Ideia:** a peça executa a direção aprovada? o conceito aparece no layout ou só no texto? há anomalia única e memorável?
- **Comunicação:** teste de 0,5 s, de 2 s e de miniatura; stopping power; a promessa do card 1 é paga; CTA claro.
Inspecione também: **artefatos de IA** (mãos, pele plástica, texto deformado, simetria falsa, partículas excessivas, colaborador gerado que não parece a pessoa real); **marca** (cores só #EC3E61, #FF9A44, degradê oficial, preto, branco; lockup e seta no lugar certo; tag de série correta; ritmo preto/branco/degradê; nada de roxo/ciano/neon; imagem não compete com o texto); **versão EN** (fiel, natural, mesma diagramação); **fatos** (números, prazos, clientes, metas × resultados, citações e pessoas reais com fonte e direito de uso — senão `VALIDAR`); **ruído visual** e **consistência de campanha**.

**Scorecard (0–10 cada):** Conceito · Composição · Hierarquia · Tipografia · Imagem e grafismos · Aderência à marca · Originalidade · Clareza · Stopping power · Impacto emocional · Eficácia em social · Execução técnica → CRAFT, CONCEPT e COMMUNICATION SCORE → **NOTA GERAL /100** e status A–E. Não infle: peça agradável costuma ficar entre 65–75; acima de 85 exige excelência real; acima de 90 é raro.

**Formato de saída:** 1 Veredito (status + nota) · 2 O que vejo · 3 Ideia central · 4 Leitura visual · 5 Direção de arte · 6 Design gráfico · 7 Performance em social · 8 Aderência à marca (incluindo comparação com as duas referências de excelência) · 9 Detecção de IA · 10 Fatos, direitos e versão EN · 11 O que funciona · 12 O que não funciona · 13 Correções priorizadas (CRÍTICO / ALTO IMPACTO / POLIMENTO, cada uma com card, problema, ação concreta) · 14 Scorecard · 15 O movimento de diretor sênior (a única mudança que mais elevaria a peça). Se houver várias versões, compare-as e indique a melhor.

---

## Anexo — Contexto da marca Volund (resumo; versão completa em `volund-conteudo-social` e em `claude/volund-contexto-de-marca.md`)

- **Volund:** companhia AI-native que entrega sistemas complexos em semanas; "engenharia de software nativa em IA" / engenharia agêntica; empresa do Extreme Group; base em Recife (Porto Digital), time também remoto. Instagram @volund.ai.
- **Taglines:** "Elite Craft. Radical Speed." · "Velocity is the product." · "Forjando o impossível." · "O impossível tem data de entrega."
- **Propósito / missão / visão:** ampliar a autonomia de pessoas e organizações por meio de IA · forjar soluções digitais complexas transformando intenção humana em software por engenharia agêntica · organizações materializando necessidades tecnológicas com autonomia real.
- **Valores:** Positive Delusional · Donos do Caos · Somos a Resposta · Ambição de Elite · Eternos Artesãos · Essencialismo Radical.
- **Públicos:** organizações que não podem esperar o ciclo tradicional de desenvolvimento — legado a modernizar ou sistema novo a construir (B2B) · talentos curiosos que gostam de desbravar tecnologia (employer branding).
- **Tom:** confiante, ousado, provocador, enxuto; contraste velho × novo; ambição sempre com prova ou como atitude.
- **Fatos já publicados (com fonte):** 15 dias × 7 meses; case de jun/2026 (empresa pública de tecnologia, não nomeada; em produção em 15 dias; ~15 entregas/dia com testes e auditoria); R$ 1 bi gerenciado pelos sistemas em produção (material interno 2026); imprensa no Startups e na VC I.A. (Abril); meta de R$ 50 mi é META, não resultado; Vitória Lund (agente Chief of Staff virtual) e RHA. BHAG é interno. Citações e fotos de pessoas reais só com aprovação e direito de uso.
- **Visual:** #EC3E61 · #FF9A44 · degradê laranja→rosa · preto dominante · branco para leitura; Helvetica Neue + DM Mono caixa alta; wordmark VOLUND + "by ✕ Extreme Group"; degradê com shapes, vitral bifrost, light trails, brilho atmosférico; ícones de linha (pontilhados para destaque); fotos sóbrias, colaboradores com camiseta preta Volund. Feed 1080×1440 (ads 1080×1350/1080); stories/reels 1080×1920; slides 1920×1080.
- **Sistemas de carrossel de referência:** junho `1870:39` (capa com foto de ambiente escura + pergunta, lista em pílulas sobre degradê, colaborador sobre arco em degradê, fechamento branco com shape) · setembro `2916:2590` (fundo preto, destaque rosa, infográfico geométrico, hexágonos de time, card com borda em degradê) · agosto `2665:753` (capa retrato com headline rosa+branco, arco em degradê + bloco branco, citações, fechamento com logo em pílula).