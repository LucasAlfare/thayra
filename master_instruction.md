# Cronograma sequencial — Desenvolvimento do TCC sobre acompanhamento farmacêutico e terapia hormonal na menopausa

## 1. Contexto

O projeto consiste em um TCC de Farmácia, desenvolvido em Markdown, com o tema:

“Qual é o papel do acompanhamento farmacêutico no manejo da terapia hormonal em mulheres na menopausa para a otimização
dos benefícios e mitigação dos riscos?”

O objetivo do cronograma é transformar o planejamento já realizado em um trabalho acadêmico completo, rastreável e
compatível com as exigências institucionais.

O índice bibliográfico inicial já foi auditado preliminarmente. A bibliografia, porém, ainda não está fechada. O
trabalho deve avançar pela definição da estrutura e da metodologia, busca complementar direcionada, seleção e leitura
das fontes, consolidação das evidências e redação progressiva.

Regra de execução: cada etapa depende da conclusão da anterior. Se faltarem arquivos necessários, a implementação deve
parar até que sejam fornecidos. Não se deve inventar informações para contornar arquivos ausentes.

## 2. Regras obrigatórias de implementação

1. Aplicar rigor acadêmico, escrita objetiva e organização consistente em Markdown, evitando redundâncias e conteúdo
   desnecessário.
2. Não inventar fontes, dados, citações, resultados, páginas, DOI, critérios de seleção ou números de estudos.
3. Não confundir evidências clínicas da terapia hormonal com evidências específicas da atuação farmacêutica.
4. Não assumir automaticamente que a modalidade da revisão será sistemática, integrativa ou narrativa. A decisão deve
   considerar as exigências institucionais e a viabilidade real.
5. Registrar as buscas e a seleção efetivamente realizadas. Não reconstruir retrospectivamente um método que não foi
   executado.
6. Não redigir capítulos com base apenas em referências citadas por terceiros quando a leitura da fonte original for
   necessária.
7. Preservar os materiais institucionais e os arquivos já produzidos, modificando-os somente quando a etapa exigir.
8. Não converter para DOCX ou PDF durante as etapas de desenvolvimento.
9. Não executar código ou testes. A conferência se limita aos documentos, à consistência científica, aos links e às
   referências.
10. Não avançar para a etapa seguinte enquanto os critérios de conclusão da etapa atual não forem atendidos.

### Regras de fornecimento dos arquivos

Para cada etapa, os arquivos são classificados como:

- Consultar/anexar: necessários como contexto, mas sem alteração prevista.
- Modificar: arquivos existentes cujo conteúdo deverá ser atualizado.
- Criar: novos arquivos Markdown produzidos pela etapa.

Os arquivos novos listados abaixo são nomes propostos para os próximos documentos, não arquivos que já existam. Como não
foi fornecida uma estrutura de diretórios, o cronograma considera inicialmente todos os Markdown na mesma pasta de
trabalho.

Quando uma etapa depender de PDFs científicos, deverão ser anexados os arquivos realmente obtidos. O cronograma não
presume que esses PDFs já estejam disponíveis.

# 3. Etapas de implementação

## Etapa 1 — Consolidar a estrutura institucional do TCC

Contexto: estabelecer uma estrutura única de trabalho, respeitando as exigências institucionais e usando o
trabalho-modelo apenas como referência.

Objetivo verificável: produzir uma estrutura que identifique todos os elementos pré-textuais, textuais e pós-textuais,
com sua hierarquia e requisitos aplicáveis.

Arquivos envolvidos

- Consultar/anexar: `00_LEIA-ME.md`, `01_REGRAS_INSTITUCIONAIS_TRANSCRICAO.md`, `02_MODELO_TCC_TRANSCRICAO.md` e
  `04_MAPA_REGRAS_MODELO_PROXIMOS_PASSOS.md`.
- Modificar: nenhum.
- Criar: `05_ESTRUTURA_TCC.md`.

Escopo fechado: organizar títulos, seções, subseções e requisitos formais. Não redigir os capítulos.

Critério de conclusão: a estrutura contempla todos os elementos obrigatórios identificados no documento institucional e
registra eventuais dúvidas que não podem ser resolvidas apenas com os materiais disponíveis.

Commit: `docs(feat): define TCC structure`

## Etapa 2 — Definir o protocolo metodológico e a estratégia de busca

Contexto: antes de ampliar a pesquisa, estabelecer como a revisão será conduzida e documentada, sem escolher uma
modalidade metodológica incompatível com as regras institucionais.

Objetivo verificável: criar um protocolo que documente a modalidade escolhida, as bases a consultar, os descritores, os
critérios preliminares de elegibilidade e o método de síntese.

