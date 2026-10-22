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