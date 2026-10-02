# Projeto de IA Jurídica — Caso Fictício de Locação

## Finalidade

Este projeto foi desenvolvido para demonstrar a aplicação de um fluxo
de trabalho com inteligência artificial em um caso jurídico inteiramente
fictício.

O caso envolve uma controvérsia sobre a retenção de caução após o
encerramento de uma locação residencial.

O projeto utiliza organização de contexto, RAG manual, verificação de
fontes, auditoria e revisão humana.

## Público

O projeto possui finalidade exclusivamente acadêmica e foi elaborado
para a disciplina de Inteligência Artificial Jurídica.

## Organização do projeto

- `Entrada/`: contém o relato bruto do caso fictício.
- `Apoio/`: contém o caso sanitizado e as fontes permitidas para consulta.
- `Docs/`: contém os limites, a especificação e os prompts utilizados.
- `Evidencias/`: registra a resposta inicial, a verificação, a auditoria
  e a revisão humana.
- `Entrega/`: contém a orientação inicial revisada.

## Fluxo realizado

O projeto segue o seguinte fluxo:

Caso fictício → seleção das fontes → consulta inicial com IA → verificação
humana → auditoria em segunda conversa → decisão humana sobre os achados
→ orientação inicial revisada.

## Limites

O caso é inteiramente fictício.

Não foram utilizados dados pessoais reais, documentos reais de clientes,
processos reais ou informações protegidas por sigilo.

A inteligência artificial foi utilizada somente como ferramenta de apoio
e não substitui a análise jurídica humana.

As respostas foram limitadas às fontes selecionadas no projeto e eventuais
insuficiências das fontes foram registradas durante o fluxo.

## Critérios de aceitação

O projeto deve:

- utilizar somente as fontes permitidas nas consultas;
- identificar as fontes utilizadas;
- não inventar fatos ou documentos;
- diferenciar alegações de fatos comprovados;
- registrar limitações das fontes;
- preservar dados pessoais;
- registrar a verificação humana;
- realizar auditoria independente;
- registrar a decisão humana sobre os achados;
- apresentar orientação inicial revisada.

## Como compreender o repositório

Para acompanhar o fluxo do projeto, recomenda-se consultar os arquivos
na seguinte ordem:

1. `Entrada/relato_bruto.md`;
2. arquivos da pasta `Apoio/`;
3. `Docs/especificacao.md`;
4. `Docs/limites_e_sigilo.md`;
5. arquivos existentes em `Docs/prompts/`;
6. `Evidencias/resposta_inicial.md`;
7. `Evidencias/verificacao.md`;
8. `Evidencias/auditoria.md`;
9. `Evidencias/revisao_humana.md`;
10. `Entrega/orientacao_inicial.md`.

## Repositório

URL pública do repositório: 
https://github.com/rochabnicole-dev/projeto_locacao_ia
