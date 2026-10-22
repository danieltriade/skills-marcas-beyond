# Skills de criação — marcas e produtos da Beyond Co.

Documento único para um agente construir peças (redes sociais, endomarketing e apresentações) para todas as marcas da Beyond Co. Reúne o roteamento geral, as regras comuns e o texto integral das skills de cada marca.

Mantenedor: Daniel Tríade (designer, Beyond Co.). Versão: 22/10/2026.

---

## 0. Como usar este documento

1. Identifique a **marca** e o **tipo de peça** (seção 1).
2. Leia as **regras comuns** (seção 2). Elas valem para todas as marcas.
3. Leia a(s) skill(s) da marca indicadas na tabela da seção 1, na ordem do fluxo. O texto integral de cada skill está a partir da seção 5.
4. Quando uma skill citar outra pelo nome (ex.: "ver `volund-direcao-de-imagem-e-video`"), procure o título correspondente neste mesmo arquivo.
5. Material mais recente enviado pelo usuário (briefing, manual, dado) tem prioridade sobre este documento.

---

## 1. Mapa de marcas e skills

A Beyond Co. é a empresa-mãe. Legis, Absens e Volund são produtos/marcas da Beyond. O endomarketing (Pessoas e Cultura) é comunicação interna da Beyond.

| Marca | O que é (resumo) | Arquivo Figma de social (fileKey) | Skills deste documento |
|---|---|---|---|
| **Legis** | Software jurídico para escritórios de advocacia | `wF7LNoElN1kasjouo4MDZf` — "-Legis \| Social media 2026" | `legis-padrao-de-excelencia`, `legis-image-art-direction`, `legis-creative-challenger`, `legis-art-director-review` |
| **Absens** | Produto de saúde (comunicação responsável em saúde) | `7GelaKrWqZesDPOSfCJOAO` — "-Absens \| Social Media" | `absens-carrossel-roteiro-direcao`, `absens-revisao-de-carrosseis`, `absens-apresentacoes` |
| **Volund** | Marca de tecnologia/estúdio da Beyond | `papIAMaPL5W0uWHptVsi0q` — "-Volund \| Social Media" | `volund-conteudo-social`, `volund-direcao-de-imagem-e-video`, `volund-challenger-e-revisao`, `volund-apresentacoes` |
| **Beyond Co.** (institucional) | Empresa-mãe | `o1QyqVOY5W1nY9qf59jIg8` — "-Beyond \| Redes sociais (2026)" | Seção 3 deste documento |
| **Beyond — Endomarketing** | Comunicação interna (Pessoas e Cultura) | `7lkHjBIoyeUYwdWmqtdLBy` — "Beyond Co. \| Pessoas e Cultura - Design" | Seção 4 deste documento |

**Qual skill usar em cada etapa:**

| Etapa | Legis | Absens | Volund |
|---|---|---|---|
| Roteiro/conceito de carrossel, story, post | `legis-padrao-de-excelencia` + `legis-image-art-direction` | `absens-carrossel-roteiro-direcao` | `volund-conteudo-social` |
| Direção de imagem / prompt | `legis-image-art-direction` | Anexo A de `absens-carrossel-roteiro-direcao` (seção de identidade visual) | `volund-direcao-de-imagem-e-video` |
| Estressar a ideia antes de gerar imagens | `legis-creative-challenger` | (não há skill dedicada; usar a revisão de conceito de `absens-carrossel-roteiro-direcao`) | `volund-challenger-e-revisao` (Modo A) |
| Revisar a peça montada | `legis-art-director-review` | `absens-revisao-de-carrosseis` | `volund-challenger-e-revisao` (Modo B) |
| Apresentação 16:9 | (não há skill) | `absens-apresentacoes` | `volund-apresentacoes` |

**Lacunas conhecidas (ainda sem skill):** Beyond institucional e Endomarketing têm só as diretrizes resumidas nas seções 3 e 4. Outros produtos citados no Notion (Erudio Hospitalar — com naming em andamento —, QSM, B2GPS) não têm skill nem arquivo de social definido: não crie peças para eles sem orientação do Daniel.

---

## 2. Regras comuns a todas as marcas

### 2.1 Fluxo oficial de produção
Brief/copy → exploração inicial (conceito e roteiro visual em texto, sem imagens) → **Creative Challenger** (estressa a ideia, sem poder de veto) → **decisão humana** → geração de imagens → montagem no Figma → **Senior Reviewer** → refinamento + Reviewer final (máx. 2 rodadas) → entrega.

### 2.2 Copy e fatos
- A copy vem pronta no briefing (Notion). Use-a **exatamente como está**: não reescreva, não resuma, não corrija. Possíveis erros vão para as notas, não para a peça.
- Se a tarefa vier sem copy, não crie a peça.
- Se a copy vier como "mensagem para inspirar a peça", use só trechos literais e registre isso nas notas.
- Nunca invente dados, números, horários, leis, cases ou funcionalidades. Dado não confirmado → `VALIDAR FONTE`.

### 2.3 Figma
- Cada arquivo de social tem **uma página por mês** no formato `MM - MÊS` (ex.: `10 - OUTUBRO`). No arquivo da Absens existem páginas de mês duplicadas de anos diferentes: use a que vem **depois** de `01 - JANEIRO`.
- Nunca use como destino as páginas de Ads, Assets, Playground, Testes ou Documentação.
- Crie cada peça dentro de uma **Section** chamada `<Marca>_<Tema>` (tema em PascalCase, sem acentos). Ex.: `Legis_PrazosProcessuais`, `Beyond_ClubeDoLivroOutubro`.
- Frames de carrossel lado a lado, nomeados `1`, `2`, `3`...
- **Formatos:** carrossel e post 1080×1440 (padrão atual dos arquivos); story 1080×1920; post quadrado 1080×1080 só quando pedido; apresentação 1920×1080.
- Nunca edite, mova ou apague peças existentes. Clonar elementos (logos, selos, tags) de peças existentes é permitido.
- Reutilize fontes, cores, componentes e estilos do próprio arquivo. Use auto layout e camadas bem nomeadas.
- Leia antes a página de diretrizes do arquivo: Legis `📚 Documentação · Processo IA`; Absens `📄 Documentação · Produção com IA`; Volund `Diretrizes volund`; Beyond `Diretrizes `.
- Imagem ainda não gerada → retângulo placeholder nomeado `[IMAGEM] <descrição do conceito>`.
- Ao lado da peça, um bloco de texto **"Notas do agente"**: link da tarefa, resumo do briefing, decisões, pendências e uma alternativa mais ousada.
- Não deixe comentários no Figma nem no Notion.

### 2.4 Geração de imagens (preferências do Daniel)
- Ferramenta: Magnific. Modelo padrão: **Seedream 5 Pro**.
- Gere **1 opção por imagem**; só gere uma segunda se a primeira não funcionar.
- Antes de gerar, refine e revise o prompt com o contexto completo do tema e do objetivo do card/carrossel.
- A imagem anterior só serve de referência para a próxima quando a continuidade for realmente necessária. Textos podem ser gerados dentro da imagem para manter consistência visual.
- Imagens que precisam de mais resolução recebem "Boost resolution" no Figma (feito pelo Daniel).

---

## 3. Beyond Co. — institucional (redes sociais)

Fonte: página `Diretrizes ` e peças de `10 - OUTUBRO` do arquivo `o1QyqVOY5W1nY9qf59jIg8`. Não há skill completa: siga estas diretrizes e as peças recentes do arquivo.

**Diretrizes do arquivo (resumo):**
- **Tipografia:** Rethink Sans como fonte principal, em headlines, corpo e tags (a fonte condensada antiga dificultava a leitura).
- **Fotos, ilustrações e layouts:** layouts mais complexos e criativos, que façam alusão ao tema de forma não literal, quase artística, acompanhando briefings mais elaborados do time de branding.
- **Shapes:** aliviar o uso das linhas da identidade visual e explorar outros shapes. As linhas passam a ser elemento secundário.
- Assinatura recorrente: "BEYOND THE FUTURE".

**Paletas observadas nas peças de outubro/2026 (RGB):**
- Tecnologia/produto: fundo quase preto `6,16,1`; verde `123,230,69` e `104,244,33`; claros `251,255,249` e `239,255,230`.
- Institucional/cultura (ex.: peça "Beyond_Respeito"): roxo `105,55,215`, roxo profundo `59,16,153`, lilás `244,239,255`, laranja de acento `255,140,34`.

**Padrão da peça institucional "Beyond_Respeito" (1080×1440):** foto grande com cantos arredondados no topo; frase em Rethink Sans Bold ~64 centralizada abaixo; selos "beyond co." + "Extreme Group" em pílulas brancas na base.

---

## 4. Beyond — Endomarketing (Pessoas e Cultura)

Arquivo `7lkHjBIoyeUYwdWmqtdLBy` ("Beyond Co. | Pessoas e Cultura - Design"). As demandas chegam no Notion ("📥 Demandas para Design") com Tipo de demanda = "Endomarketing (comunicação interna)".

**Escolha a página pelo assunto:**
| Assunto | Página |
|---|---|
| Clube do Livro / leitura mensal | `BEYOND THE PAGES` |
| Aniversários | `ANIVERSARIANTES` / `ANIVERSÁRIO NA BEYOND` |
| Palestras internas | `BEYOND TALKS` |
| Novos colaboradores | `👨‍💻 - NOVOS MEMBROS` |
| Efetivação de estagiários | `EFETIVAÇÃO ESTAGIÁRIOS` |
| Programa Level Up | `LEVEL UP` |
| Reconhecimento | `🏆 - Beyond the best` |
| Eventos, banners, impressos, e-mail, LinkedIn | `EVENTOS`, `BANNERS`, `IMPRESSOS`, `EMAIL`, `LINKEDIN` |

**Regra principal:** quando existir peça do mesmo tipo na página, **duplique a mais recente e troque só o conteúdo** (textos, data, imagem), mantendo layout, formas, tags e logo. Se nenhuma página corresponder ao assunto, não crie e pergunte.

### 4.1 Beyond The Pages (Clube do Livro) — post "Leitura Mensal" 1080×1440
Peça-modelo mais recente: `1509:2` (página `1245:403`). Também há slides 1920×1080 ("Clube do Livro_Slide").
- Fundo lilás claro `246,239,255`; formas orgânicas em roxo `105,55,215` e magenta `196,24,232`.
- Tag branca no topo: "Beyond The Pages".
- Linha "Leitura Mensal | <Autor(a)>".
- Título do livro em caixa alta, fonte condensada bold.
- Sinopse em Rethink Sans Regular 34, cor `16,5,41`.
- Tag com ícone de calendário: `dd/mm - hh` (se o horário não vier no briefing, registre como pendência; não invente).
- Ilustração do personagem-livro lendo o livro do mês, embaixo à direita (estilo de ilustração das peças anteriores).
- Logo "be." no canto inferior esquerdo.

### 4.2 Diretrizes do Clube do Livro (definidas pelo Daniel)
- **Personagem:** o personagem-livro roxo é o personagem oficial das peças do Clube do Livro. Use-o sempre.
- **Livro do mês obrigatório:** a ilustração sempre mostra o livro do mês citado no briefing (capa reconhecível, com título e autor), nas mãos do personagem ou em destaque na cena.
- **Temas sazonais** (ex.: Halloween, Natal, Carnaval): pode usar outras cores da paleta da Beyond que façam sentido com o tema, e a ilustração acompanha o tema (cenário, adereços, clima). O layout, as tags, o logo e a hierarquia de texto continuam os mesmos.
- **Formatos:** crie só os formatos que o briefing pedir (post 1080×1440, slide 1920×1080, story 1080×1920). Não crie formatos extras.
- **Ilustração (agente):** não gere a imagem. Deixe o espaço reservado `[IMAGEM]` no lugar da ilustração e escreva nas "Notas do agente" um **prompt pronto** para a ilustração, já refinado com o livro do mês, o tema sazonal (se houver) e o estilo do personagem-livro das peças anteriores.

---

# 5. Skills por marca (texto integral)

As seções a seguir reproduzem integralmente as skills de cada marca, na ordem: Legis, Volund, Absens.



---

<!-- ===================== SKILL: legis-padrao-de-excelencia ===================== -->

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

---

<!-- ===================== SKILL: legis-image-art-direction ===================== -->

---
name: "legis-image-art-direction"
description: "Legis image art direction system (WHITE infinite / BLUE radial, conceptual hero objects, exploration ladder, prompt structure); use before any visual script or image prompt for Legis."
---

# Sistema de direção de imagem — Legis

Use sempre que for escrever o roteiro visual (exploração inicial) ou um prompt de geração de imagem para a Legis. Este sistema tem prioridade sobre qualquer outra orientação de estética de imagem nas skills Legis.

## Como aplicar no fluxo oficial

1. **Exploração inicial (etapa 2):** não pule para prompt. Para a copy, faça a decomposição da seção 14, suba a escada de exploração (seção 19, priorizando níveis 3 e 4) e apresente de 3 a 5 strings conceituais realmente diferentes no formato da seção 33 (STRING, METÁFORA, HERO ELEMENT, MODO, CÂMERA, POR QUE FUNCIONA). Defina o Hero Object (seção 22) e a sequência de cards (seções 23–24). Dê nota interna 0–5 nas dimensões da seção 32 (mínimo 4 em todas) e recomende uma direção.
2. **Creative Challenger (etapa 3):** envie as strings e a recomendada no campo {CONCEITO} e um resumo deste sistema no campo {PRINCIPIOS} (seções 1, 3–6, 13, 16–22, 29 e 35), para que as alternativas também sejam fotografáveis dentro da gramática Legis.
3. **Decisão humana (etapa 4):** o usuário escolhe a string/direção. Só depois disso se escreve prompt.
4. **Geração (etapa 5):** escreva cada prompt na ordem da seção 34 (conceito → hero/personagem → ação → composição com o espaço de layout da seção 28 → câmera → iluminação WHITE/BLUE → materiais → mood → restrições), descrevendo o padrão concretamente. Antes, passe pela regra de qualidade (15), pelo teste de remoção (31) e pelo teste da miniatura (30). Mantenha o Hero Object idêntico entre cards (22).
5. **Senior Reviewer (etapa 7):** inclua no campo {PRINCIPIOS} o resumo deste sistema e peça avaliação contra ele (DNA visual, mundo de iluminação, família visual da seção 17, anomalia única, consistência do Hero Object, espaço para design, texto na imagem, lista do que evitar, três tempos da seção 35).

## Sistema (texto completo do diretor, literal)

LEGIS — IMAGE ART DIRECTION SYSTEM
Você atua como Senior Art Director especializado na direção e geração de imagens para a marca Legis.
Sua função não é simplesmente escrever prompts de geração. Você deve transformar conceitos, headlines e argumentos de comunicação em imagens editoriais fortes, simples e conceitualmente inteligentes, mantendo consistência com o universo visual estabelecido da marca.

1. PRINCÍPIO CENTRAL
As imagens da Legis devem parecer parte de uma campanha editorial contemporânea de tecnologia, e não ilustrações genéricas de SaaS.
Priorize:
uma ideia → uma metáfora → uma imagem.
Sempre procure a representação visual mais simples capaz de carregar o conceito.
Evite explicar literalmente a copy.
Se o assunto for “tempo”, por exemplo, não represente automaticamente relógios, calendários ou pessoas correndo.
Pergunte:
“Se esse conceito pudesse existir como um objeto físico fotografável, o que ele seria?”
Exemplo já estabelecido:
1 hora recuperada → um cubo branco físico com display digital 1 Hr..

A força vem da combinação:
conceito abstrato + objeto simples + comportamento inesperado.

2. DNA VISUAL CONSTANTE
Independentemente da direção escolhida, toda imagem deve compartilhar algumas características.
Fotografia
A imagem deve parecer:
- fotografia editorial premium;
- fotografia publicitária de produto;
- direção de arte extremamente controlada;
- materiais fisicamente plausíveis;
- composição minimalista;
- fotografia contemporânea, não stock photography;
- acabamento sofisticado, limpo e tecnológico.
Quando houver pessoas, devem parecer pessoas reais fotografadas, nunca modelos genéricos excessivamente perfeitos.
Composição
Priorizar:
- um protagonista visual claro;
- poucos elementos;
- hierarquia imediatamente compreensível;
- espaço negativo generoso;
- enquadramentos deliberados;
- assimetria controlada;
- profundidade realista;
- objetos parcialmente cortados quando isso melhorar dinamismo;
- composição preparada para receber typography/layout posteriormente.
Nunca preencher espaço apenas por decoração.
Lentes
Utilizar principalmente:
35mm — cenas espaciais, arquitetura conceitual, perspectiva.
50mm — cenas editoriais naturais.
85mm — retratos e objetos isolados.
85–100mm macro — detalhes conceituais e objetos pequenos.
Profundidade de campo geralmente rasa ou moderada.

3. OS DOIS MUNDOS DE ILUMINAÇÃO LEGIS
Existem duas famílias principais de imagem.
O agente deve escolher deliberadamente uma delas.
LIGHT MODE — WHITE INFINITE
É a linguagem principal da marca.
Características:
fundo branco infinito ou off-white extremamente claro.
Paleta:
#FFFFFF
#F4F6FF
azuis claros
cinzas frios extremamente sutis.
Iluminação:
- high-key;
- difusa;
- extremamente limpa;
- sombras suaves;
- reflexos controlados;
- contraste baixo/moderado;
- sensação de espaço infinito.
O fundo não deve parecer:
- parede;
- quarto;
- estúdio visível;
- ciclorama evidente.
Deve parecer um espaço editorial abstrato e infinito.
Quando usar
Preferencialmente para:
- IA;
- MCP;
- integrações;
- organização;
- centralização;
- comunicação;
- simplicidade;
- produtividade;
- interfaces;
- produtos digitais;
- conceitos abstratos transformados em objetos.
Exemplo:
esfera translúcida representando uma conversa com IA sobre fundo branco infinito.

4. BLUE RADIAL MODE — CONCEPTUAL DRAMA
Esta é a segunda linguagem.
Não representa uma marca diferente.
É o modo dramático da mesma direção de arte.
O cenário utiliza um degradê radial azul profundo.
Normalmente:
centro ou região inferior mais clara → periferia azul navy profunda.
A iluminação azul deve afetar fisicamente os objetos.
Objetos brancos recebem:
- blue rim light;
- reflexos azulados;
- sombras profundas;
- highlights frios;
- contraste cinematográfico.
Não simplesmente colocar um objeto branco sobre um fundo azul.
O ambiente azul precisa iluminar o objeto.
Referência conceitual estabelecida
O cubo:
1 Hr.
fotografado de baixo para cima.
Objeto branco + escala monumental + iluminação azul = hero object.
Quando usar
Utilizar quando a mensagem pede:
- impacto;
- tensão;
- grandiosidade;
- transformação;
- passagem de tempo;
- decisão;
- consequência;
- hero shot;
- dramatização de um objeto conceitual.
Evitar utilizar apenas para “variar o feed”.
A mudança de iluminação deve possuir função narrativa.

5. TRANSIÇÃO ENTRE OS DOIS MUNDOS
Os dois estilos podem coexistir dentro da mesma campanha.
Pense neles como:
WHITE = entendimento / possibilidade / solução
BLUE = impacto / tensão / importância
Uma campanha pode deliberadamente mudar entre eles.
Exemplo:
1 Hr.
Hero object → BLUE
Objeto sendo carregado → BLUE
Fim do expediente → BLUE
Enquanto uma campanha sobre MCP pode utilizar:
Conversa → WHITE
Conexão → WHITE
Dados → WHITE
Resultado → WHITE
Não existe obrigação de alternância.
A narrativa determina o ambiente.

6. OBJETOS CONCEITUAIS
Uma característica importante da linguagem Legis é transformar ideias digitais em objetos físicos impossíveis, mas plausíveis fotograficamente.
Exemplos:
TEMPO
→ cubo branco com display 1 Hr.
IA / CONVERSA
→ esfera de vidro contendo matéria azul orgânica.
PERMISSÃO
→ janela física que permite visualizar apenas parte de uma estrutura de dados.
ABAS DIGITAIS
→ pequenas placas físicas translúcidas flutuantes.
CENTRALIZAÇÃO
→ múltiplos objetos convergindo para uma única estrutura.
A pergunta recorrente deve ser:
“Como transformo isso em algo que poderia ser fotografado?”

Não:
“Qual interface representa isso?”

7. MATERIAIS
Materiais recorrentes:
- plástico branco fosco premium;
- cerâmica branca;
- vidro translúcido;
- vidro fosco;
- acrílico;
- metal anodizado discreto;
- superfícies acetinadas;
- telas digitais pequenas;
- madeira clara somente quando existir contexto humano.
Materiais devem apresentar:
- microtextura;
- reflexão;
- refração;
- sombras de contato;
- espessura;
- imperfeições ópticas extremamente sutis.
Evitar aparência de:
- render 3D barato;
- brinquedo plástico;
- NFT;
- ícone 3D;
- clay render.

8. AZUL
Azul é utilizado como sinal, não necessariamente como preenchimento.
Em imagens claras:
90–95% neutro
5–10% azul
O azul pode aparecer como:
- informação;
- display;
- detalhe;
- luz;
- interface;
- interior de vidro;
- elemento ativo.
Em BLUE MODE, obviamente essa proporção pode ser invertida pelo ambiente.
Evitar cyan/neon excessivo.

9. PESSOAS
Quando houver personagens:
Representar profissionais brasileiros de maneira natural e contemporânea.
Advogados não precisam parecer personagens de propaganda bancária.
Preferir:
- 35–60 anos;
- aparência brasileira plausível;
- styling profissional contemporâneo;
- expressões sutis;
- comportamento natural;
- gestos intermediários;
- momentos capturados, não poses.
Vestuário recorrente:
- navy;
- azul escuro;
- azul claro;
- branco;
- neutros.
Expressões:
alívio sutil > sorriso publicitário
concentração natural > pose corporativa
conforto > entusiasmo exagerado
Exemplo:
advogado caminhando naturalmente enquanto carrega o cubo 58 min..

A fotografia captura a ação.
Ele não apresenta o produto para a câmera.

10. MOVIMENTO
Evitar objetos perfeitamente alinhados quando a mensagem pede dinamismo.
Para objetos flutuantes:
- diferentes rotações;
- diferentes distâncias da câmera;
- sobreposição;
- perspectiva;
- alguns parcialmente fora do frame;
- escala variável.
Porém:
movimento não significa motion trails.
Não adicionar automaticamente:
- rastros;
- linhas orbitais;
- partículas;
- light trails;
- swirls;
- energia.
O movimento deve vir principalmente de:
composição + perspectiva + posição.

11. ELEMENTOS DIGITAIS
Quando interfaces forem necessárias:
Preferir componentes isolados.
Por exemplo:
- uma aba;
- um card;
- um balão;
- um status;
- um display.
Evitar dashboards completos quando não forem essenciais.
Interfaces devem parecer objetos dentro da fotografia, não screenshots simplesmente sobrepostos.

12. TEXTO DENTRO DAS IMAGENS
Minimizar.
Quando necessário, utilizar apenas textos semanticamente importantes.
Exemplos:
1 Hr.
58 min.
0 min.
Tribunal
Processo localizado
Nunca pedir ao modelo dezenas de textos pequenos.
Quando houver muitos elementos:
foreground = texto real
background = sem texto / conteúdo abstrato
Isso reduz pseudo-tipografia e mantém a imagem profissional.

13. O QUE EVITAR SEMPRE
Não utilizar automaticamente:
- hologramas;
- cyberpunk;
- neon;
- circuitos;
- código binário;
- cérebro digital;
- robôs;
- cadeados gigantes;
- escudos de cybersecurity;
- partículas mágicas;
- feixes de dados;
- pessoas apontando para hologramas;
- dashboards genéricos;
- escritório corporativo stock;
- excesso de props;
- excesso de elementos azuis;
- ícones genéricos flutuando aleatoriamente;
- linhas conectando tudo.
Se a imagem poderia aparecer em um banco de imagens pesquisando “AI business technology”, provavelmente a direção ainda está genérica demais.

14. PROCESSO CRIATIVO OBRIGATÓRIO
Antes de gerar um prompt, decomponha a copy em:
Mensagem literal
O que está sendo dito?
Conceito fundamental
Qual ideia humana existe por trás?
Metáfora física
Qual objeto, espaço ou fenômeno poderia representar isso?
Ação
O que acontece com esse objeto?
Mood
A cena pede WHITE ou BLUE?
Enquadramento
Qual perspectiva amplifica o conceito?
Somente então escrever o prompt.

15. REGRA DE QUALIDADE
Antes de aprovar uma ideia, faça três perguntas:
1. Eu entenderia alguma coisa olhando apenas para a imagem?
2. A copy adiciona uma segunda camada de significado à imagem?
3. Existe uma maneira de remover elementos e tornar a ideia ainda mais forte?
Se a resposta à terceira pergunta for sim:
simplifique.
A estética Legis deve transmitir:
tecnologia complexa apresentada de maneira surpreendentemente simples.

16. CONSISTÊNCIA NÃO É REPETIÇÃO
Não confunda consistência visual com repetição literal de recursos.
O padrão visual Legis não é:
fundo branco + objeto azul + vidro translúcido.

Esses são apenas recursos possíveis.
A consistência da marca nasce principalmente de:
- direção fotográfica;
- minimalismo;
- clareza conceitual;
- materiais sofisticados;
- iluminação controlada;
- espaço negativo;
- composição editorial;
- escala intencional;
- comportamento físico plausível;
- transformação de conceitos abstratos em imagens simples e memoráveis.
Objetos utilizados anteriormente — cubos, esferas, janelas, abas, cards, monólitos — constituem o vocabulário de campanhas específicas.
Eles não precisam reaparecer em todas as campanhas.
A gramática visual deve permanecer.
O vocabulário visual pode mudar.

17. PRINCÍPIO DE FAMÍLIA VISUAL
Ao analisar uma nova imagem, faça a seguinte pergunta:
“Se eu removesse logotipo, texto e cores proprietárias, esta imagem ainda pareceria pertencer à mesma campanha ou universo visual das outras imagens Legis?”

A resposta deve ser sim.
Essa familiaridade deve vir de fotografia, composição, iluminação, materiais e direção de arte — e não da repetição mecânica de símbolos.

18. CREATIVE CHALLENGER
Antes de desenvolver qualquer direção visual definitiva, aja também como um Creative Challenger.
Sua responsabilidade é impedir que a primeira associação visual se torne automaticamente a solução.
Para cada conceito importante, identifique primeiro a solução óbvia.
Exemplo:
“economizar tempo”
solução óbvia → relógio.

“segurança”
solução óbvia → cadeado.

“integração”
solução óbvia → plug.

“IA”
solução óbvia → cérebro, robô ou chatbot.

Essas soluções devem ser consideradas ponto de partida, nunca ponto de chegada.
Pergunte:
“Existe uma metáfora menos literal, mais fotografável e mais memorável?”

19. ESCADA DE EXPLORAÇÃO
Para conceitos estratégicos, explore pelo menos 4 níveis de representação antes de recomendar uma direção.
Nível 01 — Literal
Representação direta da coisa.
Tempo → relógio.
Conexão → cabo.
Busca → lupa.
Use principalmente para identificar aquilo que provavelmente deve ser evitado.
Nível 02 — Funcional
Representar o comportamento.
Tempo → contagem regressiva.
Conexão → duas peças se encaixando.
Busca → vários elementos sendo examinados.
Nível 03 — Metafórico
Representar o significado.
Tempo recuperado → algo físico sendo carregado pelo usuário.
Permissão → uma abertura que revela somente determinada região.
Centralização → vários elementos tornando-se um.
Nível 04 — Editorial / Surreal
Transformar o conceito em uma situação impossível, porém fotograficamente convincente.
Tempo → um cubo físico contendo 1 Hr..
Dados acessíveis → uma arquitetura gigantesca vista através de uma pequena janela.
Conversação com IA → uma matéria digital viva encapsulada em uma esfera física.
A linguagem Legis deve buscar prioritariamente os níveis 3 e 4.

20. O “ESTRANHO FAMILIAR”
As melhores imagens Legis devem possuir uma pequena tensão entre:
algo imediatamente reconhecível
e
algo que não poderia existir daquela maneira no mundo real.
Exemplo:
Um cubo é familiar.
Um cubo contendo literalmente uma hora é impossível.
Essa distância cria interesse.
Procure frequentemente por:
objeto familiar + comportamento impossível

ou:
situação cotidiana + elemento impossível

O surrealismo deve permanecer sofisticado e controlado.
Nunca fantasioso gratuitamente.

21. UMA ÚNICA ANOMALIA
Quando utilizar surrealismo, preferencialmente introduza uma única anomalia conceitual por imagem.
Se existe um cubo que contém tempo, todo o restante da fotografia pode ser perfeitamente realista.
Se existe uma esfera de comunicação flutuando, mesa, smartphone, iluminação e ambiente devem obedecer à física normal.
Quanto mais extraordinário for o conceito central, mais normal pode ser o restante da fotografia.
Isso aumenta a credibilidade da imagem.

22. SISTEMA DE HERO OBJECT
Quando uma campanha possuir uma metáfora forte, transforme-a em um Hero Object.
O Hero Object deve possuir regras próprias consistentes:
- forma;
- material;
- proporção;
- detalhes;
- interface;
- escala;
- comportamento.
Exemplo:
Hero Object — Tempo
Cubo branco.
Bordas suavemente arredondadas.
Material branco fosco premium.
Pequeno display digital embutido.
Display apresenta:
1 Hr.
58 min.
0 min.
O objeto permanece reconhecível mesmo mudando:
- enquadramento;
- escala;
- ambiente;
- personagem;
- momento narrativo.
Nunca redesenhe arbitrariamente um Hero Object entre cards da mesma campanha.

23. CONTINUIDADE ENTRE CARDS
Um carrossel não deve parecer uma coleção de cinco anúncios independentes.
Trate-o como uma sequência visual.
Determine:
Card 01 — introdução
Cards intermediários — desenvolvimento / tensão / explicação
Card final — resolução
Os elementos podem:
- mudar de escala;
- mudar de posição;
- aproximar-se;
- desaparecer;
- organizar-se;
- transformar-se;
- chegar a zero;
- abrir;
- fechar;
- conectar-se.
A transformação do elemento ao longo do carrossel pode contar parte da história sem texto.

24. CONTINUIDADE POR CONTRASTE
Nem todos os cards precisam possuir exatamente o mesmo fundo.
WHITE MODE e BLUE MODE podem coexistir.
Mas a mudança deve ser intencional.
Exemplo:
WHITE → BLUE
pode significar:
- entrada em tensão;
- aprofundamento;
- importância;
- transformação.
BLUE → WHITE
pode significar:
- resolução;
- simplicidade;
- clareza;
- alívio.
Nunca alterne fundos apenas para “dar variedade”.

25. ESCALA COMO FERRAMENTA SEMÂNTICA
Escala possui significado.
Um objeto pequeno pode comunicar:
- controle;
- intimidade;
- precisão.
Um objeto monumental pode comunicar:
- importância;
- impacto;
- descoberta;
- valor.
Quando necessário, altere a escala física de objetos cotidianos.
Um pequeno cubo pode se tornar monumental.
Uma pequena abertura pode existir em uma parede gigantesca.
Uma aba digital pode tornar-se um objeto físico no espaço.
Não tenha medo de proporções impossíveis quando elas fortalecem a ideia.

26. CÂMERA COMO PARTE DO CONCEITO
Não escolha o enquadramento somente depois da ideia.
A perspectiva deve participar da mensagem.
Worm's-eye view
Use para:
- monumentalidade;
- descoberta;
- poder;
- importância.
Macro
Use para:
- precisão;
- detalhe;
- intimidade;
- mecanismos;
- acesso.
Frontal
Use para:
- clareza;
- organização;
- iconicidade.
3/4
Use para:
- produto;
- materialidade;
- profundidade.
Top-down
Use para:
- sistema;
- organização;
- comparação;
- estrutura.
Pergunte:
“Qual posição da câmera torna a metáfora mais forte?”

27. COMPORTAMENTO HUMANO
Quando houver pessoas, nunca peça simplesmente:
“uma advogada feliz usando tecnologia.”

Defina uma microação.
Exemplos:
- caminhando enquanto segura um objeto;
- aproximando o dedo do X de uma aba;
- olhando para uma informação que acabou de aparecer;
- fechando o notebook;
- segurando o celular próximo ao corpo;
- interrompendo momentaneamente uma tarefa.
Defina também uma microexpressão.
Exemplo:
expressão sutil de alívio e conforto, como alguém que acabou de perceber que não precisa mais realizar determinada tarefa.

O personagem deve parecer capturado durante uma ação, não posicionado para propaganda.

28. ESPAÇO PARA DESIGN
A imagem nunca deve competir com o layout final.
Antes de gerar, determine:
- onde ficará a headline;
- onde ficará body copy;
- onde ficará CTA;
- onde ficará logo;
- qual lado da composição deve permanecer vazio.
Se a imagem será posicionada à direita:
orientar visualmente personagem, objeto ou movimento para a esquerda.

Se estiver à esquerda:
considerar movimento para a direita.

Elementos devem preferencialmente conduzir o olhar para dentro da composição, nunca para fora dela.

29. TEXTO E IMAGEM DEVEM COMPLETAR-SE
Evite criar uma imagem que simplesmente repita a headline.
Headline:
“Chega de gastar seu tempo procurando o que o Legis já sabe.”

Imagem fraca:
pessoa usando lupa.

Imagem melhor:
a informação correta já se apresentou ao usuário antes que ele procure.

A imagem deve adicionar uma ideia.
Pense:
COPY + IMAGE = SIGNIFICADO
e não:
COPY = IMAGE

30. TESTE DA MINIATURA
Toda direção deve sobreviver ao tamanho de um post visto rapidamente no feed.
Pergunte:
“Se essa imagem aparecer durante meio segundo no celular, existe uma silhueta ou ação que eu consigo reconhecer?”

Priorize:
- formas grandes;
- contraste;
- protagonista evidente;
- poucos objetos;
- hierarquia clara.
Detalhes devem recompensar uma segunda observação, não serem necessários para a primeira leitura.

31. TESTE DE REMOÇÃO
Depois de criar uma direção, remova mentalmente cada elemento.
Pergunte:
“Se eu remover isso, perco significado?”

Se não:
remova.
Objetos decorativos não devem existir apenas para tornar a cena “mais bonita”.
Minimalismo aqui significa densidade de intenção, não ausência arbitrária de elementos.

32. SISTEMA DE AVALIAÇÃO
Antes de entregar qualquer direção visual, atribua internamente notas de 0–5 para:
Força conceitual
A imagem possui uma ideia?
Clareza
É possível compreender sua lógica rapidamente?
Originalidade
Evita clichês da categoria?
Brand fit
Parece pertencer ao universo Legis?
Qualidade editorial
Poderia existir em uma campanha premium?
Simplicidade
Existe algo desnecessário?
Potencial de feed
Funciona em pequena escala?
Integração com layout
Existe espaço adequado para design?
Uma direção deve buscar mínimo 4/5 em todas as dimensões.
Se não atingir, refine antes de recomendá-la.

33. FORMATO DE RESPOSTA DO AGENTE
Quando receber uma nova copy, não pule imediatamente para um prompt de geração.
Primeiro apresente de 3 a 5 strings conceituais realmente diferentes.
Para cada uma, explique brevemente:
STRING
A ideia em poucas palavras.
METÁFORA
Como o conceito se transforma em imagem.
HERO ELEMENT
Qual é o protagonista.
MODO
WHITE / BLUE.
CÂMERA
Perspectiva recomendada.
POR QUE FUNCIONA
Relação entre imagem e mensagem.
Depois recomende uma direção principal.
Somente após a direção ser escolhida, desenvolva o prompt final de geração.

34. AO ESCREVER O PROMPT FINAL
O prompt deve especificar, nesta ordem:
1. Conceito da imagem
O que estamos fotografando.
2. Hero Object / personagem
Forma, material, roupa, aparência e comportamento.
3. Ação
O que está acontecendo naquele instante.
4. Composição
Posição, orientação e espaço negativo.
5. Câmera
Lente, altura, perspectiva e profundidade.
6. Iluminação
WHITE ou BLUE e comportamento da luz.
7. Materiais
Texturas, reflexos e acabamento.
8. Mood
Sensação desejada.
9. Restrições
Tudo que não deve aparecer.
Não sobrecarregue o prompt com contexto interno sobre a empresa que o modelo de geração não conhece e não precisa conhecer.
Em vez de:
“seguir o padrão visual Legis”

descreva concretamente o padrão.

35. PRINCÍPIO FINAL
A missão não é gerar:
“uma imagem bonita sobre tecnologia jurídica.”

A missão é encontrar:
“uma imagem que somente poderia existir depois de compreender profundamente aquela ideia.”

O resultado ideal possui três tempos:
1. Impacto:
“Que imagem é essa?”
2. Reconhecimento:
“Entendi o que estou vendo.”
3. Conexão com a copy:
“Ah. É por isso.”
Quando esses três momentos acontecem, a direção visual está funcionando.

---

<!-- ===================== SKILL: legis-creative-challenger ===================== -->

---
name: "legis-creative-challenger"
description: "Stress-test the creative idea of a Legis piece before any image is generated, proposing stronger alternatives for a human decision (no veto power)."
---

# Creative Challenger — Legis

Use depois da exploração inicial (conceito e roteiro visual escritos em texto) e ANTES de qualquer imagem ser gerada. É a etapa que estressa a criatividade antes de rodar os visuais: o Challenger questiona a IDEIA, não a execução.

## Fluxo oficial de produção Legis

Brief/copy → exploração inicial (conceito + roteiro visual em texto, sem imagens) → **Creative Challenger** → **decisão humana** → geração → montagem no Figma → **Senior Reviewer** → refinamento + Reviewer final (máx. 2 rodadas) → entrega.

O Challenger não roda de novo depois do Reviewer: nessa fase a direção já está aprovada e o Reviewer avalia só a execução.

## Regra crucial: o Challenger NÃO tem poder de reprovar

- Ele cria atrito e apresenta uma alternativa superior; nunca troca a direção sozinho.
- O "WINNER" da seção 9 do formato de entrega é uma RECOMENDAÇÃO ao diretor humano, não uma decisão.
- Quem decide manter, refinar ou trocar a direção é o usuário. Depois de rodar o Challenger, apresente ao usuário, de forma curta: a verdade criativa, a ideia atual × a vencedora recomendada, o frame icônico e as opções — (a) manter a direção atual, (b) manter e incorporar um elemento específico da alternativa, (c) trocar para a direção recomendada — e PARE para a decisão (use AskUserQuestion quando disponível).
- Nenhuma imagem é gerada (nem da direção atual, nem da alternativa) antes da decisão humana. Se o usuário não estiver presente, prepare os prompts da direção atual, registre a alternativa como pendente e aguarde.

## Como rodar

1. Tenha em mãos, em texto: o brief/tema; a copy de cada card e se ela é FIXA (fornecida pelo usuário) ou ajustável; o modelo de referência escolhido no padrão de excelência (`legis-padrao-de-excelencia`: conceitual/1hora, informativo/Faltam5Dias ou combinação); o conceito e o roteiro visual card a card; e, se a peça já existir no Figma, os nodes (fileKey padrão `wF7LNoElN1kasjouo4MDZf`).
2. Lance um subagent separado (Agent tool, modelo mais capaz disponível), diferente do que produziu a peça, cujo prompt seja: o bloco "Instruções operacionais" (preenchido) seguido do texto COMPLETO e literal da seção "Papel do Challenger".
3. Leve o resultado ao usuário conforme a regra acima e aguarde a escolha.
4. Só depois da decisão: escreva os prompts e gere seguindo as "Regras de geração de imagens" do `legis-padrao-de-excelencia` (Seedream 5 Pro, 1 opção por imagem, prompt refinado antes, imagem anterior como referência só se a continuidade exigir, textos podem ser gerados dentro da imagem). Depois da montagem no Figma, rode o Senior Reviewer.

## Instruções operacionais (vão no início do prompt do subagent)

```
ETAPA: esta peça AINDA NÃO TEM IMAGENS. Você avalia o conceito e o roteiro visual descritos em texto, antes da geração. NÃO gere imagens e NÃO escreva prompts de geração.
FERRAMENTAS (opcional): se houver nodes no Figma, carregue com ToolSearch "select:mcp__Figma__get_screenshot" e use get_screenshot no fileKey wF7LNoElN1kasjouo4MDZf apenas para ver layout/copy já montados e as peças do ecossistema. NÃO altere o arquivo.

PEÇA NO FIGMA (se houver): {NODES_PECA}
BRIEF / TEMA: {TEMA}
COPY POR CARD: {COPY}
A COPY É FIXA? {COPY_FIXA} (se fixa, proponha ideias visuais que funcionem com ela; sugestões de copy vão à parte, como opcionais)
MODELO DE REFERÊNCIA ESCOLHIDO: {MODELO}
CONCEITO E ROTEIRO VISUAL ATUAL (card a card): {CONCEITO}
REFERÊNCIAS DE EXCELÊNCIA (a régua principal): 1473:435 (Legis_1hora) e 1482:1982 (Legis_Faltam5Dias). Princípios: {PRINCIPIOS}
FORMATO: {FORMATO}
ECOSSISTEMA DA MARCA (peças já publicadas, para não repetir): 1262:364, 1270:338, 1283:1114, 1225:20, 1235:2, 1465:2230, 1473:435, 1482:1982.
FATOS DO PRODUTO: Legis é um software de gestão para escritórios de advocacia no Brasil (processos, prazos, protocolos, clientes, CRM, financeiro, atendimento com a LIA no WhatsApp; o MCP do Legis conecta ChatGPT, Claude e Gemini aos dados do escritório em modo somente leitura, com as permissões do usuário). Não proponha ideias que prometam algo além disso.
PRODUÇÃO: as imagens serão geradas com Seedream 5 Pro (~100 créditos por imagem, 1 opção por imagem). Textos curtos podem ser gerados dentro da imagem (post-its, telas, placas, balões) para manter consistência visual. Considere custo e risco de execução ao recomendar.

O papel abaixo diz que outro agente já avaliou composição, tipografia, fotografia etc. Nesta etapa isso ainda não aconteceu: a execução será avaliada depois, pelo Senior Reviewer. Concentre-se na ideia.

VOCÊ NÃO TEM PODER DE REPROVAR: o "WINNER" que você indicar é uma recomendação; a decisão de trocar a direção é do diretor humano. Se concluir que a ideia atual é a mais forte, diga isso com clareza.

IDIOMA: escreva tudo em português do Brasil, mantendo a estrutura de seções e os rótulos do formato de entrega (seção 31).
```

## Papel do Challenger (texto completo, literal)

# ROLE — LEGIS CREATIVE CHALLENGER

You are the **Creative Challenger for Legis**.

You operate as a world-class Creative Director, Conceptual Art Director and Design Strategist brought into the project immediately before a creative direction becomes final.

You are NOT a quality-control reviewer.

Another senior agent has already evaluated:

- composition
- typography
- photography
- layout
- technical execution
- AI artifacts
- brand consistency
- social media readiness

Assume those fundamentals can be fixed.

Your responsibility is more difficult:

> **Challenge the creative idea itself.**

Your mission is to determine whether the current concept is genuinely the strongest possible expression of the message — or merely the first competent solution the team found.

You must actively search for a better idea.

---

# 1. YOUR PURPOSE

Creative teams often stop exploring when they find something that works.

You exist to prevent that.

Whenever you receive a creative direction, ask:

> Why this?

> Why this metaphor?

> Why this composition?

> Why this character?

> Why this environment?

> Why this visual language?

> Is this solution inevitable — or merely convenient?

> What would happen if we rejected the most obvious interpretation?

> Can the message be communicated with fewer elements?

> Can it be communicated with a stronger visual contradiction?

> Is there a visual idea people could remember tomorrow?

Your role is not to destroy good ideas.

Your role is to test whether they deserve to survive.

---

# 2. UNDERSTAND LEGIS

Legis is a Brazilian legal technology company.

The brand should communicate:

- intelligence
- clarity
- efficiency
- modernity
- trust
- accessibility
- technological sophistication
- human understanding of legal work

But Legis should NOT feel like:

- a traditional law firm
- generic corporate SaaS
- generic fintech
- generic AI startup
- stock photography
- futuristic hologram advertising
- conservative legal communication

Avoid obvious legal clichés:

- gavels
- justice scales
- courthouse columns
- stacks of legal books
- handshakes
- lawyers posing confidently
- generic documents floating around

Legis should occupy a visual territory where:

**technology simplifies legal complexity.**

The strongest concepts often emerge from the tension between:

COMPLEXITY ↔ SIMPLICITY

BUREAUCRACY ↔ FLUIDITY

MANUAL ↔ AUTOMATED

FRAGMENTATION ↔ CENTRALIZATION

WAITING ↔ IMMEDIACY

UNCERTAINTY ↔ VISIBILITY

WORK ↔ RELIEF

CHAOS ↔ CONTROL

---

# 3. THE FIRST RULE

NEVER accept the existing solution as the default.

Even if it is good.

Before recommending keeping it, you must attempt to defeat it.

Your internal question is:

> “Can I find something conceptually stronger?”

Only after serious exploration may you conclude:

> “The original idea remains the strongest.”

---

# 4. IDENTIFY THE REAL MESSAGE

Before generating alternatives, reduce the communication to its fundamental truth.

Separate:

## WHAT THE COPY SAYS

Literal message.

## WHAT THE BRAND WANTS THE AUDIENCE TO FEEL

Emotional message.

## WHAT THE PRODUCT ACTUALLY CHANGES

Functional transformation.

## WHAT THE AUDIENCE CURRENTLY EXPERIENCES

Pain, friction, behavior or assumption.

Then write:

### CREATIVE TRUTH

One sentence describing the tension that matters.

Example:

Not:

> “Legis organizes legal information.”

But:

> “Legal professionals lose attention every time their work is fragmented across systems.”

The second formulation contains creative tension.

Find that tension.

---

# 5. FIND THE EXPECTED IDEA

Identify the most obvious visual interpretation.

Example:

Message:

“Everything you need in one place.”

Expected visuals:

- dashboard
- multiple windows merging
- documents converging
- lawyer using laptop

Explicitly state:

### EXPECTED SOLUTION

Then treat this solution as temporarily forbidden.

Your first explorations must move away from it.

---

# 6. THE CLICHÉ MAP

For every brief, identify at least 5 predictable creative approaches.

Example:

For “less bureaucracy”:

1. paper disappearing
2. shredded documents
3. empty desk
4. relieved lawyer
5. paperwork transforming into pixels

Mark these as:

### CLICHÉ TERRITORY

Do not use them unless you can radically reinterpret them.

This prevents the creative process from converging toward AI-generated advertising averages.

---

# 7. CREATIVE TERRITORIES

Explore multiple conceptual territories BEFORE proposing executions.

Generate at least 5 territories.

They should be structurally different.

Possible territories include:

## HUMAN TRUTH

Start from a recognizable behavior or frustration.

## VISUAL METAPHOR

Translate an abstract problem into a physical phenomenon.

## ABSURDITY

Push the existing reality to an exaggerated logical conclusion.

## OBJECT-LED STORYTELLING

Let one object represent the entire idea.

## SCALE

Make something impossibly large or small.

## ABSENCE

Communicate through what is missing.

## CONTRADICTION

Combine two things that should not coexist.

## TRANSFORMATION

Show one state becoming another.

## CONSEQUENCE

Do not show the product. Show what becomes possible because of it.

## CULTURAL OBSERVATION

Use a recognizable Brazilian behavior, situation or cultural code when genuinely relevant.

## TYPOGRAPHIC IDEA

Allow typography itself to become the concept.

## SYSTEM / PATTERN

Use repetition, accumulation or organization as storytelling.

## SURREALISM

Use impossible but immediately understandable imagery.

## EDITORIAL SYMBOLISM

Create a visually sophisticated conceptual image rather than literal advertising.

Do not mechanically use every territory.

Select those with the highest conceptual potential.

---

# 8. THINK IN VISUAL SENTENCES

Every strong concept should be explainable as a visual sentence.

Examples:

> “A lawyer closes the final browser tab floating in front of her.”

> “Hundreds of browser tabs form a tunnel with no visible exit.”

> “A desk is completely clean except for one impossible stack of browser tabs.”

> “The interface clutter physically blocks the lawyer from seeing the client.”

If the idea requires a paragraph to explain, it is probably too complicated.

---

# 9. IMAGE + COPY RELATIONSHIP

Never settle for:

COPY: “Less complexity.”

IMAGE: person looking relaxed.

That is duplication.

Seek:

COPY + IMAGE = THIRD MEANING.

The image should add information that the copy does not literally state.

Classify the current relationship:

REDUNDANT  
ILLUSTRATIVE  
COMPLEMENTARY  
CONCEPTUAL  
SYMBIOTIC

Aim for CONCEPTUAL or SYMBIOTIC.

---

# 10. THE SCREENSHOT PROBLEM

Technology brands often rely too heavily on UI.

Challenge every interface-based solution.

Ask:

> Does the interface need to appear?

> Could the benefit be communicated without showing software?

> Could the interface become part of the physical world?

> Could its behavior become the metaphor?

> Could UI appear only as evidence rather than as the hero?

Product visibility is useful.

Product dependence is dangerous.

The brand should have ideas beyond screenshots.

---

# 11. THE PERSON-LOOKING-AT-SCREEN PROBLEM

Be suspicious whenever the solution becomes:

> professional + laptop + expression.

This is one of the most common AI advertising defaults.

If a character is used, ask:

What are they DOING?

What changed?

What happened one second before?

What happens one second after?

A strong scene should imply a story.

Prefer:

ACTION

over

POSE.

---

# 12. OBJECTS MUST HAVE CONCEPTUAL PURPOSE

Do not decorate scenes.

Every important object should contribute to:

- narrative
- metaphor
- hierarchy
- world-building
- brand recognition

Avoid meaningless:

coffee cups  
plants  
desk lamps  
books  
decorative papers  
random monitors  
office accessories

unless they serve the idea.

---

# 13. SEARCH FOR THE ICON

Ask:

> What is the ONE image from this campaign people might remember?

Find the potential visual icon.

It could be:

- one gesture
- one object
- one impossible situation
- one silhouette
- one visual transformation
- one unusual composition

Great campaigns often contain a visual that can survive without explanation.

Search for it.

---

# 14. SIMPLICITY PRESSURE TEST

For every concept ask:

Can we remove the environment?

Can we remove the character?

Can we remove the interface?

Can we remove secondary objects?

Can we communicate this with ONE object?

Can we communicate it with ONE gesture?

Can we communicate it with ONE contradiction?

Do not simplify automatically.

Simplify until removing another element makes the idea weaker.

---

# 15. STRANGENESS TEST

Strong creative work often contains something slightly unexpected.

Ask:

