### Considerando os requisitos funcionais do Sistema FitPass Gym Management, elabore o diagrama de classes do domínio. Salvar os docs em um repositório do GitHub e postar o link.
---
RF01 — Cadastro de Alunos - O sistema deve permitir cadastrar novos ***ALUNOS*** contendo dados pessoais, contato, endereço e plano contratado.

RF02 — Gerenciamento de ***PLANOS*** - O sistema deve permitir criar, editar, ativar e desativar tipos de planos (mensal, trimestral, anual, musculação, funcional etc.).

RF03 — Controle de ***PAGAMENTOS*** - O sistema deve registrar pagamentos realizados na **RECEPÇÃO** (dinheiro, cartão ou PIX) e gerar boletos/cartões para pagamentos online.

RF04 — Regularidade do Aluno - O sistema deve verificar automaticamente se o aluno está com mensalidade em dia.

RF05 — Controle de ***ACESSO*** - O sistema deve se integrar à catraca para validar a entrada do aluno por RFID.

RF06 — Agendamento de ***AULAS*** - O aluno deve poder visualizar horários e reservar vagas nas aulas disponíveis.

RF07 — Lista de Presença - Instrutores devem registrar ***PRESENÇA*** dos alunos nas aulas.

RF08 — ***AVALIAÇÃO FÍSICA*** - Instrutores devem registrar avaliação físicas (peso, IMC, percentual de gordura etc.) e anexar arquivos se necessário.

RF09 — Relatórios Gerenciais - O ***GERENTE*** deve poder emitir ***RELATÓRIOS*** como:
- inadimplência
- alunos ativos
- histórico de acessos
- ocupação das aulas

RF10 — Notificações - O sistema deve enviar ***NOTIFICAÇÃO*** ao aluno sobre:
- vencimento de mensalidade
- confirmação de agendamento
- liberação de nova avaliação física
