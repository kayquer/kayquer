# Kayque 👋

Escrevo código desde 2002, quando tinha 11 anos, e trabalho com isso desde 2013. Sou **Gerente de Tecnologia da Informação** na ImobiBrasil desde 2018. Lá cuido do CRM imobiliário de ponta a ponta: backend em PHP e MySQL, app em Flutter e a infraestrutura.

Fora do trabalho, escrevo skills para o Claude Code que revisam texto em português e conferem citações ABNT, faço um jogo educativo sobre água no mestrado e publico packs de modelos 3D low poly gratuitos no [itch.io](https://kkyqr.itch.io).

## Projetos

### 🧊 [Assets 3D low poly no itch.io](https://kkyqr.itch.io)

<a href="https://kkyqr.itch.io"><img src="./assets/readme/itch-kkyqr.png" width="100%" alt="Banner do perfil kkyqr no itch.io: caixa d'água, casa térrea, ipê-amarelo, lobo-guará, carro de rali, piloto, placa de curva e roda low poly"></a>

Oito packs de modelos 3D em glTF/GLB, todos em domínio público (CC0): uso livre, inclusive comercial, sem precisar de crédito. O download no itch é gratuito e a doação é opcional. O código e os scripts do Blender ficam no GitHub.

| Pack | O que tem | itch.io | GitHub |
|---|---|---|---|
| City Kit | 129 modelos para city builder: prédios, ruas e terreno modulares, veículos | [baixar](https://kkyqr.itch.io/low-poly-city-kit) | [repo](https://github.com/kayquer/kit-cidade-lowpoly) |
| Brazil Buildings | 45 prédios com cara de cidade brasileira | [baixar](https://kkyqr.itch.io/low-poly-brazil-buildings-kit) | [repo](https://github.com/kayquer/kit-predios-brasil-lowpoly) |
| Brazil Props | 100 props de natureza, rua, rio e poluição | [baixar](https://kkyqr.itch.io/low-poly-brazil-props-kit) | [repo](https://github.com/kayquer/kit-props-brasil-lowpoly) |
| Threatened Fauna | 435 espécies do Livro Vermelho da fauna ameaçada | [baixar](https://kkyqr.itch.io/threatened-brazilian-fauna-low-poly-kit) | [repo](https://github.com/kayquer/kit-fauna-ameacada-lowpoly) |
| Rally Fleet 64 | 89 carros de rali com visual de console de 64 bits | [baixar](https://kkyqr.itch.io/scitizia-rally-fleet-64) | [repo](https://github.com/kayquer/scitizia-frota-64) |
| Rally People | 55 personagens com esqueleto e 10 animações | [baixar](https://kkyqr.itch.io/scitizia-people) | [repo](https://github.com/kayquer/scitizia-pessoas-64) |
| Rally Props 64 | 142 props de rali, 69 quebráveis | [baixar](https://kkyqr.itch.io/scitizia-props-64) | [repo](https://github.com/kayquer/scitizia-props-64) |
| Wheels 64 | 39 rodas, 36 pneus e 39 conjuntos montados | [baixar](https://kkyqr.itch.io/scitizia-wheels-64) | [repo](https://github.com/kayquer/scitizia-rodas-64) |

### 📐 [Português Técnico Controlado](https://github.com/kayquer/portugues-tecnico-controlado)

Reescreve texto técnico em PT-BR para ter uma leitura só. Inspirada no ASD-STE100, com 9 regras próprias, 3 níveis de rigor e um modo bilíngue EN/PT que confere se as duas versões dizem a mesma coisa.

<a href="https://github.com/kayquer/portugues-tecnico-controlado"><img src="./assets/readme/ptc.svg" width="100%" alt="Tabela de violações de um runbook: PTC-1 'deve-se verificar' vira 'verifique', PTC-4 'Realize a validação' vira 'Valide', PTC-7 '1.5 GB' vira '1,5 GB', PTC-8 'micro-serviços' vira 'microsserviços'. Medido: 12,3 para 7,5 palavras por frase"></a>

Serve para tutorial, documentação, runbook e procedimento. → [Página de instalação](https://kayquer.github.io/portugues-tecnico-controlado/) (Claude Code, Claude.ai, Cursor, Codex, Gemini CLI, ChatGPT e Perplexity)

### 📚 [Citações ABNT](https://github.com/kayquer/citacoes-abnt-skill)

Confere se as referências de um TCC, artigo ou tese existem de fato e aplica a ABNT vigente com as regras do manual da universidade. Cada obra é procurada em cinco bases abertas (Crossref, OpenAlex, Semantic Scholar, Open Library e Google Books). Só passa como verificada a obra que aparece em pelo menos duas delas. Referência inventada por IA, título real com autor trocado e DOI de outra obra aparecem separados.

<a href="https://github.com/kayquer/citacoes-abnt-skill"><img src="./assets/readme/citacoes-abnt.svg" width="100%" alt="Saída do checador: Deep learning e Pedagogia do oprimido verificadas em duas bases; Attention is all you need atribuído a Souza e Pereira marcado como quimera; um artigo sobre redes neurais quânticas na safra de café não encontrado em nenhuma base; embaixo, (SILVA, 2020, s.p.) corrigido para (Silva, 2020) pela NBR 10520:2023"></a>

Formata pela NBR 6023:2025, 10520:2023 e 14724:2024. Traz os perfis de 50 instituições, entre elas USP, Unicamp, UFMG, UFRJ, institutos federais e Fatec, cada um com o link do manual oficial consultado. Também gera o modelo Word da instituição e exporta a bibliografia em BibTeX, RIS e CSL-JSON.

```bash
claude plugin marketplace add kayquer/citacoes-abnt-skill
claude plugin install citacoes-abnt@citacoes-abnt-skill
```

→ [Regras de cada universidade](https://kayquer.github.io/citacoes-abnt-skill/) · [Normas ABNT vigentes em 2026](https://kayquer.github.io/citacoes-abnt-skill/normas-abnt-vigentes.html)

### 💧 [Guardião da Água](https://github.com/kayquer/guardiao_da_agua_js)

<a href="https://kayquer.github.io/guardiao_da_agua_js/"><img src="https://raw.githubusercontent.com/kayquer/guardiao_da_agua_js/HEAD/docs/media/cidade.webp" width="100%" alt="Cidade do Guardião da Água com bairros, reservatório, estação de tratamento e parque eólico"></a>

Jogo educativo de construção de cidade sobre recursos hídricos, para o 6º ano. O estudante governa a cidade e aprende de onde vem a água, por que ela falta ou fica poluída e como cada escolha afeta rios e nascentes. Pesquisa de mestrado na Unesp, feito em JavaScript com Babylon.js.

**[▶ Jogar no navegador](https://kayquer.github.io/guardiao_da_agua_js/)**, sem instalar nada.

### ✂️ [deai-text](https://github.com/kayquer/deai-text)

Remove padrões de texto de IA. Cada trecho marcado sai com o ID da regra, a skill reescreve e depois faz uma segunda passada na reescrita.

<a href="https://github.com/kayquer/deai-text"><img src="./assets/readme/deai-text.svg" width="100%" alt="Antes e depois do deai-text: 'possui' e o gerúndio final 'garantindo mais segurança nas transações' são marcados pelas regras AI-9 e AI-10; a reescrita diz que os dados do cartão não passam mais pelo servidor"></a>

O catálogo em português é próprio, não tradução do inglês: pega o gerúndio final, o `possui` no lugar de `tem` e decalques como `alavancar`. A suíte de regressão testa também o que **não** deve ser marcado.

```bash
claude plugin marketplace add kayquer/deai-text
claude plugin install deai-text
```

Também funciona como system prompt em qualquer outro LLM.

### ⚔️ [Batalha Naval](https://github.com/kayquer/batalha-naval)

O jogo clássico implementado em C.

## 🛠️ Stack

PHP · MySQL · JavaScript · Flutter · C · HTML e CSS · Cloudflare · Git · Claude Code

## 📫 Contato

Para os projetos, as issues do repositório são o melhor caminho. Para o resto, e-mail ou LinkedIn. Moro em Presidente Prudente, SP.

<div align="center">
  <a href="mailto:kayquerocha@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.linkedin.com/in/kayquerotondo/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://www.instagram.com/kayquerotondo/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
  <a href="https://kkyqr.itch.io" target="_blank">
    <img src="https://img.shields.io/badge/itch.io-FA5C5C?style=for-the-badge&logo=itchdotio&logoColor=white" alt="itch.io"/>
  </a>
</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=kayquer&color=blue&style=flat-square" alt="Profile views"/>
</div>
