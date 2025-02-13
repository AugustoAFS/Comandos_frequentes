> #### Comandos frequentes
>
> ### **Git** (Versionamento de Código)
>
> - `git add .` – Adiciona todas as mudanças ao stage.
> - `git commit -m "mensagem do commit"` – Salva as alterações localmente.
> - `git push origin <nome-da-branch>` – Envia as mudanças para o repositório remoto. **Sempre especifique o nome da branch ao fazer push.**
> - `git pull origin <nome-da-branch>` – Atualiza o repositório local com as mudanças do repositório remoto. **Sempre especifique o nome da branch ao fazer pull.**
> - `git branch` – Lista as branches disponíveis.
> - `git branch <nome>` – Cria uma nova branch.
> - `git checkout <nome>` – Alterna para outra branch.
> - `git merge <branch>` – Mescla uma branch com a atual.
> - `git stash` – Salva temporariamente mudanças não commitadas.
> - `git stash pop` – Restaura as mudanças salvas.
> - `git log --oneline` – Exibe um histórico compacto dos commits.
>
> ### **Frontend**
>
> #### React
> - `npm create vite@latest` – Cria um novo projeto com Vite.
> - `npm install` – Instala as dependências do projeto.
>
> #### Angular
> - `npm i -g @angular/cli` – Instala o Angular CLI globalmente.
> - `ng new Nome do projeto --prefix Nome do prefixo --minimal` – Cria um novo projeto Angular.
> - `ng generate component components/nome do componente` – Gera um novo componente.
> - `ng serve` – Inicia o servidor de desenvolvimento.
> - `ng build` – Compila o projeto para produção.
>
> ### **C#**
>
> #### Entity Framework Core
> - `dotnet run dev` – Inicia o servidor de desenvolvimento.
> - `dotnet add package Microsoft.EntityFrameworkCore`
> - `dotnet add package Microsoft.EntityFrameworkCore.SqlServer`
> - `dotnet add package Microsoft.EntityFrameworkCore.Design`
> - `dotnet add package Microsoft.EntityFrameworkCore.Tools`
> - `Add-Migration InitialCreate` – Cria uma nova migração.
> - `Update-Database` – Aplica as migrações ao banco de dados.
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
