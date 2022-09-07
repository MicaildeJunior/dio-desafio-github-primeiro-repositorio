## Download Git

[Link de Download Git](https://git-scm.com/downloads)

### Comandos básicos do Git

- git config

  

1. Um dos comandos git mais usados é o **git config** que pode ser usado para definir valores de configuração específicos do usuário como e-mail, algoritmo preferido para diff, nome de usuário e formato de arquivo etc. Por exemplo, o seguinte comando pode ser usado para definir o email:

   - ```
     git config --global user.email sam@google.com
     ```

- git init

1. Este comando é usado para crias um novo repositório GIT. Uso:

   - ```
     git init
     ```

   - git add

   O comando **git add** pode ser usado para adicionar arquivos ao índice. Por exemplo, o seguinte comando irá adicionar um arquivo chamado temp.txt presente no diretório local para o índice:

   - ```
     git add temp.txt
     ```

- git clone

1. O comando **git clone** é usado para fins de verificação de repositório. Se o repositório estiver em um servidor remoto, use:

   - ```
     git clone alex@93.188.160.58:/path/to/repository
     ```

2. Por outro lado, se uma cópia de trabalho de um repositório local for criada, use:

   - ```
     git commit –m “coloque sua mensagem aqui”
     ```

- git status

3. **git push** é outro dos comandos git básicos mais usados. Um simples envio envia as alterações feitas para o ramo mestre do repositório remoto associado ao diretório de trabalho. Por exemplo:

   git push origin master

- git checkout

4. O comando **git checkout** pode ser usado para criar ramos ou alternar entre eles. Por exemplo, o seguinte cria um novo ramo e muda para ele:

   ```
   command git checkout -b <branch-name>
   ```

5. Para simplesmente mudar de um ramo para outro, use:

   ```
   git checkout <branch-name>
   ```

- git remote

6. O comando **git remote** permite que um usuário se conecte a um repositório remoto. O comando a seguir lista os repositórios remotos atualmente configurados:

   - ```
     git remote –v
     ```

7. Esse comando permite que o usuário se conecte a um servidor remoto:

   ```
   git remote add origin <93.188.160.58>
   ```

- git branch

8. O comando **git branch** pode ser usado para listar, criar ou excluir ramos. Para listar todos os ramos presentes no repositório, use:

   ```
   git branch
   ```

9. Para excluir um ramo:

   ```
   git branch –d <branch-name>
   ```

- git pull

  10. Para mesclar todas as alterações presentes no repositório remoto para o diretório de trabalho local, o comando pull é usado. Uso:

- git merge

  11. O comando **git merge** é usado para mesclar uma ramificação no ramo ativo. Uso:

  ```
  git merge <branch-name>
  ```

- git diff

  12. O comando **git diff** é usado para listar os conflitos. Para visualizar conflitos com o arquivo base, use

  ```
  git diff --base <file-name>
  ```

  13. Para simplesmente listar todos os conflitos atuais, use:

  ```
  git diff
  ```