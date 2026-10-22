---
name: "volund-apresentacoes"
description: "Cria roteiro, estrutura e direção visual de apresentações (decks 16:9) da Volund a partir de um briefing, usando o sistema de slides dos decks de marca e apenas fatos aprovados."
---

# Volund — apresentações

Use quando o pedido envolver criar, estruturar, adaptar ou revisar uma apresentação da Volund: proposta comercial, pitch para cliente, evento ou palestra, institucional, investidor/parceiro, onboarding e cultura, recrutamento ou comunicação interna.

## Referências obrigatórias

1. **Anexo A — Contexto da marca Volund** (fim deste arquivo): posicionamento, fatos e provas já publicados, tom e regras factuais.
2. **Anexo B — Sistema visual de apresentações** (fim deste arquivo): formato, grid, tipografia, cores, componentes e catálogo de tipos de slide com node IDs de referência no Figma.
3. Para imagens de slide, aplique `volund-direcao-de-imagem-e-video`.

Material mais recente do usuário (deck novo, números, briefing) tem prioridade, sem alterar as referências salvas.

## Princípios

1. **Comece pela audiência e pela decisão.** Quem assiste e o que precisa decidir ou sentir no fim: contratar, agendar discovery, investir, entrar no time, adotar um processo. O deck serve a essa decisão.
2. **Títulos-tese, poucas palavras.** Cada slide afirma algo com a voz da Volund ("O impossível tem data de entrega.", "Sistemas envelhecem. As demandas, não."). Uma ideia por slide; o texto é o protagonista.
3. **Contraste velho × Volund.** Estruture a tensão: o jeito convencional (meses, grandes squads, alinhamento infinito) contra o jeito agêntico (escopo, prazo, entrega). Sem depreciar clientes, devs ou concorrentes.
4. **Prova antes de adjetivo.** Use os fatos da seção 12 do Anexo A (15 dias × 7 meses, case de jun/2026, R$ 1 bi gerenciado, imprensa), sempre com fonte. Meta (R$ 50 mi) nunca vira resultado. Dado ausente → `VALIDAR FONTE` e formulação sem número.
5. **Ritmo preto/foto/degradê.** Base preta; alterne slides só de texto, split texto + foto e split texto + textura (degradê com shapes ou vitral bifrost). Momentos de virada em frase única centralizada. No máximo três slides seguidos com a mesma estrutura.
6. **Use o sistema existente.** Monte cada slide a partir do catálogo (Anexo B). Se nenhum servir, descreva o novo layout com os mesmos tokens e marque `NOVO LAYOUT — VALIDAR`.
7. **Pessoas e direitos.** Fotos de pessoas reais só com direito de uso; pessoa gerada por IA nunca representa colaborador ou cliente real. Cliente do case não é nomeado sem autorização.
8. **Idioma.** PT por padrão; prepare versão EN quando a audiência for internacional (Extreme Group International) — adaptar, não traduzir literalmente.

## Fluxo

### 1. Interprete o briefing
Audiência e contexto · objetivo e decisão esperada · tempo de fala ou nº de slides · mensagem central · provas disponíveis · apresentador (capa e encerramento) · CTA · idioma · restrições. Liste só lacunas que mudam o deck e siga com suposições explícitas.

### 2. Escolha o arco narrativo
Proponha **dois ou três arcos**, recomende um e desenvolva-o.

| Objetivo | Arco sugerido |
|---|---|
| Proposta / pitch para cliente | Capa → a tensão do cliente (legado que envelhece ou sistema a construir) → por que o modelo convencional trava → o que é a Volund → como funciona (esteira agêntica, humanos decidem) → prova (case 15 dias, números com fonte) → como trabalhamos juntos (escopo, prazo, entrega; manter interno ou evolução contínua) → próximos passos (discovery call) → contato |
| Institucional / evento | Capa → frase-manifesto → o problema do software convencional → AI-native de verdade (nativo × acoplado) → como a Volund opera → provas e imprensa → origem (Recife, Porto Digital, Extreme Group) → visão → encerramento |
| Investidor / parceiro | Capa → mercado e mudança (AI-native services) → tese Volund → modelo de negócio → tração (com fonte) → time → visão/BHAG (só se aprovado) → pedido → contato |
| Cultura / onboarding / recrutamento | Capa → propósito → missão → visão → valores → manifesto → como trabalhamos (AI-native do requisito à entrega) → quem somos (time) → convite |
| Interno (comunicado, evento do time) | Capa com série/tema → mensagem → detalhes práticos → CTA |

