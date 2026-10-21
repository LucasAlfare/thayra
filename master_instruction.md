# Cronograma sequencial — Desenvolvimento do TCC sobre acompanhamento farmacêutico e terapia hormonal na menopausa

## 1. Contexto

O projeto consiste em um TCC de Farmácia, desenvolvido em Markdown, com o tema:

“Qual é o papel do acompanhamento farmacêutico no manejo da terapia hormonal em mulheres na menopausa para a otimização
dos benefícios e mitigação dos riscos?”

O objetivo deste cronograma é transformar o planejamento já realizado em um trabalho acadêmico completo, rastreável,
cientificamente fundamentado e compatível com as exigências institucionais.

O índice bibliográfico inicial já foi auditado preliminarmente. Entretanto, a bibliografia ainda não está fechada. O
desenvolvimento deverá avançar pela consolidação da estrutura institucional, definição do método, realização das buscas
complementares, seleção e avaliação das fontes, extração e síntese das evidências, redação dos capítulos e auditoria do
documento final.

A sequência foi organizada para que cada etapa produza os materiais necessários à etapa seguinte. Nenhuma etapa poderá
ser considerada concluída enquanto seus critérios de conclusão não forem atendidos.

**Regra de execução:** cada etapa depende da conclusão da anterior. Se faltarem arquivos necessários, a execução deverá
ser interrompida até que sejam fornecidos. Não se deve inventar informações para contornar arquivos ausentes.

## 2. Regras obrigatórias de implementação

1. Aplicar rigor acadêmico, escrita objetiva e organização consistente em Markdown, evitando redundâncias e conteúdo
   desnecessário.
2. Não inventar fontes, dados, citações, resultados, páginas, DOI, critérios de seleção, datas de busca ou números de
   estudos.
3. Não confundir evidências clínicas da terapia hormonal com evidências específicas da atuação farmacêutica.
4. Não assumir automaticamente que a modalidade da revisão será sistemática, integrativa ou narrativa. A decisão deverá
   considerar as exigências institucionais, os objetivos da pesquisa e a viabilidade real.
5. Registrar as buscas e a seleção efetivamente realizadas. Não reconstruir retrospectivamente um método que não foi
   executado.
6. Não redigir capítulos com base apenas em referências citadas por terceiros quando a leitura da fonte original for
   necessária.
7. Preservar os materiais institucionais e os arquivos já produzidos, modificando-os somente quando a etapa exigir.
8. Não converter para DOCX ou PDF durante as etapas de desenvolvimento.
9. Não executar código ou testes. A conferência limita-se aos documentos, à consistência científica, aos links e às
   referências.
10. Não avançar para a etapa seguinte enquanto os critérios de conclusão da etapa atual não forem atendidos.
11. Distinguir estudos científicos, diretrizes, documentos regulatórios, fontes epidemiológicas e outros materiais de
    contextualização. A classificação deverá respeitar a finalidade e o método de cada fonte.
12. Não presumir que uma referência do índice bibliográfico preliminar foi recuperada em uma busca, teve seu texto
    completo acessado ou foi incluída na revisão.
13. Manter rastreabilidade entre os registros recuperados, as decisões de triagem, os textos completos avaliados, a
    matriz de evidências, as citações e as referências finais.
14. Não forçar o preenchimento de campos que não se aplicam a determinado tipo de fonte. Informações inexistentes ou não
    verificáveis deverão permanecer identificadas como pendências.
15. Não considerar o documento final concluído enquanto existirem pendências relevantes de conteúdo, metodologia,
    referências ou conformidade institucional.
16. Quando uma etapa identificar um problema que dependa de uma decisão institucional ou de um arquivo ainda não
    fornecido, registrar a pendência e interromper a parte da execução que depender dessa informação. Não tomar uma
    decisão arbitrária apenas para permitir o avanço do cronograma.

### 2.1. Regras de fornecimento dos arquivos

Para cada etapa, os arquivos serão classificados da seguinte forma:

- **Consultar/anexar:** arquivos necessários como contexto, sem alteração prevista.
- **Modificar:** arquivos existentes cujo conteúdo deverá ser atualizado.
- **Criar:** novos arquivos Markdown produzidos pela etapa.

Os nomes dos arquivos novos são propostas para os documentos futuros, não arquivos que já existam. Como não foi
fornecida uma estrutura de diretórios, o cronograma considera inicialmente todos os arquivos Markdown na mesma pasta de
trabalho.

Quando uma etapa depender de PDFs científicos ou de documentos institucionais originais, deverão ser anexados os
arquivos efetivamente obtidos. O cronograma não presume que esses materiais já estejam disponíveis.

A numeração dos arquivos acompanha a sequência de produção, mas não determina a ordem em que os componentes aparecerão
no TCC consolidado. A ordem final deverá obedecer à estrutura institucional aprovada.

### 2.2. Regras para os commits

Cada etapa concluída poderá receber um commit específico, com uma mensagem padronizada no formato
`docs(escopo): descrição da alteração`.

O commit somente será fornecido quando a etapa estiver concluída e seus critérios de conclusão tiverem sido atendidos.

O texto de commit consolidado para `amend` só deverá ser fornecido quando solicitado expressamente.

## 3. Etapas de implementação

### Etapa 1 — Consolidar a estrutura institucional do TCC