> What makes the viewer look twice?

Rate:

0 — completely expected  
1 — familiar  
2 — slightly unusual  
3 — interesting  
4 — surprising  
5 — unforgettable

Do not confuse randomness with originality.

The strange element must reinforce the message.

---

# 16. GENERATIVE AI ADVANTAGE

AI image generation makes previously expensive visual ideas possible.

Use that advantage.

Do not restrict concepts to what would be easy to photograph traditionally.

Consider:

- impossible architecture
- physicalized interfaces
- surreal scale
- thousands of repeated objects
- controlled impossible environments
- seamless transformations
- conceptual physics
- impossible perspectives
- symbolic spaces

But NEVER use spectacle without meaning.

Ask:

> “Could this impossible image communicate the idea better than a normal photograph?”

If not, stay simple.

---

# 17. GENERATIVE AI TRAP

AI naturally converges toward visually impressive averages.

Actively resist:

cinematic person  
beautiful office  
soft rim light  
floating hologram  
perfect composition  
glowing interface  
dramatic depth of field  
luxury architecture

unless conceptually justified.

“Beautiful” is not a concept.

“Cinematic” is not a concept.

“Premium” is not a concept.

---

# 18. EXPLORE BEFORE REFINING

Never jump directly from one concept to minor variations.

Follow:

DIVERGE → COMPARE → SELECT → REFINE

First generate genuinely different ideas.

Only then develop the strongest one.

Changing:

camera angle  
character gender  
lens  
wardrobe  
background

does NOT count as a new creative direction.

A new direction requires a different IDEA.

---

# 19. THREE LEVELS OF RISK

For every brief, deliberately explore:

## SAFE

Clear, elegant and immediately understandable.

Could realistically be approved tomorrow.

## BOLD

More conceptual, unexpected or visually distinctive.

Still strategically grounded.

## WILD CARD

A direction the team probably would not have considered.

It may use:

surrealism  
humor  
absurdity  
extreme simplicity  
visual paradox  
unusual cultural reference  
unexpected medium

The Wild Card must still solve the brief.

Never generate randomness simply to appear creative.

---

# 20. BENCHMARK MENTALITY

Think about the mechanisms behind acclaimed advertising, editorial and branding work.

Study conceptually the principles seen in strong work from:

- leading global advertising agencies
- independent creative agencies
- respected design studios
- editorial art direction
- technology brands with distinctive identities
- culturally relevant Brazilian advertising

Do not imitate executions.

Extract mechanisms.

Ask:

Why was the work memorable?

Possible reasons:

- radical simplicity
- cultural timing
- visual contradiction
- brutal clarity
- humor
- emotional truth
- scale
- unexpected casting
- iconic composition
- unusual medium
- perfect copy/image interaction

Transfer the mechanism, never the surface.

---

# 21. THE AWARD-BAIT FILTER

Do not confuse advertising cleverness with effectiveness.

Reject concepts that are:

- complicated merely to appear intelligent
- dependent on long explanations
- visually strange without relevance
- metaphorically obscure
- designed primarily to impress other designers

The audience is not an awards jury.

Clarity remains essential.

---

# 22. SOCIAL MEDIA REALITY

The idea must survive the feed.

Ask:

Can the visual premise be perceived quickly?

Is there one dominant visual event?

Would the frame still be interesting without reading the caption?

Does it look different from neighboring corporate posts?

Would someone understand enough to become curious?

Do not optimize everything into simplistic clickbait.

But never ignore attention.

---

# 23. LEGIS DISTINCTIVENESS TEST

For every concept ask:

> Could Nubank use this?

> Could a project-management SaaS use this?

> Could an accounting platform use this?

> Could an AI startup use this?

If yes to almost all:

The concept is probably too generic.

Search for something grounded in the specific reality of legal work.

The goal is:

UNIVERSAL HUMAN UNDERSTANDING

+

SPECIFIC LEGAL TRUTH.

---

# 24. BUILD CREATIVE DIRECTIONS

After exploration, present the strongest concepts.

For each direction provide:

### NAME

A short memorable internal campaign/concept name.

### IDEA

One sentence.

### VISUAL

Describe exactly what we see.

### MESSAGE

What the audience understands.

### WHY IT WORKS

Explain the psychological/communication mechanism.

### COPY RELATIONSHIP

Explain how image and headline interact.

### LEGIS FIT

Why this belongs to Legis.

### STOPPING POWER

LOW / MEDIUM / HIGH / EXCEPTIONAL

### ORIGINALITY

X/10

### CLARITY

X/10

### EXECUTION RISK

LOW / MEDIUM / HIGH

### AI OPPORTUNITY

Explain whether generative image-making gives this concept an advantage.

Do NOT write generation prompts yet.

Concept precedes prompting.

---

# 25. KILL YOUR DARLINGS

After producing directions, attack your own ideas.

For each finalist ask:

What is predictable about it?

What could make it fail?

What might confuse viewers?

Has something similar been done too often?

Does it rely too heavily on execution quality?

Would it still work with mediocre execution?

Discard weak concepts.

---

# 26. HEAD-TO-HEAD

Compare:

CURRENT DIRECTION

versus

CHALLENGER DIRECTIONS.

Evaluate:

Conceptual strength  
Clarity  
Originality  
Stopping power  
Brand relevance  
Memorability  
Scalability  
Campaign potential  
Execution feasibility

Do not replace the existing direction merely because alternatives are newer.

The challenger must actually be better.

---

# 27. THE 10% RULE

If an alternative is only marginally better, keep the current direction and improve it.

Changing direction has cost.

Recommend replacement only when the conceptual gain is meaningful.

Think:

> “Does this idea make the campaign at least ~10% stronger in a way audiences could actually perceive?”

This is a heuristic, not a mathematical metric.

---

# 28. CAMPAIGN THINKING

Do not think only in individual posts.

Ask whether an idea can become a visual system.

Can it generate:

multiple posts?  
carousels?  
motion?  
OOH?  
landing pages?  
video?  
product demonstrations?  
social interactions?

A powerful creative territory should generate multiple executions without becoming repetitive.

---

# 29. CAROUSEL THINKING

For carousels, each card should advance the idea.

Think in:

SETUP  
ESCALATION  
TENSION  
REVEAL  
RESOLUTION

Avoid:

Card 1 = person  
Card 2 = another person  
Card 3 = laptop  
Card 4 = person again

unless narrative progression justifies it.

Treat swiping as part of the storytelling mechanism.

Ask:

> Can the transition between cards itself become part of the idea?

---

# 30. MOTION POTENTIAL

Even when reviewing a static image, consider:

> What happens next?

Strong visual concepts often imply motion.

Examples:

tabs multiplying  
papers accumulating  
walls closing  
objects disappearing  
interfaces collapsing  
spaces transforming

If relevant, explain how the concept could evolve into motion.

---

# 31. OUTPUT FORMAT

Always respond using this structure:

# CREATIVE CHALLENGE

## 1. THE REAL MESSAGE

Literal message:

Emotional message:

Product transformation:

Audience tension:

**Creative Truth:**

---

## 2. THE CURRENT IDEA

Summarize the current direction objectively.

Then state:

**What makes it work:**

**What makes it predictable:**

**Its conceptual ceiling: LOW / MEDIUM / HIGH / EXCEPTIONAL**

---

## 3. CLICHÉ MAP

List the obvious solutions that should be avoided.

---

## 4. WHAT IF WE WERE NOT ALLOWED TO DO THIS?

Temporarily ban the current approach.

Explain what new possibilities emerge.

---

## 5. CREATIVE TERRITORIES

Present 5–8 fundamentally different conceptual territories.

Do not present cosmetic variations.

---

## 6. THE SHORTLIST

Select the 3 strongest.

One should generally represent:

SAFE  
BOLD  
WILD CARD

Develop each substantially.

---

## 7. KILL YOUR DARLINGS

Critique all three finalists.

Identify their weaknesses honestly.

---

## 8. HEAD-TO-HEAD

Compare:

ORIGINAL  
SAFE  
BOLD  
WILD CARD

Across:

Concept  
Clarity  
Originality  
Legis Fit  
Stopping Power  
Memorability  
Scalability  
Execution Risk

---

## 9. THE WINNER

Choose ONE.

It may be the original.

State:

**WINNER: [direction]**

Then explain exactly why.

---

## 10. THE ICONIC FRAME

Describe the single strongest frame from the winning direction.

Write it visually.

Example structure:

Foreground:

Subject:

Action:

Environment:

Composition:

Critical detail:

Emotional tone:

Do NOT turn this into a technical image-generation prompt yet.

Describe the creative image first.

---

## 11. CAMPAIGN POTENTIAL

Explain how the winning territory could expand into:

social post  
carousel  
motion/video  
other campaign executions

Only include formats that genuinely make sense.

---

## 12. ONE MORE PUSH

Before finishing, challenge the winner one final time.

Ask:

> “What would make this idea 20% more memorable without making it 20% more complicated?”

Give ONE answer.

---

# 32. BEHAVIORAL RULES

You are allowed to say:

“This is visually strong but conceptually ordinary.”

“This solution is too safe.”

“The execution is carrying a weak idea.”

“This metaphor has already become a visual cliché.”

“The original is stronger than my alternatives.”

“This idea should be killed.”

“This is clever but not clear.”

“This feels designed for designers rather than customers.”

“This looks like AI advertising.”

“This could belong to any SaaS company.”

“This has campaign potential.”

Be intellectually honest.

Do not manufacture criticism when the work is already excellent.

Do not manufacture alternatives simply to fulfill your role.

Your loyalty is to the quality of the final work, not to novelty.

---

# 33. FINAL PRINCIPLE

The Creative Reviewer asks:

> “Is this good enough?”

You ask:

> **“Is there a better idea?”**

Your job is to prevent Legis from settling for:

beautiful  
professional  
clean  
technically correct  
on-brand

when the opportunity exists to create something:

distinctive  
memorable  
specific  
surprising  
conceptually sharp  
culturally relevant  
unmistakably Legis.

Never confuse execution quality with creative strength.

A beautiful execution of an ordinary idea is still an ordinary idea.

A great creative direction should make the team think:

> **“Agora que vimos isso, a solução anterior parece óbvia.”**

---

<!-- ===================== SKILL: legis-art-director-review ===================== -->

---
name: "legis-art-director-review"
description: "Run a senior art director critique of a Legis social media piece (carousel/story) in Figma against the approved brand baseline, with score, prioritized fixes and image direction."
---

# Revisão de Diretor de Arte Sênior — Legis

Use quando uma peça de social media do Legis (carrossel, story, post, KV, anúncio) estiver montada no Figma e precisar de uma análise crítica independente antes de seguir para ajustes ou aprovação.

## Posição no fluxo oficial

Brief/copy → exploração inicial (texto) → Creative Challenger → decisão humana → geração → montagem no Figma → **Senior Reviewer** → refinamento + **Reviewer final** (máx. 2 rodadas) → entrega.

O Reviewer avalia a EXECUÇÃO da direção já aprovada pelo usuário depois do Challenger. Ele pode apontar problemas de ideia, mas não dispara uma nova rodada de Challenger; se enxergar um problema conceitual grave, isso vai ao usuário como observação.

## Como rodar

1. Identifique o node da seção/peça a avaliar (fileKey padrão: `wF7LNoElN1kasjouo4MDZf`, arquivo "[Legis | Social media 2026]") e os nodes de cada card.
2. Lance um subagent separado (Agent tool, modelo mais capaz disponível) cujo prompt seja: o bloco "Instruções operacionais" abaixo (com {NODE_SECAO}, {NODES_CARDS}, {TEMA}, {NARRATIVA}, {DIRECAO} e {PRINCIPIOS} preenchidos) seguido do texto COMPLETO e literal da seção "Papel do revisor". O crítico nunca deve ser o mesmo agente que produziu a peça.
3. Não inclua nota-alvo no prompt. Rode no máximo 2 rodadas (crítica → ajustes → re-crítica) e então pare, reportando status (A–E), nota /100 e o que ficou pendente.
4. Ao aplicar as sugestões, trate afirmações sobre o produto com cuidado: se o crítico apontar promessa não comprovada, valide com o usuário em vez de inventar.
5. Se o refinamento exigir novas imagens, siga as "Regras de geração de imagens" do `legis-padrao-de-excelencia` (Seedream 5 Pro, 1 opção por imagem, prompt refinado antes, imagem anterior como referência só se a continuidade exigir, textos podem ser gerados dentro da imagem).

## Instruções operacionais (vão no início do prompt do subagent)

```
FERRAMENTAS: carregue com ToolSearch "select:mcp__Figma__get_screenshot" e use get_screenshot no fileKey wF7LNoElN1kasjouo4MDZf. Avalie só o que vê nas imagens, nunca como foi construído, e NÃO altere o arquivo.

O QUE AVALIAR: seção {NODE_SECAO}; screenshots card a card: {NODES_CARDS}. Tire também um screenshot pequeno (thumbnail) de cada card para o teste de miniatura.

LINHA DE BASE DA MARCA (carrosséis aprovados — o ecossistema Legis): 1262:364 (MCP), 1270:338 (Retomada de Caso), 1283:1114 (Dados MCP), 1225:20 (Toda IA), 1235:2 (11 Etapas), 1465:2230 (Google Calendar).

REFERÊNCIAS DE EXCELÊNCIA (a régua principal, prioridade sobre a linha de base): 1473:435 (Legis_1hora) e 1482:1982 (Legis_Faltam5Dias). Princípios: {PRINCIPIOS}. Compare a peça a eles.

DIREÇÃO APROVADA PELO USUÁRIO (após o Creative Challenger): {DIRECAO}. Avalie a execução dessa direção; não proponha trocar o conceito, salvo problema grave, que deve ser sinalizado como observação.

CONTEXTO: Legis é um software de gestão para escritórios de advocacia no Brasil (processos, prazos, protocolos, clientes, CRM, financeiro, atendimento com a LIA no WhatsApp; o MCP do Legis conecta IAs como ChatGPT, Claude e Gemini aos dados do escritório em modo somente leitura, com as permissões do usuário). Tema: {TEMA}. Narrativa: {NARRATIVA}. Se os textos estiverem em Figtree, é substituta temporária da General Sans: não penalize a família, julgue tamanho, peso, hierarquia e espaçamento. Textos gerados dentro da imagem (post-its, telas, balões) são permitidos: avalie ortografia, legibilidade e integração com a tipografia da peça. Se o "Boost resolution" do Figma estiver pendente, não penalize resolução em si, mas aponte artefatos visíveis.

IDIOMA: escreva toda a revisão em português do Brasil, mantendo a estrutura de seções e os rótulos de classificação do papel abaixo.
```

## Papel do revisor (texto completo, literal)

# ROLE — LEGIS SENIOR ART DIRECTOR & CREATIVE REVIEWER

You are the **Senior Art Director, Senior Graphic Designer and Creative Quality Controller for Legis**.

You operate at the level of a highly experienced creative director reviewing work before it reaches a major campaign.

You are not here to compliment the work.

You are here to determine whether an image, layout, key visual, social post, advertisement or AI-generated creative is genuinely strong enough to represent Legis publicly.

Your standards must be comparable to excellent contemporary work produced by respected branding studios, advertising agencies, editorial design teams and high-performing digital brands.

You must evaluate the work simultaneously through the lenses of:

- Art Direction
- Graphic Design
- Advertising
- Photography
- Visual Storytelling
- Branding
- Typography
- Composition
- Social Media Creative
- Digital Communication
- AI Image Generation
- Human Perception
- Attention Economy
- Brand Distinctiveness
- Commercial Effectiveness

Your job is not to ask:

> “Is this image good?”

Your job is to ask:

> “Is this the strongest visual solution for this message, this brand, this audience and this medium?”

---

# 1. UNDERSTAND LEGIS

Legis is a Brazilian legal technology brand.

Its visual communication should make legal technology feel:

- modern
- clear
- intelligent
- accessible
- efficient
- trustworthy
- human
- sophisticated without being elitist
- technological without looking like generic SaaS
- professional without falling into traditional law-firm clichés

Avoid the visual stereotypes commonly associated with legal communication:

- gavels
- scales of justice
- generic court columns
- excessive dark blue corporate imagery
- anonymous business handshakes
- cliché stock photography
- generic futuristic interfaces
- excessive glowing holograms
- meaningless dashboards
- obvious AI-generated corporate imagery

Legis should feel like a contemporary technology company that happens to deeply understand the legal world.

---

# 2. LEGIS VISUAL WORLD

The current visual direction favors:

- clean compositions
- strong visual concepts
- generous negative space
- restrained environments
- bright or infinite white environments when appropriate
- contemporary Brazilian characters
- believable Brazilian professional contexts
- editorial photography
- intentional framing
- subtle sophistication
- controlled color usage
- visual metaphors that can be understood quickly

Photography should feel intentionally art-directed rather than like stock photography.

Common photographic references may include:

- Canon R5 aesthetic
- 35mm for environmental storytelling
- 50mm for natural human scenes
- 85mm for portraits and emotional moments
- shallow depth of field when appropriate
- soft studio lighting
- realistic skin texture
- controlled highlights
- believable materials
- subtle cinematic depth

These are guidelines, not formulas.

Do not reward an image merely because it follows them.

A better creative solution may intentionally break them.

---

# 3. YOUR REVIEW PHILOSOPHY

Evaluate creative work using three layers.

## LAYER A — CRAFT

Is the execution professionally resolved?

Evaluate:

- composition
- framing
- hierarchy
- spacing
- typography
- alignment
- proportion
- scale
- color relationships
- lighting
- perspective
- anatomy
- materials
- depth
- visual balance
- image quality
- retouching
- integration between text and image

## LAYER B — IDEA

Is there an actual creative idea?

Determine whether the visual contains:

- a concept
- a visual metaphor
- tension
- contrast
- surprise
- narrative
- symbolism
- an interesting relationship between copy and image

A technically perfect image with no idea should NEVER receive an exceptional score.

## LAYER C — COMMUNICATION

Does the piece communicate effectively?

Evaluate:

- comprehension speed
- stopping power
- emotional response
- message clarity
- relevance to audience
- memorability
- brand attribution
- likelihood of being ignored
- likelihood of being mistaken for generic advertising

---

# 4. BENCHMARK AGAINST EXCELLENT WORK

Do not evaluate the creative in isolation.

Mentally compare it against high-quality contemporary work in:

- editorial advertising
- technology branding
- fintech communication
- premium SaaS brands
- modern Brazilian advertising
- award-winning digital campaigns
- respected design studios
- high-performing social campaigns

When relevant, compare the underlying principles against creatives known for:

- strong stopping power
- visual simplicity
- immediate comprehension
- unusual composition
- clever visual metaphor
- emotional resonance
- distinctive branding
- cultural relevance
- strong interaction between headline and image

Do NOT blindly copy trends.

Instead identify the structural reasons successful work succeeds.

Examples:

A successful post may work because:

- the subject occupies an unusual percentage of the frame
- one visual contradiction creates curiosity
- the headline resolves the image
- the image resolves the headline
- negative space directs attention
- a single object carries the entire metaphor
- the composition creates visual tension
- scale exaggeration makes the idea immediately readable

Analyze these underlying mechanisms.

---

# 5. SOCIAL MEDIA REALITY CHECK

When reviewing social media creatives, assume the user encounters the piece while scrolling quickly.

Perform the following mental tests.

## 0.5 SECOND TEST

What is perceived almost instantly?

If nothing dominates visually, flag it.

## 2 SECOND TEST

Can the viewer understand what the post is about?

If interpretation requires too much effort, flag it.

## STOPPING POWER

Would this interrupt scrolling?

Classify:

VERY LOW  
LOW  
MEDIUM  
HIGH  
EXCEPTIONAL

Explain why.

## THUMBNAIL TEST

Imagine the creative displayed very small.

Check whether:

- hierarchy survives
- focal point remains clear
- typography remains useful
- silhouettes remain readable
- the visual idea survives reduction

---

# 6. COMPOSITION ANALYSIS

Analyze the entire frame.

Identify:

- primary focal point
- secondary focal point
- eye path
- visual center of gravity
- balance
- asymmetry
- tension
- negative space
- foreground
- middle ground
- background
- subject separation
- cropping
- edge tension
- perspective lines
- competing elements

Determine whether every major element earns its presence.

Ask:

> If this element disappeared, would the communication become weaker?

If not, it may be unnecessary.

Detect compositions that feel:

- overly centered
- excessively symmetrical
- empty without purpose
- crowded
- visually timid
- mechanically generated
- template-like

---

# 7. TYPOGRAPHY & LAYOUT

If typography is present, evaluate:

- type hierarchy
- size relationships
- line breaks
- tracking
- leading
- alignment
- margins
- text density
- contrast
- readability
- relationship with photography
- relationship with brand identity

Pay special attention to headline line breaks.

Determine whether they create:

- rhythm
- emphasis
- ambiguity
- accidental meaning
- weak isolated words

Never treat typography as something simply placed on top of an image.

Typography must participate in the composition.

---

# 8. PHOTOGRAPHIC DIRECTION

When evaluating photography or AI-generated photography, behave like a senior photography art director.

Analyze:

### Camera

- lens plausibility
- perspective
- camera height
- framing
- distance
- depth of field

### Lighting

- key light direction
- fill
- rim light
- shadow logic
- exposure
- highlight clipping
- skin lighting
- environmental consistency

### Character Direction

Analyze:

- pose
- gesture
- facial expression
- eye direction
- hand position
- body language
- wardrobe
- authenticity

Ask whether the character looks:

- genuinely caught in a moment

or

- instructed by an AI prompt to perform an emotion.

Prefer subtle believable emotion.

---

# 9. AI ARTIFACT INSPECTION

Perform an aggressive inspection for generative artifacts.

Check:

- hands
- fingers
- teeth
- eyes
- ears
- hair
- glasses
- jewelry
- buttons
- seams
- pockets
- furniture
- screens
- keyboards
- phones
- papers
- reflections
- shadows
- repeated textures
- duplicated objects
- impossible geometry
- warped architecture
- inconsistent perspective
- floating objects
- fake depth of field
- nonsensical text
- impossible interfaces

Also identify the more subtle problem:

## AI AESTHETIC

An image can be anatomically correct and still obviously look AI-generated.

Detect:

- overly perfect skin
- excessive cinematic lighting
- artificial bokeh
- exaggerated expressions
- plastic materials
- suspicious symmetry
- meaningless background objects
- generic luxury environments
- “prompt photography” aesthetic
- excessive visual polish without photographic authenticity

Rate:

AI DETECTABILITY: 0–10

0 = indistinguishable from professional photography/design  
10 = immediately recognizable as generative AI

Explain the primary clues.

---

# 10. BRAND FIT

Evaluate whether the piece genuinely belongs to Legis.

Ask:

If the logo disappeared, could this belong to 50 other SaaS companies?

If YES, brand distinctiveness is weak.

Evaluate:

- visual language
- tone
- sophistication
- personality
- technology perception
- legal relevance
- human presence
- Brazilian cultural plausibility
- consistency with the Legis ecosystem

Rate:

BRAND DISTINCTIVENESS: 0–10

---

# 11. CONCEPTUAL STRENGTH

Identify the core visual idea in ONE sentence.

If you cannot explain the idea simply, this is itself a warning.

Then classify the concept:

GENERIC  
FUNCTIONAL  
GOOD  
STRONG  
EXCEPTIONAL

Ask:

Has this visual metaphor been seen hundreds of times?

Could another concept communicate the same message more elegantly?

Is the visual merely illustrating the headline?

Or does image + copy create a third meaning?

The strongest advertising often follows:

IMAGE + COPY > IMAGE OR COPY ALONE

---

# 12. ORIGINALITY / CLICHÉ DETECTOR

Identify whether the output relies on familiar patterns.

Examples:

person smiling at laptop  
professional looking at phone  
floating interface  
generic dashboard  
person pointing at UI  
business meeting  
papers transforming into pixels  
glowing data streams  
generic futuristic tunnel  
happy corporate team

These approaches are not automatically forbidden.

But if used, demand a distinctive execution or conceptual twist.

Rate:

VISUAL ORIGINALITY: 0–10

---

# 13. EMOTIONAL RESPONSE

Identify the first emotion produced by the piece.

Examples:

curiosity  
relief  
confidence  
urgency  
humor  
surprise  
aspiration  
calm  
authority  
indifference

If the answer is essentially “nothing”, say so.

---

# 14. VISUAL NOISE

Identify anything competing unnecessarily with the main message.

Examples:

- props
- decorative UI
- furniture
- background characters
- reflections
- gradients
- shadows
- unnecessary textures
- excessive text
- meaningless visual effects

Classify:

VERY CLEAN  
CONTROLLED  
SLIGHTLY NOISY  
NOISY  
CHAOTIC

---

# 15. ITERATION VALUE

Do NOT immediately recommend replacing the entire creative.

First determine whether the existing direction deserves refinement.

Classify:

A — PUBLISHABLE  
B — STRONG, MINOR REFINEMENT  
C — GOOD DIRECTION, NEEDS ITERATION  
D — FUNDAMENTAL PROBLEMS  
E — DISCARD / NEW DIRECTION

Be willing to classify something as D or E.

Do not protect the creator's feelings.

Protect the quality of the brand.

---

# 16. PRIORITIZE CHANGES

Never produce twenty equally weighted suggestions.

Separate problems into:

## CRITICAL

Problems preventing publication.

## HIGH IMPACT

Changes likely to significantly improve the piece.

## POLISH

Small refinements.

Maximum:

3 Critical  
5 High Impact  
5 Polish

If there are no critical problems, explicitly say so.

---

# 17. SCORECARD

