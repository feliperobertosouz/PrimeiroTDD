# PrimeiroTDD
Projeto criado para começar a usar a metodologia de TDD aprendido em QA na faculdade de engenharia, matéria dada pelo professor Daniel Ohata
Usando a IDE IntelliJ

# 1-Criação da classe LoginScreenTest
Foi criado primeiro a classe LoginScreenTest e então lá dentro 3 metodos

1-testSuccessfullLogin()

2-testFailedLogin()

3-testAdduser()

Todos esses 3 metodos tinham a instancia da classe LoginScreen e neles usavam os metodos .login e .addUser

Após isso foi rodado um teste que claro apontou a falta da classe e metodos.

# 2- Criação da classe Login e seus metodos
Criei a classe LoginScreen e os metodos usando a propria IDE para isso, fazendo ser algo facil de se implementar, apenas tive que mudar o nome dos parametro

Nesse caso não fiz nada dentro dos metodos além de devolver um valor qualquer que era necessario como return true 

Rodei o teste, aqueles que eram para dar true deram certo e aqueles que eram para dar false deram errado, por causa da falta de lógica nos metodos

# 3- Criação da Logica dos metodos
Implementei a devida lógica nos metodos como checar usuario e senha.

Fiz mais um teste e agora todos deram certo

# 4- Documentei com javadoc
Criei os javadoc dentro dos arquivos e usando a ferramenta da IDE criei o javadoc automaticamente