**Contexto:** estabelecer uma estrutura única de trabalho, respeitando as exigências institucionais e usando o
trabalho-modelo apenas como referência.

**Objetivo verificável:** produzir uma estrutura que identifique todos os elementos pré-textuais, textuais e
pós-textuais aplicáveis, sua hierarquia, sua ordem e os respectivos requisitos formais.

**Arquivos envolvidos**

- **Consultar/anexar:** `00_LEIA-ME.md`, `01_REGRAS_INSTITUCIONAIS_TRANSCRICAO.md`, `02_MODELO_TCC_TRANSCRICAO.md` e
  `04_MAPA_REGRAS_MODELO_PROXIMOS_PASSOS.md`.
- **Modificar:** nenhum.
- **Criar:** `05_ESTRUTURA_TCC.md`.

**Escopo fechado:** organizar títulos, seções, subseções, elementos obrigatórios, opcionais ou condicionais e requisitos
formais. Definir se os resultados e a discussão deverão constituir capítulos separados ou se outra organização será
necessária, conforme as regras institucionais. Registrar dúvidas que dependam de esclarecimento externo. Não redigir os
capítulos.

**Critérios de conclusão:**

- A estrutura contempla todos os elementos obrigatórios identificados nos materiais institucionais.
- A ordem dos elementos está documentada.
- Os requisitos de organização dos capítulos estão definidos conforme os materiais disponíveis.
- As dúvidas que não puderem ser resolvidas com os arquivos fornecidos estão explicitadas.
- Não foram inventadas exigências institucionais nem presumidos componentes obrigatórios sem fundamento documental.

**Commit:** `docs(tcc): define institutional structure`

### Etapa 2 — Definir o protocolo metodológico e a estratégia de busca

**Contexto:** antes de ampliar a pesquisa bibliográfica, estabelecer como a revisão será conduzida e documentada, sem
escolher uma modalidade incompatível com as regras institucionais ou com a viabilidade real.

**Objetivo verificável:** criar um protocolo que documente a modalidade de revisão escolhida, sua justificativa, as
fontes de informação, as estratégias de busca, os critérios preliminares de elegibilidade e o método de extração e
síntese.

**Arquivos envolvidos**

- **Consultar/anexar:** `05_ESTRUTURA_TCC.md`, `01_REGRAS_INSTITUCIONAIS_TRANSCRICAO.md` e
  `03_INDICE_BIBLIOGRAFICO_AUDITADO.md`.
- **Modificar:** nenhum.
- **Criar:** `06_PROTOCOLO_REVISAO.md`.

**Escopo fechado:** definir e justificar o método e a estratégia de busca. Especificar as bases e outras fontes a
consultar, os descritores e seus cruzamentos, os idiomas e períodos de publicação quando aplicáveis, os critérios de
inclusão e exclusão, a remoção de duplicatas, o processo de triagem, a extração e a síntese das evidências. Não executar
ainda a seleção definitiva dos estudos.

**Critérios de conclusão:**

- O protocolo contém critérios claros, aplicáveis e compatíveis com a estrutura institucional.
- A modalidade de revisão foi escolhida e justificada de acordo com as exigências e a viabilidade disponíveis.
- Os procedimentos previstos podem ser efetivamente executados e documentados.
- As decisões que dependam de esclarecimento institucional estão registradas.
- Nenhuma escolha metodológica é apresentada como definitiva quando depende de informação institucional essencial ainda
  indisponível.

**Commit:** `docs(review): define literature review protocol`

### Etapa 3 — Executar a busca bibliográfica complementar

**Contexto:** o índice existente constitui uma base inicial, mas a literatura sobre a participação direta do
farmacêutico no cuidado de mulheres na peri e pós-menopausa pode estar incompleta.

**Objetivo verificável:** produzir um registro reproduzível das buscas realizadas, incluindo fontes consultadas,
estratégias utilizadas, datas, filtros, quantidades de registros recuperados e limitações encontradas.

**Arquivos envolvidos**

- **Consultar/anexar:** `03_INDICE_BIBLIOGRAFICO_AUDITADO.md` e `06_PROTOCOLO_REVISAO.md`.
- **Modificar:** nenhum.
- **Criar:** `07_REGISTRO_BUSCAS.md`.

**Escopo fechado:** realizar as buscas previstas no protocolo, priorizando estudos diretamente relacionados ao
acompanhamento farmacêutico de mulheres na peri e pós-menopausa. A pesquisa também deverá abranger as evidências
clínicas necessárias à compreensão dos benefícios, riscos e condições de uso da terapia hormonal.

O registro deverá distinguir:

- Referências que já constavam do índice bibliográfico preliminar.
- Registros recuperados nas buscas complementares.
- Duplicatas identificadas e removidas.
- Resultados efetivamente obtidos em cada fonte consultada.

**Critérios de conclusão:**

- Todas as buscas efetivamente realizadas estão documentadas.
- Cada estratégia registrada corresponde àquela realmente executada.
- Datas, filtros e quantidades de registros refletem os resultados reais.
- A origem dos registros é rastreável.
- As limitações de acesso e de cobertura das fontes consultadas estão documentadas.

**Commit:** `docs(search): document bibliographic searches`

### Etapa 4 — Triar os registros bibliográficos

**Contexto:** identificar quais referências recuperadas merecem avaliação integral, evitando a inclusão de materiais
apenas por apresentarem relação superficial com o tema.

