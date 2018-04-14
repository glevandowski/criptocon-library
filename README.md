LibCriptocon - Biblioteca para pesquisa de itens em um Spinner.

Um spinner customizado de fácil adaptação e possiveis melhorias,Utilizado bibliotecas externas e adaptado.
Por não estar implementado de maneira externa(Online), a sua adição deve ser feita de forma local(Offline).

Tarefas para adicionar:
1) Execute a biblioteca no android studio.
2) Efetue o comando make project ou make module app.
3) Acesse o diretório ...\libcriptocon-master\app\build\outputs\aar.
4) Dentro dessa pasta você encontrará o arquivo .aar , necessário para adicionarmos no projeto. 
5) Faça suas modificações, após gerar o arquivo .aar copie e cole em outro local de armazenamento.
6) Execute o seu projeto, com ele aberto vá em file>new>new module...
7) Selecione Import JAR/AAR package, localize o arquivo .aar salvo anteriormente.
8) Após incluido, vá em file>Project Structure...> Na guia lateral esquerda, Modules>app.
9) Com o módulo selecionado, entre na guia Dependencies>Add>Module Dependency e selecione o módulo importado anteriormente.
10) No Build.gradle faça a adição da sua biblioteca local com o comando: implementation project(":Search") **onde search é o nome do módulo.

Observações:
Para adição dos Recursos no layout é utilizado o endereço do package. 
Exemplo: <primao.levandowski.searchcriptocon.searchablespinnerlibrary.SearchableSpinner/>



©39
