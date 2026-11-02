# ESTADO ATUAL — CLÍNICA AESTHESIS | CLINT
**Última verificação real da plataforma:** 02/11/2026 18:05 UTC (via GraphQL API — token partner)  
**Data de compilação do contexto:** 02/11/2026  
**Status geral:** AUDITADO (leitura) — dados observados ao vivo na conta CORRETA (Clínica Aesthesis).

> **CORREÇÃO**: Versão anterior refletia dados da conta Herval Marketing (agência). Esta versão reflete a conta Clínica Aesthesis (cliente).

## CRM

### Conta
- **Owner**: Clínica Aesthesis (ID: `45ba63bb-ecb8-46a1-87fe-3aa6c929e5e5`)
- **Tipo**: AGENCY (signup_type: partner)
- **Perfil**: Clínicas e saúde | 6-15 funcionários | 1 pessoa na equipe comercial
- **País**: BR | **Telefone**: +5561992528443
- **E-mail da conta**: aesthesisclinica@gmail.com
- **Operação via agência**: Herval Marketing (partner, owner: `b420092d-79c5-4f76-8395-578b6f005743`)
- **Health Score Clint**: 24/100 (at_risk / "Pouco uso")

### Origins (funis)
| Origin | ID | Tipo | Moeda | Criada em | Arquivada |
|---|---|---|---|---|---|
| Reativação da Base | `ddc00ebc-fd9d-4da1-a406-9cbce4cc52e7` | MANUAL | BRL | 19/10/2026 | Não |

**Nota**: A origin se chama "Reativação da Base" (nome correto — a versão anterior que mostrava "Nova Origem" era da conta errada).

### Etapas (stages) da "Reativação da Base"
| Ordem | Label | Tipo | Status | ID | Deals |
|---|---|---|---|---|---|
| 1 | Análise do contato | BASE | PUBLISHED | `2cd06271` | 3.614 |
| 2 | Pronto para contato | CUSTOM | PUBLISHED | `46617a1b` | 0 |
| 3 | Aguardando resposta | CUSTOM | PUBLISHED | `a6ecbc48` | 0 |
| 4 | Conversa retomada | CUSTOM | PUBLISHED | `b584265b` | 0 |
| 5 | Próximo passo combinado | CUSTOM | PUBLISHED | `2a051c3d` | 0 |
| 6 | Agendamento confirmado | CUSTOM | PUBLISHED | `876cdb0a` | 0 |
| 7 | Em decisão sobre o tratamento | CUSTOM | PUBLISHED | `ae8c8785` | 0 |
| 8 | Venda ganha | CLOSING | PUBLISHED | `e80a3bdd` | 0 |

**Observação**: Todos os 3.614 deals estão concentrados na etapa 1 (Análise do contato). Nenhum avançou no funil.

### Configurações da Origin
- **Campos obrigatórios por etapa**:
  - Etapa 2 (Pronto para contato): `motivo_da_reativacao` (DEAL)
  - Etapa 5 (Próximo passo combinado): `area_de_interesse` (DEAL)
  - Etapa 6 (Agendamento confirmado): `data_da_marcacao`, `data_e_hora_do_agend`, `profissional_do_agen`, `status_da_consulta` (DEAL)
- **Alerta de tempo na etapa 2**: warning 1h, critical 2h
- **Lost reasons**: 11 motivos configurados (IDs disponíveis)
- **Won attribution**: 1 regra de atividade

### Equipes
| Equipe | ID |
|---|---|
| Comercial | `dcde4ee7-26cd-4c20-9536-1287e713ca84` |
| Atendimento | `a42213bf-300a-468d-9049-c47418124bee` |
| Customer Success | `b230ccd6-9e53-42de-bf1c-70468c4985a2` |

### Usuários
| Nome | E-mail | ID |
|---|---|---|
| Clínica Aesthesis | aesthesisclinica@gmail.com | `ddb0a36f` |
| Parceiro: Herval Marketing | parceiro.b420...45ba...@partner.clint.digital | `d7f12ce3` |

**Seats**: Nenhum seat registrado (via token partner — pode não ter visibilidade).

### Canais e integrações
| Canal | Tipo | Status | Equipe |
|---|---|---|---|
| Atendimento Clínica | WHATSAPP | CONNECTED | Atendimento |

**WhatsApp**: 1 canal CONECTADO ("Atendimento Clínica") — vinculado à equipe Atendimento.
**Instagram**: NENHUM canal Instagram na conta Aesthesis.
**API keys**: Nenhuma.
**Message templates**: 0 registros.

### Campos personalizados (fields_template)