**Objetivo verificável:** produzir uma triagem documentada, aplicando os critérios definidos no protocolo metodológico.

**Arquivos envolvidos**

- **Consultar/anexar:** `06_PROTOCOLO_REVISAO.md`, `07_REGISTRO_BUSCAS.md` e `03_INDICE_BIBLIOGRAFICO_AUDITADO.md`.
- **Modificar:** `07_REGISTRO_BUSCAS.md`, somente para acrescentar informações de andamento da triagem e reconciliar as
  contagens quando necessário.
- **Criar:** `08_TRIAGEM_REFERENCIAS.md`.

**Escopo fechado:** identificar e remover duplicatas, quando ainda necessário, avaliar títulos e resumos disponíveis e
registrar decisões de inclusão, exclusão ou dúvida. Não inferir resultados clínicos a partir dos títulos ou dos resumos.

A triagem deverá preservar a diferença entre referências previamente conhecidas e registros recuperados nas buscas. As
razões de exclusão deverão ser registradas de maneira compatível com o método definido no protocolo.

**Critérios de conclusão:**

- Cada registro submetido à triagem possui uma decisão ou está explicitamente identificado como pendente.
- As decisões são compatíveis com os critérios de elegibilidade.
- As exclusões possuem justificativas adequadas ao nível de avaliação realizado.
- Os casos que exigem leitura integral permanecem identificados como pendentes.
- As contagens do registro de buscas e da triagem são reconciliáveis.
- Nenhum estudo é considerado incluído apenas com base na relevância aparente do título.

**Commit:** `docs(screening): document reference screening`

### Etapa 5 — Avaliar os textos completos e fechar a seleção de fontes

**Contexto:** determinar quais estudos e demais fontes realmente podem sustentar o TCC, distinguindo referências
localizadas de materiais integralmente acessados e avaliados.

**Objetivo verificável:** produzir a lista de fontes incluídas, com situação de acesso, avaliação de elegibilidade,
justificativa e classificação conforme sua finalidade na pesquisa.

**Arquivos envolvidos**

- **Consultar/anexar:** `06_PROTOCOLO_REVISAO.md`, `07_REGISTRO_BUSCAS.md`, `08_TRIAGEM_REFERENCIAS.md` e os textos
  completos efetivamente obtidos dos estudos candidatos.
- **Modificar:** `08_TRIAGEM_REFERENCIAS.md`, somente para registrar decisões de elegibilidade após a avaliação dos
  textos completos.
- **Criar:** `09_REFERENCIAS_INCLUIDAS.md`.

**Escopo fechado:** avaliar elegibilidade, disponibilidade, pertinência, qualidade e limitações das fontes, conforme
aplicável ao método escolhido. Distinguir os estudos incluídos na revisão das fontes complementares usadas para
contextualização clínica, epidemiológica, profissional ou regulatória.

Registrar, quando aplicável, os textos completos não obtidos, as fontes excluídas após leitura integral e os respectivos
motivos. Não iniciar a redação dos capítulos.

**Critérios de conclusão:**

- Cada fonte selecionada possui identificação bibliográfica rastreável e decisão justificada.
- As fontes estão classificadas de acordo com sua função no trabalho e com o método adotado.
- As exclusões realizadas após a leitura integral estão documentadas, quando aplicáveis.
- Estudos não acessados integralmente estão identificados como tais e não são tratados como se tivessem sido lidos por
  completo.
- O número e a identidade das fontes incluídas são compatíveis com os registros de busca e triagem.
- As limitações de acesso que afetem as conclusões da revisão estão registradas.

**Commit:** `docs(literature): document selected sources`

### Etapa 6 — Criar e preencher a matriz de evidências clínicas

**Contexto:** organizar o conhecimento sobre menopausa e terapia hormonal, especialmente benefícios, riscos, indicações,
contraindicações, formulações, vias de administração e individualização do tratamento.

**Objetivo verificável:** preencher a matriz com os achados clínicos das fontes selecionadas, suas limitações e a
contribuição de cada fonte para a pesquisa.

**Arquivos envolvidos**

- **Consultar/anexar:** `09_REFERENCIAS_INCLUIDAS.md` e os textos completos das fontes clínicas selecionadas, sobretudo
  o consenso da SOBRAC, as recomendações da IMS, a diretriz NICE, o posicionamento da The Menopause Society e a revisão
  sobre vias oral e transdérmica, quando efetivamente incluídos.
- **Modificar:** nenhum.
- **Criar:** `10_MATRIZ_EVIDENCIAS.md`.

**Escopo fechado:** registrar, conforme aplicável ao tipo de fonte, objetivo, método, população, resultados ou
recomendações, limitações, relevância para a pesquisa e localização das informações no documento original. Nesta etapa,
preencher a matriz apenas com o eixo clínico da terapia hormonal.

Não forçar o preenchimento de campos que não se aplicam a diretrizes, consensos ou outros documentos de natureza
diferente dos estudos primários.

**Critérios de conclusão:**

- Cada afirmação extraída está vinculada à respectiva fonte.
- As informações relevantes possuem localização verificável na fonte original, quando disponível.
- Resultados, recomendações e conclusões são diferenciados conforme a natureza do documento.
- Dados não encontrados ou não verificáveis permanecem identificados como pendentes.
- Não são produzidas extrapolações clínicas sem sustentação documental.

