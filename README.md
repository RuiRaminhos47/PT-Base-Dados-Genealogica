# Base de Dados Genealógica

A tabela Pessoas é a fonte primária de informação sobre todas as pessoas na base de dados, onde, para cada pessoa única, existe um número automático, o ID, também este único, atribuído a essa pessoa. Todos os outros campos são informações, como o Nome ou a Morada da pessoa em questão.

Em primeiro lugar, no que diz respeito às tabelas de relações, as tabelas É_Pai_De e É_Irmão_De são compostas, ambas, por duas colunas. No caso da É_Irmão_De , cada coluna, e para cada entrada, representa o ID do irmão 1 e o ID do irmão 2, sem que a ordem importe. Na tabela É_Pai_De, a primeira coluna é o ID do pai e a segunda coluna o ID do filho, e cada entrada representa uma relação pai-filho.
Por outro lado, a tabela É_Casado_com além de ter uma coluna para o ID das duas pessoas casadas, tem uma coluna para o início e uma coluna para o fim do casamento dessa entrada.

Em segundo lugar, o formulário permite navegar, editar, adicionar, eliminar e personalizar as relações e pessoas existentes na base de dados. Na parte superior do formulário encontra-se a árvore da família próxima da pessoa selecionada (pais, irmãos, filhos e cônjugues). Relativamente aos irmãos, filhos e casamentos, existe uma ListBox para demonstrar todas as relações existentes. Todas estas relações possuem um botão de eliminar. Os casamentos são editáveis.~

Na parte inferior do formulário, existe a ListBox geral das Pessoas da base de dados, sendo possível inserir uma nova pessoa ou consultar as existentes, com os dados aparecendo ao lado. É possível adicionar, eliminar e editar pessoas. Ainda nesta seccção, é possível definir as 3 relações, pai de, irmão de, casado com. Para promover a inteligência artificial da base de dados e das suas operações, quando uma pessoa 1 é definida como filha de outra pessoa 2, 1 herda os irmãos que são filhos de 2.

 