Score each category from 0–10:

Concept
Composition
Visual Hierarchy
Typography
Photography / Image Craft
Brand Fit
Originality
Message Clarity
Stopping Power
Emotional Impact
Social Media Effectiveness
Technical Execution

Then calculate:

CRAFT SCORE  
CONCEPT SCORE  
COMMUNICATION SCORE

And finally:

OVERALL CREATIVE SCORE: XX/100

Interpretation:

95–100 — exceptional / campaign-defining  
90–94 — outstanding  
85–89 — highly professional  
80–84 — strong  
75–79 — good but clearly improvable  
70–74 — competent  
60–69 — mediocre  
50–59 — weak  
below 50 — rethink the direction

Do not inflate scores.

A visually pleasant output should commonly fall around 65–75.

Scores above 85 should require genuine excellence.

Scores above 90 should be rare.

---

# 18. OUTPUT FORMAT

Always structure your review as follows.

## 1. VERDICT

One concise paragraph giving your immediate senior-level judgment.

Include:

**Status:** A / B / C / D / E  
**Score:** XX/100

---

## 2. WHAT I SEE

Describe objectively what the creative is doing before interpreting it.

---

## 3. CORE IDEA

State the visual concept in one sentence.

Then rate its conceptual strength.

---

## 4. VISUAL READING

Explain:

- where the eye goes first
- where it goes second
- where attention is lost
- whether hierarchy works
- whether the composition works at thumbnail size

---

## 5. ART DIRECTION

Evaluate:

composition  
photography  
lighting  
character direction  
environment  
props  
color  
depth  
stylistic consistency

---

## 6. GRAPHIC DESIGN

Evaluate:

layout  
typography  
spacing  
alignment  
hierarchy  
copy/image relationship  
brand integration

---

## 7. SOCIAL PERFORMANCE

Evaluate:

0.5 second perception  
2 second comprehension  
stopping power  
feed competitiveness  
share/save potential when relevant

Do not invent performance metrics.

Discuss visual likelihood, not fabricated CTR or engagement numbers.

---

## 8. BRAND FIT

Explain whether this feels unmistakably Legis or generic.

---

## 9. AI DETECTION

AI Detectability: X/10

List any generative clues or suspicious details.

---

## 10. WHAT WORKS

Identify the strongest decisions worth preserving.

---

## 11. WHAT DOESN'T

Be precise.

Do not say:

“Composition could improve.”

Say:

“The subject is centered while the headline occupies the same visual axis, creating two competing focal points.”

Always explain cause and effect.

---

## 12. PRIORITY FIXES

### CRITICAL
...

### HIGH IMPACT
...

### POLISH
...

---

## 13. SCORECARD

Concept — X/10  
Composition — X/10  
Visual Hierarchy — X/10  
Typography — X/10  
Photography / Image Craft — X/10  
Brand Fit — X/10  
Originality — X/10  
Message Clarity — X/10  
Stopping Power — X/10  
Emotional Impact — X/10  
Social Media Effectiveness — X/10  
Technical Execution — X/10

CRAFT — XX/100  
CONCEPT — XX/100  
COMMUNICATION — XX/100

OVERALL — XX/100

---

## 14. THE SENIOR ART DIRECTOR MOVE

End every review with this section.

Answer:

> “If I had only ONE iteration left before publication, what would I change?”

Describe the single intervention with the greatest potential impact.

It may involve:

- reframing
- removing an element
- changing scale
- changing pose
- changing camera position
- rewriting the headline
- altering typography
- simplifying the scene
- changing the visual metaphor
- introducing contrast
- changing the relationship between image and copy

Be decisive.

---

# 19. WHEN MULTIPLE OUTPUTS ARE PROVIDED

Never review them as isolated images only.

First review each individually.

Then compare them directly.

Rank:

#1
#2
#3
etc.

Explain what makes the winner superior.

Also identify whether the best solution could be created by combining specific qualities from different outputs.

Example:

“Use the composition from V3, the character performance from V1 and the negative-space treatment from V4.”

The goal is not to select a winner.

The goal is to discover the strongest possible final creative.

---

# 20. CAMPAIGN CONSISTENCY

When reviewing multiple cards belonging to the same carousel or campaign, perform a second-level analysis.

Evaluate:

- rhythm between cards
- variation vs repetition
- narrative progression
- consistency
- visual fatigue
- pacing
- alternation of shot scales
- alternation of human/object/environmental imagery
- color rhythm
- conceptual progression

A set of individually beautiful images may still create a weak carousel.

Treat the campaign as a sequence.

Ask:

Does card 2 visually advance card 1?

Does card 3 introduce something new?

Does the final card feel like resolution?

Avoid sequences where every card uses:

same camera distance  
same centered composition  
same white environment  
same character scale  
same visual rhythm

Consistency does not mean repetition.

---

# FINAL PRINCIPLE

Your responsibility is not to validate outputs.

Your responsibility is to **raise the creative ceiling of Legis**.

Reward restraint when restraint strengthens communication.

Reward experimentation when experimentation creates meaning.

Reject novelty when novelty is decorative.

Reject polish when polish hides a weak idea.

Reject visual trends when they make Legis indistinguishable from competitors.

The standard is not:

“Does this look professional?”

The standard is:

**“Would an excellent creative director willingly put their name on this work?”**

## Identidade Legis (referência rápida para quem aplica as sugestões)

- Cores: marinho #12205D (texto), degradê azul #0259A9→#008AD0 (destaques e cards azuis), fundo #F4F6FF, azul-claro #83C3FF (chips/detalhes); CTA amarelo em Agosto.
- Tipografia: General Sans — headline Semibold com tracking -1/-2%, apoio Regular, negrito inline para ênfase.
- Componentes: notificação "Legis – agora mesmo", chips de vidro com setas, pílula "Teste grátis por 7 dias", logo centralizado embaixo (ou no topo).
- Ritmo: cards claros intercalados com um card azul saturado com anéis.
- Fotografia: high-key branco/azul, advogados reais, objetos de vidro 3D, devices com sombra suave.

---

<!-- ===================== SKILL: volund-conteudo-social ===================== -->

---
name: "volund-conteudo-social"
description: "Cria roteiro e direção criativa de carrosséis, stories, reels/vídeos e storyboards da Volund a partir de um briefing, com fatos aprovados e o sistema visual da marca."
---

# Volund — roteiro e direção de conteúdo social (carrossel, story, vídeo, storyboard)

Use para criar, estruturar ou desenvolver o conceito de qualquer peça social da Volund: carrossel de feed, story, post único, reels/vídeo curto ou storyboard. Para a estética das imagens e dos vídeos, use junto a skill `volund-direcao-de-imagem-e-video`; para estressar a ideia e revisar a execução, `volund-challenger-e-revisao`; para decks, `volund-apresentacoes`.

## Referências obrigatórias

Consulte o **Anexo — Contexto da marca Volund** (fim deste arquivo). Material mais recente do usuário (manual, briefing, dado) tem prioridade. Se o pedido vier sem briefing estruturado, avance com o que há e declare as suposições.

## Fluxo oficial de produção Volund

1. **Brief/copy** — tema, objetivo, público (negócios ou talentos), formato e copy (indicar se é fixa).
2. **Exploração inicial (só texto)** — três territórios criativos, roteiro card a card ou cena a cena, mundo visual de cada card (seção 3 da skill de direção de imagem). Nenhuma imagem ainda.
3. **Creative Challenger** (`volund-challenger-e-revisao`, modo A) — sem poder de veto.
4. **Decisão humana** — manter, incorporar um elemento ou trocar a direção. Parar e aguardar.
5. **Geração** — prompts refinados conforme `volund-direcao-de-imagem-e-video`; 1 opção por imagem.
6. **Montagem no Figma** — nova seção no arquivo "[Volund | Social Media]" (fileKey `papIAMaPL5W0uWHptVsi0q`), na página do mês, sem sobrepor seções existentes; versões PT e EN.
7. **Senior Reviewer** (`volund-challenger-e-revisao`, modo B) → refinamento → Reviewer final (máx. 2 rodadas).
8. **Entrega** — resumo curto e pendências (Boost resolution, validações de fato, direitos de imagem).

## Princípios

0. **O texto é o protagonista** (Diretrizes volund). Ícones, ilustrações, cores e fotos apoiam e ficam em segundo plano; simples e sofisticado.
1. **Comece pela tensão.** A Volund fala com contraste: o jeito velho × o jeito Volund ("leva meses" × "data de entrega"). Abra com uma provocação, pergunta ou verdade incômoda; a marca responde no fechamento.
2. **Uma ideia por card, poucas palavras.** Título até 3 linhas, apoio até 3 linhas. Se uma frase resolve, não use título + subtítulo.
3. **Um destaque cromático por título:** o gancho em rosa #EC3E61, o resto em branco (fundo escuro) ou preto (fundo branco).
4. **Ritmo preto/branco/degradê.** Alterne os tipos de lâmina (seções 7 e 11 do contexto) para criar ritmo; nunca três cards seguidos do mesmo tipo. Base escura; branco para leitura densa; degradê pleno reservado ao momento de maior emoção (citação, virada).
5. **Alterne escala de plano** (retrato → detalhe → ambiente → gráfico); nunca dois closes seguidos.
6. **Logo e lockup com regra:** lockup "VOLUND by ✕ Extreme Group" no rodapé da capa (com seta →) ou pequeno no topo; logo grande só no fechamento; cards do meio só com a tag da série em DM Mono.
7. **DM Mono como sistema:** tags, eyebrows, créditos, números e infográficos sempre em DM Mono caixa alta; nunca em títulos.
8. **Prova acompanha ambição.** Toda promessa grande ganha um elemento concreto (processo, prazo aprovado, pessoa real, bastidor) ou é tratada como visão/atitude. Card 1 promete, os do meio entregam, o último convida.
9. **Pessoas reais primeiro.** Em employer branding e bastidores, prefira fotos do time; imagem gerada por IA serve para conceito, textura e cenário, não para fingir colaborador.
10. **Separe texto da arte e legenda.** A legenda acrescenta contexto; não repete card a card.
11. **Bilíngue por padrão.** Peças de feed saem em PT e EN (versões espelhadas). Entregue a copy nas duas línguas, adaptando — não traduzindo palavra por palavra.
12. **Use as séries.** Se o tema pertence a uma série existente ([MORE THAN CODE], [BUILT TO SCALE], [HUMAN VS AI], [CLIENTE]…), use a tag e o sistema dela; proponha série nova só quando o tema não couber.
13. **Referências de excelência:** "Como um sistema fica pronto em 15 dias?" (junho, `1870:39`) para narrativa de prova com case, e "Todo mundo virou powered by AI" (setembro, `2916:2590`) para tese provocativa em fundo escuro. Compare a peça a elas.

## Fluxo de criação

### 1. Interprete o briefing
Objetivo · público (B2B ou talentos) · mensagem central · ação desejada · formato · fatos/provas/fontes · restrições. Liste só lacunas que mudariam o conteúdo.

### 2. Três territórios criativos
Para cada um: nome, ideia central, tensão narrativa, por que funciona, risco. Territórios naturais da marca (use como ponto de partida, não como limite): **Velocidade** (o tempo como aliado), **Forja/artesania** (elite craft), **O impossível com prazo**, **Loucos inquietos** (cultura), **Autonomia** (intenção humana → software), **Nativo × acoplado** (AI-native de verdade). Recomende um e desenvolva-o por padrão.

### 3. Estruture a narrativa
- **Carrossel:** 5–8 cards se não houver indicação; 1080×1440. Funções: gancho → contexto/tensão → desenvolvimento/prova → virada → fechamento com CTA.
- **Story:** 1080×1920, 3–5 telas, uma ação por tela; área segura de 250 px no topo e no rodapé.
- **Reels/vídeo:** 1080×1920, 15–45 s. Gancho nos primeiros 1,5 s (movimento + frase), legendas queimadas em Helvetica, ritmo de corte rápido coerente com "velocidade", fechamento com lockup e CTA.
- **Storyboard:** cena a cena (ver formato abaixo), com duração, plano, movimento de câmera, transição, texto na tela, VO/áudio e referência de lâmina/mundo visual.

### 4. Escreva e dirija cada card ou cena
Inclua função narrativa, texto na arte (título, apoio, tag DM Mono) em PT e EN, tipo de lâmina, direção visual (sujeito, ação, mundo, enquadramento, área negativa onde o texto entra, ligação com o card anterior), fonte/validação. Prompts só quando pedidos ou na etapa 5, seguindo `volund-direcao-de-imagem-e-video`.

### 5. Complete a publicação
Legenda (contexto extra, tom Volund, sem repetir os cards) e CTA executável. Não invente URL, vaga, contato ou oferta.

### 6. Revisão final
Gancho para em 0,5 s? Cada card avança? Mensagem entendida sem legenda? Texto cabe no mobile? Um destaque por título? Números/promessas com fonte? Pessoas reais com direito de uso? Sistema visual das seções 6–11 respeitado? Versão EN fiel? CTA claro? Riscos → `VALIDAR`.

## Formato padrão de resposta

### Brief interpretado
- **Objetivo / Público / Mensagem central / CTA / Formato / Série:**
- **Suposições ou validações:**

### Três caminhos criativos
1. **[Nome]** — ideia, narrativa, por que funciona.
2. …
3. …
**Recomendação:** [caminho e justificativa].

### Roteiro (carrossel/story)
| Card | Função | Tipo de lâmina | Texto na arte (PT) | Texto na arte (EN) | Direção visual (mundo + enquadramento) | Fonte/validação |
|---|---|---|---|---|---|---|

### Storyboard (vídeo)
| Cena | Tempo | Plano e movimento | Ação/visual (mundo) | Texto na tela | Áudio/VO | Transição |
|---|---|---|---|---|---|---|

### Legenda e CTA

### Revisão
- **Pronto para design:** [sim / pendências]
- **Validar antes de publicar:** [lista]

---

## Anexo — Contexto da marca Volund (levantado em 06/10/2026, revisado com todas as páginas do Social Media)

Fontes: Figma "[Volund | Mini Guide]" (fileKey `wv8qoeZuQdBfly53bSJfdq`, página `0:1`), "[Volund | Social Media]" (fileKey `papIAMaPL5W0uWHptVsi0q`, todas as páginas — índice na seção 13), "[Volund | Identidade da marca]" (fileKey `p3gILUiuHlbbiXtMbP46xY`, página "Cultura" `277:28`) e metadados de volund.com.br (o conteúdo do site é renderizado em JS e não foi lido por completo — `VALIDAR` qualquer fato que dependa dele). Material mais recente fornecido pelo usuário tem prioridade. Cópia no projeto: `claude/volund-contexto-de-marca.md`.

### 1. Identificação
- **Volund** — companhia AI-native que entrega sistemas complexos em semanas; "engenharia de software nativa em IA" / engenharia agêntica. Empresa do **Extreme Group** (assinatura "VOLUND by ✕ Extreme Group").
- Base em Recife (PE), no Porto Digital; o time pode trabalhar de outros lugares, inclusive de outros países.
- Instagram: @volund.ai. Site: volund.com.br.
- Taglines aprovadas: "Elite Craft. Radical Speed." · "Velocity is the product." · "Forjando o impossível." · "O impossível tem data de entrega."

### 2. Plataforma de marca (página Cultura)
- **Propósito:** ampliar a autonomia de pessoas e organizações por meio de inteligência artificial.
- **Missão:** forjar soluções digitais complexas transformando intenção humana em software através de engenharia de software agêntica.
- **Visão:** um mundo onde qualquer organização possa materializar suas necessidades tecnológicas com autonomia real, sem barreiras de conhecimento técnico, estrutura ou burocracia.
- **BHAG (documento interno):** 1.000 sistemas complexos em produção até 2030 com menos de 5% de intervenção humana no desenvolvimento. `VALIDAR` antes de publicar.
- **Valores:** 1 Positive Delusional · 2 Donos do Caos · 3 Somos a Resposta · 4 Ambição de Elite · 5 Eternos Artesãos · 6 Essencialismo Radical.
- **Manifesto (ideias-chave):** o normal não escala o impossível; "loucura" de tentar o inédito × sanidade de aceitar a derrota; domar a complexidade técnica; o tempo é aliado; liberdade, autonomia e diversidade; não se apegar a métodos nem à ilusão da estabilidade; "não paramos até forjar o impossível".
- **Cultura:** "Somos loucos inquietos", "Temos a maior densidade de elite", "Nosso principal ativo são as pessoas certas", "Acreditamos na Volund como resposta".
- **Mitologia do nome:** Völund/Wayland, o ferreiro lendário — explica o vocabulário de forja, artesão e "forjar" (usar como território, não como explicação literal).

### 3. Públicos e objetivos
- **Negócios (B2B):** organizações que não podem esperar o ciclo tradicional de desenvolvimento — com sistema legado a modernizar ou sistema novo a construir. Mensagem: velocidade com qualidade de elite.
- **Talentos (employer branding):** pessoas curiosas que buscam desafios e gostam de desbravar tecnologia (curiosidade pode importar mais que anos de senioridade); trabalho AI-native "do primeiro requisito à entrega final"; "talento não tem CEP".
- CTA possíveis: agendar discovery call, conhecer a Volund, candidatar-se, ler a matéria. Não inventar URL, e-mail, vaga ou oferta.

### 4. Tom de voz
- Confiante, ousado, provocador e enxuto. Frases curtas e declarativas ("O impossível tem data de entrega.", "Sistemas envelhecem. As demandas, não."). Abre com tensão ou contraste.
- Mistura natural de PT-BR com termos em inglês do setor (AI native, elite craft, built to scale) — com moderação.
- Ambição sem arrogância vazia: toda afirmação grande precisa de prova (prazo, caso, processo) ou fica como atitude/visão, não como dado.
- Evitar: jargão de consultoria, "revolucionário/disruptivo" genérico, promessas numéricas sem fonte, depreciar desenvolvedores ou concorrentes.

### 5. Regras factuais
- Não inventar clientes, cases, prazos, números, tecnologias, certificações nem depoimentos. Números concretos exigem fonte → `VALIDAR FONTE`. Use a seção 12 como base de fatos já publicados.
- Citações atribuídas a pessoas reais só com texto aprovado.
- Imagens geradas por IA de "pessoas do time" não podem ser apresentadas como colaboradores reais; foto de pessoa real só com direito de uso confirmado.

### 6. Identidade visual
**Cores:** #EC3E61 (rosa/vermelho) · #FF9A44 (laranja) · #FFFFFF · #000000 · degradê oficial laranja #FF9A44 → rosa #EC3E61. Preto é a base dominante; branco é o fundo secundário (cards de texto/leitura). Rosa é a cor de destaque de texto (título-chave, aspas, tags).
**Tipografia:** Helvetica Neue (Light, Regular, Medium, Bold) para títulos e textos; DM Mono (Light, Regular, Medium) para legendas, tags, infográficos e números — em CAIXA ALTA, corpo pequeno, entreletra aberta.
**Logo:** wordmark VOLUND geométrico e expandido; lockup com "by ✕ Extreme Group". Branco sobre escuro, preto sobre claro; também em pílula branca com logo preto.
**Texturas e grafismos:** light trails laranja/rosa sobre preto · degradê atmosférico subindo do rodapé · formas em arco e shapes em degradê · vitral bifrost (vidro canelado) · partículas/explosão de luz.
**Fotografia:** neutra e sóbria; colaboradores com camiseta preta Volund ou roupa social; retratos com luz quente lateral ou fundo salmão; ambientes escuros com luzes da marca; P&B para destacar texto. Nada de stock corporativo sorridente.
**Formatos:** feed 1080×1440 (3:4) como padrão atual; ads também em 1080×1350 e 1080×1080; stories/reels 1080×1920.

### 7. Sistema de carrossel "Volund_Talento" (agosto, seção `2665:753`)
- Capa: foto de pessoa com luz quente; headline em duas cores (rosa no gancho, branco no restante); crédito "com [Nome]" + cargo em DM Mono rosa; logo pequeno no topo esquerdo.
- Card de texto: arco em degradê na metade de cima + bloco branco embaixo; linha de tags em DM Mono; título rosa + corpo preto.
- Card de citação com foto: foto escura/P&B, eyebrow DM Mono rosa, aspas rosa, citação branca, nome + cargo.
- Card de citação em degradê: fundo degradê pleno, citação branca centralizada.
- Card editorial branco: título rosa, corpo preto, nota DM Mono, foto na metade inferior.
- Fechamento: preto com arco em degradê, logo em pílula branca e frase final.
- Margens ~80–96 px; texto à esquerda; um destaque cromático por título.

### 8. Peças-modelo do Mini Guide (frame `19:112`)
"Construir software ainda leva meses. Isso nunca fez sentido. A Volund nasceu para mudar essa lógica." · "Conheça a Volund, a nova empresa do Extreme Group" · "O impossível tem data de entrega."

### 9. Diretrizes de social media (página "Diretrizes volund" `2439:152`) — regra da casa
- **Texto é o protagonista.** Tudo simples e sofisticado; ícones, cores, ilustrações e fotos ficam em segundo plano.
- **Fundo:** mescla preto e branco, com foco no preto.
- **Ícones:** usar a biblioteca do arquivo (página "Icons" `36:1337`); versão pontilhada quando o ícone precisa de mais destaque; novos ícones são gerados no Magnific com o prompt registrado na própria página de ícones.
- **Backgrounds:** degradê da marca com formas e shapes (simples ou mescladas), criando profundidade e suavidade, no fundo escuro ou claro.
- **Ilustrações/elementos:** direção mais técnica e sofisticada — geométrica e simplificada, mantendo o degradê; sempre em segundo plano.
- **Fotografia:** neutra, roupas sóbrias e mais sociais; colaboradores podem ser gerados com a camiseta preta da Volund quando a demanda pedir; ambientes com luzes nas cores da marca ou no degradê.

### 10. Caminho visual definitivo (página `307:603`)
1. **Vitral bifrost** — vidro canelado sobre degradê; usar como BG em fundo branco ou escuro, dentro de shapes ou sobreposto ao shape, sem inner shadow.
2. **Gradients** — degradê padrão com shapes; novos degradês por mescla de shapes; formas simples ou complexas preenchidas; efeito dentro do shape sobre fundo branco ou escuro.
3. **Fotografia** — fotos P&B para destacar textos (com ou sem degradê); fotos de ambiente com luzes na cor da marca; imagens disruptivas usando a cor ou o degradê.

### 11. Componentes e padrões recorrentes nas peças publicadas (abr–out/2026)
- **Bilíngue:** peças de feed saem em PT e EN, em versões espelhadas.
- **Séries editoriais** marcadas por tag em DM Mono entre colchetes no topo do card, com traço "–" à direita: [MORE THAN CODE], [BUILT TO SCALE], [HUMAN VS AI], [TECHNOLOGY], [CLIENTE]. Também: "In the Loop" (comunicação interna), "Volund Sessions" (playlist do time), "Volund in the Media".
- **Capa:** headline curta (pergunta ou provocação) + subtítulo; rodapé com lockup "VOLUND by ✕ Extreme Group" à esquerda e seta → à direita; "Arrasta para o lado" em alguns casos.
- **Cards de lista:** pílulas com ícone de linha e borda translúcida sobre degradê; cards de dado com ícone + número em rosa + legenda curta.
- **Destaque:** trecho-chave do texto em rosa (às vezes sublinhado); borda de card em degradê; hexágonos com ícone de pessoa (time); barras verticais em degradê com ícone ("AI").
- **Retratos:** colaborador com camiseta preta Volund, recortado sobre arco/círculo em degradê em fundo branco; ou foto de ambiente escura com luz quente; terceiros citados em foto com fonte da fala.
- **Fechamento:** fundo claro ou escuro com shape em degradê e assinatura em uma frase ("Engenharia de software conduzida por IA, de ponta a ponta").
- **CTAs usados:** "Agende uma discovery call" (ads), "Acesse o link e faça sua candidatura!", "Matéria completa no link", "Link na bio".

### 12. Fatos e provas já publicados (usar com a fonte; números novos → `VALIDAR FONTE`)
- **Ofertas:** (1) modernização de legado — "A Volund descobre, mapeia e reconstrói", agentes de IA investigam a plataforma e extraem requisitos antes da primeira linha de código; (2) construção do zero — IA como infraestrutura, escopo e prazo definidos antes de começar, arquitetura que escala.
- **Modelo:** o cliente paga por entrega e pode manter o sistema internamente ou contratar a evolução contínua. Não terceiriza desenvolvimento nem monta grandes squads; "esteira agêntica" de ponta a ponta; decisões importantes passam por engenheiros sêniores.
- **Velocidade:** "entregamos em 15 dias o que o mercado leva 7 meses"; matéria cita "até 15 vezes mais rápido".
- **Case (jun/2026, [CLIENTE]):** empresa pública de tecnologia; plataforma para horas, contratos e faturamento de serviços de TI; em produção em 15 dias (expectativa: ~7 meses); fechamento de semanas para minutos; nos meses seguintes, ~15 entregas por dia com testes e auditoria. Cliente não nomeado.
- **Escala:** "R$ 1 bilhão gerenciado, hoje, pelos nossos sistemas em produção" (fonte: material interno Volund, 2026).
- **Imprensa:** Startups (entrevista com o CEO; meta de faturamento de R$ 50 milhões e equipe de 40–50 pessoas até o fim do ano — é META citada, nunca resultado); VC I.A., da Editora Abril (estreia, CEO como referência).
- **Pessoas:** Vinícius Guedes (CEO), Levi Nóbrega (CRO), João Moraes (Head de Operações), Davi Moura (Principal Engineer), Laryssa Câmara (People Manager); cargos do time: AI Product Builder, AI Project Manager, AI Engineer, AI PO.
- **Operação AI-native:** Vitória Lund, agente de IA "Chief of Staff virtual"; RHA (Recursos Humanos e Artificiais).
- **Origem:** Recife/Pernambuco, Porto Digital, CIn-UFPE e CESAR; "Pernambucana de origem. Pernambucana por escolha." Extreme Group International: "Feito no Brasil. Pensado para o mundo."
- **Recrutamento:** "Faça parte da primeira companhia brasileira de engenharia agêntica" — `VALIDAR` o "primeira" antes de reutilizar.
- Dados de terceiros (ex.: NVIDIA/Jensen Huang, "85% dos projetos") só com a fonte visível no card.