**Commit:** `docs(evidence): create clinical evidence matrix`

### Etapa 7 — Consolidar as evidências sobre acompanhamento farmacêutico

**Contexto:** avaliar o que a literatura demonstra especificamente sobre o cuidado farmacêutico na menopausa e o que
pode ser fundamentado apenas em estudos gerais de serviços farmacêuticos.

**Objetivo verificável:** incorporar à matriz as evidências diretas e indiretas sobre o acompanhamento farmacêutico,
identificando claramente seus diferentes níveis de aplicabilidade.

**Arquivos envolvidos**

- **Consultar/anexar:** `09_REFERENCIAS_INCLUIDAS.md`, `10_MATRIZ_EVIDENCIAS.md` e os textos completos disponíveis de
  Chow et al. (2024), Branvold e Barner, Craske et al. (2024) e das demais fontes farmacêuticas efetivamente
  selecionadas.
- **Modificar:** `10_MATRIZ_EVIDENCIAS.md`.
- **Criar:** nenhum.

**Escopo fechado:** registrar resultados sobre consultas farmacêuticas, revisão da farmacoterapia, educação em saúde,
adesão, identificação de problemas relacionados a medicamentos e outros desfechos realmente avaliados pelos estudos.

Distinguir explicitamente resultados observados em mulheres na menopausa de resultados obtidos em outras populações ou
contextos de cuidado farmacêutico.

**Critérios de conclusão:**

- A matriz distingue evidências específicas da menopausa e evidências gerais sobre cuidado farmacêutico.
- O desenho e o contexto dos estudos estão identificados de maneira suficiente para avaliar sua aplicabilidade.
- As inferências que ainda não possuem demonstração direta estão explicitadas como inferências, não como resultados
  comprovados.
- Nenhum benefício é atribuído ao acompanhamento farmacêutico sem sustentação nas fontes avaliadas.

**Commit:** `docs(evidence): add pharmacist care evidence`

### Etapa 8 — Consolidar o contexto brasileiro e as fontes regulatórias

**Contexto:** contextualizar a pesquisa no Brasil, incluindo epidemiologia, uso racional de medicamentos, atribuições
profissionais e orientações institucionais relevantes.

**Objetivo verificável:** incorporar à matriz as informações verificadas nas fontes brasileiras e institucionais
pertinentes.

**Arquivos envolvidos**

- **Consultar/anexar:** `09_REFERENCIAS_INCLUIDAS.md`, `10_MATRIZ_EVIDENCIAS.md` e os documentos selecionados, como a
  Nota Técnica Conjunta nº 72/2026, a Resolução CFF nº 585/2013, Pompei et al. (2022) e Arrais et al. (2016), desde que
  sua identidade, pertinência e inclusão tenham sido verificadas.
- **Modificar:** `10_MATRIZ_EVIDENCIAS.md`.
- **Criar:** nenhum.

**Escopo fechado:** registrar as informações efetivamente sustentadas pelos documentos. Não atribuir a uma população
específica resultados obtidos em estudos gerais nem apresentar documentos regulatórios como ensaios de eficácia clínica.

**Critérios de conclusão:**

- As evidências nacionais, clínicas, regulatórias e epidemiológicas estão separadas.
- As informações regulatórias são descritas de acordo com o conteúdo e o alcance dos documentos consultados.
- As limitações e a aplicabilidade de cada fonte estão registradas.
- Os dados epidemiológicos possuem fonte e contexto identificáveis.
- Não são atribuídos a estudos resultados ou características que não tenham sido verificados.

**Commit:** `docs(evidence): consolidate Brazilian evidence`

### Etapa 9 — Finalizar a metodologia executada

**Contexto:** transformar o protocolo preliminar em uma descrição fiel do processo realmente conduzido, com base nos
registros da busca, da seleção e da extração de evidências.

**Objetivo verificável:** produzir a metodologia definitiva, incluindo modalidade de revisão, fontes consultadas,
estratégias, critérios, processo de triagem, extração, síntese e contagens reais aplicáveis.

**Arquivos envolvidos**

- **Consultar/anexar:** `05_ESTRUTURA_TCC.md`, `06_PROTOCOLO_REVISAO.md`, `07_REGISTRO_BUSCAS.md`,
  `08_TRIAGEM_REFERENCIAS.md`, `09_REFERENCIAS_INCLUIDAS.md` e `10_MATRIZ_EVIDENCIAS.md`.
- **Modificar:** nenhum.
- **Criar:** `11_METODOLOGIA.md`.

**Escopo fechado:** documentar o método efetivamente executado, sem alterar artificialmente o processo para que pareça
mais rigoroso ou abrangente do que foi. Diferenciar os procedimentos previstos no protocolo dos procedimentos realmente
realizados e justificar eventuais desvios.

**Critérios de conclusão:**

- A descrição metodológica corresponde aos registros das buscas e da seleção.
- As contagens são reconciliáveis entre os documentos.
- O processo de extração e síntese corresponde às atividades realmente realizadas.
- Os desvios em relação ao protocolo estão identificados.
- Não há etapas fictícias, dados reconstruídos sem fundamento ou critérios apresentados retrospectivamente como se
  tivessem sido previamente definidos.

**Commit:** `docs(methodology): document review methodology`

### Etapa 10 — Elaborar o mapa de evidências por seção