Arquivos envolvidos

- Consultar/anexar: `05_ESTRUTURA_TCC.md`, `01_REGRAS_INSTITUCIONAIS_TRANSCRICAO.md` e
  `03_INDICE_BIBLIOGRAFICO_AUDITADO.md`.
- Modificar: nenhum.
- Criar: `06_PROTOCOLO_REVISAO.md`.

Escopo fechado: definir e justificar o método e a estratégia de busca. Não executar ainda a seleção definitiva dos
estudos.

Critério de conclusão: o protocolo contém critérios claros, aplicáveis e compatíveis com as exigências disponíveis.
Decisões que dependam de esclarecimento institucional ficam explicitamente registradas.

Commit: `docs(feat): define literature review protocol`

## Etapa 3 — Executar a busca bibliográfica complementar

Contexto: o índice existente apresenta uma base inicial, mas a busca sobre a participação direta do farmacêutico na
menopausa pode estar incompleta.

Objetivo verificável: produzir um registro reproduzível das buscas, incluindo fontes consultadas, estratégias
utilizadas, datas, filtros e quantidades de registros recuperados.

Arquivos envolvidos

- Consultar/anexar: `03_INDICE_BIBLIOGRAFICO_AUDITADO.md` e `06_PROTOCOLO_REVISAO.md`.
- Modificar: nenhum.
- Criar: `07_REGISTRO_BUSCAS.md`.

Escopo fechado: realizar as buscas previstas no protocolo, priorizando estudos diretamente relacionados ao
acompanhamento farmacêutico de mulheres na peri e pós-menopausa. A busca também deverá cobrir as evidências clínicas
necessárias à discussão.

Critério de conclusão: todas as buscas efetivamente realizadas estão documentadas e seus resultados são rastreáveis.
Cada contagem corresponde aos registros realmente encontrados.

Commit: `docs(feat): document bibliographic searches`

## Etapa 4 — Triar os registros bibliográficos

Contexto: identificar quais referências recuperadas merecem avaliação integral, evitando incluir estudos apenas por
serem relacionados ao tema.

Objetivo verificável: produzir uma triagem documentada, aplicando os critérios definidos no protocolo.

Arquivos envolvidos

- Consultar/anexar: `06_PROTOCOLO_REVISAO.md`, `07_REGISTRO_BUSCAS.md` e `03_INDICE_BIBLIOGRAFICO_AUDITADO.md`.
- Modificar: `07_REGISTRO_BUSCAS.md`, somente para acrescentar o andamento da triagem, se necessário.
- Criar: `08_TRIAGEM_REFERENCIAS.md`.

Escopo fechado: remover duplicatas, avaliar títulos e resumos disponíveis e registrar decisões de inclusão, exclusão ou
dúvida. Não inferir resultados clínicos a partir dos títulos.

Critério de conclusão: cada registro avaliado tem uma decisão e justificativa compatíveis com os critérios
estabelecidos. Os casos que exigem texto completo permanecem identificados como pendentes.

Commit: `docs(update): document reference screening`

## Etapa 5 — Avaliar os textos completos e fechar a seleção de fontes

Contexto: determinar quais estudos realmente podem sustentar o TCC, distinguindo referências localizadas de estudos
efetivamente lidos e avaliados.

Objetivo verificável: produzir a lista de fontes incluídas, com situação de acesso e justificativa metodológica.

Arquivos envolvidos

- Consultar/anexar: `06_PROTOCOLO_REVISAO.md`, `08_TRIAGEM_REFERENCIAS.md` e os textos completos efetivamente obtidos
  dos estudos candidatos.
- Modificar: nenhum.
- Criar: `09_REFERENCIAS_INCLUIDAS.md`.

Escopo fechado: avaliar elegibilidade, disponibilidade, pertinência e limitações das fontes. Não iniciar a redação dos
capítulos.

Critério de conclusão: cada fonte selecionada tem referência rastreável e decisão justificada. Estudos não acessados
integralmente são identificados como tais; não são tratados como se tivessem sido lidos por completo.

Commit: `docs(feat): document selected literature`

## Etapa 6 — Criar e preencher a matriz de evidências clínicas

Contexto: organizar o conhecimento sobre menopausa e terapia hormonal, especialmente benefícios, riscos, indicações,
contraindicações, formulações, vias de administração e individualização do tratamento.

Objetivo verificável: preencher a matriz com os achados clínicos das fontes selecionadas, suas limitações e a
contribuição de cada uma para a pesquisa.

Arquivos envolvidos

