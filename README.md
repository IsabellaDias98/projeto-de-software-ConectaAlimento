# Sistema de Gerenciamenton de Coleta de Alimentos (ConectaAlimento)
Trabalho acadêmico da disciplina de Projeto de Software (Engenharia de Software - PUC Minas). O repositório contém a modelagem UML (Diagramas de Caso de Uso , Classes , Componentes e Implantação ) para um Sistema de Gerenciamento de Doação de Alimentos (ConectaAlimento), focado em gerenciar doações de estabelecimentos, coletas por voluntários e a distribuição para ONGs.

## Histórias de Usuário (User Stories)

**US01 - Cadastrar Colaborador**

Como um colaborador (restaurante ou evento), Eu desejo me cadastrar na plataforma, Para poder registrar sobras de alimentos para doação.

**US02 - Cadastrar Voluntário**

Como um voluntário, Eu desejo me cadastrar no sistema informando meus dados (além da CNH), Para poder aceitar e realizar o transporte de doações.

**US03 - Cadastrar ONG**

Como uma ONG, Eu desejo me cadastrar no sistema (enviando CNPJ e documentos), Para ser validada e listada como beneficiária para receber doações.

**US04 - Realizar Login**

Como um usuário (Doador, Voluntário, ONG ou Admin), Eu desejo realizar login com meu e-mail e senha, Para acessar as funcionalidades específicas da minha conta.

**US05 - Recuperar Senha**

Como um usuário, Eu desejo solicitar a recuperação da minha senha, Para poder acessar o sistema caso eu a esqueça.

**US06 - Cadastrar Doação de Alimentos**

Como um Doador, Eu desejo cadastrar um pedido de doação, Para notificar voluntários sobre os alimentos disponíveis.

**US07 - Visualizar Status da Coleta**

Como um Doador, Eu desejo acompanhar o status da minha doação, Para saber quando o voluntário irá retirar o alimento.

**US08 - Confirmar Retirada do Voluntário**

Como um Doador, Eu desejo confirmar no sistema que o voluntário retirou o alimento, Para registrar que a minha parte do processo foi concluída.

**US09 - Visualizar Histórico de Doações**

Como um Doador, Eu desejo visualizar meu histórico de doações, Para ter um registro do impacto social que gerei e para minha própria organização.

**US10 - Visualizar Coletas Disponíveis**

Como um Voluntário, Eu desejo visualizar, em uma lista, as coletas de doação disponíveis perto de mim, Para poder escolher qual irei transportar.

**US11 - Aceitar Coleta**

Como um Voluntário, Eu desejo aceitar uma coleta disponível, Para me responsabilizar pelo transporte daquela doação específica e informar ao Doador e à ONG.

**US12 - Registrar Retirada (Check-in Doador)**

Como um Voluntário, Eu desejo registrar no aplicativo que cheguei ao Doador e retirei o alimento, Para atualizar o status da entrega para todos os envolvidos.

**US13 - Registrar Entrega (Check-in ONG)**

Como um Voluntário, Eu desejo registrar no aplicativo que cheguei à ONG e entreguei o alimento, Para finalizar o processo de transporte e confirmar o recebimento.

**US14 - Visualizar Histórico de Entregas**

Como um Voluntário, Eu desejo ver meu histórico de entregas realizadas, Para acompanhar minhas atividades de voluntariado.

**US15 - Visualizar Entregas Agendadas**

Como uma ONG, Eu desejo visualizar as doações que estão a caminho, e quem é o voluntário, Para que eu possa me preparar para receber o alimento no horário correto.

**US16 - Confirmar Recebimento da Doação**

Como uma ONG, Eu desejo confirmar o recebimento da doação e avaliar sua conformidade, Para validar a entrega, agradecer ao Doador e Voluntário, e fechar o ciclo no sistema.

**US17 - Gerenciar Perfil e Necessidades**

Como uma ONG, Eu desejo atualizar meu perfil e listar minhas necessidades (tipos de alimentos), Para que o sistema possa me alocar as doações mais adequadas.

**US18 - Visualizar Histórico de Recebimentos**

Como uma ONG, Eu desejo consultar o histórico de alimentos que recebi, Para auxiliar na minha prestação de contas, gestão interna e relatórios de impacto.

**US19 - Validar Cadastro de ONG**

Como um Administrador, Eu desejo analisar e aprovar, ou reprovar, o cadastro de novas ONGs, Para garantir que apenas instituições legítimas e verificadas recebam as doações.

**US20 - Validar Cadastro de Voluntário**

Como um Administrador, Eu desejo validar os dados e aprovar o cadastro de novos Voluntários, Para garantir a segurança e confiabilidade do transporte de alimentos.

**US21 - Moderar Doações**

Como um Administrador, Eu desejo monitorar os pedidos de doação cadastrados, Para remover publicações inadequadas.

**US22 - Gerenciar Usuários**

Como um Administrador, Eu desejo poder bloquear ou desativar usuários que violem os termos de uso, Para manter a integridade e segurança da plataforma.

**US23 - Visualizar Dashboard do Sistema**

Como um Administrador, Eu desejo visualizar um dashboard com estatísticas gerais, Para monitorar o impacto e o funcionamento do sistema.
