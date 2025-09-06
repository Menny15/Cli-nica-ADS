#requisitos funcionais para o sistema de supermercado
RU1 - Quero cadastrar os médicos
RF1 - O sistema deve possibilitar o cadstro de médicos com os seguintes dados: nome completo, crm, epeciaidade, disponibilidade, cpf

RU2 - Quero cadastrar os pacientes
RF2 - O sistema deve possibilitar o cadastro de pacientes com os seguintes dados: nome completo, data de nascimento, sexo, cpf, convênio

RU3 - Quero visualização de consultas agendadas
RF3 - O sistema deve possibilirtar o paciente para visualizar uma lista com suas consultas futuras e passadas, com data, horário, nome do médico e status (confirmada, cancelada, realizada)

RU4 - Quero o acesso prontuário médico
RF4 - O sitema deve posssibilitar o médico que registre e consulte o prontuário do paciente, contendo informações como diagnóstico, sintomas, medicamentos prescritos e exames solicitados

RU5 - Quero uma emissão de receita médica
RF5 - O sistema deve possibilitar o médico para emitir uma receita médica digital, contendo os dados do paciente, medicamentos prescritos, posologia e assinatura digital do profissional

RU6 - Quero um cancelamento e reagendamento de consulta
RF6 - O sistema deve posibilitar o paciente para cancelar ou reagendar uma consulta com pelo menos 24 horas de antecedência, selecionando uma nova data e horário disponíveis

RU7 - Quero notificações e lembretes para o paciente
RF7 - O sistema deve possibilitar o envio das notificações automáticas por e-mail ou SMS para lembrar o paciente de consultas agendadas com 24 horas de antecedência

RU8 - Quero um login com controle de acesso
RF8 - O sistema deve possibilitar o login de diferentes tipos de usuários (paciente, médico, administrador), e garantir que cada um tenha acesso apenas às funcionalidades correspondentes ao seu perfil

RU9 - Quero o histórico de consultas e diagnósticos
RF9 - O sisatema deve possibiltar o paciente que visualize o histórico completo de suas consultas passadas, incluindo o diagnóstico registrado, exames realizados, prescrições e observações feitas pelo médico

RU10 - Quero a integração com sistema de exames laboratoriais
RF10 - O sistema deve possibiltar o médico que solicite exames laboratoriais diretamente pelo sistema, e que os resultados sejam enviados automaticamente para o prontuário eletrônico do paciente, com acesso para o médico e o próprio paciente

#requisitos não funcionais para o o sistema de clínica médica
RFN1 - O sistema deve garantir a proteção de dados pessoais dos pacientes, médicos e administradores, conforme as exigências da LGPD (Lei Geral de Proteção de Dados), utilizando criptografia de ponta a ponta para informações sensíveis, como dados de login,
prontuários e receitas médicas

RFN2 - O sistema deve ser capaz de processar até 1000 requisições simultâneas de usuários, garantindo que o tempo de resposta para qualquer operação, como o agendamento de consulta ou a consulta ao prontuário médico, seja inferior a 3 segundos em condições
normais de carga.

RFN3 - O sistema deve ser intuitivo e fácil de usar, com interfaces amigáveis tanto para o paciente quanto para o médico. O design deve ser responsivo e acessível, atendendo às normas de acessibilidade WCAG 2.1 (Web Content Accessibility Guidelines) para
garantir que usuários com deficiências possam utilizar o sistema sem dificuldades.

RFN4 - O sistema deve ter uma disponibilidade mínima de 99,5% durante o horário comercial, garantindo que os usuários possam acessar o sistema sem interrupções. Em caso de falha, o tempo de recuperação não deve ultrapassar 1 hora.

RFN5 - O sistema deve ser escalável, ou seja, capaz de ser ampliado para suportar um aumento no número de usuários e no volume de dados sem comprometer seu desempenho. A arquitetura deve permitir o aumento de recursos (como servidores
ou bancos de dados) sem a necessidade de reformulação significativa do sistema.
