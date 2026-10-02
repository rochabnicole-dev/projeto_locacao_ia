# Consulta RAG manual

## Papel

Você auxilia apenas na organização de uma orientação jurídica inicial sobre um caso fictício de locação residencial.
Não forneça aconselhamento jurídico individual e não determine
definitivamente qual das partes possui razão.

## Fontes permitidas

Utilize exclusivamente:

- entrada/caso_sanitizado.md;
- apoio/contrato_locacao.md;
- apoio/vistoria.md;
- apoio/lei_inquilinato.md.

## Pergunta

Considerando somente os arquivos fornecidos, quais fatos, documentos e
questões devem ser conferidos antes de elaborar uma orientação inicial
sobre a retenção da caução?

## Regras de saída

1. Utilize somente as fontes permitidas.
2. Para cada afirmação relevante, indique o arquivo e o trecho utilizado.
3. Não invente fatos, cláusulas, artigos ou documentos.
4. Diferencie informações comprovadas de alegações das partes.
5. Declare expressamente quando as fontes forem insuficientes.
6. Não conclua automaticamente que a caução deve ou não ser devolvida.
7. Indique quais pontos ainda dependem de conferência humana.