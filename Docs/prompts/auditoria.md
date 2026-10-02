# Resultado da auditoria

A auditoria abaixo foi realizada em uma segunda conversa com IA, a partir
dos arquivos e limites definidos no projeto.

CRÍTICO Problema encontrado: A decisão de que a cliente “tem direito total à devolução integral da caução” e a afirmação de que “não sendo necessária nenhuma correção” extrapolam o limite do projeto e são incompatíveis com a regra de não decidir definitivamente.
Arquivo: evidencias/verificacao.md

Por que precisa ser revisado:

A especificação do projeto diz que a IA não deve decidir definitivamente qual das partes possui razão.
A própria documentação do caso afirma que as fontes são insuficientes para decidir definitivamente.
O arquivo lei_inquilinato.md também adverte que a fonte não deve ser usada isoladamente para concluir que a retenção da caução é correta ou incorreta.
O requisito de auditoria exige registrar a verificação humana e a decisão humana sobre os achados da auditoria, e não uma conclusão final sem ressalvas.
Correção recomendada: Reescrever a conclusão como análise preliminar, por exemplo: “com base nos materiais disponíveis, há indícios favoráveis à locatária, mas a conclusão depende de confirmação documental e humana”; e manter explicitamente a pendência de verificação.

CRÍTICO Problema encontrado: Afirmar que “as vistorias comprovam apenas desgaste normal” e que a imobiliária “não apresentou documentação” é uma conclusão factual sem suporte direto nos arquivos.
Arquivo: evidencias/verificacao.md

Por que precisa ser revisado:

O arquivo vistoria.md registra apenas:
“pequenas marcas de uso nas paredes”;
“manutenção do risco anteriormente registrado”;
“piso sem novos danos relevantes”;
“necessidade de nova pintura” alegada pela imobiliária.
Isso não equivale a prova de que o desgaste era apenas normal, nem a prova de ausência de documentação.
O projeto exige diferenciar fato, documento e conclusão jurídica; o arquivo em questão confunde esses níveis.
Correção recomendada: Remover a afirmação de que as vistorias comprovam desgaste normal. Substituir por: “Os registros indicam desgaste leve/uso normal, mas a natureza e a extensão dos danos exigem documentação complementar (orçamento, notas, fotos, laudo) para a conclusão.”

CRÍTICO Problema encontrado: Citação de Arts. 422 e 944 do Código Civil sem suporte textual nos arquivos fornecidos.
Arquivo: evidencias/verificacao.md e apoio/lei_inquilinato.md

Por que precisa ser revisado:

No arquivo lei_inquilinato.md, os trechos selecionados incluem apenas o art. 23 e o art. 38, além da identificação dos artigos 422 e 944 no cabeçalho, mas não há texto dos artigos 422 e 944.
Em outras palavras, a decisão jurídica usa dispositivos que não foram conferidos no material de apoio.
Isso viola a regra de que a resposta deve usar somente as fontes permitidas e indicar arquivo e trecho utilizado.
Correção recomendada: Excluir a menção aos arts. 422 e 944 se não houver trecho efetivamente conferido; ou acrescentar explicitamente: “Art. 422 e Art. 944 foram apenas indicados, mas não foram conferidos no material disponível.”

CRÍTICO Problema encontrado: A resposta faz afirmações que excedem o conteúdo das fontes e tratam como certos fatos que não aparecem nos arquivos.
Arquivo: evidencias/verificacao.md

Por que precisa ser revisado:

O material fornecido não contém:
prova de que a imobiliária não apresentou orçamento/nota/laudo;
prova de que o desgaste é exclusivamente normal;
prova de que não houve dano extraordinário;
prova documental da constituição da caução em dinheiro;
avaliação técnica do necessário de pintura.
A regra do projeto exige diferenciar fato, documento e conclusão. Aqui há mistura entre premissas não provadas e conclusão jurídica definitiva.
Correção recomendada: Reduzir a linguagem para hipótese: “Se a documentação complementar comprovar que não houve dano extraordinário, a conclusão pode favorecer a locatária. Sem isso, não é possível decidir.”

ALERTA Problema encontrado: Há inconsistência de nomenclatura e caminho dos arquivos citados na auditoria em relação aos arquivos efetivamente fornecidos.
Arquivo:

docs/limites_e_sigilo.md
apoio/...
evidencias/resposta_inicial.md
evidencias/verificacao.md
e os arquivos efetivamente recebidos no prompt: resposta_inicial.md e verificação.md
Por que precisa ser revisado:

A auditoria manda analisar os arquivos em caminhos específicos, mas os arquivos consolidados no material enviado aparecem em outra estrutura.
Isso pode comprometer rastreabilidade e o controle de qual versão foi realmente analisada.
Correção recomendada: Padronizar os nomes e caminhos dos arquivos e confirmar a estrutura exata antes da análise. Se a pasta for diferente, indicar claramente que a revisão foi feita sobre os arquivos recebidos no contexto atual.

OK Problema encontrado: Sem exposição de dados pessoais.
Arquivo: Todos os arquivos analisados, especialmente docs/limites_e_sigilo.md e apoio/caso_sanitizado.md

Por que está OK:

Os textos usam “locatária”, “locador”, “imobiliária”, sem nome completo, CPF, telefone, endereço residencial, dados bancários ou assinatura.
Isso está em conformidade com as regras do projeto.
Correção recomendada: Manter a forma genérica e não incluir qualquer dado identificador em eventuais revisões.

OK Problema encontrado: A resposta inicial foi mais cautelosa e mais compatível com o projeto.
Arquivo: evidencias/resposta_inicial.md

Por que está OK:

Ela admite insuficiência das fontes para decidir definitivamente.
Reconhece a necessidade de conferir documentos e exames.
Mantém a separação entre fato, documento e avaliação jurídica.
Correção recomendada: Manter esse padrão e evitar que as respostas de verificação e revisão regridam para conclusões definitivas sem suporte documental.    