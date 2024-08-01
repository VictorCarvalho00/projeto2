   O projeto Jogos escolares dos ifs conta com uma modularização dividida entre: 
atleta, modalidade, equipes, torneio, jogo e o principal. Para cada um foi criado tanto um arquivo .h como arquivo .c, e por fim é existente um arquivo estruturas.h, para melhor organização do código.
   Os módulos de atleta, modalidade, equipes, torneio e jogo contém todos a mesma criação, no seguinte formato, cadastro, exclusão, atualizar, registro geral e submenu, a uma exceção no torneio onde contém uma função para armazenar torneios criados, já no módulo principal e onde está a função main, contendo os menus principais e por fim no módulo de estruturas contêm as estruturas e bibliotecas usadas no projeto.

   Para o desenvolvimento desse projeto foi usado funções, ponteiros, struct e modularização.
OBS: Foi muito utilizada a função strcmp que é usada para comparar duas strings. Ela está definida na biblioteca <string.h>. Essa função foi de muita importância para esse trabalho.

Como compilar:

No terminal do linux abra a pasta onde o arquivo "projeto2" estiver, cd Nome_da_pasta, depois abra a pasta do projeto, cd projeto2. Após chegar na pasta do projeto se preferir use o comando "make clean" para limpar o diretório, após todos esses passos basta digitar "make" ou "make all" e em seguida "./principal".