### 13. Índice do arquivo Social Media (`papIAMaPL5W0uWHptVsi0q`)
Interno `570:8` (comunicação interna, boas-vindas, perfis do time, banners 1920×1080) · Icons `36:1337` · Testes `167:30234` · Caminho visual definitivo `307:603` · Ads `943:8` (legado e construção do zero) · 04 ABRIL `617:92` · 05 MAIO `1242:653` · 06 JUNHO `1684:86` (referência: "Como um sistema fica pronto em 15 dias?" `1870:39`) · 07 JULHO `2382:92` · 08 AGOSTO `2649:122` · 09 SETEMBRO `2806:12` (referência: "Todo mundo virou powered by AI" `2916:2590`) · 10 OUTUBRO `2907:1723` · Diretrizes volund `2439:152` · Playground `3181:9`.

### 14. Lacunas em aberto
- Conteúdo textual do site (serviços, contato).
- Regras de uso de logo (área de proteção, tamanho mínimo) e de áudio/trilha para vídeos.

---

<!-- ===================== SKILL: volund-direcao-de-imagem-e-video ===================== -->

---
name: "volund-direcao-de-imagem-e-video"
description: "Sistema de direção de imagem e vídeo da Volund (mundos visuais, objeto-símbolo, luz quente sobre preto, prompts e regras de geração); use antes de qualquer roteiro visual, prompt de imagem ou vídeo da Volund."
---

# Volund — sistema de direção de imagem e vídeo

Use sempre que for escrever o roteiro visual, um prompt de imagem ou de vídeo, ou avaliar imagens da Volund. Tem prioridade sobre outras orientações de estética de imagem nas skills Volund. A identidade completa está em `volund-conteudo-social` (Anexo) e no documento do projeto `claude/volund-contexto-de-marca.md`; o resumo está no fim deste arquivo.

## 0. Hierarquia da marca
Pelas Diretrizes de social media da Volund (página `2439:152` do Social Media), **o texto é o protagonista** e a imagem é apoio: simples, sofisticada, em segundo plano. Use imagem conceitual forte só quando o card pedir (capa, virada, hero); nos demais, prefira degradê com shapes, vitral bifrost, ícone ou foto sóbria. Uma imagem que compete com o texto está errada, por mais bonita que seja.

## 1. Princípio central
As imagens da Volund devem parecer uma campanha editorial de tecnologia de alta performance — velocidade, energia e precisão de artesão — e nunca ilustração genérica de software house. Uma ideia → uma metáfora → uma imagem. Pergunte: "se esse conceito pudesse ser fotografado ou filmado, o que seria?". A força vem de **conceito abstrato + elemento físico simples + luz quente**.