- Consultar/anexar: `09_REFERENCIAS_INCLUIDAS.md` e os textos completos das fontes clínicas selecionadas, sobretudo o
  consenso da SOBRAC, as recomendações da IMS, a diretriz NICE, o posicionamento da The Menopause Society e a revisão
  sobre vias oral e transdérmica, quando incluídos.
- Modificar: nenhum.
- Criar: `10_MATRIZ_EVIDENCIAS.md`.

Escopo fechado: registrar objetivo, método, população, resultados, limitações, relevância e localização das informações
nas fontes. Nesta etapa, preencher a matriz apenas com o eixo clínico da terapia hormonal.

Critério de conclusão: cada afirmação extraída está vinculada à respectiva fonte; dados não encontrados ou não
verificáveis são identificados como pendentes, sem preenchimento especulativo.

Commit: `docs(feat): create clinical evidence matrix`

## Etapa 7 — Consolidar as evidências sobre acompanhamento farmacêutico

Contexto: avaliar o que a literatura demonstra especificamente sobre o cuidado farmacêutico na menopausa e o que pode
ser fundamentado apenas em estudos gerais de serviços farmacêuticos.

Objetivo verificável: incorporar à matriz as evidências diretas e indiretas, identificando claramente seus diferentes
níveis de aplicabilidade.

Arquivos envolvidos

- Consultar/anexar: `09_REFERENCIAS_INCLUIDAS.md`, `10_MATRIZ_EVIDENCIAS.md` e os textos completos disponíveis de Chow
  et al. (2024), Branvold e Barner, Craske et al. (2024) e das demais fontes farmacêuticas selecionadas.
- Modificar: `10_MATRIZ_EVIDENCIAS.md`.
- Criar: nenhum.

Escopo fechado: registrar resultados sobre consultas farmacêuticas, revisão da farmacoterapia, educação em saúde,
adesão, identificação de problemas relacionados a medicamentos e outros desfechos realmente avaliados pelos estudos.

Critério de conclusão: a matriz distingue evidências específicas da menopausa, evidências gerais sobre cuidado
farmacêutico e inferências que ainda não possuem demonstração direta.

Commit: `docs(update): add pharmacist care evidence`

## Etapa 8 — Consolidar o contexto brasileiro e as fontes regulatórias

Contexto: contextualizar a pesquisa no Brasil, incluindo epidemiologia, uso racional de medicamentos, atribuições
profissionais e orientações institucionais.

Objetivo verificável: incorporar à matriz as informações verificadas nas fontes brasileiras e institucionais
pertinentes.

Arquivos envolvidos

- Consultar/anexar: `09_REFERENCIAS_INCLUIDAS.md`, `10_MATRIZ_EVIDENCIAS.md` e os documentos selecionados, como a Nota
  Técnica Conjunta nº 72/2026, a Resolução CFF nº 585/2013, Pompei et al. (2022) e Arrais et al. (2016).
- Modificar: `10_MATRIZ_EVIDENCIAS.md`.
- Criar: nenhum.

Escopo fechado: registrar as informações efetivamente sustentadas pelos documentos. Não atribuir a uma população
específica resultados obtidos em estudos gerais nem apresentar documentos regulatórios como ensaios de eficácia.

Critério de conclusão: as evidências nacionais, clínicas, regulatórias e epidemiológicas estão separadas, com limitações
documentadas e indicação de uso potencial no TCC.

Commit: `docs(update): consolidate Brazilian evidence`

## Etapa 9 — Finalizar a metodologia executada

Contexto: transformar o protocolo preliminar em uma descrição fiel do processo realmente conduzido.

Objetivo verificável: produzir a metodologia definitiva, com modalidade de revisão, bases, estratégias, critérios,
processo de triagem, extração e síntese, além das contagens reais aplicáveis.

Arquivos envolvidos

- Consultar/anexar: `05_ESTRUTURA_TCC.md`, `06_PROTOCOLO_REVISAO.md`, `07_REGISTRO_BUSCAS.md`,
  `08_TRIAGEM_REFERENCIAS.md` e `09_REFERENCIAS_INCLUIDAS.md`.
- Modificar: nenhum.
- Criar: `11_METODOLOGIA.md`.

Escopo fechado: documentar o método executado, sem alterar artificialmente o processo para que pareça mais rigoroso ou
abrangente do que foi.

Critério de conclusão: a descrição metodológica corresponde aos registros das buscas e da seleção, sem divergências nas
contagens e sem etapas fictícias.

Commit: `docs(feat): document final review methodology`

## Etapa 10 — Elaborar o mapa de evidências por seção

