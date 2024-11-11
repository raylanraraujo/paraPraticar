# paraPraticar
projeto para praticar comandos em GIT

README criado para ser utilizado como cobaia para praticar comandos do Git

testando adicionar informações

é possível utilizar ferramenta do VScode para evitar o uso do terminal e de diversos códigos dentro dele...trabalhando assim de manaiera mais visual e intuitiva. 

O terceiro ícone da barra lateral do VScode (Controle do Código-Fonte) tem essa função. Nele são exibidos uma lista com os arquivos que foram alterados e para cada arquivo temos algumas opções:
1ª - opção de abrir o arquivo;
2ª - opção de descartar as alterações realizadas (mesmo princípio do CTRL + Z);
3ª - adicionar os arquivos ("Preparar os arquivos") --> simnilar ao comando [git add nome do arquivo] 

Ao adicionar o arquivo, este por sua vez sai da lista dos arquivos alterados e vai para a lista "Alterações preparadas", disponibilizando-o para serem commitados (git commit -m “ first commit ”). Basta incluir uma mensagem e apertar no botão de commit (confirmação).  

Após commitar, o botão altera para ser um de sincronização, pois ele detecta que há arquivos commitados no repositório local que não foram enviador para o GitHub (repositório remoto). Essa sincronização é equivalente ao comando [git push -u origin main].