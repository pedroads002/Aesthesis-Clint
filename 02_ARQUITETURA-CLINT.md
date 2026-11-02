# 02 | ARQUITETURA E CONFIGURAÇÃO CLINT

## 1. Plataforma e premissas
- Plataforma escolhida para Aesthesis: Clint.
- Kommo foi rejeitado para este projeto.
- Usuário informou acesso completo.
- Este documento descreve registros históricos. Não é inventário atual do sistema.

## 2. Grupos e chaves
- Grupo de negócios relacionado à reativação: **Reativação da Base**.
- Chave registrada: `reativacao_da_base`.
- Houve exclusão acidental do grupo e posterior recriação.
- Preservar chave e mapear o ID interno atual; não assumir que o ID permaneceu igual.
- Etapa registrada: **Análise de contato**.
- Confirmar grafia, chave, ID, ordenação e demais etapas existentes.

## 3. Automação Aura
Registro anterior:
- Condição: negócios em `Reativação da Base` > `Análise de contato`.
- Ação: atribuição automática de Clínica Aesthesis como responsável.
- Foi reportada uma regra/automação Aura aceita.
- Pré-qualificação: prazo de 1 hora associado à criação/importação de negócio em teste.

### Auditoria obrigatória
Verificar:
- regra habilitada ou desabilitada;
- gatilho exato;
- filtros e escopo;
- se disparo ocorre em criação, entrada na etapa ou ambos;
- responsável atribuído e significado de “Clínica Aesthesis” (usuário, equipe ou entidade);
- timer, fila, responsável e ações da pré-qualificação;
- fuso horário e condições de execução;
- logs de sucesso, falhas e duplicidade;
- efeitos sobre importações e novos negócios;
- idempotência e prevenção de reprocessamento.

Não concluir que a atribuição ou pré-qualificação funciona apenas pelo cadastro da regra.

## 4. Horário comercial registrado
Informado como confirmado para:
- Atendimento;
- Comercial;
- Customer Success.

Horários:
- Segunda a sexta: 10:00–20:00.
- Sábado: 10:00–13:00.
- Sem pausa de almoço.

Validar onde os horários estão configurados e se cada setor utiliza a mesma regra, fuso e calendário.

## 5. Campos
- **Área de interesse:** foi corrigido e reportado funcionando após ajuste no grupo.
- **Nutrição Estética:** adicionada como opção/categoria.
- Campos provisórios com revisão pendente:
  - `Próximo passo combinado`
  - `Status da consulta`
  - `Especialidade proposta`

Para cada campo, auditar: entidade (contato/negócio), tipo, opções, obrigatoriedade, valor padrão, uso em filtros/automações/relatórios, compatibilidade e dados já preenchidos. Não substituir ou recriar antes de mapear dependências.

## 6. Categorias e profissionais registradas
- Facial: Dra. Yorrana Rodrigues; Dra. Karla Massaria; Dra. Maria Luiza.
- Corporal: Dra. Beibiane Lima.
- Nutrição Estética: Dra. Rayanne Marques.

Confirmar cadastro, vínculos, especialidades, permissões e disponibilidade atuais. Não atribuir leads com base apenas nesta lista histórica.

## 7. WhatsApp, integrações e comunicação
O material disponível não confirma de forma suficiente:
- integração WhatsApp ativa e oficial;
- provedor/canal atualmente utilizado;
- templates aprovados;
- status de conexão;
- consentimentos e mecanismos de opt-out;
- logs e entregabilidade.

Auditar antes de planejar disparos ou assumir capacidade de envio.

## 8. Inventário mínimo a produzir
Criar tabela com:
- objeto/configuração;
- nome e ID/chave;
- estado atual;
- origem/evidência;
- última verificação;
- dependências;
- risco;
- ação recomendada.

Incluir grupos, etapas, campos, responsáveis, automações, integrações, permissões e amostra representativa de negócios.