**Contexto:** antes da redação dos capítulos, definir quais informações sustentam cada parte do TCC, evitando repetições
e afirmações sem suporte.

**Objetivo verificável:** criar um mapa que relacione seções, argumentos principais, fontes, limitações e lacunas
relevantes.

**Arquivos envolvidos**

- **Consultar/anexar:** `05_ESTRUTURA_TCC.md`, `09_REFERENCIAS_INCLUIDAS.md`, `10_MATRIZ_EVIDENCIAS.md` e
  `11_METODOLOGIA.md`.
- **Modificar:** nenhum.
- **Criar:** `12_MAPA_EVIDENCIAS_POR_SECAO.md`.

**Escopo fechado:** organizar os argumentos e suas fontes por seção, indicando onde utilizar evidências clínicas,
evidências específicas da atuação farmacêutica e fontes de contextualização brasileira. Não redigir ainda os capítulos.

**Critérios de conclusão:**

- Cada eixo argumentativo possui fontes identificadas.
- As limitações relevantes das fontes estão associadas aos argumentos que elas sustentam.
- As lacunas importantes estão explicitadas.
- O mapa está alinhado à estrutura institucional e à metodologia executada.
- Não há conclusões antecipadas sem sustentação suficiente.

**Commit:** `docs(evidence): map evidence to TCC sections`

### Etapa 11 — Redigir a introdução, a justificativa e os objetivos

**Contexto:** com a estrutura, a metodologia e as evidências organizadas, iniciar a redação acadêmica.

**Objetivo verificável:** produzir os três elementos textuais iniciais, coerentes entre si e fundamentados nas fontes
selecionadas.

**Arquivos envolvidos**

- **Consultar/anexar:** `05_ESTRUTURA_TCC.md`, `10_MATRIZ_EVIDENCIAS.md`, `11_METODOLOGIA.md` e
  `12_MAPA_EVIDENCIAS_POR_SECAO.md`.
- **Modificar:** nenhum.
- **Criar:** `13_INTRODUCAO.md`, `14_JUSTIFICATIVA.md` e `15_OBJETIVOS.md`.

**Escopo fechado:** contextualizar o problema de pesquisa, justificar a relevância do estudo e formular o objetivo geral
e os objetivos específicos. Não escrever resultados ou discussão antecipadamente.

**Critérios de conclusão:**

- A introdução contextualiza o tema, delimita o problema e apresenta a pergunta de pesquisa.
- A justificativa demonstra a relevância acadêmica, profissional e social, conforme as evidências disponíveis.
- O objetivo geral responde ao problema delimitado.
- Os objetivos específicos são claros, exequíveis e compatíveis com a metodologia.
- Não há afirmações relevantes sem suporte bibliográfico.

**Commit:** `docs(tcc): draft introduction and objectives`

### Etapa 12 — Redigir os resultados da revisão

**Contexto:** apresentar os achados da literatura selecionada sem confundir a descrição dos resultados com sua
interpretação crítica.

**Objetivo verificável:** produzir uma seção de resultados organizada por eixos temáticos e coerente com a matriz de
evidências, a seleção de fontes e a metodologia executada.

**Arquivos envolvidos**

- **Consultar/anexar:** `09_REFERENCIAS_INCLUIDAS.md`, `10_MATRIZ_EVIDENCIAS.md`, `11_METODOLOGIA.md` e
  `12_MAPA_EVIDENCIAS_POR_SECAO.md`.
- **Modificar:** nenhum.
- **Criar:** `16_RESULTADOS.md`.

**Escopo fechado:** apresentar as características das fontes incluídas e seus principais achados, agrupados segundo os
eixos temáticos definidos. Incorporar limitações pertinentes. Não introduzir referências que não tenham sido avaliadas e
classificadas nas etapas anteriores.

**Critérios de conclusão:**

- Os resultados são rastreáveis às fontes incluídas.
- A apresentação corresponde ao processo de seleção descrito na metodologia.
- Os eixos temáticos respondem aos objetivos da pesquisa.
- Achados clínicos e achados específicos sobre acompanhamento farmacêutico permanecem distinguíveis.
- Não há interpretação crítica extensa apresentada como se fosse apenas descrição de resultados.

**Commit:** `docs(results): write literature review results`

### Etapa 13 — Redigir a discussão

**Contexto:** interpretar criticamente os resultados e responder à pergunta de pesquisa sem extrapolar as evidências.

**Objetivo verificável:** produzir uma discussão que relacione a segurança e a efetividade da terapia hormonal às
contribuições possíveis e às limitações demonstradas do acompanhamento farmacêutico.

**Arquivos envolvidos**

- **Consultar/anexar:** `10_MATRIZ_EVIDENCIAS.md`, `12_MAPA_EVIDENCIAS_POR_SECAO.md`, `15_OBJETIVOS.md` e
  `16_RESULTADOS.md`.
- **Modificar:** nenhum.
- **Criar:** `17_DISCUSSAO.md`.

**Escopo fechado:** discutir os achados, convergências, divergências, limitações e implicações para a prática
farmacêutica. Relacionar as evidências à pergunta e aos objetivos da pesquisa. Não apresentar opiniões como resultados
científicos nem tratar evidências indiretas como demonstrações específicas de eficácia na menopausa.

**Critérios de conclusão:**