Contexto: antes da redação, definir quais informações sustentam cada parte do TCC, evitando repetições e afirmações sem
suporte.

Objetivo verificável: criar um mapa que relacione seções, argumentos principais, fontes e limitações relevantes.

Arquivos envolvidos

- Consultar/anexar: `05_ESTRUTURA_TCC.md`, `09_REFERENCIAS_INCLUIDAS.md`, `10_MATRIZ_EVIDENCIAS.md` e
  `11_METODOLOGIA.md`.
- Modificar: nenhum.
- Criar: `12_MAPA_EVIDENCIAS_POR_SECAO.md`.

Escopo fechado: organizar os argumentos e suas fontes por seção. Não redigir ainda os capítulos.

Critério de conclusão: cada eixo argumentativo tem fontes identificadas e as lacunas importantes estão explicitadas, sem
antecipar conclusões não demonstradas.

Commit: `docs(feat): map evidence to TCC sections`

## Etapa 11 — Redigir a introdução, a justificativa e os objetivos

Contexto: com a estrutura, o método e as evidências consolidados, iniciar a redação acadêmica.

Objetivo verificável: produzir os três elementos textuais iniciais, coerentes entre si e fundamentados nas fontes
selecionadas.

Arquivos envolvidos

- Consultar/anexar: `05_ESTRUTURA_TCC.md`, `10_MATRIZ_EVIDENCIAS.md` e `12_MAPA_EVIDENCIAS_POR_SECAO.md`.
- Modificar: nenhum.
- Criar: `13_INTRODUCAO.md`, `14_JUSTIFICATIVA.md` e `15_OBJETIVOS.md`.

Escopo fechado: contextualizar o problema, justificar a relevância da pesquisa e formular objetivo geral e objetivos
específicos. Não escrever resultados ou discussão antecipadamente.

Critério de conclusão: a introdução apresenta o tema e a pergunta de pesquisa; a justificativa demonstra a relevância do
estudo; os objetivos são claros, exequíveis e compatíveis com a metodologia.

Commit: `docs(feat): draft introduction and objectives`

## Etapa 12 — Redigir os resultados da revisão

Contexto: apresentar os achados da literatura selecionada sem confundir a descrição dos resultados com sua interpretação
crítica.

Objetivo verificável: produzir uma seção de resultados organizada por eixos temáticos e coerente com a matriz e a
seleção de estudos.

Arquivos envolvidos

- Consultar/anexar: `09_REFERENCIAS_INCLUIDAS.md`, `10_MATRIZ_EVIDENCIAS.md`, `11_METODOLOGIA.md` e
  `12_MAPA_EVIDENCIAS_POR_SECAO.md`.
- Modificar: nenhum.
- Criar: `16_RESULTADOS.md`.

Escopo fechado: apresentar o conjunto de estudos e seus principais achados, incluindo as limitações relevantes. Não
introduzir referências sem avaliação prévia.

Critério de conclusão: os resultados são rastreáveis às fontes incluídas e correspondem ao processo de seleção descrito
na metodologia.

Commit: `docs(feat): write literature review results`

## Etapa 13 — Redigir a discussão

Contexto: interpretar criticamente os resultados e responder à pergunta de pesquisa sem extrapolar as evidências.

Objetivo verificável: produzir uma discussão que relacione a segurança e a efetividade da terapia hormonal às
contribuições possíveis e às limitações demonstradas do acompanhamento farmacêutico.

Arquivos envolvidos

- Consultar/anexar: `10_MATRIZ_EVIDENCIAS.md`, `12_MAPA_EVIDENCIAS_POR_SECAO.md` e `16_RESULTADOS.md`.
- Modificar: nenhum.
- Criar: `17_DISCUSSAO.md`.

Escopo fechado: discutir os achados, convergências, divergências, limitações e implicações para a prática farmacêutica.
Não apresentar opiniões como resultados científicos.

Critério de conclusão: a discussão distingue evidências diretas e indiretas, considera as limitações dos estudos e não
atribui ao farmacêutico resultados que não foram efetivamente investigados.

Commit: `docs(feat): write critical discussion`

## Etapa 14 — Redigir a conclusão

Contexto: sintetizar a resposta obtida na revisão sem introduzir dados ou fontes novos.

Objetivo verificável: produzir uma conclusão que responda diretamente à pergunta-tema e esteja alinhada aos resultados e
objetivos.

Arquivos envolvidos

- Consultar/anexar: `13_INTRODUCAO.md`, `15_OBJETIVOS.md`, `16_RESULTADOS.md` e `17_DISCUSSAO.md`.
- Modificar: nenhum.
- Criar: `18_CONCLUSAO.md`.

