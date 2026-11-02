# 03 | HISTÓRICO, DECISÕES E CORREÇÕES

**Nota:** a cronologia abaixo resume fatos e decisões encontrados no contexto disponível. Não substitui exportação integral das conversas, logs e comprovantes.

## Registro cronológico

### 1. Escolha de CRM
- A implementação foi direcionada para Clint.
- Kommo foi rejeitado pela Aesthesis.
- Usuário informou acesso completo à conta Clint.

### 2. Estrutura inicial e grupo de reativação
- Foi criado/trabalhado o grupo de negócios Reativação da Base.
- Chave correta registrada: `reativacao_da_base`.
- O grupo foi excluído acidentalmente e recriado.
- Implicação: mapear o ID atual e verificar automações, vínculos e referências; não presumir continuidade de identificadores.

### 3. Horários de funcionamento
Horários confirmados pelo cliente para Atendimento, Comercial e Customer Success:
- Seg–Sex: 10h–20h.
- Sáb: 10h–13h.
- Sem pausa de almoço.

### 4. Campos e categorias
- Área de interesse apresentou problema relacionado à estrutura/grupo e depois foi reportada funcionando.
- Nutrição Estética foi adicionada.
- `Próximo passo combinado`, `Status da consulta` e `Especialidade proposta` foram tratados como campos de texto provisórios a corrigir/revisar.

### 5. Profissionais/categorias
- Facial: Dra. Yorrana Rodrigues, Dra. Karla Massaria e Dra. Maria Luiza.
- Corporal: Dra. Beibiane Lima.
- Nutrição Estética: Dra. Rayanne Marques.

### 6. Base de leads e importações — registros de 26–27/10/2026
- Levantamento citou 3.509 contatos brasileiros, 25 internacionais, 3 contatos opt-out/não contatar e 7 números para revisão.
- Outro registro apontou 3.535 contatos preparados, mantendo nomes e telefones originais e incluindo inicialmente internacionais.
- Foram mencionados: 3.447 contatos brasileiros sem procedimento identificável.
- Indícios por palavras-chave: Botox 31 já importados; Facial 2; Corporal 2; Enzimas 1.
- Esses indícios não equivalem a intenção confirmada.
- Houve importações pequenas por categorias; o histórico resumido não garante que esses números representem todos os lotes ou estado atual.
- O usuário relatou que uma importação posterior foi concluída com sucesso, sem recusas.

### 7. Aprendizado de teste operacional
- Teste de criação/importação indicou que cada negócio entrava em Análise de contato e acionava “Pré qualificação” após 1 hora.
- A automação Aura foi reportada aceita: negócios em Reativação da Base > Análise de contato recebiam Clínica Aesthesis como responsável.
- A confirmação em escala e o comportamento em todos os cenários não estavam comprovados no registro resumido.

### 8. Decisão de método para a base
Foi orientado:
- parar novas importações separadas com base em palavras-chave;
- preparar base geral deduplicada;
- remover registros já importados, conforme reconciliação;
- trabalhar em lotes compatíveis com a capacidade;
- identificar interesse na conversa e segmentar progressivamente.

### 9. Campanha Dia D
- Aniversário: 19/11/2026.
- Plano anterior: tráfego 05/11; convites ao grupo 13/11; aquecimento 14–16; fechamento 17; valores 18; evento 19, 10h–20h; atendimentos a partir de 23/11.
- Preços somente no grupo; não melhorar condições depois.
- Cashback, combos, metas e indicadores finais em aberto no registro.
- Status de aprovação/execução precisa ser confirmado.

## Discrepâncias e cuidados
1. Quantidades da base diferem conforme momento e critério; não reconciliadas.
2. “Importação concluída” não define automaticamente o universo de registros importados.
3. “Regra criada/aceita” não equivale a automação validada por evidência de execução.
4. Planejamento Dia D não prova campanha aprovada ou executada.
5. Campo corrigido não prova que os dados antigos estejam preenchidos corretamente.

## Modelo para novas entradas
- Data/hora:
- Solicitante/aprovador:
- Objetivo:
- Estado anterior:
- Decisão:
- Ação:
- Objetos/IDs afetados:
- Quantidade:
- Evidência:
- Resultado do teste:
- Riscos/pendências:
- Responsável:
