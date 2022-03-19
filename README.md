

# DESAFIO DE PROJETO -  DIO

Este repositório foi criado para o desafio de projeto Git e GitHub da Digital Innovation One (DIO).



## :key: Comandos  

Principais comandos ensinados na aula **Introdução ao Git e ao GitHub** da plataforma DIO.

####       1. Navegação básica

| Windows     | Unix   | Descrição                                                    |
| :---------- | ------ | ------------------------------------------------------------ |
| cd          | cd     | Utilizado para navegar da pasta atual para uma determinada pasta. |
| cd ..       | cd ..  | Utilizado para retornar à pasta anterior.                    |
| dir         | ls     | Utilizado para listar as pastas do diretório que você está.  |
| mkdir       | mkdir  | Utilizado para criar uma pasta no diretório que você está.   |
| del / rmdir | rm -rf | Utilizado para deletar arquivo / pasta (respectivamente)     |



####       2. Git

| Comando    | Código                                                       | Descrição                                                    |
| ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| git config | `git config --global user.name "alymaramaldo"`  / `git config --global user.email "alymaramaldo@gmail.com"` | Configuração de usuário e e-mail no GitHub.                  |
| git init   | `git init`                                                   | Criação de um novo subdiretório chamado *.git*.              |
| git clone  | `git clone [url]`                                            | Para clonagem de um repositório existente.                   |
| git add    | `git add`                                                    | Para monitorar um novo arquivo.                              |
| git status | `git status`                                                 | Para visualizar em quais estados os arquivos estão.          |
| git commit | `git commit -m "Mensagem"`                                   | Envia as alterações para o repositório.                      |
| git rm     | `git rm seu_arquivo.txt `                                    | Para remover um arquivo do commit.                           |
| git pull   | `git pull oringin master `                                   | Busca e baixa conteúdos de repositórios remotos.             |
| git push   | `git push origen master`                                     | Empurra/envia o conteúdo do repositório local para o repositório remoto. |





## :memo: Anotações

- A configuração do usuário e e-mail no comando *git config* só precisará ser realizada uma única vez. É importante que esteja de acordo com o e-mail de login e usuário do git;
- No subdiretório *.git* contém todos os arquivos necessários do meu repositório.
- Após utilizar o comando *git add*,  os arquivos serão movidos para área de *staged*, e estarão prontos para fazerem parte do commit. Para monitorar todos os arquivos, colocar o comando `git add .`.
- Como o *git status* é possível ver quais arquivos estão sendo monitorados;
- Os commit podem apontar para as tree, para os parentes, para o autor, mensagem e o tempo. Importante colocar a mensagem, para que outras pessoas possam ver o que foi realizado.
- Após a utilização do *git pull* é comum em caso de conflito, caso o repositório tenha colaboração de outras pessoas, que pode ser resolvido com a comparação, mesclagem, inclusão ou exclusão de informações, decidido pelo colaborador que queira fazer a última atualização.





## :dart: Outros Assuntos Abordados


1. SHA (Secure Hash Algorithm): conjunto de funções hash criptográficas projetadas pela NSA (Agência de Segurança Nacional);
2. Objetos internos do Git (Blobs, Trees e Commits);
3. Chaves SSH (forma de estabelecer uma conexão segura e encriptada entre duas máquinas) e Tokens;
4. Passo a passo no ciclo de vida (Untracked, Unmofified, Modified e Straged);
5. Conflitos no GitHub.





## :link: Links Úteis 

[Baixar o Git](https://git-scm.com/)

[Sintaxe Básica Markdown](https://www.markdownguide.org/basic-syntax/)

[+ Comandos GitHub](https://comandosgit.github.io/)

[DIO](https://web.dio.me/)
