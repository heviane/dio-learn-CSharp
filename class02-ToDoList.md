# Class 01: ToDoList

Projeto .NET do tipo Web usando o Padrão MVC, default para projetos fullstack.

## Instalação do SDK .NET

Baixe e instale o SDK .NET no site [https://dotnet.microsoft.com/en-us/](https://dotnet.microsoft.com/en-us/)

Verifique a instalação via terminal:

```bash  
    dotnet --version
```

## Projeto .NET

- Listar os templates disponiveis para criação de projetos.

```bash
    dotnet new --list 
```

- Criar projeto usando o template **ASP.NET Core Web App (Model-View-Controller)**.

Aplicação web que utiliza o padrão de projeto MVC.
É o padrão para aplicações fullstack, frontend e backend integrados.
**OBS:** Se fosse apenas APIs usariamos **ASP.NET Core Web App API**.

```bash
    dotnet new mvc -o ToDoList --no-https
```

**mvc** é o tipo de projeto.
**-o** para criar uma pasta para o projeto.
**ToDoList** é o nome da pasta do projeto.
**--no-https** para não usar https, mas sim http.
.NET por padrão cria projetos https, e isso exige uso de certificado de segurança. 

- Entrar na pasta do projeto e abrir com o VSCode

```bash
    cd ToDoList
    code .
```

O comando **code .** automaticamente detecta que estão faltando alguns arquivos do VSCode obrigatórios para a execução do projeto, e exibe uma mensagem informando isso. Basta aceitar e será criado a pasta **.vscode** e os arquivos **launch.json** e **tasks.json**.

- Execute a aplicação

```bash
    dotnet run
```

No prórpio terminal já é informado onde a aplicação está sendo executada.
Exemplo: Now listening on: http://localhost:5295