Sem tamanho indicado, proponha 10–15 slides (5–8 no institucional curto) e diga que é ajustável.

### 3. Roteirize slide a slide
Para cada slide: **tipo** (nº e nome do catálogo, com node de referência) · **fundo/lado visual** · **rótulo** (label do topo) · **título/frase** · **apoio** (curto) · **elementos** (números, lista de valores, cards, foto, textura) · **direção de imagem** (cena, enquadramento, área livre) · **fonte/validação** · **nota de fala** opcional (1–2 frases que o apresentador diz e não estão no slide).

### 4. Montagem no Figma (quando solicitado)
- Duplique os frames de referência pelos node IDs do catálogo para um arquivo ou página nova indicada pelo usuário; nunca altere os arquivos de marca originais.
- Antes de usar as ferramentas de escrita do Figma, carregue a skill `figma-use` (e `figma-generate-design` para mudanças visuais).
- Imagens: 1 opção por imagem no Magnific (Seedream 5 Pro), prompt refinado antes, sem texto nem logo na imagem; texturas de degradê e vitral bifrost são construídas no Figma.

### 5. Revisão final
O deck responde à decisão da audiência? Capa e encerramento conversam? Todo slide tem título-tese e uma ideia? Números com fonte e período, metas separadas de resultados? Ritmo de fundos variado e viradas em frase única? Logo e lockup só onde o sistema prevê? Pessoas reais com direito de uso? CTA e contatos vieram do briefing (nunca inventar e-mail, telefone ou link)?

## Formato de resposta

### Brief interpretado
- **Audiência e contexto / Decisão esperada / Mensagem central / Tamanho e idioma:**
- **Suposições e validações:**

### Arcos possíveis
1. **[Nome]:** lógica e por que serve.
2. **[Nome]:** …
**Recomendação:** [arco e justificativa]

### Roteiro
| # | Tipo (catálogo) | Fundo / lado visual | Rótulo | Título | Conteúdo e elementos | Fonte/validação |
|---|---|---|---|---|---|---|

### Direção de imagens
[Uma linha por foto ou textura: mundo visual, cena, enquadramento, área livre.]

### Revisão
- **Pronto para montagem:** [sim / pendências]
- **Validar antes de apresentar:** [lista curta]

---

## Anexo B — Sistema visual de apresentações Volund

Fontes: "[Volund | Mini Guide]" (fileKey `wv8qoeZuQdBfly53bSJfdq`, página `0:1`), "[Volund | Identidade da marca]" (fileKey `p3gILUiuHlbbiXtMbP46xY`, página "Cultura" `277:28`) e banners 1920×1080 da página "Interno" do Social Media (fileKey `papIAMaPL5W0uWHptVsi0q`, `570:8`). Analisados em 06/10/2026.

### 1. Formato e grid
- 1920×1080 (16:9). Margem de 56 px nas laterais, topo e base.
- **Rótulo do slide** (nome da seção): Helvetica Neue Medium ~29–48 px, branco, em x56 y56.
- **Frase principal** em slides split: começa em y≈389, coluna de ~700–890 px à esquerda.
- **Lado visual** (foto, textura ou degradê): metade direita, a partir de x≈944–1129, sangrando até a borda.
- Texto longo (manifesto): duas colunas de ~667 px, a partir de y≈223.
- Sem rodapé fixo; logo só na capa, encerramento e slides-assinatura.

### 2. Tipografia
- **Helvetica Neue** — rótulo (Medium ~29–48), frase principal (Regular ~56–67, entrelinha ~1,2), corpo (Regular ~24–32), títulos de lista (Medium ~32).
- **DM Mono** caixa alta — tags de série (ex.: [MORE THAN CODE]), legendas, números de dado, fontes. Corpo pequeno, entreletra aberta.
- Um destaque rosa #EC3E61 por slide, no trecho-chave da frase.