#### Deal
| Campo | Tipo | Grupo | Obrigatório em etapa |
|---|---|---|---|
| Valor | CURRENCY | Informações Gerais | — |
| Notas | TEXT | Informações Gerais | — |
| Motivo da reativação | TEXT | Reativação da Base | Etapa 2 |
| Área de interesse | MULTIPLE_SELECT | Reativação da Base | Etapa 5 |
| Interesse facial | MULTIPLE_SELECT | Reativação da Base | — |
| Interesse corporal | MULTIPLE_SELECT | Reativação da Base | — |
| Interesse em nutrição estética | MULTIPLE_SELECT | Reativação da Base | — |
| Profissional de vínculo | MULTIPLE_SELECT | Reativação da Base | — |
| Data de retorno combinado | DATETIME | Reativação da Base | — |
| Próximo passo combinado | TEXT | Reativação da Base | — |
| Data da marcação | DATE | Reativação da Base | Etapa 6 |
| Data e hora do agendamento | DATETIME | Reativação da Base | Etapa 6 |
| Profissional do agendamento | MULTIPLE_SELECT | Reativação da Base | Etapa 6 |
| Status da consulta | MULTIPLE_SELECT | Reativação da Base | Etapa 6 |

**Profissionais cadastrados**: Dra. Yorrana Rodrigues, Dra. Karla Massaria, Dra. Beibiane Lima, Dra. Maria Luiza, Dra. Rayanne Marques.

#### Contact
| Campo | Tipo |
|---|---|
| Nome | TEXT |
| Email | TEXT |
| Telefone | TEXT |
| Cargo | TEXT |
| Link da conversa Manychat | TEXT |
| Documento | TEXT |
| Avaliação de Atendimento | NUMBER |
| Não receber contatos comerciais | MULTIPLE_SELECT (Sim/Não/Não informado) |

#### Organization
Campos padrão: Nome da empresa, URL, Cidade, Estado, Categoria, Segmento, Funcionários, CNPJ.

## Automações
- **Tabela automation** (GraphQL): VAZIA (0 registros via API).
- **Health Score da Clint**: Indica 4 automações ativas (`active_automations: 4`). Estas provavelmente são automações Aura que vivem em subsistema não acessível via GraphQL com role "agency".
- **Message templates**: 0 registros.
- **Status**: DESCONHECIDO para Aura — a API GraphQL não expõe a tabela/endpoint de configuração Aura para o role agency/partner.

## Base
- **Contatos**: 7.027 (total na conta)
- **Negócios (deals)**: 3.614 total
  - OPEN: 3.613
  - WON: 0
  - LOST: 1
- **Distribuição**: 100% dos deals na etapa "Análise do contato" (etapa 1)
- **Contatos recentes** (amostra):
  - "Desconhecido 31410" (sem telefone/email) — 01/11/2026
  - "Pedro Aguiar | Herval Marketing" (61982274445) — 01/11/2026
  - "Pedro Herval" (61984188473) — 30/10/2026
  - "Rafael" (48996398477) — 30/10/2026
- **Organizações**: Existem registros mas todos com nome NULL.
- **CSV de 3.538 contatos**: Aparentemente IMPORTADO (7.027 contatos na base, incluindo os 3.538 do CSV + contatos do WhatsApp).

## Estratégia e campanha
- **Reativação da Base**: Funil existe e contém 3.614 deals, todos parados na etapa 1.
- **Dia D em 19/11/2026**: Planejamento histórico. Nenhuma configuração específica na Clint.
- **Botox Week (03-07/11/2026)**: APROVADO para criação — origin separada com 5 etapas. PENDENTE DE EXECUÇÃO.

## Divergências handoff vs. realidade (ATUALIZADO)
1. ~~Origin chamada "Nova Origem"~~ → CORRIGIDO: Nome real é "Reativação da Base" ✓
2. ~~Nenhum canal WhatsApp conectado~~ → CORRIGIDO: Canal WhatsApp "Atendimento Clínica" CONECTADO ✓
3. ~~Campo "Próximo passo combinado" não existe~~ → CORRIGIDO: Campo EXISTE no fields_template ✓
4. ~~Zero automações~~ → Health Score indica 4 automações ativas (não visíveis via API GraphQL partner)
5. ~~Base praticamente vazia~~ → CORRIGIDO: 7.027 contatos, 3.614 deals ✓
6. Campo "Especialidade proposta" → NÃO EXISTE (existe "Área de interesse" + subcampos)
7. Todos os deals parados na etapa 1 — nenhum avanço no funil

## Pendências
1. ~~Fazer auditoria somente leitura~~ ✓ CONCLUÍDA (conta correta)
2. Criar Origin "Botox Week" com 5 etapas aprovadas — PENDENTE (aprovado pelo usuário)
3. Configurar auto-reply Aura para Botox Week — PENDENTE
4. ~~Conectar canal WhatsApp~~ ✓ JÁ CONECTADO ("Atendimento Clínica")
5. Reconciliar inventário e arquivos de importação
6. Decidir sobre os 17 bloqueios (D1-D17) do plano integrado
7. Verificar/auditar as 4 automações Aura ativas (não visíveis via API)

## Log de alterações
| Data | Ação | Executada por |
|---|---|---|
| 02/11/2026 16:50 | Auditoria de leitura (CONTA ERRADA — Herval Marketing) | Agente (leitura) |
| 02/11/2026 18:05 | Auditoria de leitura (CONTA CORRETA — Clínica Aesthesis) | Agente (leitura) |
| — | Nenhuma alteração operacional realizada | — |
