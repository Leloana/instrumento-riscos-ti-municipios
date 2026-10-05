# Instrumento de maturidade em gestão de riscos de TI para municípios

Material de apoio a um artigo sobre um instrumento adaptativo de maturidade em gestão de riscos de TI
para órgãos municipais e cidades inteligentes.

| Pasta | Conteúdo |
|---|---|
| [`questionario/`](questionario/) | o questionário aplicado nos órgãos: 134 itens, uma Seção 0 obrigatória e 22 seções abertas por pergunta de triagem |
| [`catalogo/`](catalogo/) | o catálogo dos 134 riscos (94 de TI em geral e 40 de cidades inteligentes), com probabilidade, impacto, triagem, calibração e referências normativas |
| [`avaliacao/`](avaliacao/) | as notas dos cinco especialistas às sete afirmações sobre os requisitos de desenho (escala de 1 a 5), com mediana e concordância por afirmação |
| [`processos/`](processos/) | dois processos em BPMN que dão sequência ao diagnóstico: criar o plano de tratamento dos riscos, e implantá-lo e monitorá-lo |

## Processos

| Arquivo | Atividades |
|---|---|
| [`criar-plano-de-tratamento-dos-riscos.bpmn`](processos/criar-plano-de-tratamento-dos-riscos.bpmn) | definir contexto, identificar, analisar (probabilidade × impacto), avaliar e criar o plano, com comunicação às partes interessadas |
| [`monitorar-e-implantar-plano-de-riscos.bpmn`](processos/monitorar-e-implantar-plano-de-riscos.bpmn) | monitorar ou implantar, executar o plano, fazer a análise crítica e atualizar o registro do risco, reabrindo o plano quando surgem riscos novos |

Cada tarefa traz a descrição do passo no campo de documentação do BPMN. Para abrir: [demo.bpmn.io](https://demo.bpmn.io)
no navegador (arrastando o arquivo) ou o [Camunda Modeler](https://camunda.com/download/modeler/).

## Catálogo

A planilha tem uma aba por base (TI e cidades inteligentes), a aba de triagem que leva cada risco a uma seção do
questionário, a calibração de probabilidade e impacto com a justificativa de cada nota, as escalas, o dicionário de
campos e as referências normativas.
