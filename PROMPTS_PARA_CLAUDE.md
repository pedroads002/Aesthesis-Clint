# PROMPTS DE EXECUÇÃO PARA CLAUDE — ORDEM RECOMENDADA

Use um prompt por vez. Só avance quando o entregável do anterior estiver concluído e revisado. A primeira etapa é sem alterações.

## PROMPT 1 — Ingestão e compreensão do pacote
Leia `00_LEIA-ME_E_CONTEXTO.md`, `01_ESTRATEGIA-COMERCIAL.md`, `02_ARQUITETURA-CLINT.md`, `03_HISTORICO-DECISOES-E-ALTERACOES.md`, `04_STATUS-PENDENCIAS-E-ROADMAP.md`, `05_REGRAS-DO-AGENTE.md` e `ESTADO_ATUAL.md`.

Não execute ações na Clint. Entregue:
1. Resumo executivo do projeto.
2. Decisões vigentes versus históricas.
3. Fatos, inferências e desconhecidos separados.
4. Contradições/lacunas do pacote.
5. Perguntas estritamente necessárias.
Não invente nem converta estado histórico em atual.

## PROMPT 2 — Auditoria de prontidão e plano de acesso
Determine quais meios autorizados você realmente possui para consultar a Clint e quais dados consegue ler. Não alegue conexão ou acesso sem teste verificável.

Liste:
- capacidades disponíveis e limitações;
- dados acessíveis e não acessíveis;
- exportações/telas/logs que precisam ser fornecidos pelo usuário;
- riscos de segurança e privacidade.

Não solicite senha, token, cookie ou credencial em texto. Não altere nada.

## PROMPT 3 — Auditoria somente leitura da Clint
Com acesso autorizado, realize diagnóstico sem modificar dados ou configurações.

Inventarie:
- grupos, chaves e IDs;
- etapas e ordem;
- campos, tipos, opções e entidades;
- responsáveis/equipes;
- automações, gatilhos, filtros, ações e timers;
- integrações e canais;
- amostra e totais de contatos e negócios, quando disponíveis;
- registros recentes de execução e falha.

Para cada item, registre fonte, data/hora, método e evidência. Diferencie ausência de acesso de ausência do objeto. Não execute teste que crie registros, dispare comunicação ou altere estado. Entregue inventário, discrepâncias e riscos.

## PROMPT 4 — Reconciliação de arquivos e base
Analise todos os arquivos históricos e atuais disponibilizados de origem, preparação e importação.

Primeiro produza apenas diagnóstico:
- manifesto de arquivos e versões;
- cabeçalhos, contagens e chaves;
- identificação de listas de exclusão, opt-outs e números sob revisão;
- comparação entre lotes e estado CRM exportado;
- duplicidades certas e possíveis;
- contatos e negócios contabilizados separadamente;
- linhas sem correspondência e motivo;
- totais reconciliados, método e margem de incerteza.

Não altere a Clint, não importe, não exclua e não envie mensagens. Não elimine ambiguidade por suposição. Se não for possível reconciliar, explicite exatamente os dados faltantes.

## PROMPT 5 — Auditoria das automações
Com base na configuração observada e evidências, mapeie Aura e pré-qualificação de 1 hora.

Descreva:
- gatilho exato e escopo;
- condições;
- ações;
- responsável/atribuição;
- temporização/timezone;
- risco de repetição, fila, disparo em massa ou conflito;
- logs e resultados comprovados;
- cenários não testados.

Não altere automações nem crie registros para testar. Entregue plano de teste controlado, critérios de sucesso e recuperação para aprovação.

## PROMPT 6 — Diagnóstico do processo comercial
Reconstrua o fluxo real a partir da Clint e documentação. Compare com a estratégia e a experiência premium.

Identifique:
- etapas e critérios;
- responsabilidade por etapa;
- SLA e cadências documentados;
- campos essenciais e qualidade de preenchimento;
- passagens para qualificação, agendamento, confirmação, comparecimento, falta e retomada;
- indicadores e lacunas de mensuração.

Não invente cadências ou políticas. Separe situação observada, recomendação e decisão necessária.

## PROMPT 7 — Revalidação Dia D
Reavalie o planejamento histórico para 19/11/2026 sem assumir aprovação ou execução.

Confirme a partir das fontes disponíveis:
- calendário e status de cada marco;
- oferta, elegibilidade e condições aprovadas;
- canais e grupo;
- base elegível e permissões;
- capacidade de atendimento;
- equipe e responsáveis;
- orçamento, metas e indicadores;
- riscos e plano de contingência.

Marcos históricos: tráfego 05/11; convites 13/11; aquecimento 14–16; fechamento 17; valores 18; evento 19, 10h–20h; atendimentos a partir de 23/11. Valores somente no grupo e não melhorar condições foram regras mencionadas no plano, ainda a validar. Não publicar nem disparar. Entregue recomendação e decisões pendentes.

## PROMPT 8 — Plano integrado de retomada
Consolide auditoria, reconciliação, automações, processo comercial e campanha.

Para cada ação, apresente:
- prioridade;
- justificativa;
- pré-requisitos;
- impacto e risco;
- dependências;
- responsável sugerido;
- critério de sucesso;
- necessidade de aprovação;
- reversibilidade.

Separe ações de leitura, ações reversíveis e ações sensíveis. Não execute nenhuma mudança. Aguarde aprovação do usuário.

## PROMPT 9 — Execução controlada de uma tarefa aprovada
Use somente após aprovação específica do plano.

Antes de executar, confirme escopo, registros/IDs, volume, critérios, janela e reversão. Faça primeiro teste controlado, quando aplicável. Pare se os resultados divergirem do esperado.

Depois:
- valide resultado;
- reporte erros e exceções;
- reconcilie contagens;
- atualize `ESTADO_ATUAL.md`;
- acrescente entrada ao histórico, sem sobrescrever registros anteriores.

Autorização para uma tarefa não se estende automaticamente a outras ações.
