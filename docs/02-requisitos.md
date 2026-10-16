# 2. Requisitos do aplicativo

## Requisitos funcionais (RF)

| ID | Descrição | Perfil | Tela |
|---|---|---|---|
| RF01 | O sistema deve permitir cadastro e login de clientes, barbeiros e administradores | Todos | 01 Login e cadastro |
| RF02 | O sistema deve permitir que o cliente visualize os serviços oferecidos (tipo, preço, duração) | Cliente | 02 Home, 03 Selecionar serviço |
| RF03 | O sistema deve permitir que o cliente escolha barbeiro e horário disponível para agendamento | Cliente | 04 Barbeiro e horário |
| RF04 | O sistema deve permitir que o cliente confirme e pague o agendamento pelo app | Cliente | 05 Confirmar e pagar |
| RF05 | O sistema deve permitir que o cliente cancele ou reagende um horário já marcado | Cliente | 06 Meus agendamentos |
| RF06 | O sistema deve exibir ao cliente o histórico de cortes realizados | Cliente | 07 Histórico e fidelidade |
| RF07 | O sistema deve calcular e exibir pontos de fidelidade acumulados pelo cliente | Cliente | 07 Histórico e fidelidade |
| RF08 | O sistema deve enviar notificações e lembretes automáticos de horário agendado | Cliente | Notificação do aplicativo (sem tela dedicada) |
| RF09 | O sistema deve exibir ao barbeiro sua agenda diária de atendimentos | Barbeiro | 08 Agenda do dia |
| RF10 | O sistema deve permitir que o barbeiro confirme ou recuse um horário solicitado | Barbeiro | 09 Detalhe do atendimento |
| RF11 | O sistema deve permitir que o barbeiro marque um atendimento como concluído | Barbeiro | 09 Detalhe do atendimento |
| RF12 | O sistema deve permitir que o barbeiro consulte o histórico de clientes atendidos | Barbeiro | 10 Histórico de clientes |
| RF13 | O sistema deve permitir que o administrador cadastre, edite e remova barbeiros | Admin | 12 Barbeiros |
| RF14 | O sistema deve permitir que o administrador cadastre, edite e remova serviços e preços | Admin | 13 Serviços |
| RF15 | O sistema deve permitir que o administrador visualize a agenda geral de todos os barbeiros | Admin | 14 Agenda geral |
| RF16 | O sistema deve gerar relatórios de atendimentos e pagamentos para o administrador | Admin | 15 Relatórios |
| RF17 | O sistema deve permitir que o administrador gerencie as regras do programa de fidelidade | Admin | 11 Painel, 15 Relatórios |

## Requisitos não funcionais (RNF)

| ID | Descrição | Categoria |
|---|---|---|
| RNF01 | O app deve ser responsivo, funcionando em Android e iOS | Compatibilidade |
| RNF02 | O tempo de resposta para carregar horários disponíveis deve ser inferior a 3 segundos | Desempenho |
| RNF03 | Os dados de pagamento devem ser processados por gateway seguro (criptografia e PCI) | Segurança |
| RNF04 | Senhas de usuários devem ser armazenadas com hash, nunca em texto puro | Segurança |
| RNF05 | A interface deve seguir a identidade visual definida (preto e amarelo) | Usabilidade |
| RNF06 | O sistema deve estar disponível pelo menos 99% do tempo em horário comercial | Confiabilidade |
| RNF07 | O app deve permitir agendar em no máximo 4 toques | Usabilidade |
| RNF08 | O sistema deve suportar crescimento do número de usuários sem perda de desempenho | Escalabilidade |

## Rastreabilidade

Cada requisito funcional aponta para a tela que o atende (coluna **Tela**). Os números das telas correspondem aos arquivos em [`design/telas/`](../design/telas).
