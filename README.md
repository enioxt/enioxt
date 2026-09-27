# Enio Rocha · investigador e arquiteto de sistemas de IA 👋

Construo infraestrutura para agentes de IA que **provam o que afirmam** e sabem o que **não** podem fazer — em domínios onde erro, segurança e rastreabilidade importam.

Ponto de partida: investigação policial. A tecnologia veio depois, para resolver problemas que eu conhecia por dentro. Isso virou método, o método virou framework, e o framework virou uma federação que roda todo dia.

> **Este é o mapa geral.** Todos os meus repositórios públicos apontam para cá; daqui você chega a tudo.

---

## O todo, em duas camadas

| Camada | O que é | Onde |
|---|---|---|
| **CINCO** | O ecossistema mais amplo — o convite, o universo, a federação de pessoas | [cinco.ia.br](https://cinco.ia.br) |
| **EGOS** | O framework/federação de IA governada que me representa dentro dele — agentes, regras, skills, memória, provas | [egos.ia.br](https://egos.ia.br) |

A premissa é simples: agente útil precisa de regras claras, proveniência (de onde veio cada informação), decisão humana nas partes sensíveis e fronteiras que não se cruzam em silêncio. Não é plataforma. É arquitetura — em público, em português, com código que você pode auditar.


---

## Como eu opero — antes do catálogo

Antes de listar ferramentas, vale dizer **como eu chego nelas**. Não trato isso como teste de personalidade
nem como identidade fixa; são modos de trabalho que aparecem repetidamente na investigação, no código,
na pesquisa e nas decisões do EGOS:

| Modo | O que faço quando ele está forte | O contrapeso que construí no sistema |
|---|---|---|
| **Investigar** | desmonto o problema, procuro contradições, fonte, cadeia de evidência e o que não fecha | prova, proveniência, REAL/CONCEPT/PHANTOM e critérios de aceite |
| **Executar** | transformo entendimento em experimento, sistema, oferta ou próximo passo concreto | HITL, limites de autonomia, gates e revisão antes do irreversível |
| **Explorar** | conecto áreas distantes, testo ferramentas e abro hipóteses que ainda não estavam formuladas | `/discover`, teto de frentes e separação entre ideia, protótipo e capacidade real |
| **Integrar** | volto às pessoas: autonomia, privacidade, compreensão, impacto e possibilidade de saída | Humano Soberano, Dado Soberano, local-first e falha visível |

O ciclo que mais se repete é **explorar → investigar → executar → integrar**. O EGOS nasceu, em parte,
para amplificar as forças desse ciclo e colocar freios onde elas podem exagerar: exploração sem corte vira
dispersão; investigação sem exposição vira construção infinita; execução sem prova vira pressa; integração
sem decisão vira adiamento.

Por isso, o que aparece abaixo é organizado por **capacidades demonstráveis**, não por uma pilha de
repositórios. O GitHub é a fonte de prova; o **Cinco é a camada que condensa a história**.

---

## Comece por aqui — três portas

1. **[O kit aberto (MIT)](https://cinco.ia.br/kit/)** — cinco motores testados (fila de agentes, painel vivo, vigia, porta de entrada, crônica). Feito para **colar inteiro na sua inteligência artificial** (Claude Code, Cursor, o que você já usa) e pedir para ela rodar. Tudo local, na sua máquina.
2. **[cinco.ia.br](https://cinco.ia.br)** — o convite completo: o céu do ecossistema com o status real de cada peça, a constituição em cinco regras, e a entrada da federação em [/entrar](https://cinco.ia.br/entrar) (login GitHub + aceite).
3. **Conversa direta** — [egos.ia.br](https://egos.ia.br) tem o botão de WhatsApp; o diagnóstico vem antes de qualquer promessa.

**O princípio que rege tudo isso:** o que se compartilha aqui é livre para forkar — *no universo que nasce na tua máquina, o sol és tu*. Ser convidado é um caminho; fundar o seu é outro, igualmente bem-vindo. Adotar cada regra é escolha sua, regra a regra — a constituição viaja como oferta, nunca como imposição.

---

## Capacidades públicas — o GitHub pelo que ele prova

Esta não é uma lista completa do que sei fazer. É a **projeção pública do que já tem evidência
inspecionável**. Um mesmo repositório pode provar mais de uma capacidade; uma capacidade pode ser
formada por vários repositórios. O índice interno continua sendo o registry do EGOS — aqui entra só o
recorte que faz sentido mostrar ao mundo.

| Capacidade | O que está sendo demonstrado | Evidências públicas |
|---|---|---|
| **Governança de IA e agentes auditáveis** | regras que viram gates, evidência antes de afirmação, HITL, SSOT e prevenção de drift | [`egos-governance-skill`](https://github.com/enioxt/egos-governance-skill) · [`egos-governance`](https://github.com/enioxt/egos-governance) (registro histórico) · [`BLUEPRINT-EGOS`](https://github.com/enioxt/BLUEPRINT-EGOS) |
| **Privacidade e segurança de dados brasileiros** | masking de PII/LGPD e desenho de superfícies em que o motor pode viajar sem o dado real | [`guard-brasil`](https://github.com/enioxt/guard-brasil) |
| **Investigação e sistemas orientados a evidência** | transformar fontes, relações e sinais em estruturas auditáveis, sem confundir hipótese com fato | [`hackathon-dados-publicos`](https://github.com/enioxt/hackathon-dados-publicos) · governança/proveniência nos projetos acima |
| **Descoberta técnica e curadoria** | procurar projetos emergentes, comparar sinais e transformar pesquisa dispersa em radar reutilizável | [`gem-hunter`](https://github.com/enioxt/gem-hunter) · [`gem-hunter-skill`](https://github.com/enioxt/gem-hunter-skill) · [`awesome-gems`](https://github.com/enioxt/awesome-gems) |
| **Sistemas pessoais local-first** | usar IA sobre informação própria preservando controle local e fronteiras explícitas | [`egos-cortex`](https://github.com/enioxt/egos-cortex) |
| **Experimentos humanos e culturais com software** | usar tecnologia também como meio de experiência, curadoria e presença — não só como automação empresarial | [`radio-philein`](https://github.com/enioxt/radio-philein) · [rádio ao vivo](https://cinco.ia.br/radio/) |
**E o resto?** Boa parte do trabalho vive em repositórios privados — clientes, investigação, dados sob sigilo. A regra é a 4ª do framework: **o motor viaja; o dado real, nunca.** O que pode ser aberto, abre; a fronteira é declarada, não escondida.

---

## Acompanhe

- 🌐 **Sites:** [egos.ia.br](https://egos.ia.br) · [cinco.ia.br](https://cinco.ia.br) · [Mission Control público](https://lab.egos.ia.br/monitor-publico)
- 💬 **Grupo Telegram:** [t.me/+z0qkXDu68N42NDcx](https://t.me/+z0qkXDu68N42NDcx)

Filosofia de trabalho: *Simplicity First* — o mínimo que resolve, falha visível, sem caixa-preta; e **verdade provada**: afirmação sem prova não sobe.

<sub>EGOS Framework · atualizado em 31 de agosto de 2026</sub>