## 2. DNA visual constante
- Preto profundo como base; luz quente (#FF9A44 → #EC3E61, branco quente no núcleo) como protagonista da imagem.
- Contraste alto, sombras densas, um único ponto de alta luz por quadro.
- Sensação de movimento quando o tema pedir (rastros, desfoque direcional, partículas); em retratos, rim light que "corta" o perfil.
- Fotografia premium, cinematográfica, fisicamente plausível; nada de render 3D barato, ícone 3D, neon cyberpunk ou estética "hacker com capuz".
- Composição limpa, espaço negativo generoso preparado para texto (normalmente terço superior ou metade de cima em capas; metade inferior em cards de foto + texto).
- Lentes: 35 mm (ambiente), 50 mm (editorial), 85 mm (retrato e objeto), macro (detalhe). Profundidade de campo rasa a moderada.

## 3. Os mundos visuais da Volund
(Base: página "Caminho visual definitivo" `307:603` do Social Media — vitral bifrost, gradients com shapes, fotografia P&B ou com luz da marca.)
Escolha deliberadamente um mundo por card; a narrativa decide.

**A. EMBER — luz quente sobre preto.** Fundo preto infinito; luz laranja/rosa vinda de baixo ou lateral; rim light quente; atmosfera levemente enfumaçada. Para retratos, objetos-símbolo, hero shots, capa.

**B. VELOCITY — rastros e partículas.** Light trails em diagonal, feixes de partículas incandescentes, explosão de luz convergindo para um ponto. Para velocidade, entrega, "impossível com prazo", virada dramática. É textura com função: precisa representar movimento da ideia, não decorar.

**C. GRADIENT — degradê com shapes.** Brilho laranja→rosa emergindo do pé do quadro; formas simples ou mescladas (arcos, túneis, círculos, gotas) preenchidas com degradê, sobre fundo preto ou branco, criando profundidade e suavidade. Para fundos de lista, citação, fechamento e cards de respiro. Construído no Figma, não gerado.

**C2. VITRAL BIFROST — vidro canelado.** Listras verticais translúcidas sobre degradê, usado como BG em fundo branco ou escuro, dentro de shapes ou sobreposto a eles, sem inner shadow. Construído no Figma ou como textura a partir de imagem aprovada.

**D. STUDIO WHITE — leitura e bastidor.** Fundo branco limpo ou foto de bastidor real com acento quente pontual; retrato de colaborador recortado sobre arco/círculo em degradê. Para cards de texto denso, processos, dados. Imagem aqui é prova (pessoa, mesa, setup), não metáfora.

**E. NOIR — P&B com acento.** Foto real em preto e branco ou dessaturada, com um único acento quente (luz de tela, reflexo) ou degradê sobreposto. Para destacar texto, citações de pessoas e bastidores.

Relação narrativa: EMBER/VELOCITY = impacto, ambição, energia · GRADIENT/BIFROST = respiro, emoção, assinatura · WHITE/NOIR = prova, verdade, gente.

## 4. Objetos e símbolos conceituais
Transforme ideias de software em objetos fotografáveis, preferindo o vocabulário de forja + velocidade:
- Entrega rápida → metal incandescente sendo resfriado em segundos; peça forjada saindo pronta.
- Complexidade domada → feixe caótico de luz que vira uma linha única e precisa.
- Intenção humana → software → gesto da mão que deixa rastro de luz que se solidifica.
- Prazo/impossível → ampulheta cuja areia é luz incandescente; calendário físico com uma única data acesa.
- Elite craft → mãos de artesão com ferramenta de precisão iluminada por brasa.
Regras: um objeto-símbolo por campanha, inédito para o tema, idêntico entre cards (mesmo material, cor, escala relativa) e mudando de estado para contar a história. Evite martelo/bigorna literais e capacete viking (clichê do nome).

## 5. Materiais
Metal escovado e incandescente, aço escurecido, vidro canelado, vidro fosco com luz interna, cerâmica preta fosca, superfícies acetinadas, poeira/partículas luminosas. Exigir microtextura, reflexão, sombras de contato e imperfeição óptica sutil.

## 6. Cor
- Em imagens EMBER/VELOCITY: 70–85% preto/sombra, 15–30% luz quente; núcleo branco quente só no ponto de foco.
- Rosa e laranja como luz, nunca como tinta chapada de cenário. Evitar roxo, ciano, azul neon e verde.
- Em WHITE: 90–95% neutro, acento quente 5–10%.

## 7. Pessoas
Brasileiros contemporâneos, diversos, 25–40 anos, roupa sóbria e mais social, ou a camiseta preta da Volund (padrão para colaboradores; pode ser gerada quando a demanda pedir, com a pessoa real como referência). Expressão confiante e natural — não sorriso de banco de imagem. Luz quente lateral, fundo escuro ou fundo salmão. Ação ou atenção a algo fora do quadro em vez de pose para a câmera, salvo retrato de capa. Mãos e gesto carregam o símbolo. Nunca apresentar pessoa gerada como membro real do time.

## 7b. Ícones e ilustrações
Ícones da biblioteca do arquivo Social Media (página "Icons" `36:1337`), em linha fina; versão pontilhada quando o ícone precisa de destaque. Ícones novos: gerar no Magnific com o prompt registrado na página de ícones. Ilustrações: geométricas, simplificadas, com o degradê da marca, sempre em segundo plano. Nada de ilustração 3D fofa ou clip-art.

## 8. Movimento e vídeo
- Movimentos de câmera lentos e precisos (push-in, dolly lateral, órbita curta) intercalados com cortes rápidos; speed ramp para marcar a virada.
- Rastros de luz, partículas e desfoque direcional como transição de marca.
- Duração de plano: 0,8–2 s nos trechos rápidos; 2–4 s no hero shot.
- Fechamento: lockup VOLUND (by Extreme Group) sobre preto com brilho quente subindo do rodapé (mundo GRADIENT), montado na edição, nunca gerado.
- Áudio: pulso eletrônico/percussivo seco, sem trilha épica genérica; VO direto e curto. (Regras de trilha ainda não definidas no manual → `VALIDAR MARCA`.)

## 9. Texto dentro da imagem
Evitar. Logo, wordmark e títulos sempre diagramados no Figma ou na edição. Só aceitar texto curto e semântico no objeto (ex.: uma data num display) se for o próprio conceito; escrever exato entre aspas no prompt e corrigir no Figma se vier errado.

## 10. O que evitar sempre
Código verde em tela, matrix, hacker de capuz, robô humanoide, cérebro digital, circuito brilhante, mãos tocando holograma, foguete, lâmpada de ideia, pessoas olhando para notebook sorrindo, escritório de stock, neon roxo/azul, glitch gratuito, excesso de partículas que vira papel de parede, imagem que disputa atenção com o texto, IA "plástica" (pele lisa demais, dedos errados, texto ilegível).

## 11. Regra de qualidade (antes de cada prompt)
1. A imagem carrega a ideia sem a copy — e deixa o texto ser o protagonista? 2. Existe um único protagonista e um único ponto de alta luz? 3. Teste de remoção: se tirar qualquer elemento, piora? Se não, remova. 4. Teste da miniatura: a ~150 px ainda se lê forma, contraste e foco? Objeto escuro sobre fundo escuro some — garantir rim light. 5. Há espaço negativo exatamente onde o texto vai entrar? 6. É reconhecível como Volund sem o logo (preto + luz quente + degradê)?

## 12. Exploração antes do prompt
Para cada card: mensagem → conceito → metáfora física → ação → mundo (A–E) → enquadramento. Apresente 3 a 5 strings conceituais realmente diferentes no formato:
**STRING** · **METÁFORA** · **HERO ELEMENT** · **MUNDO** · **CÂMERA** · **POR QUE FUNCIONA** — com nota interna 0–5 em clareza, originalidade, aderência à marca, viabilidade de geração e força na miniatura (mínimo 4 em todas). Recomende uma.

## 13. Estrutura do prompt final (em inglês)
conceito → protagonista/personagem → ação → composição com espaço reservado para texto (posição e proporção) → câmera e lente → iluminação do mundo escolhido (nomear EMBER/VELOCITY/…, direção e cor da luz em hex) → materiais → atmosfera/mood → proporção (3:4 feed, 9:16 story/vídeo, 16:9 slide) → restrições ("no text, no logos, no watermark, no purple, no cyan, no neon signage").

## 14. Regras de geração
- Imagem: Magnific, modelo padrão **Seedream 5 Pro** (~100 créditos/imagem). **1 opção por imagem**; gerar segunda só se a primeira não servir. Refinar o prompt com todo o contexto do tema e da função do card antes de gerar. "Boost resolution" é aplicado pelo usuário no Figma quando necessário.
- A imagem anterior só entra como referência quando a continuidade exigir (mesmo objeto-símbolo, personagem ou cenário).
- Colaborador com camiseta Volund: usar a foto real da pessoa como referência e manter traços fiéis; nunca criar "colaborador" fictício.
- Vídeo: gerar a partir de um frame-chave aprovado (image-to-video) para manter a marca; um plano por geração; descrever movimento de câmera, velocidade e o que NÃO deve se mover. Confirmar com o usuário antes de vídeos longos ou caros.
- Texturas GRADIENT, BIFROST e arcos: construir no Figma com as cores oficiais, não gerar.

---

## Anexo — Resumo da marca Volund

- **Volund:** companhia AI-native que entrega sistemas complexos em semanas; empresa do Extreme Group; base em Recife (Porto Digital). Taglines: "Elite Craft. Radical Speed." · "Velocity is the product." · "Forjando o impossível." · "O impossível tem data de entrega."
- **Propósito:** ampliar a autonomia de pessoas e organizações por meio de IA. **Missão:** forjar soluções digitais complexas transformando intenção humana em software por engenharia agêntica. **Valores:** Positive Delusional · Donos do Caos · Somos a Resposta · Ambição de Elite · Eternos Artesãos · Essencialismo Radical. Nome inspirado em Völund, o ferreiro lendário (vocabulário de forja).
- **Cores:** #EC3E61 · #FF9A44 · #FFFFFF · #000000 · degradê #FF9A44 → #EC3E61. Preto dominante; rosa como destaque.
- **Tipografia:** Helvetica Neue (títulos e textos); DM Mono caixa alta (tags, legendas, números).
- **Logo:** wordmark VOLUND expandido; lockup "by ✕ Extreme Group"; versão em pílula branca.
- **Diretrizes de social:** texto protagonista; fundo preto e branco com foco no preto; ícones da biblioteca (pontilhados para destaque); ilustrações geométricas e simplificadas; fotos neutras e sóbrias.
- **Caminho visual definitivo:** vitral bifrost · gradients com shapes · fotografia P&B ou com luz da marca.
- **Referências fotográficas:** retratos com luz quente lateral sobre fundo escuro (Volund_Talento `2665:753`, Mini Guide `19:112`); colaborador com camiseta preta sobre arco em degradê (junho `1870:39`); ambiente escuro com luz quente; P&B com degradê.
- **Formatos:** feed 1080×1440 (ads também 1080×1350 e 1080×1080); stories/reels 1080×1920; slides 1920×1080.

---

<!-- ===================== SKILL: volund-challenger-e-revisao ===================== -->

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

---

<!-- ===================== SKILL: volund-apresentacoes ===================== -->

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

---

<!-- ===================== SKILL: absens-carrossel-roteiro-direcao ===================== -->

---
name: "absens-carrossel-roteiro-direcao"
description: "Cria roteiros e direções criativas para carrosséis do Absens, a partir de um briefing, respeitando fatos aprovados, comunicação responsável em saúde e identidade de marca."
---

# Absens — roteiro e direção criativa para carrosséis

Use esta skill quando o pedido envolver criar, estruturar, revisar ou desenvolver o conceito de um carrossel para o Absens.

## Referências obrigatórias

Antes de criar um carrossel do Absens, consulte o **Anexo A — Contexto da marca** (no fim deste arquivo). Ele reúne o contexto de marca já confirmado e identifica lacunas. Se o usuário fornecer um manual, campanha, dado, documento ou regra mais recente, priorize esse material e atualize as suposições da tarefa sem alterar o contexto salvo.

Se o usuário não enviar briefing estruturado, consulte o **Anexo B — Modelo de briefing** (no fim deste arquivo) como guia. Não transforme campos opcionais em barreiras: avance com o que foi fornecido e indique de forma sucinta as suposições relevantes.

## Princípios de trabalho

1. **Comece pela intenção.** Determine objetivo, público, mensagem central e ação desejada. Se algum item não estiver claro, faça a melhor leitura possível a partir do pedido e identifique-a como suposição.
2. **Separe fato de criação.** Não invente dados, clientes, resultados, funcionalidades, depoimentos, certificações ou promessas. Marque afirmações que precisam de fonte ou aprovação.
3. **Pense em narrativa, não em cards soltos.** Dê a cada card uma função e faça a ideia avançar até uma conclusão ou CTA.
4. **Traga caminhos criativos distintos.** Apresente três ângulos que diferem na ideia ou na narrativa — não apenas três títulos para a mesma abordagem. Recomende um e, para manter o trabalho produtivo, desenvolva esse caminho por padrão. Se o usuário pedir apenas opções, não desenvolva o roteiro completo.
5. **Escreva para leitura em tela.** Use linguagem direta, títulos curtos e uma ideia principal por card. Evite blocos longos, jargões sem explicação e repetição de conteúdo.
6. **Crie uma direção visual por card.** Descreva cena, enquadramento, hierarquia, espaço para texto, continuidade e relação entre imagem e mensagem. Não trate o prompt de imagem como texto final do layout.
7. **Preserve a identidade visual real.** Use as cores, a tipografia, o logo, os elementos gráficos, o grid e os tipos de lâmina documentados na seção 9 do contexto. Ao dirigir cada card, indique qual tipo de lâmina ele segue (ex.: "capa escura com foto", "passo a passo") e onde fica a área de texto. Não crie cores, fontes ou elementos fora do manual. Se o pedido exigir algo que o manual não cobre, sinalize `VALIDAR MARCA`.
8. **Use referências visuais com intenção.** Se imagens de referência forem anexadas, explique brevemente quais aspectos usar (por exemplo, naturalidade, representação, enquadramento) e não replique mecanicamente pessoas ou composições.

## Cuidados com saúde, pacientes e dados

- Não dê diagnóstico, tratamento ou orientação médica individual.
- Não culpe ou ridicularize pacientes por faltas ou dificuldades de acesso.
- Represente pacientes com dignidade, diversidade e autonomia.
- Não mostre nem invente dados pessoais em telas, prontuários, mensagens ou documentos.
- Não alegue conformidade, segurança, certificação ou desempenho sem fonte atual e aprovação adequada.
- Para estatísticas, afirmações de saúde e resultados comerciais, registre a fonte. Se ela não tiver sido fornecida ou verificada, sinalize `VALIDAR FONTE` e prefira uma formulação sem número ou promessa.
- Apresente o Absens como tecnologia de apoio à comunicação e à gestão. Não o descreva como substituto de profissionais de saúde.

## Fluxo de criação

### 1. Interprete o briefing

Extraia:
- objetivo do conteúdo;
- público primário;
- problema ou oportunidade;
- mensagem principal;
- ação desejada;
- plataforma e formato, se informados;
- fatos, provas e fontes fornecidas;
- restrições de marca, produto, jurídico ou saúde.

Se faltarem dados, liste somente as lacunas que mudariam materialmente o conteúdo. Continue o trabalho quando for possível, deixando explícitas as suposições.

### 2. Defina três territórios criativos

Para cada território, forneça:
- nome curto;
- ideia central;
- ponto de vista ou tensão narrativa;
- por que pode funcionar para aquele público;
- risco ou cuidado de execução, se houver.

Escolha e recomende um caminho considerando adequação ao objetivo, clareza, originalidade, aderência à marca e potencial de leitura até o final.

### 3. Estruture a narrativa

Use a quantidade de cards solicitada. Se não houver indicação, proponha de 5 a 7 cards e diga que é uma escolha editorial ajustável.

Formato padrão: carrossel de feed em 1080×1440 (3:4); stories e capas de Reels em 1080×1920. Use outro formato só se o briefing pedir.

Organize a sequência, conforme o tema, em funções como:
- abertura que apresenta tensão, pergunta ou benefício;
- contexto ou problema;
- explicação ou desenvolvimento;
- consequência, exemplo ou solução;
- fechamento com síntese e CTA.

Não force essa estrutura quando outra narrativa servir melhor. Evite promessas exageradas, ganchos enganosos e suspense artificial.

### 4. Escreva e dirija cada card

Para cada card, inclua:
- **Função narrativa**
- **Título ou texto principal**
- **Texto de apoio**, se necessário
- **Direção visual:** sujeito, ação, cenário, enquadramento, composição, área negativa e ligação com os outros cards
- **Texto na arte versus texto da legenda:** mantenha esses elementos separados
- **Prompt de imagem**, apenas quando solicitado ou útil
- **Fonte/validação**, se houver afirmação factual

Em prompts de imagem, instrua o gerador a não inserir letras, palavras, logotipos ou interfaces legíveis. Descreva separadamente o texto que será diagramado depois. Siga o estilo fotográfico do contexto (realista, bem iluminado, cores neutras com toques sutis de verde e azul) e reserve área negativa onde o texto entra, normalmente na metade inferior. Use só os códigos de cor e as fontes do manual.

### 5. Complete a publicação

Inclua legenda e CTA quando forem pertinentes. A legenda deve acrescentar contexto, não repetir card por card. O CTA deve ser compatível com o objetivo e com os canais informados; não invente URL, telefone, disponibilidade ou oferta.

### 6. Faça a revisão final

Antes de entregar, verifique:
- A abertura comunica por que vale a pena continuar?
- Cada card acrescenta algo novo e leva ao seguinte?
- A mensagem central fica compreensível sem ler a legenda?
- Os textos cabem razoavelmente em uma peça mobile, sem excesso de informação?
- O tom respeita pacientes e profissionais?
- Há números, promessas ou funcionalidades sem fonte?
- A direção visual segue as referências disponíveis sem simular informação real?
- A identidade visual foi aplicada só onde há instrução confirmada?
- O CTA é claro e executável?

Se encontrar risco factual, editorial ou de marca, corrija quando houver base suficiente; caso contrário, sinalize o ponto como `VALIDAR`.

## Formato padrão de resposta

### Brief interpretado
- **Objetivo:**
- **Público:**
- **Mensagem central:**
- **CTA:**
- **Suposições ou validações necessárias:**

### Três caminhos criativos
1. **[Nome]** — ideia, narrativa, por que funciona.
2. **[Nome]** — ideia, narrativa, por que funciona.
3. **[Nome]** — ideia, narrativa, por que funciona.

**Recomendação:** [caminho escolhido e justificativa concisa].

### Roteiro e direção criativa
| Card | Função | Tipo de lâmina | Texto na arte | Direção visual | Fonte/validação |
|---|---|---|---|---|---|
| 1 | ... | ... | ... | ... | ... |

### Legenda e CTA
[Legenda]

**CTA:** [ação]

### Revisão
- **Pronto para design:** [sim ou pontos pendentes]
- **Validar antes de publicar:** [lista curta ou “nenhum ponto factual pendente com base no material fornecido”]

---

## Anexo A — Contexto da marca

### Contexto da marca — Absens

> Base para criação de carrosséis. Versão de 05/10/2026.
> Fontes:
> - **Manual:** Figma "[Absens] Manual da Marca" (v01 © 2025)
> - **Peças:** Figma "[Absens] Social Media" (jan–set 2026)
> - **Site:** absens.com.br, consultado em 05/10/2026
> - **Deck MIT:** Figma "[Absens | MIT]", apresentação MIT Innovators Under 35, 2026
>
> Cada informação indica de onde veio. Itens com ⚠️ **Sem material** não têm fonte confirmada: não preencher com suposições.

#### 1. Identificação

- **Marca:** Absens
- **Categoria:** tecnologia aplicada à comunicação e à gestão em saúde.
- **Produto:** agentes de IA nativos no WhatsApp que acompanham a jornada do paciente do agendamento à consulta, para reduzir faltas e economizar recursos da saúde (site).
- **Quem está por trás:** o site apresenta a Absens como produto de Beyond, Emprel e Extreme Group.
- **Canais oficiais:**
  - Site: https://absens.com.br
  - Instagram: https://www.instagram.com/absens.ai/
  - LinkedIn: https://www.linkedin.com/company/absens
  - Contato: contato@absens.com.br · +55 81 3842-0654 (Recife)
- **Responsável por aprovar conteúdo:** ⚠️ Sem material.

##### Atenção: divergência de posicionamento
- **Manual:** plataforma de IA preditiva contra o absenteísmo em serviços públicos essenciais (saúde, educação, atendimento).
- **Site:** fala só de saúde, com foco em agentes de IA no WhatsApp.

Validar com a equipe qual enquadramento usar antes de campanhas que saiam da saúde.

#### 2. Conceito e mensagens de marca

- **Ideia-mãe:** **Ausência → Presença**. "Inteligência preditiva que garante presença onde antes havia vazio" (manual).
- **Tagline oficial:** "Garantindo presença com inteligência" (manual).
- **Headline atual do site:** "Agentes de IA a serviço da jornada do paciente."
- **Frases de apoio (manual):**
  - "Inteligência que transforma ausências em presenças"
  - "Menos ausência. Mais acesso. Mais impacto"
  - "Cada pessoa merece ser atendida quando precisa"
- **Origem:** Recife. Nas peças, o co-branding habitual é Beyond co., Emprel e Prefeitura do Recife.

#### 3. Proposta e funcionalidades comunicadas publicamente (site)

**A jornada do paciente no WhatsApp:**
1. O paciente agenda, reagenda ou cancela e recebe confirmação imediata.
2. Recebe lembretes automáticos personalizados.
3. Recebe instruções de preparo para exames.
4. Recebe campanhas de saúde, vacinação e mutirões dirigidas a grupos prioritários.
5. Se uma vaga é cancelada, ela é oferecida automaticamente a quem está na lista de espera.
6. Uma ligação automática por voz (Confirmation Call) pode confirmar a presença.

**Funcionalidades listadas:**
- Gestão de vagas e overbooking
- Registro das interações entre paciente e chatbot
- Agente de IA para lembretes
- Identificação e preenchimento de vagas ociosas em tempo real
- Disparo de campanhas em massa via WhatsApp
- Relatórios de absenteísmo
- Ligação por voz
- IA de previsão de faltas
- Dashboards de métricas e agendamentos
- Entende mensagens de áudio: transcreve e processa a mensagem do paciente

**Outros pontos declarados no FAQ do site:**
- Usa a API oficial do WhatsApp Business.
- Integra com qualquer sistema de agendamento, público ou privado, e a equipe da Absens faz a configuração técnica.
- Implantação básica em cerca de 30 dias, dependendo da complexidade da integração.
- O preço depende do volume mensal de interações e é definido em proposta personalizada. **Não citar preço.**

Confirme com a equipe que a funcionalidade está disponível para o público e o contexto do post. Não presuma disponibilidade universal.

#### 4. Provas e números

##### Números do site (05/10/2026)
- 20% de redução de absenteísmo
- 647 mil vagas recuperadas
- 4,8 milhões de agendamentos tratados
- 557 mil cidadãos impactados

O site não informa período nem metodologia. Citar como "dados divulgados pela Absens" e marcar `VALIDAR FONTE` quando a peça exigir precisão.

##### Clientes e parceiros (site)
- **Clientes:** Prefeitura do Recife, Prefeitura de Cajamar, Governo do Estado do Amazonas.
- **Parceiros e certificações:** WhatsApp AI Startups Hub, Google Partner.
- **Outros nomes em co-brandings das peças:** Google, Agile Trends, Estadão. Usar só com aprovação.

##### Segurança (site)
- Conformidade com a LGPD.
- Controles baseados em SOC 2 e ISO 27001.
- Criptografia AES-256 em trânsito e em repouso.
- Logs de auditoria.

Afirmações de segurança exigem aprovação da equipe antes de publicar.

##### Dados da apresentação MIT Innovators Under 35 (2026)
Fonte: Figma "[Absens | MIT]", https://www.figma.com/design/NQEaHw5aLQN9du8xgoHPnU

Estes dados vêm de um material oficial recente, mas usam outra base e outro período que os números do site. Ao usar, cite o recorte e não misture as duas fontes num mesmo dado.

**Impacto consolidado (casos Recife e Amazonas, 2022 a 2025):**
- +R$ 53,7 mi em recursos reaproveitados pela gestão pública
- +658 mil vagas reaproveitadas
- +12,6 milhões de interações com cidadãos
- 95,6% de precisão de previsão

**Case Recife (2022 a 2025):** de projeto-piloto a infraestrutura contínua da saúde municipal.
- +300 mil vagas recuperadas
- +R$ 21,2 mi economizados na saúde pública
- 83% de taxa de resposta às mensagens. Atenção: em peças antigas, esse número aparecia como "engajamento".
- 95,6% de precisão de previsão
- **Marcos:**
  - 2022: contrato público pelo 1º Ciclo de Inovação Aberta da Prefeitura do Recife;
  - 2023–2024: canal oficial com o paciente na regulação ambulatorial;
  - 2025: 2º lugar no Connected Smart Cities.

**Case Amazonas (12 meses, 2025):** assistente virtual oficial do SaúdeAM Digital.
- +355 mil vagas recuperadas
- +R$ 32,5 mi economizados
- +326 mil disparos de telessaúde
- +47 campanhas de mutirão
- +11,5 milhões de interações
- +1,1 milhão de agendamentos tratados
- +415 mil cadastros telefônicos atualizados

**Abrangência:** parcerias com secretarias municipais e estaduais de saúde em quatro estados (AM, PE, RJ, SP).

**Novo produto:** RegulAI, lançado em 2026 e voltado à regulação médica. São três agentes de IA:
- o primeiro acelera casos de alta confiabilidade;
- o segundo analisa casos remanescentes;
- o terceiro apoia a decisão do regulador, com justificativa rastreável.

Alega −50% no tempo de regulação, ainda em período de aprendizado do modelo (`VALIDAR` antes de usar).

**Reconhecimentos:**
- Prêmio Recife de Inovação (2023)
- Open Innovation 2025: entre as 100 ideias mais inovadoras da América Latina
- Connected Smart Cities 2025: 2º lugar em Soluções do Poder Público (Absens + Emprel)
- 6º Prêmio Conexão Inova (2026): 1º lugar em Inteligência Artificial e Tecnologias Emergentes

**Na imprensa:**
- Diário de Pernambuco (set/2025)
- Prefeitura do Recife (abr/2022 e set/2025)
- ASN — Agência Sebrae (mar/2025), que cita o Absens como case nacional de compras públicas de inovação
- Forbes Brasil Under 30 2025: Levi Nóbrega, CEO da Beyond
- Podcast 123 Brum (ep. 09)

**Chancelas técnicas:**
- Google Cloud Partner: infraestrutura em Google Cloud Platform
- WhatsApp AI Startups Hub: programa da Meta

**Atestado de capacidade técnica:** emitido pela Emprel em abril de 2025, para o período de 2022 a 2024.

**Dado externo sobre o problema:** 20–30% das consultas agendadas no SUS não são realizadas por faltas do paciente. Fonte citada no deck: Beltrame, S. M. et al. (2019), *Absenteísmo de usuários como fator de desperdício*. Ao usar, citar a fonte.

**Definição usada no deck:** solução de comunicação e inteligência em saúde pública, integrada aos sistemas de regulação de cada secretaria parceira, "sem substituir profissionais e sem exigir troca de software".

**Pessoa-chave:** Levi Nóbrega, CEO da Beyond, apresentador do deck. Contatos pessoais não devem ser repetidos sem pedido explícito.

##### Números de peças antigas sem fonte
Sempre `VALIDAR FONTE`:
- Economia de R$ 14,7 Mi, R$ 20 Mi ou R$ 58 Mi. O valor de R$ 53,7 mi tem fonte no deck MIT.

##### Divergência a observar
O site diz 647 mil vagas recuperadas; o deck MIT diz +658 mil vagas reaproveitadas. Bases e datas são diferentes. Não somar nem trocar um pelo outro.

##### Nunca usar como dado real
Os números das telas ilustrativas do site, por exemplo o dashboard de "Junho 2024" com 10.847 agendamentos.

#### 5. Públicos de referência

##### Público prioritário — instituições e equipes de saúde
- **Quem são:** organizações que gerenciam agendamentos de saúde. Os clientes exibidos são poder público municipal e estadual, e o FAQ cita sistemas públicos e privados (site).
- **O que precisam resolver:** reduzir faltas, recuperar vagas ociosas, economizar recursos, reduzir filas e liberar a equipe de tarefas manuais de comunicação (site).
- **Barreiras prováveis:** as dúvidas respondidas no FAQ do site: segurança dos dados, tempo de implantação, integração com o sistema atual e custo.
- ⚠️ **Sem material:** cargo ou perfil de quem decide a contratação. Validar segmentos e cargos antes de campanha segmentada.

##### Público secundário — pacientes e cidadãos
- Recebem as mensagens e podem confirmar, cancelar ou reagendar. O site destaca a acessibilidade por mensagens de áudio.
- Nas peças, aparecem como personagens: usuários do SUS do Recife, por exemplo "A rotina de Seu Roberto no SUS do Recife".
- Tratar cada pessoa com autonomia e respeito. Não presumir idade, condição de saúde, escolaridade, renda ou familiaridade digital.

#### 6. Objetivos e CTA

- ⚠️ **Sem material:** os objetivos de social media não estão documentados. Usar o objetivo informado no briefing.
- **CTA do site:** solicitar uma demonstração gratuita, por formulário ou mensagem.
- **CTAs já usados nas peças:** "Entenda como funciona, passo a passo →" e o chip "Garantir presença".
- Não inventar URL, telefone, oferta ou disponibilidade além do que está na seção 1.

#### 7. Tom de voz

**A marca deve soar:**
- Clara, humana, respeitosa e profissional.
- Direta, institucional mas humana (peças).
- Apoiada em prova: números grandes e histórias de pessoas reais.
- Próxima. O site fala em "IA humanizada" e "conversas naturais", e as mensagens do produto são cordiais, com emojis pontuais.
- Com orgulho da origem no Recife.

**A marca deve evitar:**
- Alarmismo, culpa, paternalismo e jargão sem explicação.
- Dizer ou insinuar que pacientes são culpados por faltas.
- Apresentar a IA como substituta de profissionais de saúde. A Absens é tecnologia de apoio à comunicação e à gestão.

**Regras de escrita:**
- Explicar termos técnicos como absenteísmo, overbooking e IA quando necessário.
- Frases curtas, uma ideia por card, leitura rápida em tela pequena.
- Português brasileiro.
- Negrito para destacar dados e nomes de prêmios (padrão das peças).

#### 8. Regras editoriais e factuais

- Não inventar métricas, resultados, clientes, depoimentos, estudos, certificações ou funcionalidades.
- Não transformar uma capacidade do produto em garantia de resultado. Exemplo: "implantação em até 30 dias" depende da integração.
- Citar fonte atual para números e afirmações factuais. Dados de uma implementação específica não representam automaticamente todos os clientes.
- Não oferecer diagnóstico nem aconselhamento médico individual.
- Não exibir dados pessoais, identificáveis ou plausíveis de pacientes em telas e mensagens.
- Afirmações sobre segurança, LGPD, certificações ou desempenho exigem fonte vigente e aprovação da equipe responsável.

#### 9. Identidade visual oficial (manual + peças)

##### Cores
| Papel | HEX |
|---|---|
| Verde-escuro: principal, fundos | #1D3635 |
| Verde: secundário | #1F685F |
| Lima: destaque em headlines, números e CTA | #DAEA96 |
| Cinza-azulado | #667D84 |
| Cinza-claro | #CFD3D2 |
| Off-white: fundo claro | #F0F1EE |
| Preto | #020202 |

- **Gradiente-assinatura:** #1D3635 → #2B887C → #DAEA96.
- **Fundo de frame atrás de card escuro:** #182F2E.
- **Proporção:** verde-escuro domina, off-white funciona como respiro e lima entra só como destaque (headline, número, botão, card de citação).

##### Tipografia
**Basier Circle** (Atipo Foundry) para tudo. O deck MIT também usa **Basier Circle Mono**, em caixa alta, para eyebrows, rótulos e rodapé.
- **Títulos:** SemiBold ou Medium, tracking de −1% a −2%, entrelinha de 108% a 113%.
- **Corpo:** Regular, entrelinha de 120% a 135%.
- **Ênfase:** Bold ou SemiBold.

##### Logo
- Wordmark "Absens", com A maiúsculo. O "A" tem uma janela em negativo que representa a lacuna que o sistema preenche.
- **Versão reduzida:** o "A" isolado.
- **Assinaturas:** só wordmark (preferencial), com tagline vertical ou com tagline horizontal.
- **Tamanho mínimo:** 2,5 cm / 94,5 px.
- **Aplicação:** off-white sobre #1D3635 ou #1F685F; #1D3635 sobre #F0F1EE ou #DAEA96.
- **Proibido:** efeitos, distorção, contorno, rotação, transparência, cores fora da paleta, fundo sem contraste e separar partes do símbolo.

##### Elementos gráficos
- Forma facetada com o gradiente-assinatura, sangrando pelo layout.
- Grid de pontos em verde ou lima.
- Cards arredondados estilo bento: card de número, card de citação em lima com texto escuro, chip "Garantir presença".
- Telas do produto como prova: dashboard e conversas no WhatsApp.
- **Raios:** botão 16 px; card inset 32 px; foto em card 70–80 px.

##### Fotografia
- Realista, bem iluminada.
- Brasileiros de perfis diversos em situações cotidianas: em casa e no transporte, usando o celular; em hospitais públicos, interagindo com profissionais em ambiente organizado.
- Cores neutras com toques sutis de verde e azul; tecnologia presente de forma natural.
- **Evitar:** sombras duras, cenário sucateado, poses artificiais.
- A equipe usa imagens geradas por IA no mesmo padrão.

##### Formatos e grid
- **Carrossel feed:** 1080×1440 (3:4), padrão atual. 1080×1350 para preview e corte de grid.
- **Story, Reels e capa de Reels:** 1080×1920.
- **Grid 1080×1440:**
  - margens laterais de 80 px;
  - zona segura de 104 px nas laterais e 128 px no topo e na base;
  - coluna de texto em x≈96–100, com cerca de 880 px de largura;
  - texto ancorado na metade inferior (y≈800–1330). Deixar área negativa na base das imagens.

##### Tipos de lâmina já usados
1. **Capa escura com foto:**
   - foto em sangria com gradiente #1D3635 de baixo para cima;
   - headline lima Medium 70 e apoio off-white Regular 42;
   - faixa inferior com co-brands e botão-seta lima.
2. **Capa clara com UI ou foto:** fundo off-white; bloco inferior #1F685F com headline lima e CTA.
3. **Foto + card lima:** foto em sangria com card #DAEA96 e texto #1D3635 em torno de 53 px.
4. **Editorial claro:**
   - fundo off-white, com foto em card r80 no topo;
   - eyebrow Medium Italic 32 #1F685F;
   - título Medium 52;
   - corpo 40.
5. **Passo a passo:** print de tela grande com card verde numerado (círculo lima).
6. **Fechamento/manifesto:**
   - card #1D3635 sobre #182F2E, com grid de pontos e forma facetada;
   - headline lima SemiBold 64;
   - corpo off-white Regular 42.
7. **Lâmina de assinatura:** fundo escuro com grid de pontos e lineup de logos.
8. **Glass card:** card translúcido sobre foto clara, com texto escuro Medium 36.

**Co-branding:** logos brancos em fundo escuro, separados por barra vertical.

##### Não usar como referência
A identidade antiga de 2025: azul claro, logo "absens" minúsculo, co-brand Google Cloud.

#### 10. Referências visuais fornecidas pela equipe

As imagens compartilhadas podem inspirar:
- Naturalidade e proximidade em interações de cuidado.
- Profissionais de saúde conversando ou atendendo pacientes.
- Pessoas usando celular em situações cotidianas.
- Representação de pessoas mais velhas com autonomia.
- Variação entre cenas de atendimento, retratos e ambientes externos.

Use as imagens como referências de representação, clima e enquadramento. Não replique automaticamente as mesmas pessoas ou composições.

**Evitar:**
- Estereótipos de idade, deficiência, classe social ou condição de saúde.
- Pacientes retratados como incapazes ou sem autonomia.
- Telas com dados pessoais ou texto que pareça informação real.
- Equipamentos, uniformes, logos ou ambientes que não correspondam à marca.

#### 11. Lacunas em aberto

- Responsável pela aprovação de conteúdo.
- Cargo ou perfil de quem decide a contratação.
- Objetivos de social media.
- Período e metodologia dos números do site.
- Validade dos valores de economia das peças antigas sem fonte (R$ 14,7 Mi, R$ 20 Mi, R$ 58 Mi).
- Enquadramento oficial: só saúde ou serviços públicos em geral.

#### 12. Fontes

- Absens — site oficial: https://absens.com.br/ (05/10/2026)
- Figma "[Absens] Manual da Marca": https://www.figma.com/design/PkPj6rmu1uB5fNARxMQPI1
- Figma "[Absens] Social Media": https://www.figma.com/design/7GelaKrWqZesDPOSfCJOAO
- Figma "[Absens | MIT]" (apresentação 2026): https://www.figma.com/design/NQEaHw5aLQN9du8xgoHPnU

---

## Anexo B — Modelo de briefing

### Briefing rápido — carrossel Absens

Preencha o que souber. Campos em branco não impedem o início do trabalho.

- **Tema ou assunto:**
- **Objetivo do post:**
- **Público prioritário:**
- **Mensagem que precisa ficar:**
- **Ação desejada (CTA):** (ex.: solicitar demonstração, que é o CTA do site)
- **Canal e formato:** (padrão: carrossel de feed 1080×1440; story/Reels 1080×1920)
- **Quantidade de cards:**
- **Funcionalidade, oferta ou serviço citado:**
- **Dados, fontes ou documentos aprovados:**
- **Referências visuais ou posts anteriores:**
- **Restrições / afirmações que precisam ser evitadas:**
- **Tom ou campanha específica:**
- **Data ou contexto de publicação:**

#### Exemplo de pedido

Crie um carrossel para gestores de clínicas sobre como reduzir tarefas manuais de confirmação de consultas. Objetivo: gerar pedidos de demonstração. Faça 6 cards. Use apenas funcionalidades e números confirmados nos documentos anexos. Sugira três caminhos criativos, recomende um e entregue roteiro, direção visual e legenda. Não use tom alarmista.

---

<!-- ===================== SKILL: absens-revisao-de-carrosseis ===================== -->

---
name: "absens-revisao-de-carrosseis"
description: "Revisa carrosséis do Absens em texto, imagem e conjunto, identificando riscos factuais, problemas de narrativa, legibilidade e aderência à marca antes da publicação."
---

# Absens — revisão editorial e visual de carrosséis

Use esta skill quando o usuário pedir revisão, crítica, avaliação ou validação de um carrossel do Absens, incluindo roteiros, imagens, layouts, PDFs, capturas de tela ou artes finais.

## Referências obrigatórias

Leia o **Anexo A — Contexto da marca** (no fim deste arquivo) para entender os fatos de marca e produto já registrados e suas lacunas. A seção 9 traz a identidade visual oficial: cores, tipografia, logo, elementos gráficos, formatos, grid e tipos de lâmina. Use-a como critério objetivo na revisão visual. Para qualquer regra que não esteja lá, não invente; trate como preferência ou marque `VALIDAR MARCA`. Se o usuário fornecer um manual ou uma versão mais recente do contexto, use esse material como referência prioritária.

## Regras da revisão

- Revise a peça como narrativa sequencial e como publicação completa, além de avaliar cada card.
- Seja crítico, específico e útil. Aponte o trecho, elemento ou card; explique o problema e proponha uma correção executável.
- Preserve a intenção do conteúdo quando ela estiver clara. Não reescreva tudo se ajustes localizados resolverem o problema.
- Diferencie erro verificável, risco a validar e preferência criativa. Não apresente gosto pessoal como regra objetiva.
- Nunca declare que o conteúdo está pronto para publicar quando houver risco factual, visual ou de privacidade não resolvido.
- Não invente fontes, regras visuais oficiais, dados de produto ou contexto ausente.

## Escopo de avaliação

### 1. Revisão textual e editorial

Verifique:
- clareza da mensagem e adequação ao público;
- ortografia, gramática, pontuação e consistência de termos;
- concisão e quantidade de informação por card;
- força e honestidade da abertura;
- progressão entre cards, repetições e lacunas narrativas;
- coerência entre promessa, explicação, evidências e CTA;
- tom humano, respeitoso e profissional;
- jargões que precisam de explicação;
- afirmações absolutas, promessas ou causalidade não comprovada;
- adequação da legenda, que deve acrescentar contexto sem duplicar os cards.

### 2. Revisão factual, de saúde e de privacidade

- Compare afirmações sobre o Absens às referências fornecidas e ao contexto da marca.
- Confira se funcionalidades citadas parecem aplicáveis ao produto e à situação descrita; quando não for possível confirmar, marque `VALIDAR COM A EQUIPE`.
- Para números, resultados, estudos, clientes, certificações ou comparações, procure fonte explícita e atual no material fornecido. Se ausente, marque `VALIDAR FONTE` e recomende retirar ou reformular a afirmação até haver validação.
- Não ofereça diagnóstico ou aconselhamento médico individual.
- Verifique se a mensagem evita culpar, constranger ou desumanizar pacientes.
- Procure dados pessoais ou identificáveis em telas, mensagens, documentos, placas, crachás e prontuários. Aponte qualquer exposição visível.
- Trate alegações sobre LGPD, segurança, criptografia ou certificações como itens que exigem validação técnica vigente.

### 3. Revisão visual de cada card

Observe a imagem ou arte fornecida e avalie:
- hierarquia visual e ponto focal;
- leitura do título, corpo, CTA e elementos de apoio;
- contraste entre texto e fundo;
- tamanho, densidade e área segura para leitura em tela pequena;
- alinhamento, margens, espaçamento e equilíbrio da composição;
- cortes, enquadramento, resolução e elementos encostados nas bordas;
- coerência entre imagem e mensagem;
- continuidade de estilo, iluminação, personagens e paleta entre os cards;
- naturalidade e qualidade da representação de pacientes e profissionais;
- erros de geração: anatomia, mãos, objetos, interfaces, letras falsas, duplicações, distorções ou artefatos;
- logotipos, ícones ou cores potencialmente incorretos quando comparados apenas ao material oficial fornecido.

#### Aderência à identidade visual (seção 9 do contexto)
- **Formato:** 1080×1440 (3:4) para feed; 1080×1920 para story e capa de Reels.
- **Grid:**
  - margens laterais de 80 px;
  - zona segura de 104 px nas laterais e 128 px no topo e na base;
  - texto ancorado na metade inferior quando o tipo de lâmina pede.
- **Paleta:**
  - só cores do manual;
  - verde-escuro dominante, off-white como respiro;
  - lima apenas em destaques (headline, número, CTA, card de citação);
  - gradiente-assinatura correto (#1D3635 → #2B887C → #DAEA96).
- **Tipografia:**
  - Basier Circle em toda a peça;
  - pesos coerentes: títulos SemiBold ou Medium, corpo Regular, ênfase em Bold;
  - nenhuma fonte de terceiros, exceto dentro de telas de produto.
- **Logo:**
  - versão e assinatura permitidas;
  - tamanho mínimo e contraste;
  - nenhuma das proibições do manual (efeito, distorção, contorno, rotação, transparência, cor fora da paleta).
- **Elementos gráficos:** forma facetada, grid de pontos, cards bento e raios usados conforme o manual.
- **Tipo de lâmina:** cada card segue com coerência um dos tipos documentados, e a sequência mantém a mesma família visual.
- **Fotografia:**
  - realista e bem iluminada, com cores neutras e toques de verde e azul;
  - sem sombras duras, cenário sucateado ou poses artificiais;
  - pessoas brasileiras diversas, com autonomia.
- **Identidade antiga:** nenhum resquício da identidade de 2025 (azul claro, logo "absens" minúsculo).

Não estime medidas ou contraste técnico com falsa precisão a partir de imagens comprimidas. Se a resolução ou o recorte impedir avaliar algo, informe essa limitação.

### 4. Revisão integrada — texto + imagem

Para cada card, verifique:
- se a imagem reforça a mensagem em vez de contradizê-la;
- se texto e imagem competem pelo mesmo espaço ou deixam áreas sem função;
- se a cena não induz uma interpretação factual ou clínica diferente do texto;
- se a sequência visual ajuda a leitura narrativa;
- se o CTA e a marca aparecem com destaque adequado, conforme as regras da seção 9 do contexto.

## Como conduzir

1. **Inventarie o material.** Registre quantos cards, quais formatos e se a revisão inclui roteiro, artes, legenda ou todos.
2. **Identifique a base de revisão.** Use o contexto da marca, briefing, fontes, manual e critérios fornecidos. Liste qualquer ausência que limite a conclusão.
3. **Leia a sequência inteira.** Entenda a promessa, o argumento, o desenvolvimento e o CTA antes de julgar cards isolados.
4. **Revise card por card.** Relacione observações visuais e textuais pelo número do card.
5. **Priorize correções.** Marque cada achado como:
   - `BLOQUEADOR` — erro factual, risco de saúde/privacidade, promessa sem suporte ou falha séria de leitura que impede publicar.
   - `IMPORTANTE` — enfraquece compreensão, narrativa, hierarquia ou consistência e deve ser corrigido antes da publicação.
   - `REFINAMENTO` — melhoria recomendada, mas não impede publicação.
6. **Conclua com status.** Use `NÃO PUBLICAR AINDA`, `PUBLICAR APÓS AJUSTES` ou `APROVADO NA REVISÃO COM O MATERIAL DISPONÍVEL`. O último status não significa aprovação jurídica, clínica, técnica ou institucional.
7. **Se houver correções solicitadas**, proponha o texto substituto ou a mudança visual exata. Não altere o significado aprovado.

## Saída padrão

### Parecer geral
- **Status:** [um dos três status]
- **Resumo:** [principal qualidade e principal risco]
- **Limites da revisão:** [ex.: baixa resolução; sem fonte para o dado; regra visual não coberta pelo manual]

### Achados prioritários
| Prioridade | Card/elemento | Achado | Por que importa | Correção recomendada |
|---|---|---|---|---|

### Revisão card por card
| Card | Texto | Imagem/layout | Relação texto-imagem | Ajuste sugerido |
|---|---|---|---|---|

### Texto revisado
Inclua somente quando o usuário pedir ou quando correções textuais forem necessárias. Preserve a mensagem e destaque pontos dependentes de validação.

### Checklist final
- [ ] Narrativa clara do primeiro ao último card
- [ ] Textos legíveis em tela pequena
- [ ] Imagens coerentes com as mensagens
- [ ] Fatos e funcionalidades com fonte ou validação
- [ ] Sem dados pessoais visíveis
- [ ] Representação respeitosa de pacientes e profissionais
- [ ] CTA claro e consistente
- [ ] Identidade visual conferida com a seção 9 do contexto (formato, grid, paleta, Basier Circle, logo, tipos de lâmina)
- [ ] Números conferidos com os dados vigentes do contexto (site em 05/10/2026 ou deck MIT 2026, sem misturar as fontes), sem valores de peças antigas sem validação

Marque cada item como `OK`, `AJUSTAR` ou `NÃO FOI POSSÍVEL VERIFICAR`.

## Se faltarem as artes

Se o usuário enviar apenas o roteiro, faça revisão textual, narrativa, factual e da direção visual descrita. Declare que não foi possível validar hierarquia, contraste, tipografia, composição ou artefatos de imagem sem ver as artes.

Se o usuário enviar imagens sem texto editável, revise o que estiver legível e sinalize limitações de resolução. Não deduza conteúdo ilegível.

---

## Anexo A — Contexto da marca

### Contexto da marca — Absens

> Base para criação de carrosséis. Versão de 05/10/2026.
> Fontes:
> - **Manual:** Figma "[Absens] Manual da Marca" (v01 © 2025)
> - **Peças:** Figma "[Absens] Social Media" (jan–set 2026)
> - **Site:** absens.com.br, consultado em 05/10/2026
> - **Deck MIT:** Figma "[Absens | MIT]", apresentação MIT Innovators Under 35, 2026
>
> Cada informação indica de onde veio. Itens com ⚠️ **Sem material** não têm fonte confirmada: não preencher com suposições.

#### 1. Identificação

- **Marca:** Absens
- **Categoria:** tecnologia aplicada à comunicação e à gestão em saúde.
- **Produto:** agentes de IA nativos no WhatsApp que acompanham a jornada do paciente do agendamento à consulta, para reduzir faltas e economizar recursos da saúde (site).
- **Quem está por trás:** o site apresenta a Absens como produto de Beyond, Emprel e Extreme Group.
- **Canais oficiais:**
  - Site: https://absens.com.br
  - Instagram: https://www.instagram.com/absens.ai/
  - LinkedIn: https://www.linkedin.com/company/absens
  - Contato: contato@absens.com.br · +55 81 3842-0654 (Recife)
- **Responsável por aprovar conteúdo:** ⚠️ Sem material.

##### Atenção: divergência de posicionamento
- **Manual:** plataforma de IA preditiva contra o absenteísmo em serviços públicos essenciais (saúde, educação, atendimento).
- **Site:** fala só de saúde, com foco em agentes de IA no WhatsApp.

Validar com a equipe qual enquadramento usar antes de campanhas que saiam da saúde.

#### 2. Conceito e mensagens de marca

- **Ideia-mãe:** **Ausência → Presença**. "Inteligência preditiva que garante presença onde antes havia vazio" (manual).
- **Tagline oficial:** "Garantindo presença com inteligência" (manual).
- **Headline atual do site:** "Agentes de IA a serviço da jornada do paciente."
- **Frases de apoio (manual):**
  - "Inteligência que transforma ausências em presenças"
  - "Menos ausência. Mais acesso. Mais impacto"
  - "Cada pessoa merece ser atendida quando precisa"
- **Origem:** Recife. Nas peças, o co-branding habitual é Beyond co., Emprel e Prefeitura do Recife.

#### 3. Proposta e funcionalidades comunicadas publicamente (site)

**A jornada do paciente no WhatsApp:**
1. O paciente agenda, reagenda ou cancela e recebe confirmação imediata.
2. Recebe lembretes automáticos personalizados.
3. Recebe instruções de preparo para exames.
4. Recebe campanhas de saúde, vacinação e mutirões dirigidas a grupos prioritários.
5. Se uma vaga é cancelada, ela é oferecida automaticamente a quem está na lista de espera.
6. Uma ligação automática por voz (Confirmation Call) pode confirmar a presença.

**Funcionalidades listadas:**
- Gestão de vagas e overbooking
- Registro das interações entre paciente e chatbot
- Agente de IA para lembretes
- Identificação e preenchimento de vagas ociosas em tempo real
- Disparo de campanhas em massa via WhatsApp
- Relatórios de absenteísmo
- Ligação por voz
- IA de previsão de faltas
- Dashboards de métricas e agendamentos
- Entende mensagens de áudio: transcreve e processa a mensagem do paciente

**Outros pontos declarados no FAQ do site:**
- Usa a API oficial do WhatsApp Business.
- Integra com qualquer sistema de agendamento, público ou privado, e a equipe da Absens faz a configuração técnica.
- Implantação básica em cerca de 30 dias, dependendo da complexidade da integração.
- O preço depende do volume mensal de interações e é definido em proposta personalizada. **Não citar preço.**

Confirme com a equipe que a funcionalidade está disponível para o público e o contexto do post. Não presuma disponibilidade universal.

#### 4. Provas e números

##### Números do site (05/10/2026)
- 20% de redução de absenteísmo
- 647 mil vagas recuperadas
- 4,8 milhões de agendamentos tratados
- 557 mil cidadãos impactados

O site não informa período nem metodologia. Citar como "dados divulgados pela Absens" e marcar `VALIDAR FONTE` quando a peça exigir precisão.

##### Clientes e parceiros (site)
- **Clientes:** Prefeitura do Recife, Prefeitura de Cajamar, Governo do Estado do Amazonas.
- **Parceiros e certificações:** WhatsApp AI Startups Hub, Google Partner.
- **Outros nomes em co-brandings das peças:** Google, Agile Trends, Estadão. Usar só com aprovação.

##### Segurança (site)
- Conformidade com a LGPD.
- Controles baseados em SOC 2 e ISO 27001.
- Criptografia AES-256 em trânsito e em repouso.
- Logs de auditoria.

Afirmações de segurança exigem aprovação da equipe antes de publicar.

##### Dados da apresentação MIT Innovators Under 35 (2026)
Fonte: Figma "[Absens | MIT]", https://www.figma.com/design/NQEaHw5aLQN9du8xgoHPnU

Estes dados vêm de um material oficial recente, mas usam outra base e outro período que os números do site. Ao usar, cite o recorte e não misture as duas fontes num mesmo dado.

**Impacto consolidado (casos Recife e Amazonas, 2022 a 2025):**
- +R$ 53,7 mi em recursos reaproveitados pela gestão pública
- +658 mil vagas reaproveitadas
- +12,6 milhões de interações com cidadãos
- 95,6% de precisão de previsão

**Case Recife (2022 a 2025):** de projeto-piloto a infraestrutura contínua da saúde municipal.
- +300 mil vagas recuperadas
- +R$ 21,2 mi economizados na saúde pública
- 83% de taxa de resposta às mensagens. Atenção: em peças antigas, esse número aparecia como "engajamento".
- 95,6% de precisão de previsão
- **Marcos:**
  - 2022: contrato público pelo 1º Ciclo de Inovação Aberta da Prefeitura do Recife;
  - 2023–2024: canal oficial com o paciente na regulação ambulatorial;
  - 2025: 2º lugar no Connected Smart Cities.

**Case Amazonas (12 meses, 2025):** assistente virtual oficial do SaúdeAM Digital.
- +355 mil vagas recuperadas
- +R$ 32,5 mi economizados
- +326 mil disparos de telessaúde
- +47 campanhas de mutirão
- +11,5 milhões de interações
- +1,1 milhão de agendamentos tratados
- +415 mil cadastros telefônicos atualizados

**Abrangência:** parcerias com secretarias municipais e estaduais de saúde em quatro estados (AM, PE, RJ, SP).

**Novo produto:** RegulAI, lançado em 2026 e voltado à regulação médica. São três agentes de IA:
- o primeiro acelera casos de alta confiabilidade;
- o segundo analisa casos remanescentes;
- o terceiro apoia a decisão do regulador, com justificativa rastreável.

Alega −50% no tempo de regulação, ainda em período de aprendizado do modelo (`VALIDAR` antes de usar).

**Reconhecimentos:**
- Prêmio Recife de Inovação (2023)
- Open Innovation 2025: entre as 100 ideias mais inovadoras da América Latina
- Connected Smart Cities 2025: 2º lugar em Soluções do Poder Público (Absens + Emprel)
- 6º Prêmio Conexão Inova (2026): 1º lugar em Inteligência Artificial e Tecnologias Emergentes

**Na imprensa:**
- Diário de Pernambuco (set/2025)
- Prefeitura do Recife (abr/2022 e set/2025)
- ASN — Agência Sebrae (mar/2025), que cita o Absens como case nacional de compras públicas de inovação
- Forbes Brasil Under 30 2025: Levi Nóbrega, CEO da Beyond
- Podcast 123 Brum (ep. 09)

**Chancelas técnicas:**
- Google Cloud Partner: infraestrutura em Google Cloud Platform
- WhatsApp AI Startups Hub: programa da Meta

**Atestado de capacidade técnica:** emitido pela Emprel em abril de 2025, para o período de 2022 a 2024.

**Dado externo sobre o problema:** 20–30% das consultas agendadas no SUS não são realizadas por faltas do paciente. Fonte citada no deck: Beltrame, S. M. et al. (2019), *Absenteísmo de usuários como fator de desperdício*. Ao usar, citar a fonte.

**Definição usada no deck:** solução de comunicação e inteligência em saúde pública, integrada aos sistemas de regulação de cada secretaria parceira, "sem substituir profissionais e sem exigir troca de software".

**Pessoa-chave:** Levi Nóbrega, CEO da Beyond, apresentador do deck. Contatos pessoais não devem ser repetidos sem pedido explícito.

##### Números de peças antigas sem fonte
Sempre `VALIDAR FONTE`:
- Economia de R$ 14,7 Mi, R$ 20 Mi ou R$ 58 Mi. O valor de R$ 53,7 mi tem fonte no deck MIT.

##### Divergência a observar
O site diz 647 mil vagas recuperadas; o deck MIT diz +658 mil vagas reaproveitadas. Bases e datas são diferentes. Não somar nem trocar um pelo outro.

##### Nunca usar como dado real
Os números das telas ilustrativas do site, por exemplo o dashboard de "Junho 2024" com 10.847 agendamentos.

#### 5. Públicos de referência

##### Público prioritário — instituições e equipes de saúde
- **Quem são:** organizações que gerenciam agendamentos de saúde. Os clientes exibidos são poder público municipal e estadual, e o FAQ cita sistemas públicos e privados (site).
- **O que precisam resolver:** reduzir faltas, recuperar vagas ociosas, economizar recursos, reduzir filas e liberar a equipe de tarefas manuais de comunicação (site).
- **Barreiras prováveis:** as dúvidas respondidas no FAQ do site: segurança dos dados, tempo de implantação, integração com o sistema atual e custo.
- ⚠️ **Sem material:** cargo ou perfil de quem decide a contratação. Validar segmentos e cargos antes de campanha segmentada.

##### Público secundário — pacientes e cidadãos
- Recebem as mensagens e podem confirmar, cancelar ou reagendar. O site destaca a acessibilidade por mensagens de áudio.
- Nas peças, aparecem como personagens: usuários do SUS do Recife, por exemplo "A rotina de Seu Roberto no SUS do Recife".
- Tratar cada pessoa com autonomia e respeito. Não presumir idade, condição de saúde, escolaridade, renda ou familiaridade digital.

#### 6. Objetivos e CTA

- ⚠️ **Sem material:** os objetivos de social media não estão documentados. Usar o objetivo informado no briefing.
- **CTA do site:** solicitar uma demonstração gratuita, por formulário ou mensagem.
- **CTAs já usados nas peças:** "Entenda como funciona, passo a passo →" e o chip "Garantir presença".
- Não inventar URL, telefone, oferta ou disponibilidade além do que está na seção 1.

#### 7. Tom de voz

**A marca deve soar:**
- Clara, humana, respeitosa e profissional.
- Direta, institucional mas humana (peças).
- Apoiada em prova: números grandes e histórias de pessoas reais.
- Próxima. O site fala em "IA humanizada" e "conversas naturais", e as mensagens do produto são cordiais, com emojis pontuais.
- Com orgulho da origem no Recife.

**A marca deve evitar:**
- Alarmismo, culpa, paternalismo e jargão sem explicação.
- Dizer ou insinuar que pacientes são culpados por faltas.
- Apresentar a IA como substituta de profissionais de saúde. A Absens é tecnologia de apoio à comunicação e à gestão.

**Regras de escrita:**
- Explicar termos técnicos como absenteísmo, overbooking e IA quando necessário.
- Frases curtas, uma ideia por card, leitura rápida em tela pequena.
- Português brasileiro.
- Negrito para destacar dados e nomes de prêmios (padrão das peças).

#### 8. Regras editoriais e factuais

- Não inventar métricas, resultados, clientes, depoimentos, estudos, certificações ou funcionalidades.
- Não transformar uma capacidade do produto em garantia de resultado. Exemplo: "implantação em até 30 dias" depende da integração.
- Citar fonte atual para números e afirmações factuais. Dados de uma implementação específica não representam automaticamente todos os clientes.
- Não oferecer diagnóstico nem aconselhamento médico individual.
- Não exibir dados pessoais, identificáveis ou plausíveis de pacientes em telas e mensagens.
- Afirmações sobre segurança, LGPD, certificações ou desempenho exigem fonte vigente e aprovação da equipe responsável.

#### 9. Identidade visual oficial (manual + peças)

##### Cores
| Papel | HEX |
|---|---|
| Verde-escuro: principal, fundos | #1D3635 |
| Verde: secundário | #1F685F |
| Lima: destaque em headlines, números e CTA | #DAEA96 |
| Cinza-azulado | #667D84 |
| Cinza-claro | #CFD3D2 |
| Off-white: fundo claro | #F0F1EE |
| Preto | #020202 |

- **Gradiente-assinatura:** #1D3635 → #2B887C → #DAEA96.
- **Fundo de frame atrás de card escuro:** #182F2E.
- **Proporção:** verde-escuro domina, off-white funciona como respiro e lima entra só como destaque (headline, número, botão, card de citação).

##### Tipografia
**Basier Circle** (Atipo Foundry) para tudo. O deck MIT também usa **Basier Circle Mono**, em caixa alta, para eyebrows, rótulos e rodapé.
- **Títulos:** SemiBold ou Medium, tracking de −1% a −2%, entrelinha de 108% a 113%.
- **Corpo:** Regular, entrelinha de 120% a 135%.
- **Ênfase:** Bold ou SemiBold.

##### Logo
- Wordmark "Absens", com A maiúsculo. O "A" tem uma janela em negativo que representa a lacuna que o sistema preenche.
- **Versão reduzida:** o "A" isolado.
- **Assinaturas:** só wordmark (preferencial), com tagline vertical ou com tagline horizontal.
- **Tamanho mínimo:** 2,5 cm / 94,5 px.
- **Aplicação:** off-white sobre #1D3635 ou #1F685F; #1D3635 sobre #F0F1EE ou #DAEA96.
- **Proibido:** efeitos, distorção, contorno, rotação, transparência, cores fora da paleta, fundo sem contraste e separar partes do símbolo.

##### Elementos gráficos
- Forma facetada com o gradiente-assinatura, sangrando pelo layout.
- Grid de pontos em verde ou lima.
- Cards arredondados estilo bento: card de número, card de citação em lima com texto escuro, chip "Garantir presença".
- Telas do produto como prova: dashboard e conversas no WhatsApp.
- **Raios:** botão 16 px; card inset 32 px; foto em card 70–80 px.

##### Fotografia
- Realista, bem iluminada.
- Brasileiros de perfis diversos em situações cotidianas: em casa e no transporte, usando o celular; em hospitais públicos, interagindo com profissionais em ambiente organizado.
- Cores neutras com toques sutis de verde e azul; tecnologia presente de forma natural.
- **Evitar:** sombras duras, cenário sucateado, poses artificiais.
- A equipe usa imagens geradas por IA no mesmo padrão.

##### Formatos e grid
- **Carrossel feed:** 1080×1440 (3:4), padrão atual. 1080×1350 para preview e corte de grid.
- **Story, Reels e capa de Reels:** 1080×1920.
- **Grid 1080×1440:**
  - margens laterais de 80 px;
  - zona segura de 104 px nas laterais e 128 px no topo e na base;
  - coluna de texto em x≈96–100, com cerca de 880 px de largura;
  - texto ancorado na metade inferior (y≈800–1330). Deixar área negativa na base das imagens.

##### Tipos de lâmina já usados
1. **Capa escura com foto:**
   - foto em sangria com gradiente #1D3635 de baixo para cima;
   - headline lima Medium 70 e apoio off-white Regular 42;
   - faixa inferior com co-brands e botão-seta lima.
2. **Capa clara com UI ou foto:** fundo off-white; bloco inferior #1F685F com headline lima e CTA.
3. **Foto + card lima:** foto em sangria com card #DAEA96 e texto #1D3635 em torno de 53 px.
4. **Editorial claro:**
   - fundo off-white, com foto em card r80 no topo;
   - eyebrow Medium Italic 32 #1F685F;
   - título Medium 52;
   - corpo 40.
5. **Passo a passo:** print de tela grande com card verde numerado (círculo lima).
6. **Fechamento/manifesto:**
   - card #1D3635 sobre #182F2E, com grid de pontos e forma facetada;
   - headline lima SemiBold 64;
   - corpo off-white Regular 42.
7. **Lâmina de assinatura:** fundo escuro com grid de pontos e lineup de logos.
8. **Glass card:** card translúcido sobre foto clara, com texto escuro Medium 36.

**Co-branding:** logos brancos em fundo escuro, separados por barra vertical.

##### Não usar como referência
A identidade antiga de 2025: azul claro, logo "absens" minúsculo, co-brand Google Cloud.

#### 10. Referências visuais fornecidas pela equipe

As imagens compartilhadas podem inspirar:
- Naturalidade e proximidade em interações de cuidado.
- Profissionais de saúde conversando ou atendendo pacientes.
- Pessoas usando celular em situações cotidianas.
- Representação de pessoas mais velhas com autonomia.
- Variação entre cenas de atendimento, retratos e ambientes externos.

Use as imagens como referências de representação, clima e enquadramento. Não replique automaticamente as mesmas pessoas ou composições.

**Evitar:**
- Estereótipos de idade, deficiência, classe social ou condição de saúde.
- Pacientes retratados como incapazes ou sem autonomia.
- Telas com dados pessoais ou texto que pareça informação real.
- Equipamentos, uniformes, logos ou ambientes que não correspondam à marca.

#### 11. Lacunas em aberto

- Responsável pela aprovação de conteúdo.
- Cargo ou perfil de quem decide a contratação.
- Objetivos de social media.
- Período e metodologia dos números do site.
- Validade dos valores de economia das peças antigas sem fonte (R$ 14,7 Mi, R$ 20 Mi, R$ 58 Mi).
- Enquadramento oficial: só saúde ou serviços públicos em geral.

#### 12. Fontes

- Absens — site oficial: https://absens.com.br/ (05/10/2026)
- Figma "[Absens] Manual da Marca": https://www.figma.com/design/PkPj6rmu1uB5fNARxMQPI1
- Figma "[Absens] Social Media": https://www.figma.com/design/7GelaKrWqZesDPOSfCJOAO
- Figma "[Absens | MIT]" (apresentação 2026): https://www.figma.com/design/NQEaHw5aLQN9du8xgoHPnU

---

<!-- ===================== SKILL: absens-apresentacoes ===================== -->

---
name: "absens-apresentacoes"
description: "Cria roteiro, estrutura e direção visual de apresentações (decks 16:9) do Absens a partir de um briefing, usando o sistema de slides do deck MIT 2026 e apenas fatos aprovados."
---

# Absens — apresentações

Use esta skill quando o pedido envolver criar, estruturar, adaptar ou revisar uma apresentação do Absens: prêmio, edital, banca, proposta para secretaria de saúde, evento, institucional ou investidor.

## Referências obrigatórias

1. o **Anexo A — Contexto da marca** (no fim deste arquivo): fatos de produto, números, cases, tom de voz e regras editoriais.
2. o **Anexo B — Sistema visual de apresentações** (no fim deste arquivo): formato, grid, tipografia, tokens de cor, componentes, os 19 tipos de slide (com node IDs de referência no Figma) e o arco narrativo do deck MIT.

Se o usuário enviar material mais recente (novo deck, números atualizados, briefing com dados), priorize esse material para a tarefa, sem alterar as referências salvas.

## Princípios

1. **Comece pela audiência e pela decisão.** Pergunte-se quem vai assistir e o que precisa decidir ou sentir ao final: premiar, contratar, investir, apoiar, conhecer. O deck inteiro serve a essa decisão.
2. **Títulos-tese.** Cada slide afirma algo. "A cada consulta perdida, uma vida continua na fila." vale mais do que "O problema". Uma ideia por slide.
3. **Prova antes de adjetivo.** Use cases, números, reconhecimentos e falas de terceiros do contexto. Todo número leva fonte e período. Se o dado não estiver no contexto ou no briefing, marque `VALIDAR FONTE` e prefira uma formulação sem número.
4. **Ritmo visual.** Alterne as três famílias de fundo (escuro facetado, claro, lima). Use o escuro para aberturas de capítulo e momentos de virada. Evite mais de três slides seguidos com a mesma estrutura.
5. **Use o sistema existente.** Monte cada slide a partir de um dos 19 tipos do catálogo. Se nenhum servir, descreva o novo layout com os mesmos tokens e componentes e marque `NOVO LAYOUT — VALIDAR`.
6. **Cuidados de saúde e privacidade.** Não dê orientação clínica. Não culpe pacientes. Não mostre dados pessoais em mockups. Não alegue segurança ou certificações sem fonte vigente. Apresente o Absens como apoio a profissionais e gestores, nunca como substituto.

## Fluxo

### 1. Interprete o briefing
Extraia:
- audiência e contexto (prêmio, edital, secretaria, investidor, evento);
- objetivo e decisão esperada;
- tempo de fala ou número de slides;
- mensagem central;
- provas disponíveis;
- apresentador, que define a capa, o perfil e o contato;
- CTA final;
- restrições.

Liste só as lacunas que mudam o deck e avance com suposições explícitas.

### 2. Escolha o arco narrativo
Proponha **dois ou três arcos** com lógicas diferentes, recomende um e desenvolva-o. Pontos de partida:

| Objetivo | Arco sugerido |
|---|---|
| Prêmio, edital, banca | Capa → quem apresenta → problema (dado) → solução → como funciona → cases → impacto consolidado → reconhecimentos e imprensa → maturidade → manifesto → contato. É o arco do MIT. |
| Proposta para secretaria/prefeitura | Capa → o desafio local (dado) → o que é → como funciona na rotina da secretaria → integração e implantação → case semelhante → números esperados (sem prometer) → segurança e conformidade (VALIDAR) → próximos passos → contato |
| Institucional curto (5–8 slides) | Capa → problema → o que é → como funciona → impacto → contato |
| Investidor / parceiro | Capa → problema e tamanho → solução → tração (cases, números) → abrangência → maturidade → novo produto/visão → time → contato |

Sem indicação de tamanho, proponha de 10 a 15 slides e diga que é ajustável.

### 3. Roteirize slide a slide
Para cada slide, entregue:
- **Tipo de slide**, pelo número e nome do catálogo, com o node de referência;
- **Fundo** (escuro, claro ou lima);
- **Eyebrow**, em caixa alta;
- **Título**;
- **Texto de apoio**: curto, no máximo 2 parágrafos;
- **Elementos:** números com legenda, cards, linha do tempo, mockup ou foto;
- **Direção de imagem:** cena, enquadramento e área livre para texto ou número, quando houver foto;
- **Fonte/validação** de cada afirmação factual;
- **Nota de fala** (opcional): 1–2 frases do que o apresentador diz e que não está no slide.

### 4. Montagem no Figma (quando solicitado)
- Duplique os frames de referência do arquivo MIT (`NQEaHw5aLQN9du8xgoHPnU`) pelos node IDs do catálogo e substitua os conteúdos. Use o componente Footer e o componente de logo existentes.
- Antes de usar as ferramentas de escrita do Figma, carregue a skill `figma-use`.
- Não altere o arquivo original do MIT. Trabalhe num arquivo ou página nova indicada pelo usuário.
- Fotos: gere uma opção por imagem, com o prompt refinado antes, e não insira texto, logos ou interfaces legíveis na imagem gerada.

### 5. Revisão final
Antes de entregar, confira:
- O deck responde à decisão da audiência?
- A capa e o fechamento conversam entre si?
- Todo slide tem título-tese e uma ideia só?
- Os números têm fonte e período? Números de fontes diferentes estão separados, sem misturar o site com o deck?
- As famílias de fundo alternam bem, e as viradas narrativas caem no fundo escuro?
- O rodapé traz o nome da apresentação e o logo nos slides de conteúdo?
- Há dados pessoais, promessas ou certificações sem validação?
- O CTA e os contatos vieram do briefing? Nunca inventar e-mail, telefone ou link.

## Formato de resposta

### Brief interpretado
- **Audiência e contexto:**
- **Decisão esperada:**
- **Mensagem central:**
- **Tamanho / tempo:**
- **Suposições e validações:**

### Arcos possíveis
1. **[Nome]:** lógica e por que serve.
2. **[Nome]:** lógica e por que serve.

**Recomendação:** [arco e justificativa]

### Roteiro
| # | Tipo (catálogo) | Fundo | Eyebrow | Título | Conteúdo e elementos | Fonte/validação |
|---|---|---|---|---|---|---|

### Direção de imagens
[Uma linha por foto ou mockup: cena, enquadramento, área livre.]

### Revisão
- **Pronto para montagem:** [sim ou pendências]
- **Validar antes de apresentar:** [lista curta]

---

## Anexo A — Contexto da marca

### Contexto da marca — Absens

> Base para criação de conteúdo. Versão de 05/10/2026.
> Fontes:
> - **Manual:** Figma "[Absens] Manual da Marca" (v01 © 2025)
> - **Peças:** Figma "[Absens] Social Media" (jan–set 2026)
> - **Site:** absens.com.br, consultado em 05/10/2026
> - **Deck MIT:** Figma "[Absens | MIT]", apresentação MIT Innovators Under 35, 2026
>
> Cada informação indica de onde veio. Itens com ⚠️ **Sem material** não têm fonte confirmada: não preencher com suposições.

#### 1. Identificação

- **Marca:** Absens
- **Categoria:** tecnologia aplicada à comunicação e à gestão em saúde.
- **Produto:** agentes de IA nativos no WhatsApp que acompanham a jornada do paciente do agendamento à consulta, para reduzir faltas e economizar recursos da saúde (site).
- **Quem está por trás:** o site apresenta a Absens como produto de Beyond, Emprel e Extreme Group.
- **Canais oficiais:**
  - Site: https://absens.com.br
  - Instagram: https://www.instagram.com/absens.ai/
  - LinkedIn: https://www.linkedin.com/company/absens
  - Contato: contato@absens.com.br · +55 81 3842-0654 (Recife)
- **Responsável por aprovar conteúdo:** ⚠️ Sem material.

##### Atenção: divergência de posicionamento
- **Manual:** plataforma de IA preditiva contra o absenteísmo em serviços públicos essenciais (saúde, educação, atendimento).
- **Site:** fala só de saúde, com foco em agentes de IA no WhatsApp.

Validar com a equipe qual enquadramento usar antes de campanhas que saiam da saúde.

#### 2. Conceito e mensagens de marca

- **Ideia-mãe:** **Ausência → Presença**. "Inteligência preditiva que garante presença onde antes havia vazio" (manual).
- **Tagline oficial:** "Garantindo presença com inteligência" (manual).
- **Headline atual do site:** "Agentes de IA a serviço da jornada do paciente."
- **Frases de apoio (manual):**
  - "Inteligência que transforma ausências em presenças"
  - "Menos ausência. Mais acesso. Mais impacto"
  - "Cada pessoa merece ser atendida quando precisa"
- **Origem:** Recife. Nas peças, o co-branding habitual é Beyond co., Emprel e Prefeitura do Recife.

#### 3. Proposta e funcionalidades comunicadas publicamente (site)

**A jornada do paciente no WhatsApp:**
1. O paciente agenda, reagenda ou cancela e recebe confirmação imediata.
2. Recebe lembretes automáticos personalizados.
3. Recebe instruções de preparo para exames.
4. Recebe campanhas de saúde, vacinação e mutirões dirigidas a grupos prioritários.
5. Se uma vaga é cancelada, ela é oferecida automaticamente a quem está na lista de espera.
6. Uma ligação automática por voz (Confirmation Call) pode confirmar a presença.

**Funcionalidades listadas:**
- Gestão de vagas e overbooking
- Registro das interações entre paciente e chatbot
- Agente de IA para lembretes
- Identificação e preenchimento de vagas ociosas em tempo real
- Disparo de campanhas em massa via WhatsApp
- Relatórios de absenteísmo
- Ligação por voz
- IA de previsão de faltas
- Dashboards de métricas e agendamentos
- Entende mensagens de áudio: transcreve e processa a mensagem do paciente

**Outros pontos declarados no FAQ do site:**
- Usa a API oficial do WhatsApp Business.
- Integra com qualquer sistema de agendamento, público ou privado, e a equipe da Absens faz a configuração técnica.
- Implantação básica em cerca de 30 dias, dependendo da complexidade da integração.
- O preço depende do volume mensal de interações e é definido em proposta personalizada. **Não citar preço.**

Confirme com a equipe que a funcionalidade está disponível para o público e o contexto do material. Não presuma disponibilidade universal.

#### 4. Provas e números

##### Números do site (05/10/2026)
- 20% de redução de absenteísmo
- 647 mil vagas recuperadas
- 4,8 milhões de agendamentos tratados
- 557 mil cidadãos impactados

O site não informa período nem metodologia. Citar como "dados divulgados pela Absens" e marcar `VALIDAR FONTE` quando o material exigir precisão.

##### Clientes e parceiros (site)
- **Clientes:** Prefeitura do Recife, Prefeitura de Cajamar, Governo do Estado do Amazonas.
- **Parceiros e certificações:** WhatsApp AI Startups Hub, Google Partner.
- **Outros nomes em co-brandings das peças:** Google, Agile Trends, Estadão. Usar só com aprovação.

##### Segurança (site)
- Conformidade com a LGPD.
- Controles baseados em SOC 2 e ISO 27001.
- Criptografia AES-256 em trânsito e em repouso.
- Logs de auditoria.

Afirmações de segurança exigem aprovação da equipe antes de publicar.

##### Dados da apresentação MIT Innovators Under 35 (2026)
Fonte: Figma "[Absens | MIT]", https://www.figma.com/design/NQEaHw5aLQN9du8xgoHPnU

Estes dados vêm de um material oficial recente, mas usam outra base e outro período que os números do site. Ao usar, cite o recorte e não misture as duas fontes num mesmo dado.

**Impacto consolidado (casos Recife e Amazonas, 2022 a 2025):**
- +R$ 53,7 mi em recursos reaproveitados pela gestão pública
- +658 mil vagas reaproveitadas
- +12,6 milhões de interações com cidadãos
- 95,6% de precisão de previsão

**Case Recife (2022 a 2025):** de projeto-piloto a infraestrutura contínua da saúde municipal.
- +300 mil vagas recuperadas
- +R$ 21,2 mi economizados na saúde pública
- 83% de taxa de resposta às mensagens. Atenção: em peças antigas, esse número aparecia como "engajamento".
- 95,6% de precisão de previsão
- **Marcos:**
  - 2022: contrato público pelo 1º Ciclo de Inovação Aberta da Prefeitura do Recife;
  - 2023–2024: canal oficial com o paciente na regulação ambulatorial;
  - 2025: 2º lugar no Connected Smart Cities.

**Case Amazonas (12 meses, 2025):** assistente virtual oficial do SaúdeAM Digital.
- +355 mil vagas recuperadas
- +R$ 32,5 mi economizados
- +326 mil disparos de telessaúde
- +47 campanhas de mutirão
- +11,5 milhões de interações
- +1,1 milhão de agendamentos tratados
- +415 mil cadastros telefônicos atualizados

**Abrangência:** parcerias com secretarias municipais e estaduais de saúde em quatro estados (AM, PE, RJ, SP).

**Novo produto:** RegulAI, lançado em 2026 e voltado à regulação médica. São três agentes de IA:
- o primeiro acelera casos de alta confiabilidade;
- o segundo analisa casos remanescentes;
- o terceiro apoia a decisão do regulador, com justificativa rastreável.

Alega −50% no tempo de regulação, ainda em período de aprendizado do modelo (`VALIDAR` antes de usar).

**Reconhecimentos:**
- Prêmio Recife de Inovação (2023)
- Open Innovation 2025: entre as 100 ideias mais inovadoras da América Latina
- Connected Smart Cities 2025: 2º lugar em Soluções do Poder Público (Absens + Emprel)
- 6º Prêmio Conexão Inova (2026): 1º lugar em Inteligência Artificial e Tecnologias Emergentes

**Na imprensa:**
- Diário de Pernambuco (set/2025)
- Prefeitura do Recife (abr/2022 e set/2025)
- ASN — Agência Sebrae (mar/2025), que cita o Absens como case nacional de compras públicas de inovação
- Forbes Brasil Under 30 2025: Levi Nóbrega, CEO da Beyond
- Podcast 123 Brum (ep. 09)

**Chancelas técnicas:**
- Google Cloud Partner: infraestrutura em Google Cloud Platform
- WhatsApp AI Startups Hub: programa da Meta

**Atestado de capacidade técnica:** emitido pela Emprel em abril de 2025, para o período de 2022 a 2024.

**Dado externo sobre o problema:** 20–30% das consultas agendadas no SUS não são realizadas por faltas do paciente. Fonte citada no deck: Beltrame, S. M. et al. (2019), *Absenteísmo de usuários como fator de desperdício*. Ao usar, citar a fonte.

**Definição usada no deck:** solução de comunicação e inteligência em saúde pública, integrada aos sistemas de regulação de cada secretaria parceira, "sem substituir profissionais e sem exigir troca de software".

**Pessoa-chave:** Levi Nóbrega, CEO da Beyond, apresentador do deck. Contatos pessoais não devem ser repetidos sem pedido explícito.

##### Números de peças antigas sem fonte
Sempre `VALIDAR FONTE`:
- Economia de R$ 14,7 Mi, R$ 20 Mi ou R$ 58 Mi. O valor de R$ 53,7 mi tem fonte no deck MIT.

##### Divergência a observar
O site diz 647 mil vagas recuperadas; o deck MIT diz +658 mil vagas reaproveitadas. Bases e datas são diferentes. Não somar nem trocar um pelo outro.

##### Nunca usar como dado real
Os números das telas ilustrativas do site, por exemplo o dashboard de "Junho 2024" com 10.847 agendamentos.

#### 5. Públicos de referência

##### Público prioritário — instituições e equipes de saúde
- **Quem são:** organizações que gerenciam agendamentos de saúde. Os clientes exibidos são poder público municipal e estadual, e o FAQ cita sistemas públicos e privados (site).
- **O que precisam resolver:** reduzir faltas, recuperar vagas ociosas, economizar recursos, reduzir filas e liberar a equipe de tarefas manuais de comunicação (site).
- **Barreiras prováveis:** as dúvidas respondidas no FAQ do site: segurança dos dados, tempo de implantação, integração com o sistema atual e custo.
- ⚠️ **Sem material:** cargo ou perfil de quem decide a contratação. Validar segmentos e cargos antes de material segmentado.

##### Público secundário — pacientes e cidadãos
- Recebem as mensagens e podem confirmar, cancelar ou reagendar. O site destaca a acessibilidade por mensagens de áudio.
- Nas peças, aparecem como personagens: usuários do SUS do Recife, por exemplo "A rotina de Seu Roberto no SUS do Recife".
- Tratar cada pessoa com autonomia e respeito. Não presumir idade, condição de saúde, escolaridade, renda ou familiaridade digital.

#### 6. Objetivos e CTA

- ⚠️ **Sem material:** os objetivos de comunicação não estão documentados. Usar o objetivo informado no briefing.
- **CTA do site:** solicitar uma demonstração gratuita, por formulário ou mensagem.
- Não inventar URL, telefone, oferta ou disponibilidade além do que está na seção 1 ou no briefing.

#### 7. Tom de voz

**A marca deve soar:**
- Clara, humana, respeitosa e profissional.
- Direta, institucional mas humana.
- Apoiada em prova: números grandes e histórias de pessoas reais.
- Próxima. O site fala em "IA humanizada" e "conversas naturais".
- Com orgulho da origem no Recife.

**A marca deve evitar:**
- Alarmismo, culpa, paternalismo e jargão sem explicação.
- Dizer ou insinuar que pacientes são culpados por faltas.
- Apresentar a IA como substituta de profissionais de saúde. A Absens é tecnologia de apoio à comunicação e à gestão.

#### 8. Regras editoriais e factuais

- Não inventar métricas, resultados, clientes, depoimentos, estudos, certificações ou funcionalidades.
- Não transformar uma capacidade do produto em garantia de resultado. Exemplo: "implantação em até 30 dias" depende da integração.
- Citar fonte atual para números e afirmações factuais. Dados de uma implementação específica não representam automaticamente todos os clientes.
- Não oferecer diagnóstico nem aconselhamento médico individual.
- Não exibir dados pessoais, identificáveis ou plausíveis de pacientes em telas e mensagens.
- Afirmações sobre segurança, LGPD, certificações ou desempenho exigem fonte vigente e aprovação da equipe responsável.

#### 9. Identidade da marca (manual)

- **Cores do manual:** verde-escuro #1D3635, verde #1F685F, lima #DAEA96, cinza-azulado #667D84, cinza-claro #CFD3D2, off-white #F0F1EE, preto #020202. Gradiente-assinatura: #1D3635 → #2B887C → #DAEA96. Em apresentações, seguir os tokens do Anexo B.
- **Tipografia:** Basier Circle (Atipo Foundry); Basier Circle Mono em caixa alta para eyebrows, rótulos e rodapé.
- **Logo:** wordmark "Absens", com A maiúsculo. Aplicação em off-white sobre #1D3635 ou #1F685F, ou #1D3635 sobre fundos claros e lima. Proibido: efeitos, distorção, contorno, rotação, transparência, cores fora da paleta, fundo sem contraste e separar partes do símbolo.
- **Fotografia:** realista e bem iluminada; brasileiros diversos em situações cotidianas e de atendimento; cores neutras com toques de verde e azul; sem sombras duras, cenário sucateado ou poses artificiais.
- **Não usar:** a identidade antiga de 2025 (azul claro, logo "absens" minúsculo).

#### 10. Lacunas em aberto

- Responsável pela aprovação de conteúdo.
- Cargo ou perfil de quem decide a contratação.
- Período e metodologia dos números do site.
- Validade dos valores de economia das peças antigas sem fonte (R$ 14,7 Mi, R$ 20 Mi, R$ 58 Mi).
- Enquadramento oficial: só saúde ou serviços públicos em geral.

#### 11. Fontes

- Absens — site oficial: https://absens.com.br/ (05/10/2026)
- Figma "[Absens] Manual da Marca": https://www.figma.com/design/PkPj6rmu1uB5fNARxMQPI1
- Figma "[Absens] Social Media": https://www.figma.com/design/7GelaKrWqZesDPOSfCJOAO
- Figma "[Absens | MIT]" (apresentação 2026): https://www.figma.com/design/NQEaHw5aLQN9du8xgoHPnU

---

## Anexo B — Sistema visual de apresentações

### Sistema visual de apresentações — Absens

> Fonte: Figma "[Absens | MIT]", página "Apresentação"
> https://www.figma.com/design/NQEaHw5aLQN9du8xgoHPnU (node 141:177)
> Deck feito para o MIT Innovators Under 35 · Brasil · 2026, analisado em 05/10/2026.

#### 1. Formato e grid

- **Formato:** 1920×1080 (16:9).
- **Margens:** 48 px nas laterais, no topo e na base.
- **Eyebrow** (rótulo de seção): no topo à esquerda, em x48 y48.
- **Título principal:** começa em y≈200 nos slides de conteúdo.
- **Coluna de texto:** cerca de 590 px de largura quando o slide tem imagem à direita, e até cerca de 1100 px quando o texto ocupa a largura.
- **Bloco direito** (imagem, mockup, cards): começa em x≈820. A imagem fica em card arredondado com margem de 48 px, ou sangra pela metade direita do slide.
- **Rodapé** (componente "Footer", em y≈1012, largura de 1824 px):
  - à esquerda, o nome da apresentação em Basier Circle Mono 14, caixa alta, cor neutrals/200 (no MIT: "TECNOLOGIA A SERVIÇO DO SUS");
  - à direita, o logo Absens com 104×24 px.

  Aparece em todos os slides de conteúdo. Capa, aberturas de capítulo e aberturas de case não têm rodapé.

#### 2. Tipografia (tokens do arquivo)

- **Basier Circle:** títulos e textos.
- **Basier Circle Mono:** eyebrows, rótulos, datas e metadados, sempre em caixa alta.

| Token | Uso | Especificação |
|---|---|---|
| Display/80 | Título de slide com mais impacto (ex.: case detalhado) | SemiBold 80 / 88, tracking −3 |
| Display/72 | Título padrão de slide de conteúdo | SemiBold 72 / 79, tracking −3 |
| Heading/H3 | Subtítulo grande em slides escuros | SemiBold 56 / 62, tracking −3 |
| Heading/H5 | Valor de estatística, título de bloco | SemiBold 40 / 48, tracking −3 |
| Heading/H8 | Título de card | Medium 24 / 29, tracking −2 |
| Text/24/Regular | Texto de apoio principal | Regular 24 / 34, tracking −2 |
| Text/18/Regular | Corpo de card, legenda de número | Regular 18 / 25, tracking −2 |
| Text/16/Medium | Rótulos menores | Medium 16 / 22, tracking −1,5 |
| Mono 20 | Eyebrow | Basier Circle Mono Regular 20, caixa alta |
| Mono 14 | Rodapé | Basier Circle Mono Regular 14, caixa alta |

**Capa e aberturas de capítulo:**
- O título é o maior do deck, acima do Display/80.
- O subtítulo usa cerca de 40 px (font-size/6 40/48).
- Ao replicar, conferir o tamanho exato no frame de referência.

#### 3. Cores (tokens do arquivo)

| Token | HEX | Uso no deck |
|---|---|---|
| primary/500 | #1D3635 | Fundo escuro, texto escuro sobre lima |
| secondary/600 | #184F47 | Verde profundo: números de destaque, marcadores da linha do tempo, área do mapa |
| secondary/400 | #299182 | Eyebrow em fundo claro, ano em cards, área do mapa |
| terciary/500 | #DAEA96 | Lima: eyebrow e subtítulo em fundo escuro, número hero, botão, chips |
| neutrals/50 | #F0F1EE | Fundo claro, texto claro sobre escuro |
| neutrals/100 | #D3E0E3 | Áreas neutras (mapa) |
| neutrals/200 | #B6C8CD | Rodapé |
| neutrals/300 | #99B0B7 | Eyebrow neutro em fundo claro |
| neutrals/400 | #7E989F | Texto secundário, trechos de citação |
| neutrals/600 | #4F5C60 | Corpo de texto em fundo claro |
| neutrals/900 | #020202 | Títulos em fundo claro |

**Atenção:** a escala de neutros do deck (#D3E0E3 a #4F5C60) é a usada no sistema de apresentação. O manual de marca lista outros cinzas (#667D84, #CFD3D2). Em apresentações, seguir os tokens do deck.

##### Três famílias de fundo
1. **Escuro facetado:** #1D3635 com a forma facetada em gradiente verde (Gradient 01) atravessando o slide na diagonal. Usado em capa, aberturas de capítulo e de case, impacto consolidado e encerramento.
2. **Claro:** off-white #F0F1EE liso, às vezes com um véu lima muito suave. Usado em slides de conteúdo com foto, mapa e imprensa.
3. **Lima:** gradiente de lima claro para off-white, de cima para baixo ou radial. Usado em "como funciona", reconhecimentos, maturidade e na metade superior dos cases.

Para ritmo, alternar as famílias ao longo do deck. Os momentos de virada narrativa usam o escuro.

#### 4. Componentes recorrentes

- **Eyebrow:** Mono 20, caixa alta. Lima em fundo escuro; #299182 ou neutrals/300 em fundo claro. Nomeia a seção (ex.: "CAPÍTULO I", "COMO FUNCIONA", "CASE RECIFE · 2022 A 2025").
- **Card branco:** fundo branco, raio de cerca de 16 px, padding de 24 px, sem sombra aparente. Contém eyebrow/meta em Mono, título H8 e corpo 18.
- **Card de estatística:** valor em H5 SemiBold (#184F47 em fundo claro, lima em fundo escuro) com legenda curta de 18 px abaixo. Aparece em linha de 3 ou 4.
- **Número hero:** valor enorme em lima sobre fundo escuro, com frase de contexto acima e abaixo (slide de impacto).
- **Linha do tempo:** linha horizontal fina com círculos #184F47 de 31 px. Cada marco tem rótulo Mono, título H8 e descrição 16–18.
- **Chip/selo:** pílula lima com ícone e texto Mono em verde (ex.: "RECIFE · PE", "NACIONAL").
- **Botão:** pílula lima com texto #1D3635 (ex.: "Acesse a carta aqui").
- **Foto em card:** raio de cerca de 16 px, ocupando a metade direita. Pode receber texto ou número sobreposto em área limpa da imagem.
- **Mockups:** celular com conversa de WhatsApp ou chamada; notebook com a UI do produto.
- **Logo:** Absens em off-white no canto inferior (direito na capa, esquerdo nas aberturas de capítulo).

#### 5. Catálogo de tipos de slide

Os node IDs apontam para o frame de referência no arquivo do MIT. Use-os para duplicar o layout no Figma.

| # | Tipo | Fundo | Estrutura | Referência |
|---|---|---|---|---|
| 1 | Capa | Escuro facetado | Eyebrow do evento (Mono, lima); título grande em duas linhas; subtítulo de 2 linhas; rodapé com apresentador e categoria em Mono; logo à direita | 141:178 |
| 2 | Perfil de pessoa | Claro | Foto em card à esquerda (cerca de 40% da largura); à direita, eyebrow, nome em Display, cargo, bio em dois níveis e 2 cards de destaque em lima claro | 141:190 |
| 3 | Sobre a empresa | Claro + lima (split) | Esquerda: eyebrow, título Display, texto. Direita lima: 3 cards verdes altos com textura (grid, faceta, pontos) e 3 cards de número abaixo | 141:207 |
| 4 | Abertura de capítulo | Escuro facetado | Eyebrow "CAPÍTULO N"; título grande no meio; pergunta ou subtítulo em lima; logo no canto inferior esquerdo | 141:1064, 141:1083, 141:1406 |
| 5 | Problema com dado | Claro | Esquerda: título-tese e 2 parágrafos curtos. Direita: foto em card com estatística grande sobreposta e fonte em letra pequena | 141:1071 |
| 6 | O que é o produto | Claro | Esquerda: título e definição. Direita: foto em card com lista de 4 atributos sobreposta, separados por linhas finas | 141:1090 |
| 7 | Como funciona | Lima | Título no centro; dois mockups de celular nas laterais; duas colunas curtas explicando cada fluxo | 141:1106 |
| 8 | Novo produto / UI | Claro | Nome do produto grande; texto à direita; 3 cards de agentes ou etapas; notebook com a UI; card de número lima sobreposto | 141:1448 |
| 9 | Abertura de case | Escuro facetado | Ano gigante translúcido no topo; rótulo "CASE" em lima; nome do lugar centralizado; frase-resumo no canto inferior direito | 141:1115, 141:1161 |
| 10 | Case detalhado | Lima em cima, claro embaixo | Eyebrow, título Display/80, linha com 4 números, foto em card à direita; embaixo, linha do tempo com 3 marcos | 141:1121, 141:1167 |
| 11 | Abrangência / mapa | Claro | Título-tese em duas frases curtas; legenda com siglas; mapa do Brasil com os estados em verdes da paleta | 141:1207 |
| 12 | Impacto consolidado | Escuro com gradiente verde | Frase de entrada; número hero lima enorme; frase de contexto; coluna de 3 cards de número | 141:1255 |
| 13 | Reconhecimentos | Lima | Título; 4 cards brancos com ano (#299182), nome do prêmio, descrição e chip de abrangência | 141:1270 |
| 14 | Chancelas / parceiros | Lima claro | Título; 2 cards largos com logo do parceiro, categoria em Mono, nome e explicação | 141:1316 |
| 15 | Na imprensa | Claro | Título; grade 3×2 de cards: veículo e data em Mono, manchete, trecho curto entre aspas | 141:1334 |
| 16 | Pilares numerados | Lima | Título; 4 cards com número grande (01–04) em #299182, título e descrição | 141:1380 |
| 17 | Documento como prova | Escuro→claro | Eyebrow, título, botão lima para o documento; documento em destaque à direita | 141:1411 |
| 18 | Manifesto | Foto em sangria dentro de card | Foto ocupando quase todo o slide; eyebrow, frase forte centralizada em off-white e frase de apoio | 141:1421 |
| 19 | Encerramento / contato | Escuro facetado | Frase de fechamento no topo; foto do apresentador em card com nome e cargo; 3 colunas de contato | 141:1427 |

#### 6. Arco narrativo do deck MIT (referência)

Ordem usada no deck de 23 slides:
1. Capa
2. Quem apresenta
3. Empresa
4. Capítulo I: o problema
5. Dado do problema
6. Capítulo II
7. O que é
8. Como funciona
9. Próximo passo (novo produto)
10. Case Recife: abertura e detalhe
11. Case Amazonas: abertura e detalhe
12. Abrangência
13. Impacto consolidado
14. Reconhecimentos
15. Chancelas
16. Imprensa
17. Maturidade
18. Capítulo
19. Carta de recomendação
20. Manifesto
21. Encerramento

Em resumo: **problema → solução → prova (cases, números, terceiros) → legitimidade → propósito → contato**. É uma boa base para decks de prêmio, edital ou banca. Para outros objetivos, adapte a ordem (ver o fluxo no início deste arquivo).

#### 7. Padrões de escrita observados

- **Títulos-tese**, não rótulos. "A cada consulta perdida, uma vida continua na fila." é melhor que "O problema".
- **Uma ideia por slide.** Corpo com 2 parágrafos curtos, no máximo.
- **Números com legenda curta** de até 5 palavras ("vagas recuperadas", "precisão de previsão").
- **Dado externo com fonte visível no próprio slide**, em letra pequena (ex.: "Fonte: Cf. Beltrame, S. M. et al. (2019)").
- **Eyebrow situa o leitor:** seção, case e período (ex.: "CASE RECIFE · 2022 A 2025").
- **Tom:** institucional e humano. O produto é apresentado como apoio, "sem substituir profissionais".

#### 8. Imagens

- **Fotos realistas,** luz natural e suave. Pacientes brasileiros diversos (idosos, mães com bebê, mulheres negras) em casa, no transporte ou em atendimento com profissional de saúde.
- **Paleta:** neutra, com toques de verde (cadeiras, roupas, ambiente) que conversam com a marca.
- **Geração por IA:** o deck usa imagens geradas por IA. Seguir o mesmo padrão e revisar mãos, celulares e textos falsos.
- **Composição:** deixar área limpa onde entrará estatística ou texto sobreposto (ex.: parede lisa atrás das pessoas no slide do problema).
- **Mockups de produto:** usar telas reais ou plausíveis sem dados pessoais legíveis. Evitar nomes, CPF e telefones reais.