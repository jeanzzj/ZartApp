# 2. Requisitos do aplicativo

## Requisitos funcionais (RF)

| ID | Descrição | Perfil | Tela |
|---|---|---|---|
| RF01 | O sistema deve permitir cadastro e login de clientes, barbeiros e administradores | Todos | 02 Login, 03 Seleção de perfil |
| RF02 | O sistema deve permitir que o cliente visualize os serviços oferecidos (tipo, preço, duração) | Cliente | 04 Início, 05 Serviços |
| RF03 | O sistema deve permitir que o cliente escolha barbeiro e horário disponível para agendamento | Cliente | 06 Escolher barbeiro, 07 Data e horário |
| RF04 | O sistema deve permitir que o cliente confirme e pague o agendamento pelo app | Cliente | 08 Confirmação e pagamento |
| RF05 | O sistema deve permitir que o cliente cancele ou reagende um horário já marcado | Cliente | 10 Agendamentos |
| RF06 | O sistema deve exibir ao cliente o histórico de cortes realizados | Cliente | 11 Histórico |
| RF07 | O sistema deve calcular e exibir pontos de fidelidade acumulados pelo cliente | Cliente | 12 Fidelidade |
| RF08 | O sistema deve enviar notificações e lembretes automáticos de horário agendado | Cliente | 09 Confirmado (aviso de lembrete) e notificação do aplicativo |
| RF09 | O sistema deve exibir ao barbeiro sua agenda diária de atendimentos | Barbeiro | 13 Barbeiro: agenda |
| RF10 | O sistema deve permitir que o barbeiro confirme ou recuse um horário solicitado | Barbeiro | 13 Barbeiro: agenda |
| RF11 | O sistema deve permitir que o barbeiro marque um atendimento como concluído | Barbeiro | 14 Barbeiro: atendimento |
| RF12 | O sistema deve permitir que o barbeiro consulte o histórico de clientes atendidos | Barbeiro | 14 Barbeiro: atendimento (histórico do cliente) |
| RF13 | O sistema deve permitir que o administrador cadastre, edite e remova barbeiros | Admin | 16 Admin: gestão |
| RF14 | O sistema deve permitir que o administrador cadastre, edite e remova serviços e preços | Admin | 16 Admin: gestão |
| RF15 | O sistema deve permitir que o administrador visualize a agenda geral de todos os barbeiros | Admin | 15 Admin: dashboard, 16 Admin: gestão |
| RF16 | O sistema deve gerar relatórios de atendimentos e pagamentos para o administrador | Admin | 17 Admin: relatórios |
| RF17 | O sistema deve permitir que o administrador gerencie as regras do programa de fidelidade | Admin | 16 Admin: gestão (fidelidade) |

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
