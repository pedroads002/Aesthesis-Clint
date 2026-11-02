# AESTHESIS CLINIC | HANDOFF PARA AGENTE CLAUDE
**Versão:** 1.0 — 01/11/2026  
**Finalidade:** transferir contexto estratégico e operacional sem tratar registros históricos como estado atual.

## Como usar este pacote
1. Leia este documento primeiro.
2. Leia `05_REGRAS-DO-AGENTE.md` antes de qualquer tarefa operacional.
3. Consulte os documentos específicos conforme a tarefa.
4. Use `ESTADO_ATUAL.md` como registro operacional vivo, mas seus campos não verificados permanecem desconhecidos.
5. Faça diagnóstico sem alterações na primeira sessão. Não considere este pacote autorização para modificar a Clint.

## Projeto
Implementação e estruturação da operação comercial da Aesthesis Clinic na plataforma Clint. A clínica é posicionada como operação de estética de altíssimo padrão. O trabalho deve conectar estratégia, atendimento, dados, processos e CRM — não se limitar a configurar campos ou etapas.

## Princípios de continuidade
- Não reiniciar decisões já tomadas sem apresentar motivo e impacto.
- Não assumir que uma configuração antiga continua ativa.
- Distinguir: decisão aprovada, ação executada, estado observado e resultado validado.
- Em conflito entre documentação e sistema atual, registrar a divergência.
- Não inventar informações sobre profissionais, procedimentos, preços, ofertas, disponibilidade, automações ou métricas.
- Não executar ações irreversíveis, importações, exclusões ou disparos sem autorização explícita e plano de validação.

## Contexto consolidado disponível
- CRM escolhido: Clint; Kommo foi rejeitado para esta operação.
- O usuário informou ter acesso completo à Clint.
- Campanha de aniversário: **Dia D**, aniversário da clínica em **19/11/2026**.
- Horários informados como confirmados para Atendimento, Comercial e Customer Success: segunda a sexta, 10h–20h; sábado, 10h–13h; sem pausa de almoço.
- Grupo de negócios: chave `reativacao_da_base` (não confundir com rótulo de exibição).
- Automação Aura registrada: negócios em Reativação da Base > Análise de contato recebem Clínica Aesthesis como responsável.
- Pré-qualificação foi descrita como acionada após 1 hora por negócio criado/importado; funcionamento e escopo atuais precisam ser auditados.
- Área de interesse foi corrigida após ajuste do grupo; Nutrição Estética foi adicionada.
- Campos provisórios que precisam de revisão: `Próximo passo combinado`, `Status da consulta`, `Especialidade proposta`.
- Profissionais/categorias registrados:
  - Facial: Dra. Yorrana Rodrigues, Dra. Karla Massaria, Dra. Maria Luiza.
  - Corporal: Dra. Beibiane Lima.
  - Nutrição Estética: Dra. Rayanne Marques.
  Vínculos, grafia, disponibilidade e estado atual ainda devem ser confirmados.

## Base de contatos — fatos históricos e discrepâncias
Registros de 26–27/10/2026 indicam:
- Base brasileira mencionada: **3.509 contatos**.
- Internacionais: **25**.
- Três contatos excluídos por marcação/solicitação de “Não entrar em contato”.
- Sete números separados para revisão.
- Outro registro informa **3.535 contatos preparados**, preservando nomes e telefones originais e mantendo inicialmente internacionais.
- Um levantamento também cita **3.447 contatos brasileiros sem procedimento identificável**.
- Indícios por palavras no nome: **Botox 31 já importados; Facial 2; Corporal 2; Enzimas 1** em um registro. Esses rótulos eram pistas textuais, não comprovação de interesse.
- A importação de uma base posterior foi reportada pelo usuário como concluída com sucesso, sem recusas.
- Um teste indicou que importar/criar negócios acionava a etapa “Pré qualificação” após 1 hora.

**Não reconciliado:** os números 3.509, 25, 3.535, exclusões e registros de revisão não permitem concluir com segurança a quantidade líquida atual. As contagens podem refletir momentos, critérios ou arquivos diferentes. Não somar nem subtrair sem examinar os arquivos e registros de operação.

## Direção estratégica já registrada
A orientação foi parar importações separadas baseadas em palavras-chave e adotar uma base geral deduplicada, trabalhando em lotes compatíveis com a capacidade operacional. Identificar interesse durante a reativação e segmentar progressivamente (Facial, Corporal, Nutrição Estética etc.). Não converter pistas nominais em classificação confirmada.

## Campanha Dia D — histórico parcial
Um planejamento anterior registrou:
- Tráfego: 05/11.
- Convites para grupo: 13/11.
- Aquecimento: 14–16/11.
- Fechamento: 17/11.
- Divulgação de valores: 18/11.
- Evento comercial: 19/11, das 10h às 20h.
- Atendimentos a partir de 23/11.
- Preços somente no grupo.
- Não melhorar condições depois.
- Cashback, combos, metas e indicadores finais ainda estavam em aberto.

Esses pontos são **planejamento histórico**, não confirmação de aprovação final, execução, viabilidade ou status atual. Revalidar imediatamente antes de utilizá-los.

## Limitações deste handoff
Este pacote é compilado do contexto de trabalho disponível, não de uma auditoria ao vivo da Clint nem de um arquivo integral de todas as conversas e evidências. O agente deve tratar itens sem fonte primária anexada como registros históricos a validar.