Escopo fechado: sintetizar os achados, apontar as limitações centrais e registrar implicações ou necessidades de
investigação futura justificadas pelo trabalho.

Critério de conclusão: nenhuma afirmação excede a força das evidências e todos os objetivos são retomados de maneira
coerente.

Commit: `docs(feat): write TCC conclusion`

## Etapa 15 — Elaborar o resumo e o abstract

Contexto: sintetizar o trabalho completo depois da definição dos resultados e da conclusão.

Objetivo verificável: produzir as versões em português e inglês de acordo com as exigências institucionais.

Arquivos envolvidos

- Consultar/anexar: `11_METODOLOGIA.md`, `16_RESULTADOS.md`, `17_DISCUSAO.md` e `18_CONCLUSAO.md`.
- Modificar: nenhum.
- Criar: `19_RESUMO_ABSTRACT.md`.

Escopo fechado: elaborar resumo, abstract e palavras-chave equivalentes. Observar os limites de extensão e a estrutura
que a instituição efetivamente exigir.

Critério de conclusão: ambos representam fielmente o trabalho completo, sem resultados, conclusões ou informações
metodológicas inexistentes.

Commit: `docs(feat): add abstract and keywords`

## Etapa 16 — Consolidar e conferir as referências finais

Contexto: garantir que todas as citações do trabalho correspondam às fontes utilizadas e que os dados bibliográficos
estejam corretos.

Objetivo verificável: produzir uma lista final em ordem alfabética, com metadados e formatação conferidos de acordo com
as orientações institucionais.

Arquivos envolvidos

- Consultar/anexar: todos os capítulos redigidos, `03_INDICE_BIBLIOGRAFICO_AUDITADO.md` e `09_REFERENCIAS_INCLUIDAS.md`.
- Modificar: nenhum.
- Criar: `20_REFERENCIAS_FINAIS.md`.

Escopo fechado: verificar correspondência entre citações e referências, duplicatas, autoria, títulos, ano, periódico,
DOI, URL e demais dados disponíveis. Não incluir fontes não utilizadas apenas para aumentar a bibliografia.

Critério de conclusão: todas as citações estão vinculadas a referências rastreáveis; divergências ou dados não
confirmados permanecem identificados como pendências.

Commit: `docs(fix): reconcile citations and references`

## Etapa 17 — Consolidar o TCC em um único documento Markdown

Contexto: reunir os arquivos desenvolvidos em uma versão integral, respeitando a estrutura institucional.

Objetivo verificável: gerar um documento único que possa servir como fonte principal para revisão e futura conversão.

Arquivos envolvidos

- Consultar/anexar: `05_ESTRUTURA_TCC.md` e todos os arquivos produzidos nas etapas anteriores, de `11_METODOLOGIA.md` a
  `20_REFERENCIAS_FINAIS.md`, incluindo os três arquivos de introdução, justificativa e objetivos e os capítulos de
  resultados, discussão e conclusão.
- Modificar: nenhum dos arquivos de origem.
- Criar: `21_TCC_CONSOLIDADO.md`.

Escopo fechado: combinar os conteúdos aprovados, ajustar a hierarquia de títulos, eliminar duplicações decorrentes da
consolidação e conferir a ordem das seções.

Critério de conclusão: o documento contém todos os elementos previstos, mantém citações e referências sincronizadas e
não apresenta divergências entre os capítulos e os arquivos de origem.

Commit: `docs(feat): consolidate complete TCC`

## 4. Regra para a execução de cada etapa por outra LLM

Quando o cronograma for usado para solicitar a implementação de uma etapa específica:

1. A LLM deverá conferir a lista de arquivos necessários e solicitar os que estiverem ausentes.
2. Deverá modificar ou criar apenas os arquivos previstos para aquela etapa.
3. Deverá entregar o conteúdo completo de todos os novos arquivos e de todos os arquivos alterados, não apenas
   fragmentos ou instruções genéricas.
4. Deverá apontar limitações, fontes não acessadas e informações que não puderam ser verificadas.
5. Deverá declarar explicitamente se a etapa foi concluída e se todos os critérios de conclusão foram atendidos.
6. Deverá fornecer o commit específico da etapa somente se ela tiver sido concluída.
7. O texto de commit consolidado para `amend` só deverá ser fornecido quando solicitado expressamente.

Estado inicial: a estrutura e o índice bibliográfico preliminar já existem, mas ainda precisam ser anexados quando
necessários. A próxima execução é a Etapa 1, que exige os documentos institucionais transcritos e o mapa de regras para
produzir a estrutura formal consolidada.