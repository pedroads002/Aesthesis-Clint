# 04 | STATUS, PENDÊNCIAS E ROADMAP

## Regra
Este quadro representa o último contexto histórico disponível, não o estado atual confirmado. Atualizar após auditoria.

## Status conhecidos

| Item | Status histórico | Confiança/limitação |
|---|---|---|
| CRM Clint escolhido | Decisão estabelecida | Alta no histórico |
| Grupo Reativação da Base | Criado/recriado | Validar existência e ID atual |
| Chave `reativacao_da_base` | Registrada como correta | Validar na plataforma |
| Aura de atribuição para Clínica Aesthesis | Aceita/registrada | Execução real precisa de evidência |
| Pré-qualificação após 1h | Observada em teste | Escopo e funcionamento atual desconhecidos |
| Horários comerciais | Informados como confirmados | Validar configuração atual |
| Área de interesse | Corrigida; reportada funcionando | Validar opções e dados |
| Nutrição Estética | Adicionada | Validar cadastro atual |
| Três campos provisórios | Revisão pendente | Verificar antes de alterar |
| Base consolidada | Houve tratamento/importações | Quantidade final desconhecida |
| Importação posterior | Usuário reportou sucesso sem recusas | Arquivo, quantidade e resultado detalhado a reconciliar |
| Estratégia de reativação geral | Direção definida | Confirmar se houve alteração posterior |
| Dia D | Planejamento histórico | Aprovação e execução desconhecidas |

## Pendências prioritárias

### P0 — Auditoria e segurança
1. Acessar somente por meios autorizados e levantar inventário atual.
2. Identificar grupos, etapas, campos, responsáveis, automações e integrações.
3. Mapear IDs e dependências, especialmente após recriação do grupo.
4. Verificar se a pré-qualificação de 1h pode gerar filas, acúmulo ou efeito inesperado.
5. Identificar opt-outs, bloqueios e regras de contato.
6. Preservar evidências/exportações antes de mudanças.

### P1 — Reconciliação da base
1. Coletar todos os arquivos originais, tratados e importados.
2. Montar manifesto dos lotes: nome do arquivo, versão/hash se possível, data, objetivo, linhas, resultado e IDs.
3. Reconciliar contatos e negócios separadamente.
4. Identificar duplicados com regras documentadas e revisão de ambiguidades.
5. Conferir os 3 contatos não contatar e os 7 números para revisão citados no histórico.
6. Apurar totais atuais e registros restantes sem inferência.
7. Não importar nada até aprovação do plano de reconciliação.

### P2 — Processo e CRM
1. Documentar jornada e critérios de passagem.
2. Revisar os três campos provisórios.
3. Confirmar responsáveis e especialidades.
4. Testar automações em escopo seguro, com casos de sucesso e falha.
5. Validar registro de origem, interesse, próxima ação, agendamento, comparecimento e resultado.

### P3 — Campanha e operação
1. Confirmar status e viabilidade do calendário Dia D.
2. Revalidar ofertas, regras, canais, capacidade, orçamento, equipe e aprovações.
3. Validar base elegível e permissões de comunicação.
4. Definir metas e métricas com denominadores.
5. Preparar plano de execução e contingência para aprovação.

## Critério de saída da auditoria
Só considerar a fase concluída quando houver:
- inventário com evidências e data;
- divergências explicitadas;
- totais reconciliados ou limitações descritas;
- riscos e dependências mapeados;
- plano de ação aprovado pelo usuário.

## ESTADO ATUAL
Consultar e atualizar o arquivo separado `ESTADO_ATUAL.md`. Não usar o status histórico deste documento como prova de estado presente.