### 3. Cores
#000000 (base) · #FFFFFF (texto e fundos de leitura) · #EC3E61 (destaque, ícones numerados) · #FF9A44 · degradê #FF9A44 → #EC3E61. Fotos com fundo em rosa/salmão quente fazem a ponte com a paleta.

### 4. Componentes
- **Lockup** "VOLUND by ✕ Extreme Group" (branco) e wordmark VOLUND gigante na capa.
- **Lista numerada:** círculo rosa com número branco + título Medium + texto de 3–4 linhas (valores, pilares, etapas), em duas colunas de 3.
- **Pílulas** com contorno branco e texto Medium (ex.: "VOLUND | SESSIONS").
- **Tag de série** em DM Mono entre colchetes no topo esquerdo.
- **Texturas:** light trails (capa), degradê com shapes/arcos em boolean, vitral bifrost, brilho atmosférico subindo do rodapé, arcos vermelhos em blur sobre preto.

### 5. Catálogo de tipos de slide
| # | Tipo | Estrutura | Referência |
|---|---|---|---|
| 1 | Capa | Light trails laranja/rosa sobre preto; rótulo do deck no topo esquerdo; wordmark VOLUND ocupando a largura no rodapé | Mini Guide `1:8`; Cultura `297:152` |
| 2 | Frase-manifesto | Preto, uma frase curta centralizada (ex.: "Velocity is the product.", "Forjando o impossível.") | Mini Guide `1:14`; Cultura `297:159` |
| 3 | Statement + foto | Rótulo no topo; frase principal à esquerda; foto editorial à direita (retrato com luz quente ou fundo salmão) | Cultura `297:170`, `297:177` |
| 4 | Statement + textura | Rótulo; frase à esquerda; textura geométrica (arcos em subtract, degradê com shapes) à direita | Cultura `297:174`, `297:180` |
| 5 | Título + texto + fotos | Título grande no topo; parágrafo na base esquerda; duas fotos verticais lado a lado à direita, com degradê | Cultura `297:194`, `297:218`, `297:221` |
| 6 | Título + texto + degradê | Título grande; texto longo na base esquerda; coluna de degradê em shapes à direita | Cultura `297:215` |
| 7 | Manifesto em duas colunas | Rótulo; texto corrido em duas colunas | Cultura `297:183` |
| 8 | Citação em destaque | Texto curto à esquerda (base); bloco à direita com degradê atmosférico e citação centralizada | Cultura `327:23` |
| 9 | Lista numerada (valores/pilares) | Rótulo; 6 itens em duas colunas com círculo rosa numerado | Cultura `371:10` |
| 10 | Paleta / dado visual | Colunas verticais com raio e legenda DM Mono | Mini Guide `1:64` |
| 11 | Banner de série / evento | Preto com shapes em degradê ou foto; título com destaque rosa; pílulas no rodapé | Interno `2321:160`, `2367:61` |
| 12 | Encerramento | Preto com wordmark centralizado (opcional lockup Extreme Group sobre brilho atmosférico) | Mini Guide `1:12`, `28:603`; Cultura `297:224` |

Para dados, case e processo (não cobertos nos decks de marca), adapte os componentes das peças de social: cards de dado com ícone + número rosa + legenda (maio `1646:87`), lista em pílulas com ícone e barras em degradê "AI" (junho `1870:39`), hexágonos de time e card com borda em degradê (setembro `2916:2590`). Marque `NOVO LAYOUT — VALIDAR`.

### 6. Padrões de escrita observados
- Rótulos curtos e nominais ("Nosso propósito", "BHAG", "Nossos valores"); a frase do slide carrega a tese.
- Frases declarativas, 1–4 linhas; nada de bullets longos.
- Valores e pilares: nome forte (2–3 palavras) + descrição em segunda pessoa ("Você opera sob a convicção de que…").

---

## Anexo A — Contexto da marca Volund (resumo; versão completa em `volund-conteudo-social` e no documento do projeto `claude/volund-contexto-de-marca.md`)

