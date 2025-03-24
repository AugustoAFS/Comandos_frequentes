> #### Comandos frequentes
>
> ### **Git** (Versionamento de Código)
>
> - `git init` – Inicializa um repositório Git.
> - `git add .` – Adiciona todas as mudanças ao stage.
> - `git commit -m "mensagem do commit"` – Salva as alterações localmente.
> - `git push origin <nome-da-branch>` – Envia as mudanças para o repositório remoto. **Sempre especifique o nome da branch ao fazer push.**
> - `git pull origin <nome-da-branch>` – Atualiza o repositório local com as mudanças do repositório remoto. **Sempre especifique o nome da branch ao fazer pull.**
> - `git branch` – Lista as branches disponíveis.
> - `git branch <nome>` – Cria uma nova branch.
> - `git checkout <nome>` – Alterna para outra branch.
> - `git checkout -b <nova-branch> <branch-base>` – Cria uma branch baseada em outra branch.
> - `git merge <branch>` – Mescla uma branch com a atual.
> - `git stash` – Salva temporariamente mudanças não commitadas.
> - `git stash pop` – Restaura as mudanças salvas.
> - `git log --oneline` – Exibe um histórico compacto dos commits.
> - `git reset --hard <commit>` – Restaura o repositório para um commit específico.
> - `git rm -r --cached . && git add . && git commit -m "Atualizando .gitignore"` – Aplica mudanças ao `.gitignore` e remove arquivos já rastreados.
>
> ### **Frontend**
>
> #### React
> - `npm create vite@latest` – Cria um novo projeto com Vite.
> - `npm install` – Instala as dependências do projeto.
> - `npm run dev` – Inicia o servidor de desenvolvimento.
>
> #### Angular
> - `npm i -g @angular/cli` – Instala o Angular CLI globalmente.
> - `ng new <nome-do-projeto> --prefix <prefixo> --minimal` – Cria um novo projeto Angular.
> - `ng generate component <caminho/nome-do-componente>` – Gera um novo componente.
> - `ng serve` – Inicia o servidor de desenvolvimento.
> - `ng build` – Compila o projeto para produção.
> - `ng generate service <nome-do-serviço>` – Cria um serviço Angular.
>
> ### **C#**
>
> #### ASP.NET Core
> - `dotnet new webapi -n <NomeDoProjeto>` – Cria um novo projeto Web API.
> - `dotnet run` – Inicia o servidor de desenvolvimento.
> - `dotnet build` – Compila o projeto.
> - `dotnet watch run` – Inicia o servidor com hot reload.
>
> #### Entity Framework Core (EF Core)
> - `dotnet add package Microsoft.EntityFrameworkCore` – Adiciona o pacote EF Core.
> - `dotnet add package Microsoft.EntityFrameworkCore.SqlServer` – Adiciona suporte ao SQL Server.
> - `dotnet add package Microsoft.EntityFrameworkCore.Design` – Adiciona ferramentas de design do EF Core.
> - `dotnet add package Microsoft.EntityFrameworkCore.Tools` – Adiciona ferramentas de CLI do EF Core.
> - `Add-Migration InitialCreate` – Cria uma nova migração.
> - `Update-Database` – Aplica as migrações ao banco de dados.
> - `Remove-Migration` – Remove a última migração.
>
> #### Dapper (Alternativa ao Entity Framework para acesso a banco de dados)
> - `dotnet add package Dapper` – Adiciona o pacote do Dapper.
>
> #### Configuração da Connection String:
> ```json
> "ConnectionStrings": { 
>   "DefaultConnection": "Server=;Database=;Integrated Security=True;TrustServerCertificate=True;" 
> }
> ```