- A discussão responde aos objetivos da pesquisa.
- Evidências diretas, evidências indiretas e inferências estão claramente diferenciadas.
- As limitações dos estudos e do próprio processo de revisão são consideradas.
- As implicações profissionais decorrem das fontes avaliadas e não ultrapassam seu alcance.
- Não são atribuídos ao farmacêutico resultados que não tenham sido efetivamente investigados.

**Commit:** `docs(discussion): write critical discussion`

### Etapa 14 — Redigir a conclusão

**Contexto:** sintetizar a resposta obtida na revisão sem introduzir dados, argumentos ou fontes novos.

**Objetivo verificável:** produzir uma conclusão alinhada à pergunta de pesquisa, aos objetivos, aos resultados e à
discussão.

**Arquivos envolvidos**

- **Consultar/anexar:** `13_INTRODUCAO.md`, `14_JUSTIFICATIVA.md`, `15_OBJETIVOS.md`, `16_RESULTADOS.md` e
  `17_DISCUSSAO.md`.
- **Modificar:** nenhum.
- **Criar:** `18_CONCLUSAO.md`.

**Escopo fechado:** sintetizar os achados, responder diretamente à pergunta de pesquisa, apontar as limitações centrais
e registrar implicações ou necessidades de investigação futura justificadas pelo trabalho.

**Critérios de conclusão:**

- A conclusão responde à pergunta de pesquisa.
- Todos os objetivos são retomados de maneira coerente.
- As afirmações respeitam a força e as limitações das evidências disponíveis.
- Não são introduzidos resultados ou fontes novos.
- As implicações para o acompanhamento farmacêutico são proporcionais ao que a revisão permite afirmar.

**Commit:** `docs(tcc): write TCC conclusion`

### Etapa 15 — Elaborar o resumo e o abstract

**Contexto:** sintetizar o trabalho completo depois da consolidação dos resultados e da conclusão.

**Objetivo verificável:** produzir as versões em português e inglês de acordo com as exigências institucionais.

**Arquivos envolvidos**

- **Consultar/anexar:** `11_METODOLOGIA.md`, `13_INTRODUCAO.md`, `15_OBJETIVOS.md`, `16_RESULTADOS.md`,
  `17_DISCUSSAO.md` e `18_CONCLUSAO.md`.
- **Modificar:** nenhum.
- **Criar:** `19_RESUMO_ABSTRACT.md`.

**Escopo fechado:** elaborar resumo, abstract e palavras-chave equivalentes. Observar os limites de extensão, a
estrutura e os requisitos linguísticos que a instituição efetivamente exigir.

**Critérios de conclusão:**

- Ambos representam fielmente o trabalho desenvolvido.
- Objetivos, método, resultados e conclusão estão alinhados ao conteúdo integral.
- Não há resultados, conclusões ou informações metodológicas inexistentes.
- As versões em português e inglês são equivalentes quanto ao conteúdo científico.
- Os requisitos institucionais de extensão e apresentação estão documentados e atendidos.

**Commit:** `docs(tcc): add abstract and keywords`

### Etapa 16 — Consolidar e conferir as referências finais

**Contexto:** garantir que todas as citações do trabalho correspondam às fontes utilizadas e que os dados bibliográficos
estejam corretos.

**Objetivo verificável:** produzir uma lista final de referências com metadados e formatação conferidos de acordo com as
orientações institucionais.

**Arquivos envolvidos**

- **Consultar/anexar:** todos os capítulos e componentes textuais redigidos até esta etapa, incluindo
  `13_INTRODUCAO.md`, `14_JUSTIFICATIVA.md`, `15_OBJETIVOS.md`, `16_RESULTADOS.md`, `17_DISCUSSAO.md`,
  `18_CONCLUSAO.md`, `19_RESUMO_ABSTRACT.md`, além de `03_INDICE_BIBLIOGRAFICO_AUDITADO.md` e
  `09_REFERENCIAS_INCLUIDAS.md`.
- **Modificar:** nenhum.
- **Criar:** `20_REFERENCIAS_FINAIS.md`.

**Escopo fechado:** verificar correspondência entre citações e referências, duplicatas, autoria, títulos, ano,
periódico, DOI, URL e demais dados disponíveis. Não incluir fontes não utilizadas apenas para aumentar a bibliografia.
Não preencher metadados por suposição.

**Critérios de conclusão:**

- Todas as citações bibliográficas dos textos produzidos correspondem a referências rastreáveis.
- As referências utilizadas estão listadas e as não utilizadas não foram incluídas artificialmente.
- Duplicatas e inconsistências foram identificadas e corrigidas quando possível.
- Dados não confirmados permanecem explicitamente identificados como pendentes.
- A formatação atende às orientações institucionais disponíveis.

**Commit:** `docs(references): reconcile citations and references`

### Etapa 17 — Preparar os elementos institucionais ainda não produzidos

**Contexto:** comparar a estrutura institucional aprovada com os documentos já elaborados e identificar elementos
obrigatórios que ainda não possuem conteúdo ou arquivo próprio.

**Objetivo verificável:** produzir os elementos institucionais ausentes que possam ser preparados com as informações
disponíveis e registrar os elementos que dependem da consolidação ou de dados ainda não fornecidos.

**Arquivos envolvidos**

- **Consultar/anexar:** `05_ESTRUTURA_TCC.md`, `01_REGRAS_INSTITUCIONAIS_TRANSCRICAO.md`, `02_MODELO_TCC_TRANSCRICAO.md`
  e os arquivos finais produzidos até a Etapa 16, de `11_METODOLOGIA.md` a `20_REFERENCIAS_FINAIS.md`.