- **Volund:** companhia AI-native que entrega sistemas complexos em semanas; "engenharia de software nativa em IA" / engenharia agêntica; empresa do Extreme Group; base em Recife (Porto Digital), time também remoto. Instagram @volund.ai.
- **Taglines:** "Elite Craft. Radical Speed." · "Velocity is the product." · "Forjando o impossível." · "O impossível tem data de entrega."
- **Propósito / missão / visão:** ampliar a autonomia de pessoas e organizações por meio de IA · forjar soluções digitais complexas transformando intenção humana em software por engenharia agêntica · organizações materializando necessidades tecnológicas com autonomia real, sem barreiras técnicas, de estrutura ou burocracia.
- **BHAG (interno):** 1.000 sistemas complexos em produção até 2030 com menos de 5% de intervenção humana — `VALIDAR` antes de usar fora de decks internos.
- **Valores:** Positive Delusional · Donos do Caos · Somos a Resposta · Ambição de Elite · Eternos Artesãos · Essencialismo Radical. Manifesto: o normal não escala o impossível; domar a complexidade técnica; liberdade, autonomia e diversidade; não se apegar a métodos.
- **Públicos:** organizações que não podem esperar o ciclo tradicional (B2B) · talentos curiosos (employer branding).
- **Tom:** confiante, ousado, provocador, enxuto; contraste velho × novo; ambição sempre com prova ou como atitude.

### 12. Fatos e provas já publicados (usar com a fonte; números novos → `VALIDAR FONTE`)
- **Ofertas:** (1) modernização de legado — "A Volund descobre, mapeia e reconstrói", agentes de IA investigam a plataforma e extraem requisitos antes da primeira linha de código; (2) construção do zero — IA como infraestrutura, escopo e prazo definidos antes de começar, arquitetura que escala.
- **Modelo:** o cliente paga por entrega e pode manter o sistema internamente ou contratar a evolução contínua. Não terceiriza desenvolvimento nem monta grandes squads; "esteira agêntica" de ponta a ponta; decisões importantes passam por engenheiros sêniores.
- **Velocidade:** "entregamos em 15 dias o que o mercado leva 7 meses"; matéria cita "até 15 vezes mais rápido".
- **Case (jun/2026, [CLIENTE]):** empresa pública de tecnologia; plataforma para horas, contratos e faturamento de serviços de TI; em produção em 15 dias (expectativa: ~7 meses); fechamento de semanas para minutos; nos meses seguintes, ~15 entregas por dia com testes e auditoria. Cliente não nomeado.
- **Escala:** "R$ 1 bilhão gerenciado, hoje, pelos nossos sistemas em produção" (fonte: material interno Volund, 2026).
- **Imprensa:** Startups (entrevista com o CEO; meta de faturamento de R$ 50 milhões e equipe de 40–50 pessoas até o fim do ano — é META citada, nunca resultado); VC I.A., da Editora Abril (estreia, CEO como referência).
- **Pessoas:** Vinícius Guedes (CEO), Levi Nóbrega (CRO), João Moraes (Head de Operações), Davi Moura (Principal Engineer), Laryssa Câmara (People Manager).
- **Operação AI-native:** Vitória Lund, agente de IA "Chief of Staff virtual"; RHA (Recursos Humanos e Artificiais).
- **Origem:** Recife/Pernambuco, Porto Digital, CIn-UFPE e CESAR. Extreme Group International: "Feito no Brasil. Pensado para o mundo."
- Dados de terceiros (ex.: NVIDIA/Jensen Huang) só com a fonte visível no slide.

### Regras factuais
Não inventar clientes, cases, prazos, números, tecnologias, certificações nem depoimentos. Citações de pessoas reais só com texto aprovado. Pessoas geradas por IA não representam colaboradores ou clientes reais.

### Identidade visual (resumo)
#EC3E61 · #FF9A44 · degradê #FF9A44 → #EC3E61 · preto dominante · branco para leitura; Helvetica Neue + DM Mono caixa alta; wordmark VOLUND + "by ✕ Extreme Group"; texturas: light trails, degradê com shapes, vitral bifrost (vidro canelado), brilho atmosférico, partículas; fotografia sóbria, colaboradores com camiseta preta Volund, retratos com luz quente ou fundo salmão. O texto é o protagonista.