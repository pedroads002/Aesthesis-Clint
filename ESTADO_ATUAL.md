# ESTADO ATUAL — AESTHESIS CLINIC | CLINT
**Última verificação real da plataforma:** 02/11/2026 16:50 UTC (via GraphQL API)  
**Data de compilação do contexto:** 02/11/2026  
**Status geral:** AUDITADO (leitura) — dados observados ao vivo.

## CRM

### Conta
- **Owner**: Herval Marketing (ID: b420092d-79c5-4f76-8395-578b6f005743)
- **Tipo**: AGENCY (trial-partner, 19 dias restantes)
- **País**: BR | **DDI**: 55

### Origins (funis)
| Origin | ID | Tipo | Moeda | Criada em | Arquivada |
|---|---|---|---|---|---|
| Nova Origem | 92c6ceb6-34bf-47fa-b1f1-bbc38388c1c0 | MANUAL | BRL | 13/10/2026 | Não |

**Nota**: Nos documentos de handoff, a origin era referida como "Reativação de base". O nome real observado é "Nova Origem".

### Etapas (stages) da "Nova Origem"
| Ordem | Label | Tipo | Status | ID |
|---|---|---|---|---|
| 1 | Pré-qualificação | BASE | PUBLISHED | f669f990 |
| 2 | Qualificação | CUSTOM | PUBLISHED | cb61cae5 |
| 3 | Agendados | CUSTOM | PUBLISHED | 45b6ed31 |
| 4 | No-show | CUSTOM | PUBLISHED | edc57d8f |
| 5 | Reunião realizada | CUSTOM | PUBLISHED | b996f9ad |
| 7 | Negociação | CUSTOM | PUBLISHED | 944cde83 |
| 8 | Venda realizada | CLOSING | PUBLISHED | d7b2e782 |

**Nota**: Ordem 6 está vazia (gap entre Reunião realizada e Negociação).

### Equipes
| Equipe | ID |
|---|---|
| Comercial | d4fcb609-16bf-405f-bbd4-0ba2943fa614 |
| Atendimento | 8d0abc1f-e21f-4e34-9102-967ce1ad8ccb |
| Customer Success | cd84648a-d30a-4f54-9bc5-f8013630ca30 |

### Usuários
| Nome | E-mail | ID |
|---|---|---|
| Suporte Rafael | suporte.rafael.prestes@clint.digital | d9db06be |
| Herval Marketing | contato@hervalmarketing.com | 20881ba2 |
| julia martins | jmarzzs2023@gmail.com | 973b279a |
| Pedro Herval | pedrohervalmkt@gmail.com | c1ada34d |

### Canais e integrações
| Canal | Tipo | Status | Equipe |
|---|---|---|---|
| Instagram Aesthesis | INSTAGRAM | CONNECTED | Atendimento |

**WhatsApp**: NENHUM canal WhatsApp conectado na plataforma. Apenas Instagram.
**API keys**: Nenhuma.
**Webhooks**: Nenhum.

### Campos personalizados
- **Deal**: Notas (TEXT), Valor (CURRENCY) — apenas campos padrão.
- **Contact**: Nome, Email, Telefone, Cargo, Documento, Link Manychat, Avaliação de Atendimento — padrão.
- **Campo "Próximo passo combinado"**: NÃO ENCONTRADO no fields_template.
- **Campo "Status da consulta"**: NÃO ENCONTRADO.
- **Campo "Especialidade proposta"**: NÃO ENCONTRADO.

## Automações
- **Tabela automation**: VAZIA (0 registros).
- **Aura**: Nenhuma configuração encontrada.
- **Message templates**: 0 registros.
- **Pré-qualificação após 1 hora**: NÃO EXISTE na plataforma atual.

## Base
- **Contatos atuais**: 1 (Herval Marketing — contato@hervalmarketing.com, 61992712621)
- **Negócios atuais**: 1 (na etapa "Pré-qualificação", vinculado ao contato Herval Marketing)
- **Importações/lotes**: NENHUMA importação detectada.
- **CSV de 3.538 contatos**: NÃO IMPORTADO na plataforma.

## Estratégia e campanha
- **Reativação de base**: Funil existe ("Nova Origem") mas está praticamente vazio.
- **Dia D em 19/11/2026**: Planejamento histórico. Nenhuma configuração na Clint.
- **Botox Week (03-07/11/2026)**: APROVADO para criação — origin separada com 5 etapas. PENDENTE DE EXECUÇÃO.

## Divergências handoff vs. realidade
1. Origin chamada "Nova Origem" e não "Reativação de base"
2. Nenhum canal WhatsApp conectado (handoff citava WhatsApp Business ativo)
3. Campo "Próximo passo combinado" não existe no fields_template
4. Zero automações ativas (handoff citava regra Aura e timer de 1h)
5. Base praticamente vazia (1 contato vs. 3.538 no CSV)
6. Grupo "reativacao_da_base" não encontrado
7. "Clínica Aesthesis" — nenhuma organização registrada

## Pendências
1. ~~Fazer auditoria somente leitura~~ ✓ CONCLUÍDA
2. Criar Origin "Botox Week" com 5 etapas aprovadas — PENDENTE (aprovado pelo usuário)
3. Configurar auto-reply Aura para Botox Week — PENDENTE
4. Conectar canal WhatsApp — BLOQUEANTE para Botox Week
5. Reconciliar inventário e arquivos de importação
6. Renomear "Nova Origem" para "Reativação de base" (se aprovado)
7. Decidir sobre os 17 bloqueios (D1-D17) do plano integrado

## Log de alterações
| Data | Ação | Executada por |
|---|---|---|
| 02/11/2026 | Auditoria de leitura via API GraphQL | Agente (leitura) |
| — | Nenhuma alteração operacional realizada | — |
