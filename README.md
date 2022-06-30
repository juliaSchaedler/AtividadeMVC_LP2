# AtividadeMVC_LP2
Atividade simples para entender o funcionamento do padrão MVC utilizando php e sqlite.

No projeto temos duas classes models: Users e Tarefa. Essas classes são responsáveis por gerenciar os dados/funções vindas dos controllers, que são 3: User, Tarefa e Home. Esses controllers são feitos para intermediar as requisões vinda dos Views com as respostas do gerenciamento feito dos models, como se fosse uma troca de informações. As Views, por sua vez, apresentam essas informações para o usuário visualmente. Outros arquivos presentes são o Database, utilizado para fazer a conexão com o banco de dados, e o arquivo próprio do banco de dados Sqlite, onde é inserido as informações das tabelas users e tarefas para a realização do programa.

Os benefícios principais desse padrão são a segurança, a organização e a eficiência. Acreditamos que a maior dificuldade que esse modelo traz é a compreensão do mesmo inicialmente, já que há 3 componentes com funções distintas.