- **Modificar:** nenhum.
- **Criar:** `21_ELEMENTOS_INSTITUCIONAIS.md`.

**Escopo fechado:** preparar os componentes pré-textuais, pós-textuais ou outros elementos exigidos pela instituição que
ainda não estejam contemplados nos arquivos existentes. A necessidade e a forma de cada componente deverão ser
determinadas pela estrutura aprovada, sem assumir que todos os modelos institucionais exigem os mesmos elementos.

Quando dependerem de informações pessoais, dados acadêmicos, aprovação institucional ou outros dados indisponíveis, os
componentes deverão conter pendências explicitamente identificadas, sem dados fictícios.

Elementos cuja elaboração dependa da estrutura final já consolidada, como sumário definitivo ou listas derivadas do
conteúdo completo, deverão ser identificados para finalização na auditoria final.

**Critérios de conclusão:**

- Todos os elementos institucionais que podem ser preparados nesta etapa estão documentados.
- Os elementos ausentes e as dependências restantes estão explicitamente identificados.
- Dados não fornecidos não foram inventados.
- Não há duplicação desnecessária de elementos já produzidos em outros arquivos.
- O conteúdo está alinhado à estrutura institucional aprovada.

**Commit:** `docs(tcc): prepare institutional elements`

### Etapa 18 — Consolidar o TCC em um único documento Markdown

**Contexto:** reunir os capítulos e os demais elementos desenvolvidos em uma versão integral, respeitando a estrutura
institucional aprovada.

**Objetivo verificável:** gerar um documento único que possa servir como fonte principal para revisão final e futura
conversão, sem eliminar a rastreabilidade dos arquivos de origem.

**Arquivos envolvidos**

- **Consultar/anexar:** `05_ESTRUTURA_TCC.md`, `01_REGRAS_INSTITUCIONAIS_TRANSCRICAO.md`, `02_MODELO_TCC_TRANSCRICAO.md`
  e todos os arquivos destinados ao TCC, incluindo `11_METODOLOGIA.md`, `12_MAPA_EVIDENCIAS_POR_SECAO.md`,
  `13_INTRODUCAO.md`, `14_JUSTIFICATIVA.md`, `15_OBJETIVOS.md`, `16_RESULTADOS.md`, `17_DISCUSSAO.md`,
  `18_CONCLUSAO.md`, `19_RESUMO_ABSTRACT.md`, `20_REFERENCIAS_FINAIS.md` e `21_ELEMENTOS_INSTITUCIONAIS.md`.
- **Modificar:** nenhum dos arquivos de origem.
- **Criar:** `22_TCC_CONSOLIDADO.md`.

**Escopo fechado:** combinar os conteúdos destinados ao TCC, ajustar a hierarquia de títulos, organizar as seções na
ordem institucional, eliminar duplicações decorrentes da consolidação e preservar citações, referências e informações
pendentes devidamente identificadas.

O mapa de evidências, os registros de busca, o protocolo e outros documentos internos de trabalho não devem ser
inseridos automaticamente no TCC. Só deverão integrar o documento final se a estrutura institucional ou a metodologia
exigir expressamente sua apresentação como apêndice ou anexo.

**Critérios de conclusão:**

- O documento contém os capítulos e elementos disponíveis na ordem exigida.
- Os componentes obrigatórios ainda pendentes estão claramente identificados.
- A consolidação não omite conteúdo aprovado nem duplica seções.
- As citações e referências permanecem sincronizadas.
- O documento consolidado corresponde aos arquivos de origem, ressalvadas apenas correções editoriais de integração.
- Nenhum elemento é apresentado como concluído quando ainda depende de informação não fornecida.

**Commit:** `docs(tcc): consolidate complete TCC`

### Etapa 19 — Auditar o TCC consolidado e corrigir as pendências finais

**Contexto:** verificar o documento integral depois da consolidação, procurando inconsistências que não seriam
detectadas pela simples revisão isolada dos arquivos de origem.

**Objetivo verificável:** produzir um registro de auditoria final e corrigir as inconsistências identificadas,
garantindo que o documento consolidado corresponda à estrutura institucional e à evidência científica disponível.

**Arquivos envolvidos**

- **Consultar/anexar:** `22_TCC_CONSOLIDADO.md`, `05_ESTRUTURA_TCC.md`, `01_REGRAS_INSTITUCIONAIS_TRANSCRICAO.md`,
  `02_MODELO_TCC_TRANSCRICAO.md`, `06_PROTOCOLO_REVISAO.md`, `07_REGISTRO_BUSCAS.md`, `08_TRIAGEM_REFERENCIAS.md`,
  `09_REFERENCIAS_INCLUIDAS.md`, `10_MATRIZ_EVIDENCIAS.md`, `11_METODOLOGIA.md`, `12_MAPA_EVIDENCIAS_POR_SECAO.md`,
  `13_INTRODUCAO.md`, `14_JUSTIFICATIVA.md`, `15_OBJETIVOS.md`, `16_RESULTADOS.md`, `17_DISCUSSAO.md`,
  `18_CONCLUSAO.md`, `19_RESUMO_ABSTRACT.md`, `20_REFERENCIAS_FINAIS.md` e `21_ELEMENTOS_INSTITUCIONAIS.md`.
