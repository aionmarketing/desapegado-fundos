# DSPGD — laboratório de fundos

Atualizado em 04/11/2026. Objetivo: definir os fundos de quatro áreas da mesma ilha, com realismo fotográfico, materiais naturais e acabamento coerente, preservando a identidade de cada cenário atrás da interface. Mobile é prioritário.

## Escopo recebido

| Área | Direção inicial, aberta a refinamento |
| --- | --- |
| Beach | Praia tropical, oceano e coqueiros/palmeiras claramente visíveis; roupas de calor. |
| Trail | Mata, árvores e vegetação com caminho legível e profundidade. |
| Trekking | Montanha e altitude; definir neve, gelo e vegetação com o dono, sem presumir congelamento total. |
| Collections | Caverna longa e profunda, câmera perto da entrada, percurso central e muitos nichos naturais com caixas de tênis menores à distância. Caixas são cenografia. |

Laboratório separado. A aplicação antiga é somente referência de leitura; cadastro/addclothes, banco, autenticação, estoque e pagamentos estão fora do escopo. Nenhuma direção visual final foi aprovada neste chat.

## Entrega de cada rodada visual

| Janela de referência | Fundo limpo | Mesmo fundo na página |
| --- | --- | --- |
| Mobile: 390 × 844 | Sem UI, textos ou produtos sobrepostos | Navegação, busca/filtros e cards com fotos reais |
| Desktop: 1440 × 900 | Sem UI, textos ou produtos sobrepostos | Navegação, busca/filtros e cards com fotos reais |

Quatro imagens por rodada, sem distorcer assets; em página longa, incluir também recorte do catálogo. Reutilizar o fundo de cada formato na respectiva composição. Produtos separados, inteiros e fiéis às fotos; preços ocultos. Vidro transparente/fumê, bordas sutis, marfim e champanhe discreto; evitar blur global e opacidade que apaguem o cenário. Caixas de Collections permanecem no fundo limpo.

Preferir prévia real em HTML/CSS/React com assets separados e capturas do navegador. Se houver apenas mockup, identificar como **montagem conceitual**. O kit contém somente o print dos produtos, sem fotos privadas avulsas: confirmar acesso às fotos reais antes da composição; pedir material essencial se faltar.

## Referências conferidas

Lidos `brief-fundos/PROMPT-NOVO-CHAT.md`, `LEIA-ME.md` e `manifest.json`; vistas as oito imagens de `brief-fundos/referencias/`. Tamanhos e SHA-256 conferem com o manifesto. São referências datadas, não aprovação final.

Beach mostra coqueiros, costa rochosa e oceano; Trail, mata verde e trilha em profundidade; Trekking, montanhas nevadas sobre água (fotografia-base, sem os efeitos de nuvens da aplicação); Collections, túnel com nichos, caixas e luz superior. `interface-collections.png` orienta hierarquia, vidro e composição dos cards; sua intensidade de blur não é uma decisão aprovada para os novos estudos.

## Decisões em aberto

- Primeira área a desenvolver.
- O que manter ou mudar na referência escolhida: câmera, profundidade, elementos, luz e cores.
- Em Trekking, proporção de neve, gelo, rocha e vegetação.
- Fonte/licença dos fundos futuros e seleção/acesso às fotos reais dos produtos.
- Ambiente de execução visual e posterior disponibilidade de Codex Cloud.

## Execução e organização

Este chat foi criado **localmente**. Conforme o repasse de 04/11/2026, a consulta do aplicativo não retornou ambiente Codex Cloud acessível; não houve nova consulta neste início. A preferência por nuvem permanece registrada para quando houver ambiente publicado. Nesta abertura: somente inspeção e organização, sem instalação, render pesado, geração de assets, deploy ou contratação.

Referências originais do kit ficam preservadas em `brief-fundos/referencias/`; `originais/`, `fundos/` e `previas/` ficam reservadas para o trabalho futuro. Registrar opções e feedback em `VERSOES.md`, preservar versões anteriores e registrar a origem dos assets. Após duas rodadas sem avanço, rever a abordagem.

Antes de consultar a implementação antiga, ler seu `AGENTS.md`, `docs/START-HERE.md`, `docs/agent-core/STATUS.json` e `TASKS.json`. Não duplicar esse estado nem presumir processos históricos disponíveis. Não publicar fotos ou máscaras privadas.