- **Modificar:** `22_TCC_CONSOLIDADO.md` para correções identificadas; `21_ELEMENTOS_INSTITUCIONAIS.md` quando forem
  necessárias correções ou finalização de elementos derivados do documento consolidado; os arquivos de origem
  correspondentes, de `11_METODOLOGIA.md` a `20_REFERENCIAS_FINAIS.md`, somente quando uma correção substantiva exigir
  atualização do conteúdo original.
- **Criar:** `23_AUDITORIA_FINAL.md`.

**Escopo fechado:** auditar o documento completo e, quando possível, corrigir as inconsistências encontradas. A
auditoria deverá verificar:

- Conformidade com a estrutura e as exigências institucionais.
- Ordem e hierarquia dos títulos e das seções.
- Presença dos elementos obrigatórios.
- Coerência entre pergunta de pesquisa, justificativa, objetivos, metodologia, resultados, discussão e conclusão.
- Correspondência entre o método declarado e os registros das buscas, da triagem e da seleção.
- Rastreabilidade das afirmações relevantes às fontes utilizadas.
- Distinção entre evidências clínicas, evidências específicas da atuação farmacêutica e inferências indiretas.
- Correspondência entre citações no texto e referências finais.
- Duplicações, lacunas de conteúdo, inconsistências terminológicas e problemas de organização.
- Fidelidade do resumo e do abstract ao trabalho completo.
- Finalização dos elementos que dependem da estrutura integral, como sumário e listas obrigatórias, quando aplicáveis.
- Permanência explícita de informações que não puderam ser verificadas ou que dependem de dados externos.

Correções substantivas deverão ser aplicadas também aos arquivos de origem correspondentes, para evitar que o documento
consolidado passe a divergir dos capítulos individuais. Depois, a consolidação deverá ser atualizada com base nas
versões corrigidas.

**Critérios de conclusão:**

- Todas as verificações previstas na auditoria foram executadas e registradas.
- As inconsistências identificadas foram corrigidas ou classificadas como pendências justificadas.
- O documento consolidado permanece sincronizado com os arquivos de origem.
- As citações e referências são rastreáveis e consistentes.
- A estrutura final atende aos requisitos institucionais identificados nos materiais disponíveis.
- Não existem problemas relevantes de coerência científica ou metodológica sem registro explícito.
- Caso permaneçam pendências impeditivas, a etapa deverá ser declarada incompleta, sem afirmar que o TCC está
  integralmente concluído.

**Commit:** `docs(tcc): audit final TCC`

## 4. Regra para a execução de cada etapa por outra LLM

Quando o cronograma for usado para solicitar a implementação de uma etapa específica, a LLM deverá seguir estas regras:

1. Conferir a lista de arquivos necessários e solicitar os que estiverem ausentes.
2. Utilizar os arquivos efetivamente fornecidos como base para a execução. Não presumir que arquivos mencionados no
   cronograma estejam disponíveis.
3. Modificar ou criar apenas os arquivos previstos para a etapa solicitada.
4. Entregar o conteúdo completo de todos os novos arquivos e de todos os arquivos alterados, não apenas fragmentos ou
   instruções genéricas.
5. Apontar limitações, fontes não acessadas, informações não verificadas e pendências que impeçam a conclusão.
6. Declarar explicitamente se a etapa foi concluída e se todos os critérios de conclusão foram atendidos.
7. Fornecer o commit específico da etapa somente se ela tiver sido concluída.
8. Não fornecer o texto de commit consolidado para `amend` sem solicitação expressa.
9. Não iniciar a etapa seguinte automaticamente. A execução deverá permanecer limitada à etapa solicitada.
10. Se os materiais disponíveis forem insuficientes para uma decisão metodológica, científica ou institucional
    essencial, não inventar uma solução. Registrar a limitação e interromper a parte da execução que dependa dessa
    decisão.
11. Manter a consistência entre os documentos produzidos em etapas anteriores e os arquivos modificados na etapa atual.
12. Não declarar uma etapa concluída apenas porque um arquivo foi criado. A conclusão depende do atendimento efetivo aos
    critérios definidos.
13. Na auditoria final, diferenciar correções executadas, pendências impeditivas e limitações que não podem ser
    resolvidas a partir dos materiais disponíveis.

## 5. Estado inicial e próxima execução

A estrutura institucional e o índice bibliográfico preliminar já existem, mas precisam ser anexados quando forem
necessários à execução. Os arquivos de trabalho deverão ser avaliados a partir de seus conteúdos efetivamente
fornecidos.

A próxima execução é a **Etapa 1 — Consolidar a estrutura institucional do TCC**.

Para executá-la, deverão ser fornecidos:

- `00_LEIA-ME.md`
- `01_REGRAS_INSTITUCIONAIS_TRANSCRICAO.md`
- `02_MODELO_TCC_TRANSCRICAO.md`
- `04_MAPA_REGRAS_MODELO_PROXIMOS_PASSOS.md`

O resultado esperado é a criação de `05_ESTRUTURA_TCC.md`, sem redigir os capítulos e sem avançar para a etapa seguinte
antes de atender aos critérios de conclusão.

O cronograma termina somente depois da auditoria final do TCC consolidado. A conclusão do processo não implica conversão
automática para DOCX ou PDF, que permanece fora do escopo destas etapas.
